# 코리아 IT 아카데미 국비과정

## Load-Balancing
### Load-Balancing(로드 밸런싱)
```
여러 서버에 네트워크 트래픽(요청)을 고르게 분산시켜 하나의 서버에 부하가 집중되지 않게 하는 기술이다.
```
<br>

### Load-Balancing의 주요 기능 및 장점
<ul><li><strong>트래픽 분산</strong>
<br>: 클라이언트의 요청을 여러 서버에 자동으로 분배하여 서버 과부하를 방지한다. 트래픽이 많을 때도 서버 다운 없이 안정적인 서비스를 유지할 수 있다.
</li></ul>
<br>

<ul><li><strong>장애 대응</strong>
<br>: 특정 서버가 장애를 일으키면, 요청을 자동으로 정상 서버로 우회 전송하여 서비스의 안정성을 높인다.
</li></ul>
<br>

<ul><li><strong>응답 속도 향상</strong>
<br>: 요청이 여러 서버로 나누어 처리되므로, 처리 속도가 향상되고 응답 시간이 단축된다. 특히 트래픽이 급증할 때 성능 저하를 최소화할 수 있다.
</li></ul>
<br>

<ul><li><strong>확장성 확보</strong>
<br>: 서비스에 트래픽이 몰릴 때 서버를 추가하거나 제거하여 서비스의 중단 없이 유연하게 시스템 확장이 가능하다.
</li></ul>
<br><br>

### Load-Balancing의 주요 알고리즘
<ul><li><strong>라운드 로빈(Round Robin)</strong>
<br>: 요청을 서버 순서대로 차례로 분배하는 방식이다. 구현이 단순하고, 서버 성능이 비슷할 때 효율적이다.
</li></ul>
<br>

<ul><li><strong>최소 연결(Least Connections)</strong>
<br>: 현재 연결이 가장 적은 서버로 요청을 보낸다. 서버별 부하 상태를 고려하기 때문에, 트래픽이 불균형할 때 유용하다.
</li></ul>
<br>

<ul><li><strong>IP 해시(IP Hash)</strong>
<br>: 클라이언트의 IP 주소를 해시 값으로 계산해 항상 같은 서버로 연결되도록 한다. 세션 유지가 필요한 로그인 서비스 등에 적합하다.
</li></ul>
<br><br>



### Nginx 설치
```
# Nginx 설치
sudo apt install -y nginx

# 상태 확인
sudo systemctl status nginx

# 해당 경로에 파일 생성
sudo vim /etc/nginx/sites-available/simple-loadbalancer

    # 파일에 설정 작성
    upstream (프로젝트 명) {
            least_conn;
            server ipaddress1:80;  # 첫 번째 EC2
            server ipaddress2:80;  # 두 번째 EC2
    }

    server {
            listen 80;

            location / {
                proxy_pass http://(프로젝트 명);
                proxy_set_header Host $host;
                proxy_set_header X-Real-IP   $remote_addr;
      }
    }


# 기존 링크 삭제
sudo rm /etc/nginx/sites-enabled/default

# 새로 생성한 파일 링크 연결
sudo ln -s /etc/nginx/sites-available/simple-loadbalancer /etc/nginx/sites-enabled/

# 연결 확인
ls -l /etc/nginx/sites-enabled/

# 설정한 파일 문법 테스트(확인)
sudo nginx -t

# Nginx 설정만 다시 불러오기
sudo systemctl reload nginx
```
<br><br>


### Workflow 파일 및 Dockerfile 파일

| 파일 | 설명 | 링크 |
|------|------|------|
| `load_balancing_deploy.yml` | GitHub Actions 배포 설정 | 🔗 [보기](https://github.com/anna0121222/actions-load-balancing-kok/blob/master/.github/workflows/load_balancing_deploy.yml) |
| `Dockerfile` | Docker 빌드 설정 | 🔗 [보기](https://github.com/anna0121222/actions-load-balancing-kok/blob/master/Dockerfile) |

<br><br>

---

### CD/CI → Load Balancing 연동 흐름
<img alt="CD/CI → Load Balancing 연동 흐름" src="https://github.com/user-attachments/assets/11ed66ef-ec03-4caf-9d62-c3cb4ccfac68" />
<br><br>

<p align="right"><a href="#코리아-IT-아카데미-국비과정">⬆️ 처음으로</a></p>

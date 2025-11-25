# 콕 KOK | http://kok-ok.store/member/login
#### 접속 가능 시간 10:00(AM) ~ 5:00(PM)
일반 회원 ID/PW: user01@gmail.com/1234 <br>
기업 회원 ID/PW: kok01@gmail.com/1234 <br><br>

관리자 페이지 - http://kok-ok.store/admin/login <br>
관리자 ID/PW: admin@gmail.com/1234

<sub> ※ 회원가입은 지양해주시고, 하게 되시더라도 의미 없는 정보로 생성해주시길 바랍니다. </sub>

<br><br>

##  데이터 분석
### 분석 목적
연령대별 취업률 데이터를 통해 청년층이 겪는 노동시장 진입의 어려움이 실제로 존재하는지 확인하고자 했습니다.

<br>

### 데이터 수집
- 데이터 출처: [KOSIS](https://kosis.kr/statHtml/statHtml.do?sso=ok&returnurl=https%3A%2F%2Fkosis.kr%3A443%2FstatHtml%2FstatHtml.do%3Fconn_path%3DI2%26tblId%3DDT_1DA7002S%26orgId%3D101%26)
- 분석 대상: 2024년 10월부터 2025년 10월까지의 20세에서 59세까지 인구의 취업률

<br>

### 분석 결과
<img alt="image" src="https://github.com/user-attachments/assets/936553cc-f9d2-4aaa-855f-85552d90698f" />

<br>

- 청년층(20-29세)의 취업률은 연령대 중 가장 낮은 수준(59-62%)입니다. 이는 다른 연령층보다 노동시장 진입 장벽이 훨씬 크다는 점을 보여줍니다.
- 청년층의 취업률 변동 폭(표준편차)도 가장 큽니다. 월별로 취업률이 크게 흔들리며, 고용이 안정적으로 유지되지 않는 특성이 나타납니다.
- 반면 30~50대는 취업률이 높은 수준에서 일정하게 유지됩니다. 이는 청년층만이 유독 취업 진입 과정에서 불안정한 구조에 놓여 있다는 점을 나타냅니다.

<br>

### 결론
이러한 데이터를 통해 확인된 낮은 취업률과 높은 변동성을 고려하면, 청년층은 안정적인 경력 형성의 기회를 확보하기 어려운 환경에 놓여 있는 상태입니다.
청년층이 실무 경험을 쌓기 전에는 취업률이 안정되지 않는 구조라는 점이 드러나며, 경험 기반의 기회가 청년층의 취업률에 도움이 될 것이라고 판단했습니다.


<br><br>



## 🔍 기획 의도
### 일자리 체험 플랫폼
<img alt="슬라이드2" src="https://github.com/user-attachments/assets/e6a3caee-0e17-4456-a567-f33c622f83ce" />
<br><br>

현대 사회의 청년들은 <strong>실무 경험의 부족</strong>으로 취업 경쟁에서 여러움을 겪고 있다. 경력자인 50-60대의 취업률은 늘어나는 반면, 20-30대의 취업률은 떨어져만 가고 있다. 반대로 기업은 인재를 채용하기 전에 그들의 역량과 열정을 직접 확인하기 어려워 비경력직의 채용을 피하고 있다. <strong>또한, 기업 내 휴가·공백 기간이 발생해도 이를 효율적으로 채우기 위한 방법이 없다. </strong> 이러한 기회의 단절과 인재 탐색의 비효율성을 해결하기 위해, <strong>청년과 기업이 자연스럽게 연결되는 실무 체험 플랫폼</strong>을 제작했다.
<br><br><br>

## ⚡ 기대 효과
<img alt="슬라이드4" src="https://github.com/user-attachments/assets/2c6c71a9-c0c9-4016-bec6-13d38ed6e914" />
<ul>
<li><strong>청년층의 실무 경험 확대</strong>
<br>: 단기 체험을 통해 다양한 직무를 직접 경험하고 경력의 첫 단추를 끼울 수 있도록 지원. 실무 기반의 경험 제공으로 취업 경쟁력 강화, 다양한 직문 탐색을 통한 진로 확장</li>
<br>
<li><strong>기업의 인재 발굴 및 공백 해소</strong>
<br>: 단기 업무 공백 해소, 체험 과정에서 직접 검증된 인재 확보, 채용 리스크 감소 및 효율적 인재 발굴</li>
<br>
<li><strong>상호 이해 기반의 채용 연결</strong>
<br>: 이력서나 면접이 아닌, 실제 체험 과정에서의 태도와 역량으로 평가하는 경험 중심 채용</li>
</ul>
<br><br>



## 🛠️ 기술 스택 (Tech Stack)

| 구분 | 사용 기술 |
|------|------------|
| **HTML Engine** | Thymeleaf |
| **Frontend** | HTML, JavaScript, CSS |
| **Backend** | Spring Boot, Java |
| **Database** | PostgreSQL, Redis |
| **Infra** | AWS EC2, AWS IAM, AWS S3 |
| **Development Tools** | VS Code, IntelliJ IDEA |
| **API & Library** | Kakao Login, Kakao Map, Kakao 주소 API, SMTP Gmail API, REST API, Lombok, MyBatis, OAuth 2.0, Google Login, Boot Pay, Naver Login, JWT, Spring Security, CoolSMS, Swagger UI |
| **Collaboration & Version Control** | Git, GitHub, Slack, Postman, Sourcetree |
| **Testing** | JUnit5 |

<br><br>

## 🧱 ERD
<img alt="erd" src="https://github.com/user-attachments/assets/815cd1a4-7811-4f7e-b07f-355dea015e0f" />

<br><br>


## 👨‍💻 담당 업무
### 🗂️ 프론트엔드
<img alt="kok_front" src="https://github.com/user-attachments/assets/3d606fd3-bba1-4d8a-8960-808768672f05" />
<br>

▶ 회원가입
- 일반 회원 회원가입(+모바일)
- 기업 회원 회원가입(+모바일)

▶ 로그인
- 일반 회원 로그인(+모바일)
- 기업 회원 로그인(+모바일)
- 이메일 찾기(+모바일)
- 비밀번호 찾기(+모바일)

▶ 서비스 소개
- 사이트 서비스 소개 페이지


<br>

### 🗂️ 백엔드
<img alt="kok_back" src="https://github.com/user-attachments/assets/76e1105f-3423-4a7b-83d6-6563e439337a" />
<br>


▶ 관리자 페이지
- 홈화면: 월간 체험/인턴 공고 게시 및 신청 수, 체험 결제액, 광고 결제액 차트와 평균/총합 표 확인
(Restful)
- 관리자 등록: 새로운 관리자 계정 등록
- 체험: 올라온 모든 체험 공고 목록 및 상세보기(Restful)
- 고용: 올라온 모든 인턴 공고 목록 및 상세보기 (Restful)
- 결제(광고비): 기업이 결제한 광고비 목록 (Restful)
- 결제(체험비): 회원이 결제한 체험비 목록 (Restful)
- 공지사항: 관리자가 등록한 공지 목록 및 상세보기. 등록/수정/삭제 가능
- 신고 게시글: 커뮤니티에서 신고 받은 게시글 목록 및 상세보기 (Restful)
- 현수막: 사이트에서 사용할 배경 이미지 등록 및 삭제 (Restful)
- 광고: 기업에서 신청한 모든 광고 신청 목록 및 상세보기 (Restful)

<br>

▶ 고객센터
- 관리자 페이지에서 등록한 공지사항을 볼 수 있는 사이드 바를 누르면 나타나는 목록과 상세 (Restful)


<h2>❗ 트러블 슈팅</h2>


<img alt="20251009190811(2)" src="https://github.com/user-attachments/assets/154dbfbc-fa90-42b9-ab70-4dca3623b8e1" />
<br>

<오류 화면><br>
service.js와 layout.js를 이벤트를 실행했을 때 오류가 뜨며 데이터를 불러오는 데 실패한다. <br> <br>


<img alt="고친 코드" src="https://github.com/user-attachments/assets/a4450efc-b817-4c59-a025-32f78b6b8f3e" />
<br>

<완성 코드><br>
 DOM 요소가 만들어지기 전에 js에 불러와서 생기는 오류로, if 조건문을 통해 데이터를 불러온 이후, 즉 DOM 요소가 만들어진 뒤에 이벤트가 발생되도록 작성하면 해결되는 코드였다. 그러나 처음에는 querySelector 등으로 불러온 요소가 null인 이유를 알지 못해 어려웠다. 그래서 화면에 데이터를 불러와 배치하는 흐름을 다시 되짚어보며 순서가 잘못되지는 않았는지 확인하여 해결했다. <br><br>
 
 ✔ 위 예시 외에도 오류가 일어났던 원인들을 파악하고 나면 흐름이나 순서가 원인인 경우가 종종 있었다. 이런 경우에는 어떤 부분에서 오류가 났는지 명확히 파악하기가 어렵기 때문에 처음부터 차근차근 출력하며 짚어봐야 했고, 시간이 많이 걸리는 과정이었다. 하지만 이런 과정을 몇 번 반복하다 보니 어느 부분에서 오류가 났을지 비교적 빠르게 짐작할 수 있었다. 나중에는 단위 테스트와 작업을 같이 진행하여 오류를 찾는 데 드는 시간을 단축할 수 있었다. 문제를 해결하는 요령이 생긴 것 같아 뿌듯했다.<br>
<br><br>


## 문제 해결

### 📌무한 스크롤과 로딩 gif
<ul>
<li><strong> 🌩문제 상황 </strong>
<br>: 데이터를 10개씩 무한 스크롤 형식으로 보여주고, 불러오는 시간 동안 로딩 gif를 띄우고자 했으나 layout.js에서 +=로 목록이 중첩되므로 로딩 gif도 목록을 불러올 때마다 쌓이게 되었다.
</li><br>

<li><strong> 🚨문제 원인 </strong>
<br>: 목록을 불러올 때마다 쌓이는 로딩 gif
</li><br>

<li><strong>🚀해결 방법 </strong>
<br>: 기억나는 방법 안에서만 해결하고자 했던 것이 문제였다. 시야가 좁아지니 평소 보던 것과는 다른 문제가 나타났을 때 이를 해결할 방법을 찾지 못한 것이다. js에서 어떤 요소를 나타내거나 숨길 때에는 style의 display: none; 혹은 visible: hidden;을 사용했는데 이번 문제는 로딩 gif의 중첩이 문제였으므로 해결법이 되지 못했다. 때문에 remove();를 사용하여 중첩되는 로딩 gif를 삭제했다.
</li></ul>
<br>

### 📌상세보기의 내용이 모두 같은 목록 
<ul>
<li><strong>🌩문제 상황 </strong>
<br>: 각 항목의 버튼을 누르면 해당 항목의 상세내용을 보여줘야 하는데, 모든 항목의 상세내용이 동일했다.
</li><br>

<li><strong>🚨문제 원인 </strong>
<br>: id를 제대로 받아오지 못하여 데이터를 불러오지 못하였으므로 html에 예시로 작성해놓은 내용이 나타난 것이었다.
</li><br>

<li><strong>🚀해결 방법 </strong>
<br>: 목록을 화면에 표시할 때 태그 안에 data-id = "${id}"를 작성하여 버튼을 누를 때 해당 항목의 id를 받아와 올바른 상세 내용을 불러오도록 했다. 버튼을 누를 때 나타나는 모달 창에 데이터를 표시하기 위해서 event.js에 작성되어 있던 기존 구조를 재조립했다.
</li>
</ul>
<br><br>


## 느낀점

#### 🌟 협업: 프로젝트 속의 모든 요소는 서로 연결되어 있다
내가 맡은 부분은 관리자 페이지로, 모든 서비스를 점검하고 통계를 확인할 수 있는 영역이었다. <strong>겉보기에는 독립된 페이지처럼 보였지만, 실제로는 모든 서비스와 유기적으로 연결되어야 했기 때문에 구조적으로 전반적인 시스템 흐름을 이해해야 했다.</strong>
다른 팀원이 구현한 기능이 완료되어야 마무리할 수 있는 경우도 있었기에 수정 시 서로의 코드에 영향을 주었다. 이 과정에서 다른 팀원의 코드를 분석하고 재사용하거나 변경된 데이터 구조에 맞춰 내 코드도 함께 수정하는 일이 종종 있었다. 
겉으로는 각자 맡은 파트를 진행하는 것처럼 보였지만, <strong>실제로는 모든 작업이 연결된 협업 구조</strong>였다. <strong>각자의 역할이 분리되어 있어도 혼자서 완성할 수 있는 부분은 없었고, 팀 전체의 흐름을 이해하며 함께 조율해야 비로소 완성</strong>되는 작업이라는 것을 알게 된 프로젝트였다.
 
#### 🌟 디버깅: 문제의 본질을 파악하자 
처음에는 오류가 발생하면 어디에서 잘못된 것인지 찾기 보다는 막막한 마음이 먼저 들었다. 코드 한 줄 한 줄을 살펴봐야 한다고 생각했기 때문이다. 하지만 단순히 오류를 고치기 보다는 어떤 오류 메시지가 떴는지, 어떤 부분을 출력해보는 게 좋을 지, 그리고 현재 코드가 어떤 흐름으로 동작하는가를 이해하는 게 중요하다는 걸 깨달았다. 빨간줄을 없앤다기 보다는 문제의 근본 원인을 구조적으로 분석해야겠다고 생각했다.

#### 🌟 미래: 성장하는 개발자 
지난 프로젝트에서는 진도를 따라가기 바빠 맡은 부분이 많지 않았지만, 이번에는 일부를 제외한 관리자 페이지 전반을 직접 맡아 구현할 수 있었다.
그 과정에서 단순히 복습하며 따라 치기만 했던 REST 방식을 실제로 적용해보았고, <strong>예전에는 어렴풋하게만 이해되던 데이터 흐름과 구조가 눈에 보이기 시작</strong>했다.
직접 부딪히며 하나씩 해결할 때마다 신기하고 뿌듯했다. 이 경험이 <strong>단순한 프로젝트 참여를 넘어 한 단계 성장한 개발자로 나아가는 계기</strong>가 되었다고 생각한다.
앞으로도 이렇게 배운 것을 직접 적용하고, 스스로 이해하며 <strong>꾸준히 성장하는 개발자가 되고 싶다.</strong>

<br>

---------------------------------------------------------------------------

<br>

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

# What I learned in week1

### 기초 백엔드 스터디 OT ###

- 멘토님은 기아 타이거즈 팬이시다
- 잘생기셨다
- 첫사랑 이야기는 묻지 말자
- 구글&Stack Overflow와 깊은 면담 후 질문하기
- 우수 스터디원이 되려면 300자이상 분량을 채워야 한다
### 스터디
- Django와 백엔드 관련된 지식들
- 이론/코드/실습 형태로 수업 진행됨
- 별 일 없다면 화요일 6시~7시
---
## 1주차 수업 ##
### Django
![alt text](Django_logo.svg.png)

Python 웹 프레임워크. 오픈소스이며, 빠르고 python 언어를 사용하여 개발할 수 있다는 것이 장점이다.

~~(D는 묵음이다)~~
### 웹 기초
**인터넷**

전 세계 컴퓨터를 거대한 네트워크로 연결한 시스템이다. 이 연결을 위해 [TCP/IP](https://en.wikipedia.org/wiki/Transmission_Control_Protocol) 라는 지정된 protocol을 사용하여 정보를 주고받고 있다.

**프로토콜**

서로 다른 기기들 간에 통신을 하기 위해 서로 신호를 보내고 받는다. 문제는 정보를 어떻게 신호에 저장할지 합의하지 않으면 서로의 말을 이해하지 못한다는 것이다. 따라서 미리 규칙을 지정하여 놓은 것이 프로토콜Protocol 이다. 유명한 것으로는
- TCP/IP
- HTTP/HTTPS
- SMTP
- SSH
- FTP

등이 있다
	
**World Wide Web**

거미줄(Web)처럼 망으로 구성되어 정보를 주고 받는다. 
- HTML로 작성

![alt text](HTML5_logo_and_wordmark.svg.png)

HTML(HyperText Mark-Up Language)
Markup Language 중 하나로, XML처럼 tag(<>) 형식으로 데이터를 기록한다. 웹 페이지의 내용과 구조를 정의하는데에 사용된다. 주로 CSS, JS와 함께 사용되에 웹 페이지를 이룬다.
- URL 로 위치 지정

URL(Uniform Resource Locator)은 웹의 네트워크 상에서 특정 리소스가 어디있는지를 가리키는 일종의 주소이다. 

`프로토콜://호스트:포트/경로/파일 파라미터`
의 형태로 주로 구성된다.
- HTTP로 데이터 전송

![alt text](HTTP_logo.svg.png)

HTTP(HyperText Transfer Protocol)은 hypermedia를 전송하는데에 사용하는 인터넷 프로토콜이다. 주로 HTML을 전송하는데에 사용한다. 단순히 텍스트만 보낼 수 있는 것이 아니라는 점에서 여러 미디어가 결합된 웹 페이지를 만들 수 있게 되었다.

TCP/UDP를 사용하며, 포트 80을 사용한다. HTTP를 통해 사용자가 서버에게 요청(Request)을 보내면 서버가 대답(Response)로 대응되는 HTML/파일을 보내준다.

이후 보안을 보다 강화시킨 HTTPS 또한 만들어졌다.

```http
GET /restapi/v1.0 HTTP/1.1
Accept: application/json
Authorization: Bearer UExBMDFUMDRQV1MwMnzpdvtYYNWMSJ7CL8h0zM6q6a9ntw
```
이런 통신은 웹 브라우저에서 개발자 도구를 통해 실제 어떤 request와 response가 오갔는지 확인할 수 있다.

## 그래서 Front-end와 Back-end는 뭐하는걸까

Front-end는 client와 서버 사이에서 서버의 정보를 받고, 웹 페이지에서 그걸 어떻게 처리하고, 보여줄지 계획&설계하는 일을 한다.

Back-end는 DB와 Front-end 사이에서 원하는 정보를 client에게 보내주거나, 조건에 맞춰 DB의 내용을 수정&저장하는 일을 한다. 

<br>

# 느낀점
사실 1주차 수업은 개인사정으로 못들었는데 PPT는 내 스타일이여서 좋았다.
또 주인장 블로그 들어가보니까 백준 플래티넘이라길래 백준 실버인 1人으로써 의지가 타올랐다.


꼭 선생님 얼굴은 한번은 보고 스터디를 마치겠습니다:)


# 참고문헌
- https://en.wikipedia.org/wiki/URL
- https://en.wikipedia.org/wiki/Transmission_Control_Protocol
- https://en.wikipedia.org/wiki/URL
- https://en.wikipedia.org/wiki/Django_(web_framework)
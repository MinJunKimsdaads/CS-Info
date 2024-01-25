HTTP(Hypertext Transfer Protocol)
HTTPS(Hypertext Transfer Protocol Secure)
SSL(Secure Sockets Layer)
= 웹에서 데이터를 안전하게 전송하기 위한 프로토콜 및 보안 기술.

HTTP (Hypertext Transfer Protocol):

HTTP는 웹 브라우저와 웹 서버 간에 데이터를 전송하는 데 사용되는 프로토콜.
일반 텍스트로 통신하므로 데이터는 평문으로 전송되며, 보안성이 낮음.
예시: 사용자가 웹 브라우저에 "http://www.example.com"을 입력하면, 브라우저는 해당 서버로 HTTP 요청을 보내고, 서버는 요청된 데이터를 평문으로 응답.

SSL (Secure Sockets Layer):

SSL은 네트워크 연결을 보호하기 위한 프로토콜.
SSL은 데이터를 암호화하여 중간에 있는 공격자가 데이터를 엿보거나 조작하지 못하도록 보호.
클라이언트와 서버 간의 통신을 안전하게 만들기 위해 사용.
HTTPS (Hypertext Transfer Protocol Secure):

HTTPS는 HTTP의 보안 버전으로, SSL을 사용하여 데이터를 암호화하고 안전한 통신을 제공.
HTTPS는 URL이 "https://"로 시작하며, 보통 로그인 페이지, 결제 페이지, 개인 정보 전송 등에서 사용.
예시: 사용자가 "https://www.example.com"을 입력하면, 브라우저는 해당 서버로 안전한 HTTP 요청을 보내고, 서버는 안전한 방식으로 응답.

Handshake (악수): 클라이언트가 서버에 접속하면, SSL 핸드셰이크가 발생, 이 단계에서 서버는 공개키와 인증서를 클라이언트에게 제공.

암호화: 클라이언트는 서버의 공개키를 사용하여 세션 키를 생성하고, 이 세션 키를 서버의 공개키로 암호화하여 서버에게 전송합니다.

데이터 전송: 이제 세션 키를 양쪽에서 사용하여 데이터를 암호화하고 복호화할 수 있습니다. 클라이언트와 서버 간의 모든 통신은 이 세션 키를 사용하여 보호됩니다.

이러한 과정을 통해 HTTPS는 안전한 통신을 제공하여 중요한 정보를 안전하게 전송할 수 있도록 합니다.

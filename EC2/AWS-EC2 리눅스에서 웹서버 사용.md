## AWS-EC2 리눅스에서 웹서버 사용

웹서버를 연결하기 위해서는 Apache를 설치한후 연결해야하지만 리눅스에서는 Xshell을 이용해 

**sudo apt-get install apache2**라는 명령어를 Apache에 관한 프로그램들을 설치 하게됩니다.

**sudo apt-get update**라는 목록은 최신 목록으로 업데이트후에 설치를 해줍니다.

![image-20200508233724127](C:\Users\kouym\AppData\Roaming\Typora\typora-user-images\image-20200508233724127.png)

연결을 한 후에 퍼블릭 DNS(도메인)를 검색하면 연결된 웹페이지가 나오게 됩니다.

이 서버는 웹서버를 만든것이기 때문에 보안그룹은 webserver의 아래 있습니다.

Inbound를 통해 포트를 열어줘서 방화벽에따라 접근할 수 있는 포트를 늘릴수도 있습니다.


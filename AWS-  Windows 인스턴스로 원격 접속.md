## AWS-  Windows 서버인스턴스로 원격 접속



#### Windows 서버에 원격으로 접속하는 방법

 1.만들어둔 Window인스턴스에 연결하여 다음과 같이 원격 데스크톱 파일을 다운로드 합니다.

![window1](https://user-images.githubusercontent.com/52284829/91942497-02d8c900-ed36-11ea-8bb0-edd75a93daa5.png)



 2.암호가져오기를 통해서 인스턴스의 pw를 불러온후에 원격데스크톱 파일을 실행하여 암호를 입력합니다.

![window2](https://user-images.githubusercontent.com/52284829/91957807-80ee9d00-ed41-11ea-886a-5519ed4e5e57.png)

3. 다음과 같은 과정을 걸치면 지금 만든 윈도우 인스턴스에 접속을 하게 됩니다.

   이제 만들어둔 서버에 접속을하게 되며 원격으로 이용이 가능합니다. 이외에도 서버대용으로 사용할 것이 아니라 가상 데스크톱으로도 이용할 수 있습니다.

![window3](https://user-images.githubusercontent.com/52284829/91958682-a0d29080-ed42-11ea-9afa-7b80d7bb13a6.png)



만약 가상 데스크탑용도로 사용하려면 Server Manager에서 Local Server을 누른뒤에 IE Enhanced Security Configuration을 Off로 갱신해주면 사용하기에 용이합니다.
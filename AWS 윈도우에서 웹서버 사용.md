## AWS 윈도우에서 웹서버 사용

Window서버에서는 기본적으로 웹서버가 내장되어있다. 

WIndow서버를 통해서 웹서버를 이용하는 방법입니다.



1. Server Manager에서  Manage에서 Add roles and Feature를 클릭하여 진행합니다.

   ![image-20200902181101427](C:\Users\kouym\AppData\Roaming\Typora\typora-user-images\image-20200902181101427.png)

2.next를 진행하면서 Server Roles단계에서 Web Server(IIS)를 선택합니다.

그 이후에 next를 계속해서 진행합니다.

![image-20200902181235170](C:\Users\kouym\AppData\Roaming\Typora\typora-user-images\image-20200902181235170.png)

3.설치가 완료된 후 IIS를 실행합니다.

![image-20200902181730784](C:\Users\kouym\AppData\Roaming\Typora\typora-user-images\image-20200902181730784.png)

4. Default Web Site를 통해 EXPLORER을 들어가면 이 컴퓨터를 통해 이 웹브라우저를 접속했을때 요청을 받는 파일을 찾는 디렉토리입니다

   ![image-20200902181942677](C:\Users\kouym\AppData\Roaming\Typora\typora-user-images\image-20200902181942677.png)

5. 이 파일에 "Hello AWS"란 내용의 html파일을 만들어서 저장해줍니다.

   ![image-20200902182114231](C:\Users\kouym\AppData\Roaming\Typora\typora-user-images\image-20200902182114231.png)

6.이제 인터넷을 이용해서 localhost/index.html을 접근하면 만들어둔 html을 띄우게 됩니다.

localhost는 현재 이 웹브라우저가 설치되어있는 컴퓨터이기 때문에 이 컴퓨터의 IIS의 루트파일에서 index.html을 IIS가 웹브라우저를 전송하면서 다음과 같은 html을 보여주는 것입니다.

![image-20200902182511810](C:\Users\kouym\AppData\Roaming\Typora\typora-user-images\image-20200902182511810.png)

7. 이번에는 가상머신에서 만든 html을 가상머신으로 접속한것이 아니라 본래의 컴퓨터로 가상 웹서버로 요청하려면 만들어둔 window서버의 DNS를 통해 접근하면 다음과 같이 가상머신의 Index.html 내용이 보이는것을 확인할 수 있습니다.

   ![image-20200902182811445](C:\Users\kouym\AppData\Roaming\Typora\typora-user-images\image-20200902182811445.png)
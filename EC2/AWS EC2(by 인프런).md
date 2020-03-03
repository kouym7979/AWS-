## AWS EC2(Elastic Compute Cloud)

EC2는 아마존 웹서비스중에서 가장 먼저 생겨난 서비스중 하나이며 독립된 컴퓨터를 임대해주는 서비스이다.

특징

- 가장 범용성이 좋다.
- 컴퓨팅 요구사항의 변화에 따라 컴퓨팅 파워를 조정할 수 있다.
- 새로운 서버 인스턴스 확보 및 부팅시간을 몇분으로 단축시킬 수 있다.
- 실제로 사용한 용량만큼만 지불 가능하다.
- 다양한 운영체제를 지원한다.
- 안정성을 위해 여러 AWS리전과 가용 영역에 걸쳐 배포

EC2 설정방법입니다.

1. 우선 AWS에 가입한뒤에 EC2를 눌러서 좌측 탭에 인스턴스를 눌러서 시작해줍니다.

![EC2-1](https://user-images.githubusercontent.com/52284829/75754899-e355e900-5d70-11ea-9390-97a870a2d70d.png)



2. 저는 인프런 강의에 따라서 Ubuntu Server를 선택했습니다.

![EC2-2](https://user-images.githubusercontent.com/52284829/75754958-0385a800-5d71-11ea-86ca-8f0d30e2a791.png)

3. 그리고 인스턴스 유형에서 CPU가 1인것을 선택합니다.

   ![EC2-3](https://user-images.githubusercontent.com/52284829/75755017-22843a00-5d71-11ea-845d-4053f40f3835.png)

4.  인스턴스 개수가 1인지 확인하고 넘어갑니다.

   ![EC2-4](https://user-images.githubusercontent.com/52284829/75755144-6a0ac600-5d71-11ea-833c-290e16245c5e.png)

 ![EC2-5](https://user-images.githubusercontent.com/52284829/75755231-99213780-5d71-11ea-876a-075c7003402c.png)

5.태그에는 Name으로 웹서버(가명)을 적습니다.![EC2-6](https://user-images.githubusercontent.com/52284829/75755269-a807ea00-5d71-11ea-8f59-8a9a548f0343.png)

6.보안 그룹 이름에 web server라고 적어둡니다.

- 유형에 규칙추가를 한후 HTTP를 추가해줍니다.

![EC2-7](https://user-images.githubusercontent.com/52284829/75755323-c1109b00-5d71-11ea-96bc-021f14d895a9.png)

7.작업이 완료하면 다음과 같이 앞서 선택한 정보들을 전체적으로 보여지고 웹서버가 만들어집니다. ![EC2-8](https://user-images.githubusercontent.com/52284829/75755370-d1c11100-5d71-11ea-90d4-22729d586386.png)

완료된 모습입니다!![EC2-9](https://user-images.githubusercontent.com/52284829/75755664-6592dd00-5d72-11ea-919a-9ea8dd743b8c.png)
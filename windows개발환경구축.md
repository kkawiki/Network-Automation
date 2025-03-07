네트워크 자동화 개발을 위한 개발환경 구축

Netmiko 사용

개발환경
파이썬 : 3.9.x버전 (3.10 버전부터 import netmiko 입력시 telnetlib 모듈이 없다고 나옴. 왜냐면 3.10부터 모듈 이름이 telnetlib3으로 변경됨, 3.9.9버전 확인 완료)
netmiko 버전 : 3.1.0 버전

참고 사이트 : https://nem0.tistory.com/10


파이참 이용시 인터프린터를 사용 해야하는데
anaconda로 설치
https://toward-the-future.tistory.com/entry/Python-%ED%8C%8C%EC%9D%B4%EC%B0%B8Pycharm-%EC%84%A4%EC%B9%98-%EB%B0%8F-%EC%95%84%EB%82%98%EC%BD%98%EB%8B%A4anaconda-%EA%B0%80%EC%83%81%ED%99%98%EA%B2%BD-%EC%97%B0%EB%8F%99%ED%95%98%EA%B8%B0


파이참 인터프린터에서도 netmiko를 설치 해야하는데
3.1.0으로 맞춰주면 정상적으로 사용 가능함 (최신버전으로 해도 되는지는 테스트 해봐야 함)

```
pip install netmiko==3.1.0
```

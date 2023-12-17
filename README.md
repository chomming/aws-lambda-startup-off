# IAM 정책 생성
[정책 편집기](https://github.com/chomming/aws-lambda-startup-off/blob/main/iam.json)
- 1번 statement : CloudWatch Log에 로그를 쌓을 수 있는 권한 허용
- 2번 statement : ec2 시작 및 종료

# IAM 역할 생성
![image](https://github.com/chomming/aws-lambda-startup-off/assets/81208053/e4b2cb74-a3bc-4043-a943-476625d6c687)
![image](https://github.com/chomming/aws-lambda-startup-off/assets/81208053/432559f2-9451-4e37-8283-f3de3594560b)

# 함수 생성
![image](https://github.com/chomming/aws-lambda-startup-off/assets/81208053/69d2a0cc-e955-4f2f-b027-ad8cc9928a94)
- 런타임 : python 3.8
- 아키텍처 : X86_64
- 실행 역할 : 만든 IAM 역할로 지정
<br/>

# 함수에 사용되는 코드
- [start 코드 편집](https://github.com/chomming/aws-lambda-startup-off/blob/main/start.py)
- [stop 코드 편집](https://github.com/chomming/aws-lambda-startup-off/blob/main/stop.py)

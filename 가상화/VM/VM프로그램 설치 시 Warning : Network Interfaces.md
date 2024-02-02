## VM프로그램 설치 시 Warning : Network Interfaces

![image](https://private-user-images.githubusercontent.com/48792230/301740496-3107255b-4642-43b5-8378-9ba544a3f0fb.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY4NTI4ODMsIm5iZiI6MTcwNjg1MjU4MywicGF0aCI6Ii80ODc5MjIzMC8zMDE3NDA0OTYtMzEwNzI1NWItNDY0Mi00M2I1LTgzNzgtOWJhNTQ0YTNmMGZiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAyMDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMjAyVDA1NDMwM1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWExMTkzZWFmNDBjYTk1MTc1MzczYjQyNGI2MmExMDEwZDBiM2RhMTQ5YzI5ZTQwZWIyZmNlYjdkMmJhOWI0ZDAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.QJ9ZkH7RQf6TNXIhqsADctnMWjxvklKHBZciuQisOa8)

VMware는 가상 머신을 생성하고 운영하기 위해 호스트 컴퓨터에 가상 네트워크 어댑터를 설치합니다. 가상 네트워크 어댑터는 가상 머신이 호스트 컴퓨터의 네트워크 리소스를 공유하거나 독립적으로 사용할 수 있도록 하는 역할을 합니다.

즉, `가상 머신이 인터넷에 접속할 수 있도록 하기 위해`, 실제 컴퓨터의 네트워크 설정을 조금 바꾸는 것이죠. 이 과정에서 잠시 네트워크 연결이 끊길 수 있는데, 이는 정상적인 현상입니다.


1. VMware 설치 파일 실행: 사용자가 VMware 설치 파일을 실행하면, 설치 프로그램이 작동합니다.
2. 가상 네트워크 어댑터 설치: 설치 프로그램이 가상 네트워크 어댑터를 호스트 컴퓨터에 설치합니다. 이 과정에서 호스트 컴퓨터의 네트워크 설정이 일시적으로 변경될 수 있습니다.
3. 네트워크 연결 일시 중단: 호스트 컴퓨터의 네트워크 설정이 변경되는 동안에는 네트워크 연결이 잠시 끊어질 수 있습니다. 이는 호스트 컴퓨터의 네트워크 설정을 가상 네트워크 어댑터에 맞게 조정하는 과정에서 발생하는 현상입니다.
4. 네트워크 연결 복구: 가상 네트워크 어댑터의 설치와 네트워크 설정 변경이 완료되면, 네트워크 연결이 다시 복구됩니다.
5. VMware 설치 완료: 나머지 설치 과정이 진행되고, VMware 설치가 완료됩니다.


이와 같이 VMware가 가상 네트워크 어댑터를 설치하는 과정에서 네트워크 연결이 일시적으로 끊어질 수 있지만, 이는 일시적인 현상이므로 걱정하실 필요는 없습니다.

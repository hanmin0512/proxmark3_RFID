# Proxmakr3
Proxmark3는 RFID(무선 주파수 식별) 보안 분석, 연구, 개발을 위한 다목적 하드웨어 도구이다.
125kHz(저주파)와 13.56kHz(고주파) RFID태그를 지원하며, 태그를 일고 에뮬레이션하고, 스니핑하거나 복제할 수 있다.

## 하드웨어: proxmark3 easy 256kb
256k는 용량이 적어 512로 사는 것이 좋다고 한다.

## proxmark3 설치 방법
1. proxspace-master install: https://github.com/Gator96100/ProxSpace/archive/master.zip
2. proxmark3-3.1.0 install: https://github.com/Proxmark/proxmark3/releases
3. proxmark3(git repo) install: https://github.com/RfidResearchGroup/proxmark3

### 드라이브 설치

![image](https://github.com/user-attachments/assets/adaf6cfa-e7bb-47ce-b57b-9ed8e48f10db)

![image](https://github.com/user-attachments/assets/d2c10a76-f376-419e-85de-f283f0f55658)

![image](https://github.com/user-attachments/assets/afefd667-519b-440d-b5a9-4486942edb22)

![image](https://github.com/user-attachments/assets/214e809b-8e79-4a52-9a03-64b04d2c9e70)

![image](https://github.com/user-attachments/assets/03a13c4c-29d9-400b-9c04-a763ccbc8549)

![image](https://github.com/user-attachments/assets/04342680-2114-46c8-a865-d7a1c982b989)

![image](https://github.com/user-attachments/assets/33ca3eaf-9f12-44b2-bd51-f63682f0e1f2)

![image](https://github.com/user-attachments/assets/5924fbee-842d-43f0-a01a-20bb54b724da)

![image](https://github.com/user-attachments/assets/73efb0cf-2dfd-4d9b-bedc-5b8c6a6ac4d7)

### 파일 위치 설정

![image](https://github.com/user-attachments/assets/530f1064-3751-40b8-bff5-451770b7ad5c)

![image](https://github.com/user-attachments/assets/02b42e2d-35e1-4b9f-bd26-0213e6215af8)

- 실행 하는동안 시간이 많이 걸리기 때문에 pm3 파일안을 조금 수정해준다.

![image](https://github.com/user-attachments/assets/365570b0-6933-4011-8a7d-2a4b1b41d236)

- Makefile.platform 파일을 아래 사진과 동일하게 주석을 제거하여 수정해준다.

![image](https://github.com/user-attachments/assets/92fdf1d5-a5d7-4418-9a2f-676f8496075e)

- (20분 후 콘솔창이 뜰 것이다.)

<h3>VoIP(Voice over Internet Protocol) 기능 만들기</h3>    

#### 서버
>Asterisk : IP 기반의 전화 시스템 및 통신 응용 프로그램을 개발하는 데 사용<br>
FreePBX : Asterisk를 기반으로 한 오픈 소스 PBX (Private Branch Exchange) 시스템 GUI를 통해서 Asterisk를 손쉽게 사용 할 수 있게 함<br>

#### 클라이언트
> 라즈베리파이(Twinkle) :  Linux 운영 체제에서 동작하는 오픈 소스 VoIP 소프트폰(softphone)<br>
 모바일(MizuDroid) : MizuDroid는 안드로이드 기반의 오픈 소스 VoIP 소프트폰(softphone) 애플리케이션<br>
 윈도우PC(microSIP) : microSIP은 Windows 운영 체제에서 동작하는 오픈 소스 VoIP 소프트폰(softphone) 프로그램<br>

 ![p-r](https://user-images.githubusercontent.com/71440946/237022267-1696d3cb-22d2-4fe1-9301-2aca08f9db51.gif)
 
 phone -> rasberry
 
 ![r-p](https://user-images.githubusercontent.com/71440946/237022545-935b91b5-32b7-4fbb-97a1-f0a6fcef9f85.gif)

rasberry -> phone
 <br>
<h3>라즈베리파이에서 VoIP 기능 만들기 (2) 예정</h3>


- Thonny를 활용해서 파이썬 코딩<br>
 
 코드를 실행하면 자동으로 Twinkle을 실행해서 지정된 번호로 Dial을 거는 코드.

- Python의 pyttsx3를 활용해서 tts 음성파일을 만든 후 FreePBX IVR기능을 사용해서 전화를 받았을때 자동으로 음성파일을 재생해주는 기능

 이 부분은 음성파일을 만드는 것 까진 완료 FreePBX를 활용하는게 어려워서 문서 참조 예정


 <h4>과정 총 정리</h4>
 https://velog.io/@pokill/라즈베리파이에서-VoIP-기능-만들기-1

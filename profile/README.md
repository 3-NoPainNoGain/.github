## 🩺 청각장애인 대상 수어/음성 텍스트 변환 대면+비대면 진료 서비스, handDoc
> 🏆 이화여자대학교 컴퓨터공학과 졸업 프로젝트 포스터 세션 대상 수상 <br>
> 🏆 제 9회 개방형 클라우드 플랫폼 (K-PaaS) 활용 공모전 동상(오픈클라우드플랫폼얼라이언스의장상) 수상 <br>
> 🏆 2025 전국 대학생 창업 아이디어톤 장려상 수상 <br>
> 🏆 2025 신촌 대학 연합 SW 창업 경진 대회 은상 수상 <br>
> 🏆 2025 2학기 이화여자대학교 졸업프로젝트 대상 수상 <br>


</br> 

## 🚀 프로젝트 소개 

handDoc은 청각장애인을 위한 수어/음성-텍스트-변환 대면+비대면 진료 서비스를 제공하는 웹 애플리케이션입니다. 청각장애인의 수어를 인식하고 의사에게 텍스트로 변환되어 전송되며, 의사의 음성 또한 텍스트로 변환되어 환자에게 전달됩니다. 수어가 아닌 구음을 사용하는 환자를 위한 파인튜닝된 Whisper 모델 텍스트 변환 기능도 제공합니다. 이를 통해 청각장애인과 의료진 간의 원활한 의사소통을 지원하며, 비대면 상황에서도 의료 서비스를 동등하게 이용할 수 있는 환경을 제공합니다. 

</br> 

## 📂 파트별 Repository 
- 각 파트별 기술 스택과 세부 구현 내용은 링크된 파트별 `README.md` 에서 확인할 수 있습니다.

  - [Sign-AI](https://github.com/3-NoPainNoGain/Sign-AI) : Python 기반 AI 서버. WebSocket 통신을 통해 영상 프레임을 전달받고, 수어 인식 결과를 반환
  - [Speech-AI](https://github.com/3-NoPainNoGain/Speech-AI) : Python 기반 AI 서버. 파인 튜닝된 Whisper 모델을 통해 음성 텍스트 변환 
  - [Frontend](https://github.com/3-NoPainNoGain/FE) : React 기반 사용자 인터페이스. WebRTC 연결을 통한 화상 진료 및 실시간 사용자 인터랙션 구현 
  - [Backend](https://github.com/3-NoPainNoGain/BE) : Spring Boot 기반 백엔드, 사용자 인증, WebRTC 신호 교환 등 핵심 서비스 로직 담당

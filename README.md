# 🩺 handDoc 

> handDoc는 청각장애인을 위한 수어/음성-텍스트 변환 대면+비대면 진료 서비스를 제공하는 웹 애플리케이션입니다. 청각장애인의 수어를 인식하고 의사에게 텍스트로 변환되어 전송되며, 의사의 음성 또한 텍스트로 변환되어 환자에게 전달됩니다. 이를 통해 청각장애인과 의료진 간의 원활한 의사소통을 지원하며, 비대면 상황에서도 의료 서비스를 동등하게 이용할 수 있는 환경을 제공합니다.


## 📂 파트별 Repository 
- 각 파트별 기술 스택과 세부 구현 내용은 링크된 파트별 `README.md` 에서 확인할 수 있습니다.

  - [Sign-AI](https://github.com/3-NoPainNoGain/Sign-AI) : Python 기반 AI 서버. WebSocket 통신을 통해 영상 프레임을 전달받고, 수어 인식 결과를 반환
  - [Speech-AI](https://github.com/3-NoPainNoGain/Speech-AI) : Python 기반 AI 서버. 파인 튜닝된 Whisper 모델을 통해 음성 텍스트 변환 
  - [Frontend](https://github.com/3-NoPainNoGain/FE) : React 기반 사용자 인터페이스. WebRTC 연결을 통한 화상 진료 및 실시간 사용자 인터랙션 구현 
  - [Backend](https://github.com/3-NoPainNoGain/BE) : Spring Boot 기반 백엔드, 사용자 인증, WebRTC 신호 교환 등 핵심 서비스 로직 담당

## 👥 팀 Repository 
- [팀 그라운드 룰](https://github.com/3-NoPainNoGain/.github/blob/main/GroundRule.md) 
- [보고서](https://github.com/3-NoPainNoGain/.github/tree/main/report)

  - [1차 보고서](https://github.com/3-NoPainNoGain/.github/blob/main/report/1%EC%B0%A8%EB%B3%B4%EA%B3%A0%EC%84%9C.md)
  - [2차 보고서](https://github.com/3-NoPainNoGain/.github/blob/main/report/2%EC%B0%A8%EB%B3%B4%EA%B3%A0%EC%84%9C.md) 

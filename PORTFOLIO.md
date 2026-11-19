# 김민서 포트폴리오


📌 Intro
안녕하세요! 맡은 역할을 끝까지 해내는 끈기를 코드로 이어가고자 하는 김민서입니다.
화려함보다 기본기와 안정성을 중시하며, 직접 고민하고 구현한 프로젝트 과정은 아래에서 확인하실 수 있습니다.


📌 프로젝트 개요
진행 기간: 2026.09 ~ 2026.11
* 개발 인원: 2명 (백엔드 서버리스, 보안 구조 설계 및 고령층 특화 UI/UX 개선 오류 수정 담당)
* 사용 기술: 'Flutter' 'Dart' 'Firebase Cloud Functions' 'OpenAI Whisper' 'GPT-5.6 Luna'


📌 주요 화면 및 시연 
<img width="1080" height="2017" alt="저장완료화면" src="https://github.com/user-attachments/assets/51b7b098-3418-4d94-a2b3-153e304a1993" />
<img width="1080" height="2027" alt="일정2번째화면" src="https://github.com/user-attachments/assets/c13d32f5-9ca0-42ef-a334-8a0ba34e8975" />
<img width="1080" height="2018" alt="일정1번째화면" src="https://github.com/user-attachments/assets/ea833188-2829-4451-9108-2b920772c94c" />
<img width="1080" height="2017" alt="설정화면" src="https://github.com/user-attachments/assets/439fd082-b206-4941-ab25-e5983b4787ff" />
<img width="1080" height="2040" alt="변환중화면" src="https://github.com/user-attachments/assets/e02e19bf-82e3-4787-9d64-dd773bd38fd6" />
<img width="1080" height="2016" alt="메인화면(크게보기모드)" src="https://github.com/user-attachments/assets/102aad64-4c03-4114-98a9-722f16330078" />
<img width="1080" height="2032" alt="메인화면(기본)" src="https://github.com/user-attachments/assets/fa3d4bae-00f4-4ab2-a14c-ad6129d3e15c" />
<img width="1080" height="2027" alt="메뉴화면" src="https://github.com/user-attachments/assets/6ad69665-ed9a-42be-8a2e-412b3b321ec6" />
<img width="1080" height="2032" alt="녹음중화면" src="https://github.com/user-attachments/assets/4185debe-1e42-48ca-8f59-60dad6579912" />
<img width="1080" height="2029" alt="녹음실패화면" src="https://github.com/user-attachments/assets/c16fb541-cf25-448b-9b46-27359a4ef208" />


📌 담당 역할 및 핵심 구현 기능
  1. API 키 보안 구조 설계
  - OpenAI API 키가 클라이언트에 노출되어 유출되는 것을 방지하기 위해 서버리스 아키텍처 도입
  2. Cloud Functions 구현, 배포
  - `Firebase Cloud Functions`를 통해 Whisper 음성인식 및 GPT-5.6 Luna 일정 추출 API를 안전하게 연 동, 배포
  3. 와이어프레임 2, 4차 버전 제작
  4. UI/UX 평가 및 오류 수정
  - 알림 표시, 실패 안내, 글자 크기 관련 오류를 찾아 수정

    
📌 문제 해결 경험
* 고령층 사용자의 화면 조직 혼란 및 변환 대기 중 이탈 문제 개선

원인: 작은 글씨와 복잡한 조작이 고령층의 일정 관리에 어려움이 되며, 음성을 일정으로 변환하는 동안 진행 상태가 보이지 않으면 사용자가 기다리지 못하고 화면을 나갈 수 있음
해결: 와이어프레임 2, 4차 작업과 피드백 반영을 통해 '크게 보기 모드'를 구현하고 취소 버튼을 수정했으며, 알림 표시, 실패 안내, 글자 크기 오류를 정비함. 또한 일정 변환 중 진행 단계를 표시하도록 개선함
결과: 고령층이 별도의 도움 없이도 화면 상태를 직관적으로 파악하며 일정을 등록할 수 있는 사용성을 확보함



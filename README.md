# AI 기반 퀴즈 생성 웹서비스
### ✅ 프로젝트 개요
- StudyBoost는 사용자가 업로드한 Markdown 파일을 분석하여 AI 기반 퀴즈를 자동으로 생성하는 웹서비스입니다. 
- 사용자는 학습한 내용을 Markdown 형식으로 작성한 파일을 업로드하면 해당 파일을 바탕으로 퀴즈를 생성하고 이를 풀며 반복 학습할 수 있습니다. 주기적으로 퀴즈를 제공하여 사용자의 학습 효율성을 극대화하는 것을 목표로 합니다.
### ✅ ERD
👉 https://github.com/Han00903/StudyBoost/wiki/ERD
<img src="https://github.com/user-attachments/assets/dd8229b2-c85d-492f-bd6a-722ef6b1eccd" alt="image" width="500"/>

### ✅ 데이터 흐름
- 사용자가 회원가입 -> 로그인을 진행합니다.
- 사용자가 Markdown 파일 업로드 -> AI가 퀴즈 생성합니다.
- 생성된 퀴즈와 각 퀴즈 질문을 Quiz와 QuizQuestion 테이블에 저장합니다.
- 사용자가 퀴즈를 풀고, 결과는 QuizResult 테이블에 저장되며, 점수와 피드백을 제공합니다.



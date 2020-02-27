# 프로그라피 6기 React Native 사전 과제 안내

서비스 개발에 필요한 사항들을 보기 위한 과제입니다.

꼭 모두 구현해야 합격하는 것이 아니니, 최선을 다해 과제에 임해주시면 감사하겠습니다.

---

### 구현 기능 명세

- 구현 예시 (이 Repository에 포함된 동영상도 참고)

<img src="https://user-images.githubusercontent.com/38369729/75458490-39b5d700-59c1-11ea-8af3-f0ad51862868.png" width="300" height="600">
  <img src="https://user-images.githubusercontent.com/38369729/75458496-3c183100-59c1-11ea-8a6f-b7b166455c92.png" width="300" height="600">
  <img src="https://user-images.githubusercontent.com/38369729/75458500-3cb0c780-59c1-11ea-8b42-b033c2b7f38e.png" width="300" height="600">


- Home에서 화면 이동

  - To Do List 화면과 Movie 화면으로 이동 가능한 버튼 생성

  - 사용 라이브러리: react-navigation

- To Do List CRUD (Create Read Update Delete) 구현

  - 메모 리스트 보기, 쓰기, 수정, 삭제 + 완료 시 메모 위에 선 긋기 (line-through)

  - TextInput, TouchableOpacity 사용

  - 상태 관리 라이브러리 사용 (redux, mobx, context api 등 무관)

- API 이용한 영화 제목 리스트 출력

  - 비동기 처리

  - 사용 API: https://yts.mx/api/v2/list_movies.json?limit=50

- 스타일링

  - StyleSheet 또는 Styled-Components 라이브러리 이용

  - 각 화면 스타일링은 자유입니다.

- 그 외

  - 위에 적은 내용을 바탕으로 자유롭게 구현해주시면 됩니다.

---

### 출제 의도

- 실제 서비스 개발 과정에서 필요한 기본적인 기능을 구현할 수 있는지 파악하기 위함

- 서버와 통신 시 사용하는 Api 사용 & 비동기 처리 가능 여부 파악

- 컴포넌트 스타일링 가능 여부 파악

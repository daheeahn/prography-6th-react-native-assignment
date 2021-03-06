# 프로그라피 6기 React Native 사전 과제 안내

안녕하세요. 프로그라피에 지원해주셔서 감사합니다 :) 팀원들과 협업 시 서비스 개발에 필요한 사항들을 보기 위한 과제입니다.

꼭 모두 구현해야 합격하는 것은 아니니, 최선을 다해 과제에 임해주시면 감사하겠습니다.

---

### 구현 기능 명세

- 구현 예시 (순서대로 Home, ToDoList, Movie 화면 / 이 Repository에 포함된 동영상도 참고)

<img width="1329" alt="Apps" src="https://user-images.githubusercontent.com/38369729/75601497-0bd6ac80-5aff-11ea-9c23-657ac5b94393.png">


- Home에서 화면 이동

  - To Do List 화면과 Movie 화면으로 이동 가능한 버튼을 생성

  - 사용 라이브러리: react-navigation
  

- To Do List CRUD (Create Read Update Delete) 구현

  - 메모 리스트 보기, 쓰기, 수정, 삭제 + 완료 시 메모 위에 취소선 긋기 (line-through)
  
  - '메모를 적어보세요'가 적힌 박스에 메모를 적고 '추가' 버튼을 누르면 하단에 메모가 추가됨
  
  - 메모를 클릭하면 취소선이 그어짐. 취소선이 그어진 상태에서 다시 메모를 클릭하면 취소선이 사라짐
  
  - '수정' 버튼을 누르면 메모박스가 입력 가능해지고, '완료' 버튼을 누르면 수정사항이 반영됨
  
  - '삭제' 버튼을 누르면 해당 메모가 삭제됨
  

  - TextInput, TouchableOpacity 사용

  - 상태 관리 라이브러리 사용 (redux, mobx, context api 등 무관)
  

- API 이용한 영화 제목 리스트 출력

  - api에서 title을 가져와서 (다른 것을 추가로 가져와도 됩니다) 화면에 출력합니다. (형식 자유)

  - Api를 사용하여 데이터 가져오기 & async/await을 사용하여 비동기 처리하기

  - 사용 API: https://yts.mx/api/v2/list_movies.json?limit=50
  

- 스타일링

  - StyleSheet 또는 Styled-Components 등의 라이브러리를 자유롭게 이용

  - 각 화면 스타일링은 자유
  

- 그 외

  - 위에 적은 내용을 바탕으로 자유롭게 구현

---

### 출제 의도

- 실제 서비스 개발 과정에서 필요한 기본적인 기능을 구현할 수 있는지 파악하기 위함

- 서버와 통신 시 사용하는 Api를 사용하여 데이터 가져오기 & async/await을 사용한 비동기 처리 가능 여부 파악

- 컴포넌트 스타일링 가능 여부 파악


### 제출 방법

- 서류 제출 시 작성한 자신의 github에 prography-6th-react-native 이름의 저장소를 생성하여 업로드해주세요.

- 마감 기한은 2020년 03월 05일 23:59까지 이며, 기한 내 Commit만 인정합니다.


### 문의

- 궁금하신 점이 생기면 언제든 카카오톡 오픈채팅방을 이용해주세요. https://open.kakao.com/o/sRwadjZb

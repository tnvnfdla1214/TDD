# TDD(Test-Driven Development)
### TDD란
테스트를 먼저 만들고 테스트를 통과하기 위해 코드를 짜는 것을 TDD라 한다.

에자일과 같이 매우 빠르고 많이 프로덕션 개선이 일어나는 과정에서는 어쩔 수 없는 불확실성이 따란다 이러한 이유로 빠른 커뮤니케이션 피드백 협력이 필요할 수 밖에 없기에 사용된다.
<img src = "https://user-images.githubusercontent.com/48902047/133922306-046cbd10-b75e-4842-b132-e64d15857939.png" width="40%" height="40%"> <img src = "https://user-images.githubusercontent.com/48902047/133922308-0914f2b7-7642-4432-9c8f-081ab09d7724.png" width="40%" height="40%">
- 개발단위가 더 작아져서 문제가 생길확률이 적으며 금방 찾을수 있다
- 나중에 유지보수시 함수의 기능이 변경/추가 되면 테스트를 통해 함수의 유효성을 확인할 수 있다.
##### TDD 구현 과정
1. 비지니스 로직을 분리 할 수 있는 클린 아키텍쳐 Basecamp 구축
2. unit Test 구현을 위한 도구 도입(DI, Mock)
3. 각 Unit Test File 생성 및 목적에 맞는 시나리오 작성하기
4. 시나리오에 필요한 UseCase작성, 각 레이어 구축(Repository, Model 등)
5. 각 상태를 state Pattern 으로 표현하여 쉬운 방법으로 결과 검증하기
### :wrench: 프로젝트 사용 사례
* ToDo

##### 시나리오
1. ToRo 아이템 데이터 넣고 리스트 잘 불러오는지 확인하기
2. 아이템 업데이트, 삭제 등이 잘 되는지 확인하기
3. 상세화면에서 아이템 정보 잘 나오는지 확인하기
4. 작성,수정에 따라 ToDo 추가되거나 업데이트 되는지 확인하기

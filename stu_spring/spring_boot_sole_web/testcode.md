# 테스트코드
- 테스트코드는 옛날에는 무시받았지만, 최근들어 점점 필수요소가 되고있다.
- TDD
    - TDD가 없는 개발
        - 개발
        - 프로그램 실행
        - http 요청
        - print로 결과 확인
        - 아니면 프로그램 중지 후 수정
        - 너무 느림
        - 기존에 했던 테스트들을, 오류가 난 후에 똑같이 시도할 수 있음
    - TDD란 테스트 주도 개발(Test Driven Development)이란 뜻이다.
    - 그냥 테스트코드 짜고 개발하는거다.
    - 레드 그린 사이클
        - 레드
            - 항상 실패하는 테스트
        - 그린
            - 통과하는 코드 작성
        - 리팩토링
            - 통과하면 프로덕션 코드를 리팩토링
- 단위테스트
    - TDD의 첫번째 단계
    - 기능 단위의 테스트코드 작성
    - 문제 초기 발견
    - 코드 리팩토링과 라이브러리 업그레이드
    - 시스템의 실제 문서 제공(테스트가 곧 문서)
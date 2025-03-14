# **Going full screen**

---

<aside>

전체 화면 모드를 통해 시스템 제어기를 가리고 방해받지 않는 환경을 제공할 수 있습니다. 

</aside>

---

@### 모범 사례

- 경험을 제공하는데 적합하다면 전체 화면 모드 지원
    - 작업 또는 콘텐츠에 집중하고 싶을 때 사용
        - 게임 플레이
        - 비디오 또는 사진 → 미디어 보기
        - 방해받지 않는 환경을 원하는 작업이 수행될 때
- 전체 화면 모드에서 레이아웃 조정은 ok, 윈도우 크기는 조정 X
    - 표시되는 항목은 그대로 두고 비율을 조절
- 전체 화면 모드를 종료하지 않고도 작업을 완료할 수 있도록 기능과 제어기 접근 권한 제공
- 전체 화면 ↔ 다른 화면 전환 간에 진행 정보 유지되도록
- 전체 화면 모드 종료는 언제든지 선택 가능하도록

#@## 플랫폼 고려 사항 - iOS

- 앱에 미디어를 보는 동안 시스템에서 홈 화면 표시기를 자동으로 가리도록 요청
    - 방해될 수 있는 요소를 제거하려면 재생 또는 기타 앱 제어기를 가렸다가 다시 표시되도록

---
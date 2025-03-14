# Collaboration and sharing

---

<aside>

공동 작업 및 공유 경험은 간단하고 반응성이 뛰어나 여러 사람들과 효과적으로 소통하며 콘텐츠에 참여할 수 있습니다. 

</aside>

- 시스템 인터페이스와 메시지 앱을 통해 공동 작업 및 공유를 수행할 수 있다.
- 앱의 공동 작업 버튼을 통해서 다른 사람과 소통하고, 사용자 동작을 수행하고, 세부 사항을 관리할 수 있다.
- 사용자 설정 공동 작업 인프라를 사용하는 경우 앱에서 유니버셜 링크를 지원해야 한다.

---

#### 모범 사례

- 공유 버튼을 편리한 위치에 배치 → 쉽게 공유 작업을 시작할 수 있도록
    - iOS 16에서 시스템 제공 공유 시트를 통해 공유 방식을 선택하고 공동 작업 권한을 설정할 수 있다.
- 지원 되는 공유 권한을 요약하는 간결한 문구를 작성
    - 초대받은 사람만 편집 가능
    - 모두가 변경할 수 있음
    - 과 같은 문구를 통해서 권한 요약 제공
- 공동 작업 버튼
    - 콘텐츠가 공유되고 있다는 상태를 즉시 피드백
    - 공유 버튼 근처에 공동 작업 버튼 배치
- 공동 작업 팝오버에서 사용자 설정 동작 제공
    - 3가지 섹션으로 구성
        - 상단
            - 공동 작업자 나열
            - 메시지 앱 또는 FaceTime 앱 연결 버튼 → 커뮤니케이션 버튼
        - 가운데
            - 사용자 설정 항목
        - 하단
            - 공유 파일 관리 버튼
    - 너무 많은 항목은 사용자에게 부담 → 공동 작업에 필요한 항목으로만 구성
- 공동 작업 → 모달 뷰
    - 공동 작업 버튼에 대한 제목에 대하여 사용자화
    - 공동 작업에 대하여 기능 제공 시 사용자 설정을 통해서 보기를 생성
- 메시지 앱에서 공동 작업 이벤트 알림 고려
    - 발생한 이벤트에 대해서 삼들이 앱에서 관련하여 확인할 수 있도록 유니버셜 링크를 제공

---
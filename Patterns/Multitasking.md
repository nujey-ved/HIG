# **Multitasking**

---

<aside>

멀티 태스킹을 통해 한 앱에서 다른 앱으로 빠르게 전환하여 각각의 앱에서 작업을 수행할 수 있다. 

</aside>

- 앱 전환과 더부어 멀티태스킹은 여러 기기에서 다양한 경험을 선사
    - 다른 앱을 사요하면서 FaceTime 사용과 같은

---

### 모범 사례

- 다른 작업을 전환할 때 현재 진행 상태를 즉시 멈추고 원래 작업으로 다시 돌아왔을 때 매끄럽게 복구하여 여러 앱에서 작업을 완료할 수 있도록 지원
- iOS에서 사람들이 다른 작업으로 전환할 경우 관심이나 적극적인 참여가 필요한 활동을 일시 정지
- 오디오 중단 대응
    - 다른 앱 또는 시스템 자체가 오디오를 중단할 수 있음
        - 무한정 일시 정지
        - 짧은 중단 → 일시 정지 및 중단이 끝나면 재생 재개
- 사용자 작업을 백그라운드에서 완료
    - 작업 시작 → 앱 전환 후에도 해당 작업의 완료에 대하여 기대
    - 사용자의 직접적인 입력이 필요없는 경우 백그라운드에서 진행 → 완료
- 알림 절제
    - 백그라운드 → 알림 보낼 수 있음
    - 중요한 작업이나 빨리 처리해야한느 작업의 경우 알림이 적합
    - 그외에는 완료 여부를 알고싶지 않음 → 불필요한 알림
    - 대신 돌아왔을 때 작업을 확인할 수 있도록

---
# **Materials**

---

<aside>

머터리얼은 기본 색상 값을 흐리게 표시하거나 수정하여 반투명도를 부여합니다. 

</aside>

---

- 반투명도는 전면 및 배경 요소의 통합을 향상하여 레어어간의 분리감을 시각적으로 제공합니다.
    - 반투명도를 향상하기 위해서 머터리얼을 통해서 생동감을 부여
    - 머터리얼은 색상을 전면부로 끌어당기는 느낌을 줄 수 있어 콘텐츠의 깊이감을 풍부하게 할 수 있다.

#### 모범 사례

- 머터리얼은 깊이감과 계층 구조간의 분리감을 전달한다.
    - 단, 콘텐츠에는 집중할 수 있도록 주의를 분산시키지 않아야 한다.
- 머터리얼과 머터리얼 상단에 적용되는 색상에는 충분한 대비를 통해서 가독성을 보장해야 한다.
    - 충분히 생동감이 있는 색상을 사용
- 머터리얼과 결합 시 시각적 분리 고려
    - 두꺼운 머터리얼은 세밀한 요소(텍스트와 같은)와 대비를 높이는데 도움이 될 수 있다.
    - 반투명도는 배경 콘텐츠를 희미하게 노출함으로써 진행 상태를 유지하는데 도움이 될 수 있다.

#### 플랫폼 고려사항 - iOS

- 사용 머터리얼
    - ultraThin
    - thin
    - regular
    - thick
    - chrome(탐색)
    - chrome(탭 또는 도구 막대)
- Label color
    - 4단계 구성
        - UIVibrancyEffectStyle. label
            - 기본
        - UIVibrancyEffectStyle.secondaryLabel
        - UIVibrancyEffectStyle.tertiaryLabel
        - UIVibrancyEffectStyle.quaternaryLabel
            - thin과 ultraThin에서는 대비가 낮아 사용할 수 없다.

---
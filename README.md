# Security
19.05.24

VMware Guest pc의 devices는 소프트웨어로 구성되어 있기 때문에 한번씩 네트워크 어댑터(LAN카드)가 내려가 있을 수 있는데 이때, VMware edit>virtual network editor>restore defaults 버튼으로 기본값으로 복원해본다. (관리자 권한)

virtual network editor에 VMnet1, 8번 확인. or 명령프롬프트창에 ipconfig로 이더넷 어댑터 VMnet1, 8번에 ip할당 되어 있는지 확인.

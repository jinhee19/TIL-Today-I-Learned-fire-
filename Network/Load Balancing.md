# 로드 밸런싱(Load Balancing)

# 로드 밸런싱이란?

- 하나의 인터넷 서비스가 발생하는 트래픽이 많을 때 여러 대의 서버가 분산처리하여 서버의 로드율 증가, 부하량, 속도저하 등을 고려하여 적절히 분산처리하여 해결해주는 서비스
    - 트래픽 분산처리 → 높은 가용성
    - 부하 분산 → 고효율 웹 서비스 제공
- `로드 밸런서(Load Balancer)` : 로드 밸러싱을 수행하는 소프트웨어나 하드웨어

### 로드 밸런싱을 사용하는 이유

- 사업의 규모 확장으로 클라이언트의 수가 늘어남 → 모든 트래픽을 1대의 서버로는 정상적인 서비스 불가능
- 대응 방식
    - Scale-up
    - Scale-out

        → 여러 대의 서버로 트래픽을 균등하게 분산해주는 로드 밸런싱 필요

### 주요 기능

- NAT(Network Address Translation)
    - 사설 IP 주소를 공인 IP 주소로 바꾸는 데 사용하는 통신망의 주소 변조기
- Tunneling
    - 인터넷상에서 눈에 보이지 않는 통로를 만들어 통신할 수 있게 하는 개념
    - 데이터를 캡슐화해서 연결된 상호 간에만 캡슐화된 패킷을 구별해 캡슐화를 해제할 수 있다
- DSR(Dynamic Source Routing protocol)
    - 로드 밸런서 사용 시 서버에서 클라이언트로 되돌아가는 경우 목적지 주소를 스위치의 IP주소가 아닌 클라이언트의 IP 주소로 전달해서 네트워크 스위치를 거치지 않고 바로 클라이언트를 찾아가는 개념

# 로드 밸런싱 방식

1. 라운드로빈 방식(Round Robin Method)
2. 가중 라운드로빈 방식(Weighted Round Robin Method)
3. IP 해시 방식(IP Hash Method)
4. 최소 연결 방식(Least Connection Method)
5. 최소 리스폰타임(Least Response Time Method)

# L4 로드 밸런싱과 L7 로드 밸런싱

### L4 로드밸런서

### L7 로드 밸런서

# 참고 자료

- 로드 밸런싱

    [https://velog.io/@zkdlcl5050/로드-밸런싱](https://velog.io/@zkdlcl5050/%EB%A1%9C%EB%93%9C-%EB%B0%B8%EB%9F%B0%EC%8B%B1)

- 로드 밸런싱이란? LOAD BALANCING

    [https://cheershennah.tistory.com/176](https://cheershennah.tistory.com/176)

- [Network] 로드 밸런싱(Load Balancing)이란?

    [https://dailylifeofdeveloper.tistory.com/133](https://dailylifeofdeveloper.tistory.com/133)
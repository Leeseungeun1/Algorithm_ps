# Strongly Connected Component
* 유향 그래프에서 등장하는 개념
* 하나의 SCC 안에서는 어떤 두 정점 u,v를 골라도 u->v경로가 존재한다.
* 한 SCC는 가능한 커야한다.
* Tarjan algorithm
> * DFS를 이용하여 DFS Tree 생성
> * 생성된 DFS Tree에서 역순환 간선과 stack을 이용하여 scc를 추출
> * 어떤 node의 자손들이 node의 조상으로 갈 수 있는 경우가 하나도 없을 경우, node를 포함한 하나의 SCC 발견.
? * 이 때, stack을 이용하여 SCC에 포함되는 node를 정리한다.

# Union & Find (disjoint-set)
* union 연산, find 연산, 단 2개만 지원하는 data structure.
* disjoint한 집합들을 표시
> 1. 어떤 두 집합 사이에도 교집합의 원소가 하나도 없다.
> 2. 모든 집합의 합집합은 전체 집합니다.
* 여러개의 tree (forest) 형태를 띈다.
* find: 어떤 정점의 root를 찾아준다.
> * find의 재귀적 구현을 통해 특정 node가 포함 된 tree의 root node를 알 수 있다.
> * root node를 알았을 대, 바로 root node의 값을 저장하면 (메모이제이션) 시간복잡도를 줄일 수 있다.
* union: 두 집합을 하나로 합쳐준다.
> * find를 이용하여 두 정점의 root를 구하고, 하나의 root를 다른 하나의 root가 되도록 연결한다.
> * 시간 복잡도는 find에 의해 지배된다.
> * 집합의 크기를 이용하여 union을 진행할 수도 있다.

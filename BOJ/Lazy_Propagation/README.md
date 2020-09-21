# Lazy Propagation
* segment tree를 활용한 알고리즘
* 구간 update를 O(logN)시간에 해결
* 각 segment tree의 node 별 lazy node 지정
* lazy node: node에 해당하는 영역 전체에 얼마를 더할 계획이 있다.
* lazy node가 0이 아닌 경우, lazy node를 이용하여 tree값을 갱신 해주고, lazy 값을 자식 node로 이월

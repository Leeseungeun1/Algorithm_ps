# BFS
* graph의 모든 정점을 '한번씩만' 탐색하는 알고리즘
* 현재 방문한 node의 자식 node를 다 방문한 후, 자식 node의 자식 node를 다시 방문
* k단계에 방문하는 node는 시작점으로부터 최단거리가 k다
> * A에서 B까지의 최단거리: A에서 B로 이동하는데 필요한 최소 개수의 간선
* Queue를 이용하여 각 단계에 방문해야 할 node들의 정보를 저장

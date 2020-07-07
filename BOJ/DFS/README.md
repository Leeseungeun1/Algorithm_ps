# DFS(Depth-First-Search)
* graph의 모든 정점을 '한 번씩만' 탐색하는 그래프 탐색 알고리즘
* 현재 방문한 node에 인접한 node 중 하나를 그 다음차례에 방문
* stack을 이용하거나 재귀함수를 이용하여 구현 가능
* 시간복잡도 (V: 정점 수, E: 간선 수):  
** adjacent matrix(인접 행렬) 사용시: O(V^2)
** adjecent list(인접 리스트) 사용시: O(V+E)

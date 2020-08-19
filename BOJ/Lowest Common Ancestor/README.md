# Lowest Common Ancestor (최소 공통 조상)
* LCA: 트리상에서 어떤 두 정점 u, v가 있을 때 u이거나 u의 조상이면서 동시에 v이거나 v의 조상인 node 중 가장 깊은 node
* 두 정점 u와 v의 최소 공통 조상을 w라 한다면, u에서 v로 가는 최단 경로는 u-w-v이다.
* 부모의 정보와 depth의 정보를 저장하고(using DFS), 해당 정보를 이용하여 공통 조상을 찾는다.
* 2차원 배열을 이용하여 부모를 조금 더 빠른 속도에 찾을 수 있다. (sparse table + dp)

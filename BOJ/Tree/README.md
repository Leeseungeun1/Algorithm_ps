# Tree
* 그래프 중 한 종류
> * 연결 그래프 (한 개의 component)
> * cycle이 존재하지 않는 graph
* 간선의 개수는 정점의 개수보다 항상 1개 적다.
* 용어
> * root node: 가장 상위의 node
> * depth (or level): 어떤 정점과 root node와의 거리
> * height: 가장 깊은 정점의 깊이 (또는 그 값+1 : 개인이 어떻게 정의하느냐에 따라 달라진다.)
> * parent node(부모 node): 인접한 두 정점 중에서 깊이가 작은 node
> * child node(자식 node): 인접한 두 정점 중에서 깊이가 큰 node
> * sibling node(형제자매 node): 같은 부모를 둔 서로 다른 자식 node들의 관계
> * leaf node: 자식이 하나도 없는 node
> * degree: 자식의 수
> * subtree: tree 속에 포함되어 있는 또 다른 tree.<br> 하나의 tree 안에 자식 node를 root로 하는 또 다른 tree가 존재하므로 tree는 '재귀적인 구조'를 띈다.
* tree의 순회 방법
> * preorder: 자기 자신을 먼저 방문한 후 자식 방문
> * inorder: 왼쪽 자식->자기자신->오른쪽 자식 순으로 순회 (이진 tree에서만 사용된다.)
> * postorder: 자기 자신을 방문하기 전 자식들 먼저 방문
> * levelorder: 깊이가 작은 것 부터 순회 (BFS와 유사)

# Binary Search Tree(이진 탐색 트리)
* 이진 트리
> * 왼쪽 자식에 node가 있다면, 자식 node의 값은 자기 자신의 값보다 작다.
> * 오른쪽 자식에 node가 있다면, 자식 node의 값은 자신의 값보다 크다.
* 중위 순회를 하면 방문 순서에 따라 노드의 값이 반드시 증가한다.
* perfect binary tree: 높이=n, 노드의 수=2^n-1
* complete binary tree: 각 높이마다 왼쪽부터 차례대로 채워진 tree. Perfect binary tree에 포함 됨
* node의 삽입 과정
> * 삽입하려는 node의 값이 현재 값보다 작으면 왼쪽 subtree에 추가한다.
> * 삽입하려는 node의 값이 현재 값보다 크면 오른쪽 subtree에 추가한다.
*node의 삭제 과정
> * leaf node를 삭제하는 경우: 단순 삭제
> * 자식이 하나만 있는 node를 지우는 경우: 자신을 삭제하며 부모와 자식을 연결
> * 그외: 자기 자신을 삭제하고 오른쪽 subtree나 왼쪽 subtree에서 적합한 node로 root를 대체

# Dynamic Programming (동적 계획법)
* 주어진 문제를 여러개의 부분 문제로 나누어 푼 다음, 그 결과를 이용하여 주어진 문제를 푼다.
> * 분할정복과 달리 겹치는 경우가 생기기 때문에 메모이제이션 등의 기법이 필요하다.
> * 즉, 자신보다 작은 부분문제의 답을 알면 현재 문제를 빠르게 풀수 있다.
* base case인 문제들부터 차근차근 풀어나가며 원래의 문제의 답을 구해나가는 과정이다.
* 두 가지 구현 방법
> * 재귀: top-down 방식
> * 반복문: bottom-up 방식
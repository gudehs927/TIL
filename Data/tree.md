# 트리
트리구조란 그래프의 일종으로, 여러노드가 한 노드를 가리킬 수 없는 구조이다. 트리는 하나의 루트노드를 가지고 있다. 루트노드는 0개 이상의 자식노드를 가지고 있다. 그 자식노드 또한 0개 이상의 자식노드를 가지고 있으며 이것을 반복한다.

## 용어
- 루트 노드
부모가 없는 노드 제일 위에 있는 노드이다.
- 단말 노드 
자식이 없는 노드 말단노드라 불리거나 잎 노드라고도 불린다.
- 내부노드 
단말 노드가 아닌 노드
- 간선노드 
노드를 연결하는 선
- 형제 
같은 부모를 가지는 노드
- 노드의 크기
자신을 포함한 모든 자손 노드의 개수
- 노드의 깊이 
루트에서 어떤 노드에 도달하기 위해 거쳐야 하는 간선의 수
- 노드의 레벨
트리의 특정 깊이를 가지는 노드의 집합
- 노드의 차수
하위 트리 개수,간선 수 각 노드가 지닌 가지의 수
- 트리의 차수
트리의 최대 차수
- 트리의 높이 
루트 노드에서 가장 깊숙히 있는 노드의 깊이

## 특징
계층형 모델이다

## 종류
- 이진 트리
Binary tree : 부모 노드가 자식 노드를 최대 2개씩만 갖고있는 트리.
Ternary tree : 자식 노드를 2개 이상 갖고 있는 트리

- 이진 검색 트리
노드의 왼쪽 하위 트리에는 노드의 크기보다 작은 키가 들어가야 한다 
노드의 오른쪽 하위 트리에는 노드의 크기보다 큰 키가 들어가야한다

- 밸런스
밸런스는 왼쪽노드와 오른쪽노드의 갯수가 정확히 일치 하지 않아도 되지만 양쪽으로 노드가 있어야 한다.
언밸런스는 한쪽에만 노드가 치우친 경우를 말한다.

- 완전 이진 트리
마지막을 제외한 모든 서브트리의 레벨이 같아야 하고 마지막 레벨은 왼쪽부터 채워져 있어야 한다.

- 정이진트리
자식 노드가 아예 없거나, 최대 둘뿐인 tree. 자식을 하나만 가진 노드가 없어야 한다.

- 포화이진트리 
완벽한 피라미드 형식으로 빈공간 없이 모든 노드가 2개의 자식을 갖고 있는 트리

## 이진 트리의 순회

- 중위순회(Inorder)
순서 왼쪽 루트 오른쪽이다.

- 전위순회(Preorder)
순서 루트 왼쪽 오른쪽

- 후위순회(Postorder)
순서 왼쪽 오른쪽 루트


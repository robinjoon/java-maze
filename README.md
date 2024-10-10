# 미션 - 미로 탈출

## 🚀 진행 방식
1. 미션 진행은 [미션 진행 가이드 문서](https://github.com/develup-mission/docs/blob/main/mission-guide.md)를 따른다.

## 💻 기능 요구 사항

미로 탈출 시뮬레이션 프로그램을 구현한다.

1. 사용자는 미로의 가로와 세로 크기를 입력할 수 있다.
2. 미로는 랜덤으로 생성된다.
3. 미로의 시작 위치는 왼쪽 최상단이고 미로의 끝 위치는 우측 최하단이다.
4. 사용자는 상하좌우로 움직일 수 있다.
- u : 위로 이동
- d : 아래로 이동
- l : 왼쪽으로 이동
- r : 오른쪽으로 이동

### 예시

```
미로의 가로와 세로 크기를 입력하세요.
> 6, 6

미로를 생성합니다.
1은 벽 0은 통로 x는 현재 위치 e는 도착점입니다.

1 x 1 1 1 1
1 0 0 0 0 1
1 1 0 1 0 1 
1 0 0 1 1 1
1 1 0 0 0 1
1 1 1 1 e 1

어느 방향으로 이동하겠습니까?
u
이동할 수 없습니다. 다시 입력하세요
d

1 0 1 1 1 1
1 x 0 0 0 1
1 1 0 1 0 1 
1 0 0 1 1 1
1 1 0 0 0 1
1 1 1 1 e 1

어느 방향으로 이동하겠습니까?
r

1 0 1 1 1 1
1 0 x 0 0 1
1 1 0 1 0 1 
1 0 0 1 1 1
1 1 0 0 0 1
1 1 1 1 e 1

(생략)

1 0 1 1 1 1
1 0 x 0 0 1
1 1 0 1 0 1 
1 0 0 1 1 1
1 1 0 0 x 1
1 1 1 1 e 1

어느 방향으로 이동하겠습니까?
d

1 0 1 1 1 1
1 0 x 0 0 1
1 1 0 1 0 1 
1 0 0 1 1 1
1 1 0 0 0 1
1 1 1 1 x 1

미로 탈출에 성공했습니다! 프로그램을 종료합니다
```

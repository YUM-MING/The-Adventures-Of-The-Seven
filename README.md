# The-Adventures-Of-The-Seven
[7인의 모험] 오픈소스소프트웨어 팀프로젝트
<br><br>

* * *

> ⚽ [공 튀기기 게임 분석](https://github.com/YUM-MING/The-Adventures-Of-The-Seven/blob/main/%EA%B3%B5%ED%8A%80%EA%B8%B0%EA%B8%B0%20%EA%B2%8C%EC%9E%84.md)<br>
> 🐍 [뱀 게임 분석](https://github.com/YUM-MING/The-Adventures-Of-The-Seven/blob/main/%EB%B1%80%20%EA%B2%8C%EC%9E%84.md) <br>
> 🔓 [미로 탈출 게임 분석](https://github.com/YUM-MING/The-Adventures-Of-The-Seven/blob/main/%EB%AF%B8%EB%A1%9C%20%ED%83%88%EC%B6%9C%20%EA%B2%8C%EC%9E%84.md)

* * *
<br>

## 목차
<br>

✓ [프로젝트 개요](#프로젝트-개요)<br>
✓ [게임설명 및 실행](#게임설명-및-실행)<br>
✓ [게임 기능](#게임-기능)<br>
✓ [팀원 소개](#팀원-소개)<br>
<br>

## 프로젝트 개요
**본프로젝트**에서는 **Chat-GPT4**에게 파이썬에 내장된 **파이게임**을 활용한 미니게임 3개를 제작 요청하여 코드를 받았습니다. <br>
이후 이 코드를 뜯어보고 **실행 및 분석**한 내용을 정리해 기록하는 프로젝트입니다.
<br><br>

## 게임설명 및 실행
### 1️⃣ 공 튀기기 게임 (Bounce Ball)
사용자가 패들로 공을 튕겨 화면 아래로 떨어지지 않게 유지하는 간단한 게임 ⚾
<br><br>


##### 게임 설명
- **목표** : 공을 화면에서 떨어뜨리지 않도록 패들을 조작하세요.
- **조작법** : 좌우 화살표 키로 패들을 이동시키세요.
  
<br>

[About the Game](https://github.com/YUM-MING/The-Adventures-Of-The-Seven/blob/main/%EA%B3%B5%ED%8A%80%EA%B8%B0%EA%B8%B0%20%EA%B2%8C%EC%9E%84.md)
<br><br>

### 2️⃣ 뱀 게임 (Snake Game)
뱀이 음식을 먹으며 점점 길어지는 고전적인 스네이크 게임 🎮
<br><br>

##### 게임 설명
- **목표** : 뱀을 움직여 음식을 먹고 점수를 올리세요.
- **조작법** : 방향키로 뱀의 이동 방향을 조절하세요.
- **주의사항** : 뱀이 벽이나 자기 몸에 부딪히면 게임이 끝납니다.
  
<br>

[About the Game](https://github.com/YUM-MING/The-Adventures-Of-The-Seven/blob/main/%EB%B1%80%20%EA%B2%8C%EC%9E%84.md)
<br><br>

### 3️⃣ 미로 탈출 게임 (Maze Escape)
사용자가 캐릭터를 움직여 출구에 도달하는 게임 🕹
<br><br>

##### 게임 설명
- **목표** : 목표: 캐릭터를 조작하여 미로의 출구에 도달하세요.
- **조작법** : 방향키로 캐릭터를 이동하세요.
- **특징** : 각 게임 실행 시 미로가 랜덤으로 생성됩니다.
- **주의사항** : 제한 시간 안에 도달하지 못하면 게임이 종료됩니다.
  
<br>

[About the Game](https://github.com/YUM-MING/The-Adventures-Of-The-Seven/blob/main/%EB%AF%B8%EB%A1%9C%20%ED%83%88%EC%B6%9C%20%EA%B2%8C%EC%9E%84.md)
<br><br>

## 게임 기능
### 1️⃣ 조작법

|키보드 입력|동작|
|:---:|---|
|↑|위쪽으로 이동|
|↓|아래쪽으로 이동|
|←|왼쪽으로 이동|
|→|오른쪽으로 이동|

<br>

### 2️⃣ 해상도
#### ✓ WIDTH, HEIGHT
공 튀기기 게임, 미로탈출 게임 = 800, 600<br>
뱀 게임 = 600, 400
#### ✓ screen = pygame.display.set_mode((WIDTH, HEIGHT))
설정한 넓이와 높이로 스크린 설정
#### ✓ pygame.display.set_caption :Bounce Ball Game, Snake Game, Maze Escape
스크린 이름을 다음과 같이 설정
<br><br>

## 팀원 소개

|이유민|김명서|천지연|
|:---:|:---:|:---:|
|20223618|20242513|20241515|
|메인 페이지 및 게임코드|공튀기기 분석|공튀기기 분석|
|[@YUM-MING](https://github.com/YUM-MING)|[@HelloKIMMS](https://github.com/HelloKIMMS)|[@jiyeon0530](https://github.com/jiyeon0530)|

|서유민|장여정|임지연|현예진|
|:---:|:---:|:---:|:---:|
|20242517|20241513|20242514|20241512|
|뱀 분석|뱀 분석|미로 탈출 분석|미로 탈출 분석|
|[@carvestar](https://github.com/carvestar)|[@yeojeong735](https://github.com/yeojeong735)|[@zziziz](https://github.com/zziziz)|[@yejin135](https://github.com/yejin135)|

# 종이비행기 슈팅게임

HTML5 Canvas를 사용한 모바일 웹 슈팅 게임입니다.

## 게임 소개

종이비행기를 조종하여 적들을 물리치고 최고 점수를 달성하는 슈팅 게임입니다. 모바일과 데스크톱 모두에서 플레이할 수 있습니다.

## 실행 방법

1. 웹 브라우저에서 `index.html` 파일을 열어서 게임을 실행할 수 있습니다.
2. 모바일 기기에서는 홈 화면에 추가하여 앱처럼 사용할 수 있습니다.

## 게임 조작 방법

### 데스크톱
- 방향키: 플레이어 이동
- 스페이스바: 총알 발사
- P키: 일시정지/재개
- R키: 최고점수 리셋
- 게임 오버 시 스페이스바: 재시작

### 모바일
- 화면 하단의 방향 버튼: 플레이어 이동
- "시작/재시작" 버튼: 게임 시작 또는 재시작
- "특수무기" 버튼: 특수 공격
- "일시정지" 버튼: 게임 일시정지
- "최고점수 리셋" 버튼: 최고점수 초기화

## 리소스 파일

게임에 필요한 리소스 파일들이 다음 위치에 있습니다:

### 이미지 파일
- `images/player.png` - 플레이어 종이비행기
- `images/enemy.png` - 적 종이비행기
- `images/BOSS.png` - 보스 종이비행기
- `images/missile1.png` - 미사일 1
- `images/missile2.png` - 미사일 2
- `images/snakeGroups.png` - 뱀 그룹 이미지

### 사운드 파일
- `sounds/shoot.mp3` - 발사 효과음
- `sounds/explosion.mp3` - 폭발 효과음
- `sounds/collision.mp3` - 충돌 효과음
- `sounds/levelup.mp3` - 레벨업 효과음
- `sounds/warning.mp3` - 경고 효과음

## 기술 스택

- **HTML5 Canvas**: 게임 렌더링
- **JavaScript (ES6+)**: 게임 로직
- **CSS3**: UI 스타일링
- **IndexedDB**: 로컬 점수 저장
- **Web Audio API**: 사운드 효과

## 브라우저 호환성

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+
- 모바일 브라우저 (iOS Safari, Chrome Mobile)

## 라이선스

ISC License 
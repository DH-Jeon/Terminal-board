# 터미널 보드

여러 터미널(iTerm 분할)에서 무슨 작업을 돌리는지 휴대폰에서 정리하는 보드 PWA.

🔗 **https://dh-jeon.github.io/terminal-board/**

## 기능

- 오른쪽 목록에 할일 추가 / 보기 / 삭제
- 왼쪽 보드를 가로·세로로 자유 분할 (iTerm처럼)
- 할일을 칸에 드래그해 배치, 칸을 목록으로 다시 드래그해 빼기
- 인접한 두 칸 드래그 → 병합
- 할일별 완료 / 미루기

## 사용법

1. iPhone **Safari**로 위 주소 열기
2. **공유 → 홈 화면에 추가**
3. 가로로 돌려서 사용

데이터는 기기 브라우저(localStorage)에만 저장됩니다. 서버·로그인 없음.

## 개발

```bash
python3 -m http.server 8000   # http://localhost:8000
```

의존성 없는 단일 `index.html`.

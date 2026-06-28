# JSON 포매터 (JSON Formatter)

JSON 데이터를 붙여넣으면 즉시 정렬·검증. 파일·폴더를 열어 JSON과 Markdown을 좌(원본)/우(보기)로 나란히 확인.

🔗 **바로 쓰기**: https://hanariago.github.io/tool-json-formatter

## 기능

### 붙여넣기 모드
- 실시간 포매팅 (들여쓰기 2칸/4칸 선택)
- 유효성 검사 + 오류 위치(줄·칸) 표시
- 결과 복사 / 입력 초기화 / 최소화(Minify)
- 샘플 JSON 불러오기

### 파일 열기 모드
- 폴더 또는 여러 파일 선택 → 파일 리스트 레이어에 표시
- 폴더 트리 접기/펴기 (기본 펼침, 모두 펼치기·접기 버튼)
- JSON·Markdown 파일을 클릭하면 **왼쪽 원본 / 오른쪽 보기**
  - `.json` → 포맷된 JSON (들여쓰기·검증)
  - `.md` → Markdown 미리보기 렌더링
- 모바일 대응 (상하 분할 + 목록 드로어)

### 공통
- **서버 전송 없음** — 모든 파일은 브라우저 안에서만 열림

## 기술 스택
- 순수 HTML/CSS/JS, 단일 파일 (외부 라이브러리 없음)
- `JSON.parse` / `JSON.stringify`, 자체 구현 Markdown 렌더러

---
Made by [Lena](https://github.com/hanariago) · License: MIT

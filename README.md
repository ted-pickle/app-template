# 앱 템플릿 (AI로 만드는 모바일 앱)

휴대폰 홈 화면에 설치할 수 있는 웹 앱을 만드는 시작 저장소예요.

## 사용 순서

1. 오른쪽 위 **Use this template → Create a new repository**
2. 저장소 이름은 영어 소문자와 `-` 만 (예: `word-cards`), **Public** 선택
3. **Settings → Pages** 에서 Branch를 `main` / `(root)` 로 고르고 **Save**
4. AI에게 요청할 때 `index.html` 코드 전체를 함께 붙여 넣고, "head 부분은 그대로 둬"라고 적기
5. 받은 코드로 `index.html` 전체를 바꾸고 **Commit changes**

## 파일

| 파일 | 하는 일 | 바꾸나요? |
|---|---|---|
| `index.html` | 앱의 화면과 기능 | 네 (head는 그대로) |
| `manifest.json` | 앱 이름, 아이콘, 전체 화면 설정 | 앱 이름만 바꿔도 돼요 |
| `sw.js` | 인터넷 없이도 열리게 해 줘요 | 아니요 |
| `icons/` | 홈 화면 아이콘 | 원하면 같은 이름으로 교체 |

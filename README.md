# 유앤미스튜디오 사이트 (GitHub Pages)

이 폴더는 **개인정보처리방침 + app-ads.txt 호스팅용** 정적 사이트입니다.
공개 저장소 생성은 계정 소유자 확인이 필요해 파일만 준비해 두었습니다.

## 퍼블리시 방법 (1회, 약 1분)

```bash
cd site
git init && git add -A && git commit -m "사이트 초기화"
gh repo create baenamedu-bot.github.io --public --source . --push
```

또는 github.com에서 `baenamedu-bot.github.io` 이름의 **공개** 저장소를 만들고 이 폴더 내용을 업로드하세요.
(저장소 이름이 정확히 `<계정명>.github.io`면 Pages가 자동 활성화됩니다)

퍼블리시 후 활성화되는 주소:

- 개인정보처리방침: https://baenamedu-bot.github.io/onestroke/privacy/
  → 앱 설정 화면의 링크·Play Console 스토어 등록정보에 이 URL 입력
- app-ads.txt: https://baenamedu-bot.github.io/app-ads.txt
  → AdMob 게시자 ID 발급 후 파일 안의 주석을 풀고 `pub-XXXX…`를 교체
  → Play Console의 "개발자 웹사이트"를 https://baenamedu-bot.github.io 로 설정해야 AdMob이 크롤링함

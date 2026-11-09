# 게시 절차 (창현이 실행 — 공개 저장소 생성은 AI 권한 밖)

특허 출원 접수 전에는 공개하지 않는다(DECISIONS 11/9). 접수 뒤 이 폴더에서:

    gh repo create changyoungduo/pendeck --public --source=. --push --description "Pendeck 지원 · 개인정보처리방침"
    gh api -X POST repos/changyoungduo/pendeck/pages -f build_type=legacy -f 'source[branch]=main' -f 'source[path]=/'

1~2분 뒤 https://changyoungduo.github.io/pendeck/ 와 https://changyoungduo.github.io/pendeck/privacy/ 확인.
문의 채널은 임시로 GitHub 이슈다. 공개용 이메일이 정해지면 index.md·privacy.md의 "GitHub 이슈 …" 문구를 바꾸고 푸시한다.
개발 레포 PR(docs/legal-ai-support-urls)의 SupportContact URL이 이 주소를 가리킨다.

# 땅땅!
[땅땅]은 고가의 제품만이 아닌 다양한 카테고리의 상품들을 판매자가 최저 가격과 최상 희망 가격만을 제시하여 경매 후 거래할 수 있도록 도와주는 웹사이트를 목적으로 제작하였습니다.

## 📝 목차

- [기술 스택](#기술-스택)
- [Git 커밋 및 브랜치 전략](#-git-커밋-및-브랜치-전략)

## 📚기술 스택

다음과 같은 기술을 사용하여 서비스를 제작했습니다.

### Client
- React

### Server
- Spring Boot

### Database
- Maria DB

### Cloud Services
- AWS 

## ♆ Git 커밋 및 브랜치 전략

Git을 활용하여 협업할 때 다음과 같은 commit 및 브랜치 명명 규칙을 사용했습니다.

### Commit 전략

Commit 제목의 형식은 다음과 같습니다.

```
[server ? client] | <type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<Fixes>(optional) <link>
<BLANK LINE>
```

- server 와 client 둘 다 포함 될 경우 `[server & client]` 로 작성합니다.
- subject와 body를 한글로 작성하고, 그 외엔 영어로 작성합니다.
- type: 어떤 의도로 커밋했는지를 type에 명시합니다.
- scope:  커밋의 대상이 되는 것을 명시합니다.
- subject: 최대 50글자가 넘지 않도록 하고 마침표는 찍지 않습니다.
- body: 최대한 작성합니다. How 와 Why 위주로 작성합니다. ~합니다 라는 문체로 작성합니다.
- issue: 이슈에 대한 상세한 설명이 필요한 경우 해당 이슈의 링크를 첨부합니다.
- 참조: 해당 커밋을 작성하기 위해 참고한 링크를 첨부합니다.

### Branch 전략

Branch 이름의 형식은 다음과 같습니다.

```
[유형]/[내용]_[브랜치 생성 날짜]
```

위 형식을 활용하여 다음과 같이 작성할 수 있습니다.
```
feature/search_api_20191219
refactor/search_api_20191220
```

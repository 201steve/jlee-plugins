# jlee-plugins

> Personal Claude Code plugin marketplace by jlee

## 플러그인 목록

### [spec-forge](./spec-forge)

BA → 기획자 → QA 3단계 워크플로우로 PRD를 자동 생성하는 플러그인.

요구사항 텍스트를 채팅에 입력하거나 파일을 첨부하면 자동으로 분석해서 `PRD-{기능명}.md` 파일을 생성한다.

## 설치

```
/plugin marketplace add https://github.com/201steve/jlee-plugins
/plugin install spec-forge@jlee-plugins
```

## 사용법

설치 후 Claude에게 요구사항을 주고 트리거 문구를 붙이면 된다.

```
PRD 만들어줘: {요구사항 내용}
```

파일 첨부도 가능하다. 요구사항 파일을 첨부하고 "PRD 만들어줘"라고 입력하면 파일 내용을 자동으로 읽는다.

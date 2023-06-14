# Re: ZeroBase JavaScript

자바스크립트부터 다시 보기.

## 1. Todo List

🐱‍🐉 2023.06.14

- 기본적인 투두리스트 구현
- json-server를 활용한 REST API 구축 및 연동
- 기본적인 CRUD 구현 해보기

### json-server 실행 방법

1. 터미널 json-server 설치

```
npm install -g json-server
```

2. db.json 파일 생성

```
{
  "todos": [
    {
      "content": "테스트 1",
      "completed": false,
      "id": 1
    },
    {
      "content": "테스트 2",
      "completed": true,
      "id": 2
    },
    {
      "content": "테스트 3",
      "completed": false,
      "id": 3
    }
  ]
}
```

3. 터미널 json-server 실행

```
json-server --watch db.json
```

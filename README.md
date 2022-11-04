# fastapi-playground

[공식문서](https://fastapi.tiangolo.com/ko/) 의 내용을 따라해보고, 스스로 궁금한 부분을 실습한 내용을 기록하는 저정소입니다.

## 환경

- Python 3.8
- macOS Monterey 12.3 (Apple M1 Max)

## 설치

```shell
$ pip3 install --upgrade pip
$ pip3 install "fastapi[all]"
$ pip3 install "uvicorn[standard]"
```

## 실행

```shell
# default port 8000
$ uvicorn main:app --reload
```

in Pycharm
![Pycharm setting](https://user-images.githubusercontent.com/52629158/199875423-8613066b-b78e-4150-92c2-52629fac0700.png)

## API docs

- Swagger UI : [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)
- ReDoc : [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)

## 파이썬 문법

<details>
<summary>데코레이터(Decorator)</summary>
<br/>

- 데코레이터 설명 추가 예정     
- https://dojang.io/mod/page/view.php?id=2427
</details>
<details>
<summary>코루틴(Coroutine)</summary>
<br/>

- 코루틴 설명 추가 예정
- https://dojang.io/mod/page/view.php?id=2418
</details>
<details>
<summary>비동기(async) + asyncio</summary>
<br/>

- 비동기 설명 추가 예정
- https://dojang.io/mod/page/view.php?id=2469
- https://fastapi.tiangolo.com/ko/async/#in-a-hurry
- https://pko89403.github.io/post/fastapiasync/
</details>
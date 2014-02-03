[![Stories in Ready](https://badge.waffle.io/darkkyungho/bbapi.png?label=ready)](https://waffle.io/darkkyungho/bbapi)
BudgetBook API Application
=====

## Badge
[![Code Climate](https://codeclimate.com/github/rorlab/bbapi.png)](https://codeclimate.com/github/rorlab/bbapi)
[![Build Status](https://travis-ci.org/rorlab/bbapi.png?branch=master)](https://travis-ci.org/rorlab/bbapi)
[![Coverage Status](https://coveralls.io/repos/rorlab/bbapi/badge.png)](https://coveralls.io/r/rorlab/bbapi)
[![Dependency Status](https://gemnasium.com/rorlab/bbapi.png)](https://gemnasium.com/rorlab/bbapi)

: Rails API Project

* Coding Note : https://docs.google.com/document/d/1hK0JxMtb3iIEi9nV9zeb4twrV3Hw6y_sNQlNzt11KJE/edit?usp=sharing




## 기초 데이터 셋팅 방법

1.migrate 후 rake db:seed 명령 실행

```
$ rake db:migrate
$ rake db:seed
```
2.rake db:reset 명령으로 한번에 실행

```
$ rake db:reset
```

## auth 연동 정보
root directory에 .env 파일을 생성하고 아래와 같이 정의해야 함.(실제 값은 코딩 노트 참고)
```
FACEBOOK_KEY=XXXXXXXXXXXXXXX
FACEBOOK_SECRET=XXXXXXXXXXXXXXXXXXXXXXXXXXX
```





vue2 라 좀 아쉽지만 아마도 adminLTE 가 vue2 랑 호환일수 있어서 그런가 합니다.
이전 버전이라도 기본 패턴을 이해하면 최신꺼써도 금새 붙어요

https://github.com/AnowarCST/laravel-vue-crud-starter?tab=readme-ov-file
이것 보고 오래된 패키지 문제 해결하고 올렸어요.

## Install
  - npm 환경
  - git clone https://github.com/besso73/laravel8-vue2-adminLTE.git laravue
  - cd laravue/
  - composer install
  - cp .env.example .env
  - Update .env and set your database credentials
  - laravel root/0000 으로 로컬 디비 생성
  - php artisan key:generate
  - php artisan migrate
  - php artisan db:seed
  - php artisan passport:install
  - npm install
  - npm run dev
  - php artisan serve
  - http://localhost:8000/
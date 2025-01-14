주요 기능

* 회원 관리
* 상품 카테고리
* 장바구니/주문 기능
* 관리자 대시보드
* 반응형 디자인

설치 및 실행
PHP 7.0 이상 필요
MySQL/MariaDB 데이터베이스 설정
AWS EC2에 배포
config 파일에서 DB 접속 정보 설정

--------------------------------
시스템 구성

백엔드: PHP
호스팅: AWS EC2
파일 구조:

index.php: 메인 페이지
_common.php: 공통 함수
group.php: 그룹 관련 기능
head/tail.php: 페이지 레이아웃
theme.config.php: 테마 설정

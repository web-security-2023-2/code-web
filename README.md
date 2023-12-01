* 어플리케이션 실행 방법

lnmp2$ sudo docker-compose up


* 어플리케이션 세부 정보
- nginx 버전은 1.10을 사용했다. 왜냐하면 1.17.7 이전 버전까지 HTTP request smuggling 취약점이 존재하여 실험 환경을 동일하게 구성하기 위함이다.

(출처)
https://nvd.nist.gov/vuln/detail/CVE-2019-20372

- mysql은 5.7 버전을 사용했다.

- php 5.6 버전을 사용했다.


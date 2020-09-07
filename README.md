# prediction_web_service

## 개발환경
``` sh
* Python 3.7 ver
* RDS(My sql)
* AWS EC2
* AJAX
* UBUNTU (AWS)
* Putty
```

## 세팅

``` sh
$ sudo pip3 install python3
$ sudo pip3 install flask
$ sudo pip3 install pymysql
$ sudo iptables -A PREROUTING -t nat -i eth0 -p tcp --dport 80 -j REDIRECT --to-port 5000
$ sudo python3 main.py
```

## 프로젝트 설명
* 리얼타임 스포츠 베팅 시뮬레이션 웹사이트 개발
- 해외 배당 API bets365 활용

## 주요 기능
* 실시간 베팅 서비스 (Proxy Server)
* 아이템 거래 기능
* Regional Proposal과 Classification을 순차적으로 이루기 위한 two-stage를 이용한 추천 알고리즘

## 데이터 아키텍처
<img src="static/images/data.png" height="100"></img>

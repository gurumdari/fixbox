# FixBox
FixBox는 Postfix와 Dovecot로 메일 서버를 구축한 환경에서 도메인 및 계정을 관리해주는 시스템이다. Apache SpamAssassin으로 스팸메일 필터링을 하고 있다면, Required Score 설정 및 Whitelist와 Blacklist 관리도 할 수 있게 해준다. Modern한 UI로 무료로 구축 가능한 Webmail client server인 RainLoop의 자동 설치 및 연동도 제공한다.

FixBox는 반응형 웹으로 구현되어 있어 PC뿐만 아니라, Mobile 환경에서도 쉽게 접근해서 사용이 가능하다.

### 사용 가이드
FixBox의 자세한 사용법은 아래의 FixBox 공식 사이트를 참조하기 바란다.

[https://fixbox.gurumdari.com](https://fixbox.gurumdari.com)

### 사용 환경
FixBox는 PHP 기반의 Web Application으로써, PHP 7.0 이상을 지원하는 Linux 서버 환경에 설치가 가능하다. 사전에 Postfix와 Dovecot로 메일 서버를 구축한 환경이어야 한다. Mail 계정은 MySQL (MariaDB 포함)로 관리하게 가상 계정으로 구축되어 있어야 한다. Client PC 환경은 별도의 Client용 프로그램 설치가 필요없고, HTML5를 지원하는 Web Browser를 통해 언제 어디서나 FixBox가 설치된 Server에 접속하면 바로 사용이 가능하다. 단, Internet Explorer의 경우 10 이상의 버전만 지원한다.

<p align="center"><img src="images/html5.png?raw=true" width="352" /></p>

<p align="center"><img src="images/ie10_11.png?raw=true" width="352" /></p>

### 다국어 지원
FixBox는 Web Browser에 설정된 언어에 따른 언어로 자동 표시되도록 언어팩 기능을 제공한다. 현재, 한국어, 영어를 자체 내장하고 있으며, 필요시 직접 언어 팩을 만들어 사용할 수도 있다. Web Browser에 설정된 언어와 상관없이 특정 언어로만 사용할 수 있는 기능을 시스템 환경 설정으로 할 수 있게 제공한다.

<p align="center"><img src="images/languages.png?raw=true" width="399" /></p>

### 기부 Donate
FixBox는 Jnode Framework를 기반으로 만들어진 무료 소프트웨어이다! 만약 FixBox와 Jnode Framework을 사용하면서 유용하다고 생각했다면, 자발적인 기부를 부탁드린다. 금액에 상관없이 참여한 기부금에 대해 보다 나은 FixBox와 Jnode Framework 개발로 보답하겠다. 아울러 우리 나라에서도 공개 소프트웨어가 활성화되고, 기부문화도 활성화되는 계기가 되었으면 한다.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6YYMTECUZXM9S)

### 다른 언어로 읽기
[영어 (English)](https://github.com/gurumdari/fixbox/blob/master/README.md)
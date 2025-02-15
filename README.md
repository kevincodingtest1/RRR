# PROJ
### TEST
## package
### install

```
npm i @fastify/static fastify-socket.io socket.io pm2
```

```
npm i --save rate-limiter-flexible
```

### summary
[@fastify/static](https://www.npmjs.com/package/@fastify/static)
@fastify/static은 Fastify 웹 프레임워크를 위한 플러그인으로, HTML, CSS, JavaScript, 이미지 등의 정적 파일을 지정된 디렉토리에서 제공할 수 있게 해줍니다. 개발자가 기본 디렉토리를 설정하면 모듈이 자동으로 요청된 URL 경로를 해당 파일에 매핑합니다. Fastify 버전 4.x를 지원하며, 디렉토리 목록, 캐시 제어, 사용자 정의 헤더 등의 옵션을 제공합니다.

```
npm i @fastify/static
```

[fastify-socket.io](https://www.npmjs.com/package/fastify-socket.io)

fastify-socket.io는 Socket.IO를 Fastify와 통합하기 위한 플러그인입니다. 웹 클라이언트와 서버 간의 실시간, 양방향 통신을 가능하게 합니다. 채팅 애플리케이션, 실시간 알림, 협업 도구 등 실시간 업데이트가 필요한 애플리케이션에 유용합니다. Socket.IO의 기능을 활용하면서 Fastify 프레임워크에 최적화되어 높은 성능과 낮은 오버헤드를 보장합니다.

```
npm i fastify-socket.io socket.io
```

[pm2](https://www.npmjs.com/package/pm2)
pm2는 Node.js 애플리케이션을 위한 인기 있는 프로덕션 프로세스 관리자입니다. 애플리케이션을 영구적으로 실행하고, 다운타임 없이 재로드하며, 일반적인 시스템 관리 작업을 용이하게 합니다. 프로세스 모니터링, 로그 관리, 클러스터링, 핫 리로딩 등의 기능을 지원합니다. 프로덕션 환경에서 애플리케이션이 원활하고 효율적으로 실행되도록 하는 데 널리 사용됩니다.

```
npm i pm2
```

[rate-limiter-flexible](https://www.npmjs.com/package/rate-limiter-flexible)
rate-limiter-flexible은 Node.js를 위한 유연한 속도 제한 라이브러리입니다. Redis, MongoDB, 인메모리 스토리지 등 다양한 백엔드를 지원하며, 개발자가 애플리케이션에 대한 요청 속도를 제어할 수 있게 해줍니다. 남용 방지, 공정한 사용 보장, 서비스 거부(DoS) 공격 방지에 유용합니다. 고정 윈도우, 슬라이딩 윈도우, 토큰 버킷 알고리즘 등 다양한 속도 제한 전략을 제공합니다.

```
npm i --save rate-limiter-flexible
```

[socket.io](https://www.npmjs.com/package/socket.io)
socket.io는 웹 클라이언트와 서버 간의 실시간, 양방향, 이벤트 기반 통신을 가능하게 하는 라이브러리입니다. 브라우저에서 실행되는 클라이언트 측 라이브러리와 Node.js용 서버 측 라이브러리로 구성됩니다. 멀티플렉싱, 바이너리 지원, 재연결, 다중 클라이언트 브로드캐스팅 등의 기능을 제공합니다. 채팅 애플리케이션, 실시간 업데이트, 멀티플레이어 게임 등 실시간 상호작용이 필요한 애플리케이션에 주로 사용됩니다.

```
npm i socket.io
```
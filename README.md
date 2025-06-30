# n8n-flow

n8n을 이용하여 워크플로우를 생성하여 관리 할수 있습니다.

## 사용 방법

1. 실행하기

```bash
# n8n-flow root
./start.sh
```

2. 브라우저에서 `http://localhost:5678`에 접속합니다.
3. n8n의 워크플로우를 생성하거나 불러와서 사용할 수 있습니다.
4. 종료하기

```bash
# n8n-flow root
./stop.sh
```

## 폴더 구조

- `docker-compose.yml`: n8n 및 관련 서비스 설정 파일
- `start.sh`: n8n 서비스를 시작하는 스크립트
- `stop.sh`: n8n 서비스를 종료하는 스크립트

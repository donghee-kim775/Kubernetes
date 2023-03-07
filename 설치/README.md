# Window에 Kubectl 설치 및 설정

## kubectl이란?
> 쿠버네티스를 다루기 위한 명령행 도구

---
## 윈도우에 kubectl 설치

### 윈도우에 curl을 사용하여 kubectl 바이너리 설치

1. 최신 릴리스 v1.26.0을 다운
~~~
curl -LO "https://dl.k8s.io/release/v1.26.0/bin/windows/amd64/kubectl.exe"
~~~

2. 바이너리를 검증 (선택 사항)

__kubectl__ 체크섬 파일을 다운로드 한다.
~~~
curl -LO "https://dl.k8s.io/v1.26.0/bin/windows/amd64/kubectl.exe.sha256"
~~~

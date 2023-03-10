# Docker 설치

## Docker desktop 설치
> Docker desktop은 기본적으로 Hyper-v기능 사용


---
관련 사이트
window 10 - Home (desktop 환경)
https://www.lainyzine.com/ko/article/a-complete-guide-to-how-to-install-docker-desktop-on-windows-10/

~~~
>>systeminfo
~~~
> os 및 os 버전 확인

저자의 경우 - os : window 10 home

window의 경우

1. window 10 Pro -> hyper-v기반 가상화 사용-> docker engine 사용 가능

2. window 10 Home -> WSL2가 필수

WSL을 설치하여도 도커실행시 이러한 오류가 발생할 수 있다.
![image](https://user-images.githubusercontent.com/54052704/224153950-91d94f16-e58b-4719-8f8e-a52b3d7a2d14.png)


-> 이러한 경우이기에 그냥 hyper-v를 설치하여 hyper-v 기능을 활성화하였다.

hyper-v 설치 URL : https://zkim0115.tistory.com/1523#google_vignette

hyper-v 활성화 power shell or windows terminal (관리자 권한실행)
~~~
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All
~~~

입력을 해주면되는데 Enable이 설정이 안되어있는 경우가 있다 그러한 오류가 발생시 밑 URL을 참고하여 저자는 고치게 오류를 수정하게 되었다.

> https://monstergreen.tistory.com/242

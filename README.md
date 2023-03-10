# Kubernetes란?

컨테이너화된 애플리케이션을 배포, 관리, 확장할 때 수반되는 다수의 수동 프로세스를 자동화하는 오픈소스 컨테이너 오케스트레이션 플랫폼

> 컨테이너? 어떤 환경에서나 실행하기 위해 필요한 모든 요소를 포함하는 소프트웨어 패키지

---



# 가상 머신(VM) vs 컨테이너

## 가상 머신 (VM)

- __물리적 하드웨어를 가상화__ 합니다.
- 각각의 VM에서는 __애플리케이션, 이와 연관된 라이브러리 및 종속 항목__ 과 함께 OS가 실행해야 하는 하드웨어의 가상 사본인 __게스트 OS__ 가 포함된다.

---

![image](https://user-images.githubusercontent.com/54052704/224264740-3f59249f-3efc-4ae6-8004-8cec97528c39.png)

## 컨테이너

- __운영 체제(일반적으로 Linux)를 가상화함__
- __각 개별 컨테이너__ 에는 __오직 애플리케이션과 함께 해당 라이브러리와 종속 항목__ 만 포함된다.
- __게스트 OS__ 의 부재는 컨테이너가 경량이며 빠르고 포터블한 이유를 설명한다.

## 이미지

- Docker Image는 컨테이너를 만드는데 사용되는 읽기 전용 템플릿
- 컨테이는 이러한 템플릿에서 생성된 배포된 인스턴스

Docker Image -> 레시피

Docker Container -> 그 레시피에서 준비된 케이크

# Kubernetes Infra 구축
### GCP GKE를 활용한 Container 기반 3-Tier 웹 서비스 인프라 구축

</br>

## 🗓️ 진행 기간
- 2022.10.10 ~ 2022.10.14

</br>

## 👥 팀 구성
- Infra 구축 5명

</br>

## ⚙️ 사용 기술
#### CSP
<img src="https://img.shields.io/badge/Google GCP-4285F4?style=for-the-badge&logo=Google Cloud&logoColor=white"> <!--gcp-->

#### OS
<img src="https://img.shields.io/badge/Rocky Linux 9-10B981?style=for-the-badge&logo=Rocky Linux&logoColor=white"> <!--rocky linux-->

#### DB
<img src="https://img.shields.io/badge/mysql 5.7-4479A1?style=for-the-badge&logo=mysql&logoColor=white">  <!--mysql-->

### Container
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">  <!--Docker-->

### Orchestration
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=Kubernetes&logoColor=white">  <!--k8s-->
<img src="https://img.shields.io/badge/GCP GKE-4285F4?style=for-the-badge&logo=Google Cloud&logoColor=white"> <!--gcp gke-->

### Framework
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white">  <!--spring-->

#### Team Collabolation Tool
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> <!--Notion-->
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"> <!--Git-->
<img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white"> <!--Github-->

#### Architecture Draw Tool
<img src="https://img.shields.io/badge/Drawio-000000?style=for-the-badge&logo=Drawio&logoColor=white"> <!--Draw.io-->

</br>

## 🙋🏻‍♂️ 담당 업무
- GKE Autopilot mode 클러스터 구축
- Git Repository에 Web, Was 소스코드 배포 및 수정
- Web-Was 연동(conf 파일 수정)
- Dockerfile 컨테이너 이미지 빌드
- Cloud SQL-Was 연동
- GAR(Artifact Registry)에 컨테이너 이미지 배포
- yaml 파일 생성 및 Apply
- ingress에 구글 완전관리형 인증서 옵션 추가 후 Cloud DNS 레코드 A 추가
- Cloud Monitoring를 통해 클러스터 관리

</br>

## 📝 상세 내용 
### 📌 Infra Architecture
<p align="center"><img src="https://user-images.githubusercontent.com/117608997/215993850-450aa2ad-e7b1-45b7-b34b-a6cf483435c4.png" width="75%" height="75%"></p>
```
GKE Autopilot 모드 클러스터 서비스를 활용한 컨테이너 기반 인프라 구축
```

</br>

### 📌 GKE Architecture
![image](https://user-images.githubusercontent.com/117608997/215608234-6dd86c23-2997-41a1-af82-07f75595b3d5.png)
```
GKE Web Pod는 정적인 서비스 제공하고, Was Pod는 DB와 동적인 서비스 제공
Container Registry와 Cloud Build를 통한 이미지 배포 관리
```

## ⛓️ 구축 과정
### 🔗 Notion Link
#### - [GCP Kubernetes Project](https://glen-party-257.notion.site/GCP-Kubernetes-Project-9f417ae840834d4490367826b2114c5c)

</br>

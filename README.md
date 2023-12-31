﻿# 제 8회 부산 ICT 융합 해커톤 대회 참가 프로젝트
## 1. 프로젝트 소개 
- 주제 : 인삼 년근 판독 및 등급 식별 AI 모델 개발, 인삼 부위 판별 AI 모델 개발, 웹 서비스 개발
- 주제 선정 이유 : 이미 많은 AI서비스가 제공되고 있는 지금 틈새 시장을 공략하기 위해 이번 주제 선정
- 활용 데이터 : [인삼 년근 판독 및 등급 식별을 위한 인공지능 학습데이터(AI Hub)](https://www.aihub.or.kr/aihubdata/data/view.docurrMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=71426)
- 기간: 2023.08.09 ~ 08.10(무박 2일로 진행)

- 상세 프로젝트 설명 및 기술 설명  [<img width="23" src="https://upload.wikimedia.org/wikipedia/commons/e/e9/Notion-logo.svg"/>
보러가기](https://midi-mind-784.notion.site/8-ICT-PPT-3210e50945d14e5dbd535fd11a760b2c?pvs=4)

## 2. 팀원 
|<img width="200" alt="image" src="https://avatars.githubusercontent.com/u/70638717?v=4">|<img width="200" alt="image" src="https://avatars.githubusercontent.com/u/86204430?v=4">|<img width="200" alt="image" src="https://avatars.githubusercontent.com/u/129818881?v=4">|<img width="200" alt="image" src="https://avatars.githubusercontent.com/u/98063854?v=4">|
| :---------------------------------: | :-----------------------------------:|:-----------------------------------:|:-----------------------------------:|
|                AI 모델 개발         |           AI 모델 개발                |                AI 모델 개발         |           웹 서비스 개발             | 
|             김민범                  |          최호진                      |                  하성진              |          김재민                     |        
| [GitHub](https://github.com/sou05091/)  | [GitHub](https://github.com/Gansaw/)  | [GitHub](https://github.com/JaeMin1130)  | [GitHub](https://github.com/JaeMin1130)|

## 3. 개발 일지
- 08.01 : 주제 선정 회의 진행
- 08.02 : 역할 분담 및 개발 계획 수립
- 08.03 : 데이터 환경 구성(Colab)
- 08.04 ~ 08.08 : YOLOv5 데이터 전처리 (txt파일 생성) 및 학습
- 08.09 ~ 08.10 : 발표 및 PPT작성
- 08.16 : flask 서버 구축 및 웹사이트 제작

## 4. 사용 기술
<div align="center">
  <p>
    <a align="center" href="https://ultralytics.com/yolov5" target="_blank">
      <img width="100%" src="https://raw.githubusercontent.com/ultralytics/assets/main/yolov5/v70/splash.png"></a>
  </p>
<br>

<div>
    <a href="https://github.com/ultralytics/yolov5/actions/workflows/ci-testing.yml"><img src="https://github.com/ultralytics/yolov5/actions/workflows/ci-testing.yml/badge.svg" alt="YOLOv5 CI"></a>
    <a href="https://zenodo.org/badge/latestdoi/264818686"><img src="https://zenodo.org/badge/264818686.svg" alt="YOLOv5 Citation"></a>
    <a href="https://colab.research.google.com/github/ultralytics/yolov5/blob/master/tutorial.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>
    <br>
    <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>
  </div>
  </div>
  
## 5. 결과
- Flask AI모델 연동 웹서비스 제작
<img src="https://github.com/sou05091/2023-ICTBusanHakaton/blob/main/img/Ginseng_classfication.png"/>

- 이미지 결과
<img src="https://github.com/sou05091/2023-ICTBusanHakaton/blob/main/img/Ginseng_result.png"/>

- 모델 결과

## 5. 느낀점
- 첫 해커톤 대회를 팀장으로 많은 부담감을 가지고 하다보니 부족한 부분들이 많았음
- 마지막날 다른 팀들의 최종 결과물을 보니 우리팀 프로젝트 완성도가 너무 부족하다고 느꼈음
- 이번 해커톤 대회에서는 AI, 웹서비스 기술 보다 사업성및 프로젝트 완성도를 많이 보았음
- 짧은 시간안에 모델을 학습시켜야 하기 때문에 정확도가 좋게 나오기 힘들었음

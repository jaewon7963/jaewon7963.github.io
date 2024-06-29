# AI개발자 주재원 입니다.


<p align="center">
  <kbd>
    <img src="https://lh3.googleusercontent.com/drive-viewer/AKGpihYA8AjAYVRkLKYMeh76Nek6yveJDP6H3M_aPtymLvbOk4IDSv7581zy7Dxev8tSx8MRbLV1YZVkSM2uoxuAm3b7VdeIv8lwplw=w1920-h1080-rw-v1" width="380" height="500" style="float: left;">
  </kbd>
  <div>
    
    - 1997.04.01 출생

    - 2016.03 조선대학교 항공우주공학과 입학

    - 2020.04 공군 17전투비행단 만기전역

    - 2021.03 전남대학교 전자컴퓨터공학부 소프트웨어공학전공 편입 / 조선대학교 자퇴

    - 2024.02 전남대학교 전자컴퓨터공학부 소프트웨어공학전공 학사졸업
  
  </div>
</p>

<img src="https://img.shields.io/badge/Python-3776AB?style=plastic&logo=python"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=plastic&logo=PyTorch"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=plastic&logo=mysql"/> <img src="https://img.shields.io/badge/C-A8B9CC?style=plastic&logo=c"/> <img src="https://img.shields.io/badge/C%2B%2B-512BD4?style=plastic&logo=cplusplus"/>
  
## ✔️ 진행했던 프로젝트

# 2021.03 UNITY FPS 게임 기능 구현 프로젝트

<img src="https://github.com/jaewon7963/jaewon7963.github.io/assets/81609477/1b338d51-c94a-4a69-8455-681475c0cb07"/>
<p align="center">
  <kbd>
<img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/010.gif"/>
  </kbd>
</p>

  * UNITY의 학습용 FPS 에셋을 기반으로, 운영되고 있는 게임들의 기능들을 직접 구현해보고자 가볍게 진행한 프로젝트입니다.
  * 저를 포함하여 4명의 인원으로 진행하였으며 저는 게임플레이 요소를 담당하였습니다.
  * 초기 목표는 게임 모드 추가, 스태미너 시스템 추가, 플레이어 제한 요소가 있었으나
  * 실제 구현은 스태미너 시스템과, 플레이어 제한 요소(질주 도중 사격 금지)만 성공하였습니다.

---

# 2022.11 전력소비량 시계열 예측 프로젝트

  
  * Randomforest를 이용해 전력소비량을 예상하는, 시계열 예측 프로젝트입니다.
  * 처음으로 AI에 입문을 하게 된 프로젝트이며
  * AI 모델 개발에 있어서 가장 중요한 것이 Data의 양과 품질이라는 것을 본 프로젝트를 통해 이해할 수 있었습니다.


  <p align="center">
    <kbd>
  <img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/data2.PNG" /><img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/heatmap.png"/>
    </kbd>
  </p>


  * 한전의 일별 전력 소비량, 기상청의 기상데이터들을 사용해 5년간의 데이터들을 획득하였습니다.
  * 전력 소비량에 영향을 주는 요소로 '주말(공휴일), 기온, 시간, 요일, 월' 로 지정하였습니다.
   <p align="center">
      <kbd>
    <img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/forest002.png"/>
      </kbd>
   </p>


  <p align="center">
    <kbd>
  <img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/r9.png" width="480" height="300"/><img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/r12.png" width="480" height="300"/>
    </kbd>
  <div>
  -  파란색 데이터는 실제 데이터이며 붉은색 데이터는 Randomforest 모델이 예측한 데이터입니다.
  </div>
  </p>
  
  * 생성된 모델은 보유하고 있는 테스트 데이터와 훈련 데이터셋에 대하여 높은 R2 SCORE를 가졌으나 과적합의 양상을 보였습니다.
  
  * 비록 결말이 아쉬운 마무리된 프로젝트지만 제가 AI에 입문할 수 있었던 계기가 되었습니다.
  
--- 
    
# 2023.03 화장품 성분표 인식 OCR 어플리케이션 프로젝트

  <img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/ocr_folder/%EC%84%9C%EB%B9%84%EC%8A%A4%20%EA%B5%AC%EC%A1%B0.png" width="500" height="300"/><img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/ocr_folder/%EC%8B%9C%EC%8A%A4%ED%85%9C%20%EA%B5%AC%EC%A1%B0.png" width="500" height="300"/>

  * 졸업작품이자 논문을 작성하기 위해 진행한 프로젝트입니다.
  * 유저가 카메라 또는 갤러리의 화장품 성분표 사진을 전송하면 이미지 내 글자를 인식하여 해당 성분을 DB에 검색하는 구조이며, 화장품 내 전성분과 배합제한성분 검출 여부를 화면으로 확인할 수 있는 서비스 입니다.
  
  
  * 저를 포함해 3명의 팀원과 함께 진행하였습니다.
  * Front-end, Back-end, AI 세 분야 중 저는 AI를 담당하였습니다.
  * TextDetection은 NAVER CLOVA 팀에서 개발한 CRAFT를 사용하였습니다.
  * TextRecognition은 NAVER CLOVA 팀에서 개발한 deep-text-recognition benchmark를 사용하였습니다.

  <img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/ocr_folder/AI%20%EA%B5%AC%EC%A1%B0.png"/>

  * 본 프로젝트는 textrecognition 모델의 한글과 특수문자 학습을 통한, 높은 정확도
  * 화장품 성분표 특성상, 굴곡이 진 글자 및 줄바뀜으로 인해 분리가 되는 하나의 단어 와 같은 문제해결에 초점을 두어 진행하였습니다.
  <img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/ocr_folder/init.png" width ="480" height="300"/> <img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/ocr_folder/result03.png" width ="480" height="300"/>
 
  * 한글, 특수문자 학습을 위하여 하이퍼파라미터 조절과 Data 및 학습 관리를 통하여
  * 최종적으로 한글 및 특수문자로 이루어진 약 110,000개의 훈련 데이터와 40,000개의 검증 데이터로 이루어진 Dataset을 24,000 epoch 학습을 시킨 최대 정확도 약 95% 의 textRecognition 모델을 생성하였습니다.
  * 문제해결을 위하여, CRAFT를 통하여 얻어낸 bounding box 좌표들을 원근변환에 사용하여 textdetection와 textrecognition을 연결함과 동시에 굴곡을 해결하였습니다.
  <img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/ocr_folder/convert00.png"/><img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/ocr_folder/convert01.png"/>
  * 또한, 하나의 단어가 분리되는 문제점은 ~~이러한 방식의 bounding box 정렬 및, 분리가 된 단어 판단 알고리즘을 작성하여 해결하였습니다.

---

# 2023.09 퍼스널 컬러 진단 AI 프로젝트

  <p align="center">
  <kbd>
    <img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/personal0.png" width="720" height="480">
  </kbd>
</p>
  

  * 회사에서 사용하고 있는 무인 의류매장 키오스크에 도입할 퍼스널 컬러 진단 AI 모델을 개발하는 프로젝트로써
  
  * 크롤링을 통하여 약 2,700 장의 사진을 사용하였으며, Catboost 모델을 학습해 사용하였습니다.
  
  * 1. 고객의 얼굴 이미지를 입력으로 받으며
    2. 해당 이미지에서 이마, 뺨, 턱에서 특징들(황도, 채도, 명도 등등..)을 추출합니다.
    3. 추출한 특징들을 학습시켜둔 boost 모델을 이용하여 고객의 퍼스널 컬러를 추론한 뒤
    4. 추론된 퍼스널 컬러로 데이터베이스에 저장해둔 의상에서 어울리는 상의 4개, 하의 4개를 Random choice 하여 보여줍니다. 


  - 프로젝트의 자세한 사항은 제 개인 노션페이지, [여기](https://stealth-splash-4d7.notion.site/13ebbbd32df04e269c21a54c993c4a42?pvs=74)를 통해서 확인하실 수 있습니다.

---

✔️ 경력
* 2023.09.01 ~ 2023.11.29 써니팩토리 - 무인 의류매장 플랫폼(키오스크) & 퍼스널 컬러 진단 AI 개발 인턴십
<p align="center">
  <kbd>
    <img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/002.gif" width="480" height="300">
  </kbd>
</p>


✔️ 자격증 및 수상 🏆

- 2022.09 정보처리기사

- 2023.04 한국스마트미디어학회 - 학부생논문경진대회 우수논문상 수상
  <p align="center">
  <kbd>
    <img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/prize00.png" width="480" height="300">
  </kbd>
</p>

- 2023.07 전남대학교 소프트웨어중심대학사업단 - 산학협력프로젝트 성과발표회 은상 수상
  <p align="center">
  <kbd>
    <img src="https://github.com/jaewon7963/jaewon7963.github.io/blob/master/src/assets/images/prize01.png" width="480" height="600">
  </kbd>
</p>

---

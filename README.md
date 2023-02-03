# 2023 포디블록 구조 추출 AI 경진대회

## 배경

포디블록(4Dblock)은 유아기∼전 연령을 대상으로 하는 융합놀이를 위한 조작교구 입니다.

블록놀이는 공간 지각능력과 창의력 발달에 도움이 되는 놀이도구이며, 교육용 블록교구는 다양하게 구성 및 조적하게 되어있어 비구조적인 특징을 갖습니다.

하지만 이러한 비구조적인 특성은 발달특성상 유아들에게는 목적 없는 놀이도구로 소진되기 쉽기 때문에 보다 창의적인 높은 수준의 블록놀이를 촉진하기 위해서 체계적인 쌓기 구조에 대한 사전지식의 지원이 필요합니다.

이를 위해 어린이의 쌓기 구조 데이터를 수집하고 이에 대한 반복적인 블록 쌓기 구조 패턴 인식 및 쌓기 구조의 패턴을 분류하여 효율적이고 유용한 방법 및 해결책을 제시할 수 있을 것입니다.

이 기술은 나아가 오프라인 실험군, 통제군을 대상으로한 공간지각력, 창의성 등 자체 개발 된 평가 툴을 추가 학습시켜 사용자의 융합적 레벨 테스트를 같이 제공하여 블록 놀이&활동을 통한 교육적 진단 서비스로 확장 하고자 합니다.

학습자 선호 유형에 따른 활동 및 프로그램 매칭에 적용할 2D 이미지 기반 블록 구조 추출 AI 모델을 만들어 주세요.

## 주제

2D 이미지 기반 블록 구조 추출 AI 모델 개발

## 설명 

본 경진대회에서는 2D 이미지 내 포디블록의 10가지의 블록 패턴들의 존재 여부를 분류하는 Multi-Label Classification을 수행해야합니다.

또한 실험 환경에서 촬영된 이미지가 학습 데이터로 주어지며, 평가(테스트 데이터)는 실제 환경에서 촬영된 이미지로 이루어집니다.

# 나의 접근

 
<div>
  <p align="left">
   <p> Train 데이터 </p>
   <img src="https://user-images.githubusercontent.com/74355042/216530539-a710d59d-9e5b-4777-86c8-eac0e6a14e31.jpg" width="300px" height="300px">
  </p>
  
  <p align="right">              
   <p> Test 데이터 </p>
   <img src="https://user-images.githubusercontent.com/74355042/216530615-587f7e44-1b4e-4cf7-8dc9-1b4d64a32d2b.jpg" width="300px" height="300px">
  </p>
</div>

Train, Test 데이터의 차이점으로 Train 데이터에는 배경이 존재하지 않음 </br>
-> 배경 데이터를 구하여 Train 데이터와 이미지 합성 후 학습 진행 (Check Data & Augmentation.ipynb 파일)

이후 Train (train_baseline.ipynb 파일)






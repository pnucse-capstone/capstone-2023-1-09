[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/fnZ3vxy8)
본문입니다.

# 1. 프로젝트 소개
  - 이번 프로젝트의 주제는 "심장질환 환자 ECG 데이터 분석을 위한 딥러닝 기법 설계" 입니다. RNN, CNN의 딥러닝 모델을 구현하여, 정확도 및 ROC AUC를 비교하여 어떠한 모델이 주제에 더 적합한 모델인지를 연구한 프로젝트입니다.

# 2. 팀 소개
  - 김정무 부산대학교 정보컴퓨터공학부 201824447 hansongkim@pusan.ac.kr
  - 김지윤 부산대학교 정보컴퓨터공학부 201824455 rlacl829@pusan.ac.kr
  - 천효승 부산대학교 정보컴퓨터공학부 201824601 cjsgytmd@pusan.ac.kr
    
# 3. 구성도
### <데이터 전처리>
   ![데이터전처리 구성도](https://github.com/pnucse-capstone/capstone-2023-1-09/assets/147837947/b111d53c-895b-447a-8650-0aa6108afe59)
   
### <BiLstm구성도 및 결과>
   ![BiLstm 구성도](https://github.com/pnucse-capstone/capstone-2023-1-09/assets/147837947/3dd9acd2-0b0a-4331-b4ab-7281ee82163e)
   
   ![Lstm 결과치](https://github.com/pnucse-capstone/capstone-2023-1-09/assets/147837947/0693eeda-375b-4619-8b9a-f8d95c548ddc)
   
   ![Lstm ROC/AUC curve](https://github.com/pnucse-capstone/capstone-2023-1-09/assets/147837947/3c4177dc-3fea-4a1d-b308-c2a682d997d5)


### <ResNet101구성도 및 결과>
   ![ResNet101 구성도](https://github.com/pnucse-capstone/capstone-2023-1-09/assets/147837947/f3187434-a472-4286-9acb-81acf5b70f9c)
   
   ![ResNet 결과치](https://github.com/pnucse-capstone/capstone-2023-1-09/assets/147837947/f4d52a7a-a0a8-4395-8b97-3053b749c0bb)
   
   ![ResNet 모델 ROC/AUC curve](https://github.com/pnucse-capstone/capstone-2023-1-09/assets/147837947/fe3d34ba-a110-443f-82f6-ce8e76f56f17)



# 4. 소개 및 시연 영상
[2023년 전기 졸업과제 09 DeepHeart](https://www.youtube.com/watch?v=-FRwygKBJ28)
    
# 5. 사용법
pytorch기반의 딥러닝 프로그램으로, python환경 구축이 필요합니다. 데이터셋의 크기가 구글 colab환경에서 다룰 수 있는 메모리용량을 초과하기 때문에, 32GB이상의 메모리 환경이 권장됩니다.
ECG dataset속 ptbxl_database.csv파일을 기반으로 학습을 진행합니다. 파일의 경로에 주의하여야 합니다.



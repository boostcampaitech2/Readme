![main](https://user-images.githubusercontent.com/50396533/147068283-70e7fc60-b787-45ea-b76f-15e7006f1f3e.png)

# 부스트캠프 AI Tech 2기의 Github에 오신 것을 환영합니다
부스트캠프는 좋은 경험과 습관을 가진 지속 가능한 개발자를 목표로 서로에게 배우고 문제를 해결하며 성장합니다. 이곳에서는 부스트캠프 AI Tech에 참여한 학생(캠퍼)들의 프로젝트 결과를 확인할 수 있습니다.

### [2기 교육과정 소개]
부스트캠프 AI Tech 에서는 AI로 비즈니스 가치를 창출하는 AI 엔지니어를 목표로 지난 5개월 동안 인공지능과 딥러닝에 대한 기초와 AI 모델을 구현하고 개선하는 일련의 실무 과정을 경험합니다. 

* 기간 : 2021년 8월 2일 ~ 21년 12월 27일, 총 800시간 (100일간 10:00~19:00 풀타임 학습) 
* U Stage(기초이론+실습) : AI 모델 개발/서비스 적용에 필요한 기초 지식을 학습하고 도메인마다 널리 쓰이는 backbone 모델을 다룹니다. 
* P Stage(대회형 실습) : AI를 많이 활용하는 응용 분야의 실전 프로젝트를 통해 현업과 유사한 엔지니어링 프로세스를 경험합니다.



![path_of_growth](https://user-images.githubusercontent.com/50396533/147068345-3dbc42a0-c0db-4597-b007-ccfb26a7a9dc.png)



## [프로젝트 개요]


* __공통__

이름|검색키워드|설명|평가방법
----|----|----|----
이미지분류|image-classification-level1|인물 사진에서 사람이 마스크를 쓰고 있는지, 쓰지 않았는지, 정확히 쓴 것이 맞는 지, 자동으로 가려낼 수 있는 모델을 구현합니다. |F1, accuracy


* __Computer Vision (컴퓨터 비전)__

이름|검색키워드|설명|평가방법
----|----|----|----
객체 영역 구분|object-detection-level2|쓰레기가 찍힌 사진들 속에서 물체를 분류하는 모델을 만듭니다. |mAP
객체 검출|semantic-segmentation-level2|위 프로젝트에서 분류된 결과를 기반으로 쓰레기를 구분하여 분리수거를 할 수 있는 모델을 구현합니다. |mIoU
데이터 제작|data-annotation-level3-cv|실무에서 활용되는 AI 프로젝트 과정의 전반적인 이해와 함께 피드백 사이클을 통해 점진적으로 모델 성능을 개선합니다. |F1
모델 최적화|model-optimization-level3-cv|작은 규모의 Auto ML을 활용하여 작고 빠른 이미지 분류 모델을 만드는 프로젝트입니다. 제한된 자원을 가지고 이미지에서 재활용 쓰레기를 분류하는 모델을 경량화합니다. |Score(F1, time)
최종 프로젝트|final-project-level3-cv|팀별로 자유롭게 주제를 선정하여 AI 모델링 프로젝트를 진행합니다. |-


* __Natural Language Processiong (자연어 처리)__

이름|검색키워드|설명|평가방법
----|----|----|----
한국어 언어 모델 학습 및 다중과제 튜닝|klue-level2|자연어 문장에서 단어간의 관계를 추론하여 정보를 요약하고, 중요한 성분을 파악하는 모델을 구현합니다. 이를 통해 질문에 답변하는 AI를 만들 수 있습니다. |Micro_f1
기계독해|mrc-level2|질문 데이터 없이 지식 정보만을 학습하여 다양한 질문에 답변하는 AI를 구현합니다. 어떤 질문이 입력될지 알 수 없어 어려우며, retriver와 reader 두 모델을 직접 구현해야 합니다. |EM
데이터 제작|data-annotation-level3-nlp|실무에서 활용되는 AI 프로젝트 과정의 전반적인 이해와 함께 피드백 사이클을 통해 점진적으로 모델 성능을 개선합니다. |-
모델 최적화|model-optimization-level3-nlp|작은 규모의 Auto ML을 활용하여 작고 빠른 이미지 분류 모델을 만드는 프로젝트입니다. 제한된 자원을 가지고 이미지에서 재활용 쓰레기를 분류하는 모델을 경량화합니다. |Score(F1, time)
최종 프로젝트|final-project-level3-nlp|팀별로 자유롭게 주제를 선정하여 AI 모델링 프로젝트를 진행합니다. |-

# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김준석
- 리뷰어 : 양지웅


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부

          * 트랜스포머 모델 구조를 확인함
![image](https://github.com/user-attachments/assets/b5e0a7fc-4833-4e43-a447-859a23ad0ad3)

          * 그래프를 통해서 학습 모델의 loss와 accuracy를 비교하였음
![image](https://github.com/user-attachments/assets/331c274a-28cb-4900-9136-658e5431a40c)

          * 인퍼런스 디코더를 통해 한국어 문답이 잘 진행되고 있음을 확인함
![image](https://github.com/user-attachments/assets/49379400-b15b-4728-817b-2696aa7d63f2)



- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
            * 전처리를 데이터에 맞춰서 진행하였음 
    ![image](https://github.com/user-attachments/assets/ad74b56b-eb79-4488-a305-8890e9159a4a)
            * 각 의문점들을 프로젝트를 진행하며 풀어냄
    ![image](https://github.com/user-attachments/assets/c31b0d7c-d341-40f6-8b4b-e066d368a081)
            * 예제 모델과 논문에서 구현한 모델을 비교 분석하고 의문점들을 정리 해결함
    ![image](https://github.com/user-attachments/assets/e85db55d-3794-4aa2-89a8-afca7d95b119)
            * NLP에서 활용되는 특징에 맞게 여러 평가지표(정성적,정량적)를 사용하여 비교 분석함
    ![image](https://github.com/user-attachments/assets/50742f05-e441-43a1-a7f8-f2eb923b9585)
    ![image](https://github.com/user-attachments/assets/a065aef3-947d-4cb8-89c1-2f5bfca4ba89)
    ![image](https://github.com/user-attachments/assets/745325af-6fe7-41cd-bc4e-89fe1e82de6f)




- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
      * 여러 평가지표를 비교 분석한 내용을 정리함
![image](https://github.com/user-attachments/assets/713756c5-72d6-42d4-9aae-bc4ec2806289)

        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
      * 문제점을 해결하거나, 해결을 위한 방안을 모색하였고 코멘트를 적극활용하였음
    ![image](https://github.com/user-attachments/assets/82ac594a-bd4e-4895-9e0d-cee62ae0e295)

        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부

    * 전체적으로 통일된 문법과 간결한 코드 + 문제점 및 해결 등에 대한 주석과 Markdown 해석을 철저하게 기재하였
# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
* 준석님 대단하십니다. 코드를 작성하면서 문제점을 바로바로 적고 하나하나 해결해나가는건 절대 쉽지 않은 일이죠... 준석님 코드나 프로젝트에서 이것들이 확연하게 보여서 정말 대단한 것 같습니다.
* 굉장히 인상적으로 잘 봤습니다! 고생하셨습니다!

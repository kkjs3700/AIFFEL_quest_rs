# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김준석
- 리뷰어 : 윤수영


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
          
          
        - 아래 사진과 같이 루브릭에서 요구하는 내용을 모두 수행하였음을 확인하였음
        - ![image](https://github.com/user-attachments/assets/74f6a67f-b2c6-4f4b-be94-8cec7a223a8c)
        - ![image](https://github.com/user-attachments/assets/62efe661-d2df-4b22-b1b2-8e4e2e74515b)
          
          
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          
          
        - 아래 사진과 같이 중간에 주석을 잘 활용하였으며, 중간중간 모식도나 설명을 마크다운으로 첨부하였음
        - ![image](https://github.com/user-attachments/assets/73735829-f634-4b70-9c96-f8721a50b6e7)
        - ![image](https://github.com/user-attachments/assets/1dddf0bf-b408-4f03-af98-5ac8db8c5599)

          
          
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          
          
        - 아래 사진과 같이 loss가 음수가되는 문제를 파악하고, 해결하였음
        - ![image](https://github.com/user-attachments/assets/c30912eb-68cc-4251-b389-83d20c71c009)
        - ![image](https://github.com/user-attachments/assets/e9982ccc-5415-4315-a127-1c74ced2f726)
        - ![image](https://github.com/user-attachments/assets/cb3daa78-ae76-4f2e-9274-fca8d341daf1)
          
        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          
          
        - 아래 사진과 같이 중간 중간에 회고를 잘 작성해 두었으며, 특히 U-net 및 U-net++ 결과 비교시 사전학습 weight가 주는 영향을 잘 분석하였음
        - ![image](https://github.com/user-attachments/assets/e2be6b33-5d1d-4afc-8774-48c76466fad9)
        - ![image](https://github.com/user-attachments/assets/5a1ed8a7-5ce9-495d-8598-e6a0ef77aeb5)
          
        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          
          
        - 전체적으로 반복을 피하고, 함수를 적극적으로 활용하여 자동화를 시켜 두었으먀, 아래 사진과 같이 layer를 블록화 하고, model bulid를 커스텀이 가능한 범위 내로 함수화하여, 실제 사용 및 수정이 용이하도록 하였음
        - ![image](https://github.com/user-attachments/assets/9abb1657-6c13-4dd0-a34a-ae9a69516fd7)
        - ![image](https://github.com/user-attachments/assets/dcac6c94-8c0a-4610-b565-416a4421295c)
        - ![image](https://github.com/user-attachments/assets/c670999b-85a9-47e8-bf78-ccc30df405a6)
        - ![image](https://github.com/user-attachments/assets/5f3dd2c8-f414-49fd-bb95-fcb0b0118114)
          
          
# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
- U-net++의 사전학습 가중치를 변경하여 실험을 수행하고 결과를 분석하신 부분이 매우 인상깊습니다.
- 또한 최종 결과 확인 시 label 까지 확인하도록 구현하시고, 결과를 비교 분석하신 부분도 매우 인상깊습니다.
- 코드 작성하시느라 정말 고생많으셨습니다. 새해 복 많이 받으십쇼!

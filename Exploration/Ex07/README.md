# AIFFEL Campus Online Code Peer Review Templete
- 코더 : __윤수영__
- 리뷰어 : __정우철__


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
       ![image](https://github.com/user-attachments/assets/3f8a0766-3750-465d-ad57-ca74f8ca0b5f)

- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - top-k 샘플링 기법을 도입, 소프트맥스 온도를 고려해서 출력을 조절 가능하도록 설계
    - `sampled_index = tf.random.categorical(tf.math.log(top_k_probabilities), num_samples=1)`
    - 위의 샘플링이 어떻게 되는지(로그확률값을 인자로) 설명이 살짝 있으면 다른 그루분들이 이해하기 쉬울 것 같아요 :)
       ![image](https://github.com/user-attachments/assets/ad9a60f5-6e6e-4e1c-8db9-def9a0d9c456)

        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인을 추정한 과정과 해결방향이 잘 기록되어 있네요!
     ![image](https://github.com/user-attachments/assets/fe25cf9a-25b0-4c46-b5e4-0e0c61a4d913)
     ![image](https://github.com/user-attachments/assets/8b007720-273f-4a9b-8d36-83d79dfd506c)
     ![image](https://github.com/user-attachments/assets/10ec291e-ab6b-41ea-bdb1-3dd4314b4912)

        
- [x   **4. 회고를 잘 작성했나요?**
    - 두 가지 고려사항에 대해서 회고를 작성해 주셨군요🦾
![image](https://github.com/user-attachments/assets/8ff34991-0201-4139-a4f8-a95d5b29366a)
        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 역시 함수 활용이 눈에 띄네요!
      ![image](https://github.com/user-attachments/assets/cef6907c-bbc1-44d2-a243-730d98209320)
      ![image](https://github.com/user-attachments/assets/cca2a5aa-0979-4c26-904f-2bb4e01b9825)
    - 추가실험을 시도한 부분도 눈에 띕니다
      ![image](https://github.com/user-attachments/assets/2840dc68-bfa1-4a55-bdb9-91bc9eb89050)
 



# 회고(참고 링크 및 코드 개선)
```
이틀간 진행하는 탐험 노드면서도 마직막 탐함 노드인데 멋지게 완료하신 것 같습니다! 고생 많으셨어요 :)
```

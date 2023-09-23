# De-identification
코드 사용 시, 출처 표기 바랍니다.

**이슈사항**
- python 3.9.0에서 import 안 됨
  - python 3.6 환경에서 가능
- FACE_CONNECTIONS 옵션만 가능
  - 좌표 새로 추출하였음
<br><br/>
- 구글 mediapipe 라이브러리를 사용하여 다음 face mesh 좌표 추출 <br><br/>
  pyton 3.9.0 / mediapipe 0.8.11 / openCV 4.6.0 <br><br/><br><br/>
![image](https://github.com/L-YUNNA/De-identification/assets/129636660/e46258d7-5587-49b4-b252-f622fb0056ce) 
<[출처](https://developers.google.com/mediapipe/solutions/vision/face_landmarker)>
<br><br/>
<br><br/>
- 추출 좌표 기반 **비식별화** 및 **관심 영역 패치 crop**
1. 비식별화 <br><br/>
  ![image](https://github.com/L-YUNNA/De-identification/assets/129636660/203a7432-0945-405e-bb9c-4223c8d5675e)
  <br><br/>
2. 관심 영역 패치 <br><br/>
  ![image](https://github.com/L-YUNNA/De-identification/assets/129636660/cee2f7cc-63d5-4912-a5d0-a69bca5fb402)
  <br><br/>

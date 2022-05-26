# SNUCM_medical_datascience 2022
SNUCM_medical_datascience 2022

데이터 다운로드 링크:
https://drive.google.com/drive/folders/14rghfVUoq7n0ZTEZGCDiE4DxUCDjDI25?usp=sharing

구글 드라이브 이동 후 내 드라이브에 바로가기 추가
(폴더명 클릭 -> 드라이브에 바로가기 추가)


구글 드라이브에 학습 결과가 정상적으로 write 되지 않던 문제를 해결하였습니다.
아래의 코드를 추가하였습니다.

!pip install gcsfs \\
import gcsfs

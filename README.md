# 최고의 항공사를 찾아라!
 > 스터디에서 공부한 **데이터 사이언스와 시각화**를 바탕으로 2019-2022 미국의 항공 210만 데이터를 통해 항공사의 순위를 매겨보는 프로젝트입니다.

## 🙌 Members

>*KHUDA 6기,* **Visual(lization) 담당**입니다.<br>

<br>

| 이두원 | 권서연 | 서지은 |
| :-: | :-: | :-: |
| <img src='https://github.com/DuwonLee.png' height=130 width=130></img> | <img src='https://github.com/elregansekwon.png' height=130 width=130></img> | <img src='https://github.com/maiteun.png' height=130 width=130></img> |
| <a href="https://github.com/DuwonLee" target="_blank"><img src="https://img.shields.io/badge/GitHub-black.svg?&style=round&logo=github"/></a> | <a href="https://github.com/elregansekwon" target="_blank"><img src="https://img.shields.io/badge/GitHub-black.svg?&style=round&logo=github"/></a> | <a href="https://github.com/maiteun" target="_blank"><img src="https://img.shields.io/badge/GitHub-black.svg?&style=round&logo=github"/></a> |

<br>

## Overview

![image](https://github.com/user-attachments/assets/754617dd-610c-4460-8def-ecd72a38a0b0)
<br><br>
![image](https://github.com/user-attachments/assets/2059bdcb-6e8b-443c-b8af-422b3f51178b)
<br><br>

## 1. 시각화한 것

>미국 지도와 점수를 부여한 항목(지연 시간, 취소율, 우회율, 비행 시간 정확도, 특정 시간/날짜에 정확하게 비행했는지)을 시각화하였습니다.

![image](https://github.com/user-attachments/assets/c484f250-2bd4-4087-b30f-ce849f035efc)<br><br>

## 2. 점수 부여 기준

>모든 항공사에게 점수를 부여하는 것은 1등 100점, 10등 70점으로 하여 각 값의 비율(min-max scaling 적용)에 따라 차등적으로 부여하였습니다. 그리고 일부 항공사에게만 점수를 부여하는 경우에는 각 값의 평균을 내고, 평균보다 작거나 큰 항공사에게만 점수를 부여하였습니다. 이때, 가장 높은 점수를 받는 항공사가 50점, 평균값이 0점을 기준으로 하여 min-max scaling을 적용하였습니다.

## 3. 결과 및 검증

>결과적으로 Endeavor Air(Delta Air Lines의 자회사), Delta Air Lines, SouthWest Airlines가 각 1, 2, 3위를 차지하였습니다. 이 프로젝트는 비행 시간과 취소, 우회만 따졌기 때문에 한계가 있지만, 아래에 있는 실제 기사와 유사하여 유의미한 결과를 도출했다고 볼 수 있습니다.
- [델타항공 2022년 미국 최고의 항공사로 선정](https://newswave25.com/델타항공-2022년-미국-최고의-항공사로-선정)

## 📈 Data
- [미국 항공 지연/취소 데이터](https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023/data)

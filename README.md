#  🧑 MOIM
![image](https://github.com/user-attachments/assets/0fe19b25-6e6b-4316-9e3c-a16acad1b34d)

## 1. 주제 선정 이유
**새로운 사람을 만나고 싶은 당신, moim에서 찾아보세요?
**
```
새로운 인연을 맺기 어려운 사람과 특정 활동에 동참할 사람을 찾기 어렵고 만남 주선에 부담이 있는 사람을 위한 서비스
```
## 2. 팀원 구성
![image](https://github.com/user-attachments/assets/58a3bc31-1043-4f92-9bc3-d6c8e7ec28d9)

## 3. 개발 환경
| 종류    | 기술스택                                    |
| ---------- | ------------------------------------------------------------------------------------|
| 디자인 | ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) |
|런타임|<img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">|
|언어| ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)|
|라이브러리|<img src="https://img.shields.io/badge/EJS-E34F26?style=for-the-badge&logo=EJS&logoColor=white"> <img src="https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white"> |
|패키지|<img src="https://img.shields.io/badge/npm-3776AB?style=for-the-badge&logo=npm&logoColor=white">|
|협업툴|<img src="https://img.shields.io/badge/SLACK-0000F0?style=for-the-badge&logo=slack&logoColor=white"> <img src="https://img.shields.io/badge/NOTION-0EA0F0?style=for-the-badge&logo=notion&logoColor=white">|
|IDE| <img src="https://img.shields.io/badge/VSCODE-AEA0F0?style=for-the-badge&logo=vscode&logoColor=white">|

## 4. 프로젝트 구조
```
+---config
|       config.js
|
+---controller
|       Cmain.js
|       Cmoim.js
|       Cuser.js
|
+---models
|       DibsMoim.js
|       index.js
|       Moim.js
|       MoimDetail.js
|       MoimSet.js
|       Review.js
|       User.js
|
+---routes
|       main.js
|       Moim.js
|       Router.js
|       User.js
|
+---static
|   |   404.css
|   |   edit_profile.css
|   |   index.css
|   |   index.js
|   |   login.css
|   |   moim.js
|   |   moimdetail.js
|   |   moim_detail.css
|   |   moim_detail.js
|   |   moim_insert.css
|   |   moim_list.css
|   |   moim_list.js
|   |   profile.css
|   |   profile.js
|   |   review.css
|   |   style.css
|   |
|   \---upload
|       |   .DS_Store
|       |
|       \---star_imgs
|               .DS_Store
|               star1.jpeg
|               star2.jpeg
|               star3.jpeg
|               star4.jpeg
|               star5.jpeg
|

+---utils
|       encrypt.js
|
\---views
        404.ejs
        detail.css
        detail.html
        editprofile.ejs
        index.ejs
        login.ejs
        meeting.ejs
        moimdetail.ejs
        moiminsert.ejs
        moimlist.ejs
        MoimNot.ejs
        moim_correction.ejs
        moim_detail.ejs
        moim_list.ejs
        profile.ejs
        review.ejs
        signup.ejs
        userinfo.ejs
```

## 5. 개발 기간 및 작업 관리
| 구분 | 기간|활동|비고|
| ---------- | ------ |------ |------ |
|**사전기획**|10/30(수)~10/31(목)| 기획 및 주제 선정|개발 가능성 고려하여 선정|
|**요구사항 및 기능 정의**|10/31(목)~11/02(토)|1. 요구사항 설계 2. 필요 기능 정의 및 구체화|팀원의 희망사항 고려하여 역할 분배, 개발 능력을 고려하여 소요 시간 예측|
|**필요모델 설계**|11/02(토)~11/02(토)|요구사항을 바탕으로 필요 모델 설계|    |
|**서비스 개발 1차**|11/04(월)~11/08(금)|기능 별 api 설계, 페이지 디자인 설계|   |
|**중간보고**|11/08(금)~11/08(금)|팀별 중간보고 진행|       |
|**서비스 개발**|11/08(금)~11/13(수)|1. 페이지 디자인 마무리 2. 반응형 디자인 설계 3. 기능 별 api 테스트|     |
|**기능 테스트**|11/13(수)~11/13(수)|엣지 케이스 테스트 및 기능 최종 점검|   |
|총 개발 기간|10/30(수)~11/13(수)|   |    |

## 6. 페이지별 기능
1. 로그인 화면

https://github.com/user-attachments/assets/01ae16a9-92ae-419b-a6af-79fe2ed35ecc




## 7. 트러블 슈팅 및 어려웠던 점
- 팀원의 중도 하차와 갑자기 많은 일을  떠맡게 되어, 업무 처리 과정에서 혼선이 있었다.
- 내가 담당했던 부분은 아니지만, 발생할 수 있는 오류 상황을 전부 체크할 여유가 부족해서 로그인 완료 후 처리해야 할 기본적인 부분을 놓친 점이 없지 않았다.
- 처음에 DB를 구상했을 때 함께 한 팀원 전원에 대한 실력 파악이 부족하기도 했고, 프론트와 백엔드 간 소통 부족으로 DB를 변경하는 일이 있었다. 회사에 입사하게 된다면 팀원들과의 소통에 좀더 신경을 써야할 것 같다.


## 8. 개선 목표
- 로그인 화면 : 로그인 화면, 로그인 페이지에 로그인이 되었음에도 접근이 가능한 상황에 대해 처리
- 세션 설정 문제 : 세션 없이 회원 페이지 접속 시 다이렉트 처리가 안되어 있음.
- 프론트엔드 UI : 로그인 페이지를 기준으로 하여 전체적인 디자인 통일성이 부족하다는 지적이 나옴.
- 기능적인 문제 : 모임 개설이 완료되었는지에 대한 알림창의 부재.
- 데이터의 분류 : 데이터를 분류하는 기능의 다양화.


## 9. 채택한 기술에 대한 감사
 [Node.js]
 ```
- 스퀄라이즈를 사용해서 DB를 쿼리 문이 아니라 소스 코드를 이용해서 자동으로 생성하는 방법에 대해 습득했다.
- 완성 단계에서 간단한 오류들이 홈페이지를 만드는데 있어, 얼마나 큰 하자가 되는지 이번 프로젝트를 통해 뼈져리게 느꼈던 것 같다.
```
[DB] 
```
- 테이블을 쪼개는 과정에서 너무 무분별하게 쪼개는 것도 좋지 않다는 사실을 깨달았다.
```



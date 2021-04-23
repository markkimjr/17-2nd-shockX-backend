# ShockX
![main](https://user-images.githubusercontent.com/72085261/109430603-8ce3bf00-7a45-11eb-8123-e9eae234e756.gif)



'ShockX'은 학습 목적으로 제작된 'StockX' 홈페이지를 클론 프로젝트입니다.

## 프로젝트 기간
2021.03.02(화) ~ 2021.03.12(금)

## 팀 구성
### 프론트엔드 (<a href="https://github.com/wecode-bootcamp-korea/17-1st-Dienstag-frontend">Repo</a>)
- 김민주
- 서유진
- 유승현
### 백엔드
- 김하성 (PM)
- 조혜윤
- 조수아
- 송빈호

## 사용한 기술 스택
- 프론트엔드: html, css, jsx, react
- 백엔드: Python, Django, MySQL, AQueryTool, Git, AWS

## 프로젝트 진행 방식
- Trello, Slack 앱을 활용해 Scrum 방식으로 진행
![trello](https://user-images.githubusercontent.com/72085261/109430747-3c209600-7a46-11eb-9a5a-49780b91f427.gif)

## 내가 한 일들
https://velog.io/@markkimjr/DIENSTAG-Thoughts-on-my-first-website-clone-coding-project
- 백엔드 팀뭔들이랑 같이 database 모델링 (AQueryTool 사용)
- 백엔드 팀원들이랑 같이 models.py 작성
- product/views.py 작성 (CartView GET, POST, DELETE)
- 카트에 상품 추가/삭제할떄 카트 정보 데이터베이스에 저장 (POST, DELETE)
- 카트 상품 정보 프론트한테 전달 (GET method)
- cart/urls.py 작성 (REST API방식)

## 백엔드 구현 목록
#### 회원가입 & 로그인
- Bcrypt를 활용한 비밀번호 암호화
- JWT를 활용한 Access Token 발행
- 로그인 @decorator 
#### 상품 리스트 나열
- 가방 타입 내의 모델별 리스트 나열 기능
- 모델별 상세페이지 리스트 나열 & detail 정보 전달
- 모델별 추천 상품 목록 전달
- 컬러, 사이즈 별 상품 필터링
#### 장바구니 & 결제
- 장바구니에 상품 추가
- 장바구니에 있는 상품 삭제
- 장바구니에 있는 상품 정보 전달 (GET)
- 전달받은 결제정보(billing address & shipping address) 저장
- 주문 상태 저장

## Reference
- 이 프로젝트는 <a href="http://www.stockx.com/">StockX</a> 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진은 unsplash.com에서 "open source" 이미지 입니다.

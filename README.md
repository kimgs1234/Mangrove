# Mangrove 팀프로젝트 
## 프로젝트 개요 
HTML, CSS , JavaScript 를 이용하여 맹그로브 사이트의 디자인과 기능을 구현

## 기획의도 & 목표
수업시간에 배운 HTML , CSS , JavaScript 를 활용하여 레퍼런스 사이트의 디자인과 기능을 비슷하게 만들고자 함

### 목표
* 팀원들 간의 Git Organization을 이용한 소통을 통해 통일감 있고 보기 쉽게 코드를 정리
* 자바스크립트와 자바스크립트 기반의 플러그인을 통한 기능구현
* 모바일, 피씨 두 버전의 반응형 웹 구현

## 작업 순서
1. 팀원 발표 및 레퍼런스 사이트 설정
2. git organization 만들기
3. 팀 명, 프로젝트 목표, 역할 정하기
4. 레퍼런스 사이트 요구사항 및 구조 분석
5. HTML , CSS , JavaScript 퍼블리싱 가이드  , 디렉토리 구조 작성
6. HTML 마크업과 CSS 디자인 퍼블리싱
7. JavaScript로 기능구현
8. 프로젝트 완료 보고서 작성
9. 발표 및 피드백

## 사용 기술
* 프로젝트 관리 Tool : GitHub
* 개발Tool : Visual Studio Code
* 웹화면 : HTML5 , CSS3 , JavaScript
* 플러그인 : Swiper

## 각 담당 업무 , 페이지
### 레퍼런스 사이트
Mangrove (맹그로브 mangrove – Live & Grow)

### 담당 업무
* 김신영: 팀장, main/about us 페이지, 프로젝트 보고서 내용정리
* 김경석: journal 페이지 , 발표
* 신지훈: community 페이지
* 조유빈: git관리, location(고성, 신촌, 동대문, 신설, 숭인)페이지, ppt작성


## 프로젝트 내용
### 페이지 구성 
![image](https://github.com/kimgs1234/Mangrove/assets/142865411/4d9c2e70-85b3-4bc0-bc89-f9f94c2dc952) 

### 디렉토리 구조
![image](https://github.com/kimgs1234/Mangrove/assets/142865411/f7e153a5-c1b2-4d9e-b813-c243a4dbfa2a)

### 문제 및 해결
#### 1. GitHub
* 상황 : git push를 했을 때 error:failed to push some refs to(충돌 발생) 
* 문제 확인 : 팀원들 간의 pull과 push가 겹쳐 충돌 발생
* 해결 : 먼저 pull 작업으로 팀원들의 업데이트 내용을 내 로컬로 가져온 다음 push를 실행하
여 원격저장소에 업데이트

* 상황 : merge Conflict
* 문제 확인 : 한 파일을 중복으로 수정하여 수정부분에 충돌발생
* 해결 : vscode의 source control에서 충돌 부분 병합 후 commit git pull origin main을 실
행하여 원격 저장소 정보를 로컬로 가져온 후 push

#### 2. 반응형 제작
* 상황 : book 버튼 내부 메뉴 사이즈 변경 시 내부 컨텐츠가 넘침
* 문제 확인 : 미디어 쿼리 적용 시 변화하는 사이즈 대응 문제
* 해결 : 팀원들과 논의를 통해 부모요소에 padding값을 주고 자식요소의 width값에 Pluto를
주 어 width값이 자동으로 조절되게 함

#### 3. Java Script
* 상황 : Plugin Location 섹션에서 Swiper와 Fancy box 플러그인이 결합된 이미지 박스 구
현 실패
* 해결 : 두가지가 결합된 플러그인을 찾아보려 했지만 찾지 못하였고 두가지 플러그인을 함께
사용 하지 못함

* 상황 : 제목을 눌렀을 때 부드럽게 텍스트 박스가 내려오는 효과를 구현하지 못함
* 해결 : 각 FAQ의 목록을 클릭 하였을 때 height값이 변하는 상황에서, Transition을 적용하
여 해결하려 하였으나 해결하지 못함 추후 JavaScript를 더 숙지하여 보완 예정

## 프로젝트 완료 리뷰
### 아쉬운 부분
* toggle 버튼을 눌렀을때 부드럽게 영역이 나오는 효과를 구현하고 싶었으나 구현 하지 못함
* swiper 와 Fancy box 플러그인이 결합된 이미지 박스를 구현하지 못함

### 잘한 부분
* 팀원들이 어려워하는 css나 javascript 코드들을 많이 해결 해주었으며 도움을 줌
* 팀원들이 GitHub 사용을 어려워 하는 것 같길래 친절하게 알려줌

### 배운점 및 주관적인 의견
이런 협업은 처음이라 살짝 걱정도 되기도 했었 지만 팀원 들과의 소통을 통해 혼자서는 못할 부분들을 많이 해결하였고, <br>

나중에 미래에 개발자로 취업을 하게 된다면 이런 과정을 많이 겪게 될 텐데 미래에 하게 될 일을 미리 체험해서 어떻게 팀프로젝트를 진행하는 것이 좋은지 깨닫게 된 게 좋았다. <br>

다만 이번 프로젝트는 작업을 거의 집에서 하지 못해서 피시방에서 작업을 하게 된 것 때문에 많은 작업을 하진 못했지만 이사가 완료된 다음 프로젝트부터는더 적극적으로 팀원들을 도와주고 싶다. <br>

## Mangrove 바로가기 
<a href=" https://four-programmers.github.io/Mangrove/" target="_blank">Mangrove 사이트</a>

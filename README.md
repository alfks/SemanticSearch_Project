# SemanticSearch_Project
## 1. 문제 정의
● 검색 엔진 구현 시, 시맨틱 요소를 반영해야 하는 이유
<br>
  ○ 기존 데이터셋 포털에서는 키워드 기반의 데이터 셋 검색을 제공
<br>
  ○ 사용자는 정확히 키워드가 일치하는 데이터 셋에 대한 결과만 얻음
<br>
  ○ 원하는 데이터를 찾기 위해 다양한 키워드로 검색을 수행해야 함
<br>
<br>
● 사용자가 검색되어진 결과를 다시 검색하는 문제를 방지하기 위한 방안이 필요
<br>
 ○ 단어와 구문의 의미를 해석하는 검색 엔진 기술인 시맨틱 검색을 활용한 검색 엔진 구현의 필요성 존재
 
## 2. 데이터
● 수집 날짜: 2024/04/09<br>
● 수집 사이트: https://www.kurly.com/main<br>
● 수집 카테고리: 정육·가공육·계란, 간편식·밀키트·샐러드, 생활용품·리빙, 건강식품, 헤어·바디·구강<br>
● 총 데이터 크기: 500 X 21
|Column|브랜드|상품이름|URL|가격|상품소개글|상세정보|베스트1|베스트2|베스트3|베스트4|베스트5|베스트6|베스트7|베스트8|베스트9|베스트10|리뷰수|태깅|상품정보|가장 비중이 높은 토픽
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|<br><br>|||||||||||||||||||||

## 3. 방법론
<img width="587" alt="프레임워크" src="https://github.com/alfks/SemanticSearch_Project/assets/117802772/3f0b8e86-4140-42b6-8698-dc244f5398ed">



## 4. 사용 방법
1. Git Clone
``` 
git clone (https://github.com/alfks/SemanticSearch_Project.git)
```
2. reqirements.txt 설치
```
pip intall requirements.txt
```
3. input_keyword에 검색하고싶은 내용을 넣어서 검색 진행
```
input_keyword = "피로회복에 좋고 알약을 잘 못 삼키는 사람도 쉽게 먹을 수 있는 비타민"
```

## Program Architecture

## 참여 인원
|[송다은](https://github.com/daeun6)|[김세인]()|[문미란]()|[신예린]()|[정은지]()|
| :---: | :---: | :---: | :---: | :---: |
| PM | role | role | role | role |
|<img width="100" src="https://github.com/GDSC-SWU/2023-AI-ML-study/assets/81478444/21400679-dcc3-4731-9638-d8f717e0bc84"/>|<img width="100" src=""/>|<img width="100" src=""/>|<img width="100" src="https://avatars.githubusercontent.com/u/109721289?v=4"/>|<img width="100" src=""/>|

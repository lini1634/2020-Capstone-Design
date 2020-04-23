# 2020-Capstone-Design 

+ 객체 인식 참고 깃허브 : https://github.com/5taku/custom_object_detection
  + 이미지 라벨링 https://github.com/tzutalin/labelImg


## 3/29 ~ 4/3 ( 3주차 )
- [x] 아이디어 구상(시각장애인을 위한 버스 보조 시스템)

## 4/5 ~ 4/10 ( 4주차 )
- [x] 아이디어 제안서

## 4/12 ~ 4/17 ( 5주차 )
- [x] 데이터 수집 (하차벨, 단말기, 버스 출입구, 버스 빈 좌석)
- [x] 데이터 라벨링 (하차벨, 단말기, 버스 출입구, 버스 빈 좌석)
- [x] 객체인식 전체 데이터 ssd 모델 학습, 빈좌석 데이터 faster-rcnn 모델학습
- [x] 매트랩의 ocr함수를 이용하여 숫자 인식을 진행

|TASK|김해린|백소현|이세미|이세정|
|------|------|-----|------|------|
|데이터 수집,라벨링|단말기|하차벨|버스 빈좌석|버스 출입구|
|모델학습|ssd|x|faser-rcnn|x|
|숫자인식|x|ocr|x|ocr|

## 4/19 ~ 4/24 ( 6주차 )
- [x] intel sample code-capture 코드 수정해서 실시간 사진 저장
- [x] 실시간 저장된 사진을 학습된 모델로 객체 인식 성공 
- [x] c++과 python 연동 성공: c++파일에서 python 파일 불러오기
- [x] 버스번호 인식을 위한 버스 앞부분 이미지 수집 후 라벨링
- [x] c++과 matlab 연동 성공: c++파일에서 matlab 실행파일 불러오기 

|TASK|김해린|백소현|이세미|이세정|
|------|------|-----|------|------|
|intel sample code-capture 코드 수정해서 실시간 사진 저장|o|x|o|x|
|실시간 저장된 사진을 학습된 모델로 단말기,하차벨,빈좌석,출입구 인식 |o|x|o|x|
|c++과 python 연동: c++파일에서 python 파일 불러오기|o|x|o|x|
|버스번호 인식을 위한 버스 앞부분 이미지 수집 후 라벨링|x|o|x|o|
|c++과 matlab 연동: c++파일에서 matlab 실행파일 불러오기|x|o|x|o|


## 4/26 ~ 5/1 ( 7주차 )
- [ ] ipynb를 .py로 변경한 후 c++ 에서 호출
- [ ] 버스 앞부분 이미지 포함해서 객체인식 학습 돌리기
- [ ] 매틀랩과 c또는 py연동
- [ ] 객체에서 depth 뽑기

## 5/3 ~ 5/8 ( 8주차 )
- [ ] 안드로이드 스튜디오에서 c++ 파일 연결

## 5/10 ~ 5/15 ( 9주차 )
- [ ] 테스트


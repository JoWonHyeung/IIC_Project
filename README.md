# 융복합 프로젝트

## Project Name

장애인 주차 구역 위반 방지 서비스

## Purpose

일반인들의 무분별한 장애인 주차공간 이용을 제한하여 장애인 운전자들의 편의성을 확보한다.

## Stacks

python, R

## Period

5/25 ~ 6/28

## Role

주제 선정 배경에 대한 근거자료 제시

우선 설치 구역 후보지 선정

AI-IOT 파이프라인 구축

## Contact

mesh153@naver.com

## Schedule

5/23 ~ 5/25 : 주제 선정 및 데이터 탐색

5/26 : 작업 환경 설정 및 준비. 또한 시각화 작업 준비

5/27 : 데이터 수집

5/28 : 멘토링

5/30 : 지도 시각화 작업

5/31 : 데이터 수집 및 상관관계 분석

6/1 : 데이터 전처리 작업 및 회귀 분석 

6/2 : 피드백 후 수정

6/3 ~ 6/4 : 뉴스 크롤링

6/5 ~ 6/6 : 연관분석 및 워드 클라우드 분석, AWS 환경 구축, 가설 설정

6/7 : IOT, AI 파이프라인 구축

시각화 작업, 가설 설정 마무리
      
6/8 : IOT, AI 파이프라인 구축

6/9 : IOT, AI 파이프라인 구축

6/13 : 피드백 내용 적용, 입지 선정 작업

6/14 : 회귀 분석 및 포아송 회귀 분석

6/15~6/16 : AI-IOT 파이프라인 추가작업, 기대 효과 PPT 구성 

6/17~6/19 : 차 표지판 Detect code 파이프 라인 이식 작업 및 테스트

6/20~6/23 : 시연 영상 제작 및 PPT 

6/24~26 : PPT 협업 작업

6/28 : 최종 발표

## Result
최우수상 수상

### ect...

```
#백그라운드 명령어 & log파일 생성 명령어

nohup python3 -u connect.py >> output.log & 

tail -f output_disable.log
tail -f output_carnum.log

#프로그램 확인 명령어
ps -ef | grep connect.py

#프로그램 다운 명령어
kill -9 7930

#jupyter notebook 생성 명령어
nohup jupyter-notebook --ip=0.0.0.0 --no-browser --port=8928 &
```


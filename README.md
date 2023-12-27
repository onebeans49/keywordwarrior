![KakaoTalk_20231227_134037420](https://github.com/onebeans49/keywordwarrior/assets/136784242/a9efbd06-f057-4c68-bebc-c8ec94af6a3d)


# keywordwarrior
키워드 워리어 공유 디렉토리 입니다.
키워드 워리어는 구글 플레이스토어의 리뷰를 기반으로 키워드별로 리뷰의 평점을 재부여 해주는 서비스입니다.

# 기존 시스템

![image](https://github.com/onebeans49/keywordwarrior/assets/136784242/24dd9b55-366b-4f0c-9209-ec4659f3ff43)

# 키워드 워리어

![image](https://github.com/onebeans49/keywordwarrior/assets/136784242/b6a76e0d-7400-4035-a869-842e03cd97ee)

# 프로젝트 과정

1. Googleplaystore Scraper를 이용해 '게임'카테고리의 리뷰 데이터 수집
2. rhino 형태소분석기(rhino 사전에 신조어 및 축약어는 직접 추가)를 통해 형태소 분석 실행 
3. 형태소 분석 된 데이터를 빈도 분석
4. 빈도 분석된 데이터를 통해 키워드를 추출 후 키워드별로 묶음
5. 키워드 별 세부평점 추출
6. 감성분석 모델 생성 및 학습
7. 키워드별로 감성 분석 ( 긍, 부정 분석)
8. 키워드 별 리뷰 추출 

# 서비스 시연 영상

저희들이 개발한 서비스의 시연 영상입니다.

https://github.com/onebeans49/keywordwarrior/assets/136784242/b28057f8-de1e-4392-8a68-d2384f7ff91e



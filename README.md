# (용인시) 지역별 상권분석을 통한 청년창업 지원 대책 도출 

대회기간 : 2020. 12. 15(화) ~ 2021.1.28 (목)   
[공모전 확인하기](https://compas.lh.or.kr/subj/past/info?subjNo=SBJ_2012_002)

## 배경
- 용인시는 인구 100만 이상 특례시로 지정되었고, 수도권 남부 중심도시로 신분당선과
GTX 광역철도 등 철도개통, 수도권 제2순환고속도로와 서울~세종간 고속도로 등 광역교통망 개선으로
명실상부한 사통팔달 교통요충지로써 대내외적인 여건이 지속적으로 변화하고 있습니다.

- 인구 110만을 바라보며 꾸준하게 성장하고 있는 용인시는 향후 수도권 남부지역의 랜드마크가 될
기흥역 플랫폼시티를 비롯하여 SK하이닉스 반도체산업단지 등 4차 산업혁명과 관련된 업체들이 입지하고 있습니다.

- 특히 풍부한 산‧학‧연 클러스터, 에버랜드 및 민속촌 등 다채로운 관광·여가·위락시설 등이 입지하고 있어
폭넓은 창업기회가 존재하고 있습니다.

- 용인시는 관내 업종별 매출 데이터를 활용한 지역별 상권과 청년 사업체의 생애주기와의 상관관계를 파악하고
이를 토대로 지원정책을 수립하고자 합니다.

## 해결 과제
  지역별 청년 사업체 실태를 쉽고 명확히 보이도록 시각화
  청년 창업 또는 사업 정착을 위한 아이디어 제시
  
  분석 조건
- 사용자가 자유롭게 필요 데이터를 발굴하여 사용 가능하나 최종 결과파일 제출 시
  데이터 출처와 사용한 데이터도 함께 제출
  
- 외부 데이터는 법적인 제약이 없는 경우에만 허용되며 크롤링을 통해 데이터를 생산 한 경우
  크롤링 코드도 함께 제출

## 수행 작업

1. geopandas를 이용하여 geometry 데이터 전처리, EDA
2. folium 지도 시각화

## 결과

공모전에 입상은 못했으나, 배운것이 많다.  

1. 공모전 수준을 알게됨. (어설프게 도전하는건... 시간낭비!)
2. postgreSQL, QGIS로만 해봤던 공간조인을 geopandas(sjoin)으로 할 수 있음.
3. folium으로 더 다양한 지도 시각화를 할 수 있음. (vworld 지도 레이어 추가, 여러개의 레이어 시각화 등)

[공모전](https://compas.lh.or.kr/subj/past/code-list?subjNo=SBJ_2012_002)에서 입상작 PPT, 발표 영상을 확인 할 수 있습니다.



# Weather_Big_Data_Contest <br>

## team Wake-Up 민간 부문 입상 수상작

[2021 날씨 빅데이터 콘테스트](https://bd.kma.go.kr/contest/)

날씨에 따른 맞춤형 집단별 광고를 제작하고, 그를 적절한 플랫폼에 게시하는 과정까지를 제안

---

## 활용 데이터 목록

i) `날씨` 데이터, ii) `구매 이력` 데이터, iii) `소셜` 데이터를 이용하였으며 수집한 데이터의 기간은 *2018.01.01년부터 2019.12.31년* 총 **2년**이다.

|항목|상세 내용|출처|
|:---:|:---:|:---:|
|종관기상관측 일별 데이터|평균기온, 일교차, 일강수량, 평균 풍속, 평균 상대 습도, 평균 전운량|기상청|
|대기 환경 정보 데이터|오존, 미세먼지|Air Korea|
|상품별 온라인 구매 이력 데이터|뷰티/식품/냉난방가전으로 분류되는 383개 품목의 성별/연령별 판매량|Corporation|
|SNS에서의 상품명 언급량 데이터|블로그/커뮤니티/인스타그램 각 채널별 게시글 10만건 당 물품 키워드가 포함된 게시글의 상대적 문서 수|VAIV 제공|


- `종관 관측 데이터` `대기 환경 정보 데이터`: **상위 8개 도시** 데이터 사용
	- 인구수 상위 8개 도시가 전체 인구수의 46%이므로 대표값으로 채택
		- **상위 8개 도시: 서울, 부산, 인천, 대구, 대전, 광주, 울산, 수원**
		- 백령도, 강화, 관악산 : 대표성 없다고 판단, 제외
		- 대구(기) : 지점 상세보기 정보 누락, 제외
	- `대기 환경 정보 데이터`의 경우, 날씨 데이터에 병합하여 사용
	

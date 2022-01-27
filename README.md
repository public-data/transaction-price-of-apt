# Actual Transaction Price of Apartments in Korea

## Data
- Source: [data.go.kr](https://www.data.go.kr/data/15058747/openapi.do)
- License: Public Data

# 아파트 매매 실거래가 데이터

## 데이터
- 출처: [공공데이터포털](https://www.data.go.kr/data/15058747/openapi.do)
- 이용허락범위: 이용허락범위 제한 없음

## API 
### 응답 메시지 명세
| 항목명                  | 항목명(국문)   | 항목설명        | 항목크기   | 항목구분  | 샘플 데이터          |
|------------------------|-----------|-------------|--------|-------|-----------------|
| resultCode             | 결과코드      | 결과코드        | 2      | 1     | 0               | 
| resultMsg              | 결과메세지     | 결과메세지       | 50     | 1     | NORMAL SERVICE. | 
| Deal Amount            | 거래금액      | 거래금액(만원)    | 40     | 1     | 82500           | 
| Build Year             | 건축년도      | 건축년도        | 4      | 1     | 2015            | 
| Deal Year              | 년         | 계약년도        | 4      | 1     | 2015            | 
| Dong                   | 법정동       | 법정동         | 40     | 1     | 사직동             | 
| Apartment Name         | 아파트       | 아파트명        | 40     | 1     | 광화문풍림스페이스본(9-0) | 
| Deal Month             | 월         | 계약월         | 2      | 1     | 12              | 
| Deal Day               | 일         | 일           | 6      | 1     | 1               | 
| Area for Exclusive Use | 전용면적      | 전용면적(㎡)     | 20     | 1     | 94.51           | 
| Jibun                  | 지번        | 지번          | 10     | 1     | 9               | 
| Regional Code          | 지역코드      | 지역코드        | 5      | 1     | 11110           | 
| Floor                  | 층         | 층           | 4      | 1     | 11              | 
| Cancel Deal Type       | 해제여부      | 해제여부        | 1      | 0     | O               | 
| Cancel Deal Day        | 해제사유발생일   | 해제사유발생일     | 8      | 0     | 21.01.27        | 
| REQ GBN                | 거래유형      | 중개 및 직거래 여부 | 10     | 1     | 중개거래            | 
| Rdealer Lawdnm         | 중개업소주소    | 시군구 단위      | 150    | 1     | 서울 서초구          | 
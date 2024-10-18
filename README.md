# ◈ Tableau Prepbuilder
### ■ 요약
- 정보시스템에서 생산된 원천(RAW) 데이터 소스 조인, 유니온, 계산식을 통해 새 필드 생성 시 사용
- 태블로 데스크탑 사용하여 대시보드 구성 전단계에서 전처리

![01 Prep Overview](https://github.com/user-attachments/assets/ed2b6977-7848-4fd0-bccd-83aaae9c98ab)
- 계약시작일, 계약종료일 등 계약정보 내 필드항목 기반 매출정보 추정 데이터 전처리 프로세스 구축
  
![Prep 데이터전처리](https://github.com/user-attachments/assets/275c4d6f-d1e8-4966-9ced-305c7c2da4cb)
- 계약기간(시작/종료)을 통해 일수 산출 후 계약금액(수주)으로 일별금액 산출
- [일수*일별금액 = 년월별매출]

# ◈ Tableau DeskTop
### ■ 요약
- 데이터 테이블 조인, 필드간 계산식을 통해 목표 데이터 추출/대시보드 구축
- 다양한 필드(부서,담당,요율,금액 TopN, 사업분류 등) 조건 별 하이라이트 및 필터적용

### * 계약(수주) 현황 대시보드
![수주현황](https://github.com/user-attachments/assets/395e4512-f435-43d8-bf50-25d56fcae5b1)
#### 주요지표
- 부서/담당별 계약현황(비율/금액) 및 월별수주추이
- 예년대비수주액, 잔여수주액, 목표달성율, 평균월매출, 수주요율 상관관계

### * 매출현황 대시보드
![매출현황](https://github.com/user-attachments/assets/551900d2-5e21-46c2-aa12-90be2ca66391)
#### 주요지표
- 최근 3-5개년 매출추이, 미래 순환매출추정, 본부별 매출비율, 수주/매출상관관계, 예상평균월매출

### * 잔여현황 대시보드
![잔여현황](https://github.com/user-attachments/assets/d1ca008f-f4e3-416d-8a66-41eb19c45cd9)
#### 주요지표
- 부서/담당별 잔여계약현황, 각 월별 잔여계약현황, 계약목록 상태값(지연/정상/미도래) 노출
- 잔여건수, 잔여수주액, 목표수주액, 목표달성율, 계약금액 Top N

#### - 끝 -

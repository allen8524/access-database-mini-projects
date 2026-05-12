# Microsoft Access 데이터베이스 미니 프로젝트

Microsoft Access를 활용해 제작한 주소록 관리 및 판매관리 데이터베이스 실습 프로젝트입니다.

테이블 설계, 관계 설정, 샘플 데이터 구성, 폼/보고서 기반 데이터 관리 흐름을 정리했습니다.

## 프로젝트 구성

| 구분 | 파일 | 설명 |
| --- | --- | --- |
| 주소록 관리 | `databases/address-book.accdb` | 연락처와 가족 정보를 관리하는 Access 데이터베이스 |
| 판매관리 | `databases/sales-management.accdb` | 제품 분류, 제품 정보, 판매 내역, 판매 상세 내역을 관리하는 Access 데이터베이스 |
| 문서 | `docs/database-summary.md` | 각 데이터베이스의 테이블 구성 및 관리 목적 요약 |

## 주요 기능

### 주소록 관리

- 연락처 기본 정보 관리
- 가족 정보 관리
- 주소록과 가족 정보 간 관계 구성
- 샘플 개인정보는 임의 데이터로 정리

### 판매관리

- 제품 종류 관리
- 제품 정보 관리
- 판매 내역 관리
- 판매 상세 내역 관리
- 판매번호를 기준으로 판매와 판매내용 연결

## 폴더 구조

```text
access-database-mini-projects/
├─ databases/
│  ├─ address-book.accdb
│  └─ sales-management.accdb
├─ docs/
│  └─ database-summary.md
├─ .gitattributes
├─ .gitignore
└─ README.md
```

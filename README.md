# Microsoft Access 데이터베이스 미니 프로젝트

Microsoft Access를 활용해 제작한 주소록 관리 및 판매관리 데이터베이스 실습 프로젝트입니다.

테이블 설계, 관계 설정, 샘플 데이터 구성, 폼/보고서 기반 데이터 관리 흐름을 정리했으며, `.accdb` 파일과 데이터베이스 구성 문서를 함께 관리합니다.

## 프로젝트 구성

| 구분 | 파일 | 설명 |
| --- | --- | --- |
| 주소록 관리 | `databases/address-book.accdb` | 연락처와 가족 정보를 관리하는 Access 데이터베이스 |
| 판매관리 | `databases/sales-management.accdb` | 제품 분류, 제품 정보, 판매 내역, 판매 상세 내역을 관리하는 Access 데이터베이스 |
| 문서 | `docs/database-summary.md` | 각 데이터베이스의 테이블 구성, 관계, 설계 목적 정리 |

## 주요 기능

### 주소록 관리

- 연락처 기본 정보 관리
- 가족 정보 관리
- 연락처와 가족 정보 간 관계 구성
- 임의 샘플 데이터를 활용한 주소록 관리 흐름 구성

### 판매관리

- 제품 종류 관리
- 제품 정보 관리
- 판매 내역 관리
- 판매 상세 내역 관리
- 판매번호를 기준으로 판매와 판매내용 연결

## 데이터베이스 설계 포인트

- 주소록과 가족 정보를 분리하여 연락처 1건에 여러 가족 정보를 연결할 수 있도록 구성했습니다.
- 제품 종류와 제품 정보를 분리하여 제품 분류 기준을 관리할 수 있도록 구성했습니다.
- 판매 테이블과 판매내용 테이블을 분리하여 판매 1건에 여러 상품이 포함되는 구조를 표현했습니다.
- `.accdb` 파일은 GitHub에서 직접 미리보기 어렵기 때문에 별도 문서로 테이블 구성과 설계 목적을 정리했습니다.

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

## 기술 및 도구

- Microsoft Access
- ACCDB Database
- Relational Database Design
- Git
- GitHub

## 실행 및 확인 방법

1. 저장소를 내려받습니다.
2. `databases` 폴더의 `.accdb` 파일을 Microsoft Access에서 엽니다.
3. 테이블, 폼, 보고서 구성을 확인합니다.
4. 자세한 테이블 구성은 `docs/database-summary.md` 문서를 참고합니다.

## Git 관리 참고사항

- `.accdb` 파일은 바이너리 파일이므로 GitHub에서 코드처럼 변경 내용을 비교하기 어렵습니다.
- Access에서 데이터베이스를 수정한 경우 파일 전체를 다시 커밋해야 합니다.
- Access 임시파일인 `.laccdb` 파일은 커밋 대상에서 제외합니다.

## 참고

본 저장소의 데이터는 실습 목적의 샘플 데이터이며, 실제 개인정보를 포함하지 않도록 정리했습니다.

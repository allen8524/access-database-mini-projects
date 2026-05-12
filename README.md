# Access DB Project

Microsoft Access 기반 주소록 및 판매관리 데이터베이스 파일을 정리한 저장소입니다.

## 폴더 구조

```text
access_db_git_package/
├─ databases/
│  ├─ address-book.accdb
│  └─ sales-management.accdb
├─ docs/
│  └─ database-summary.md
├─ .gitattributes
├─ .gitignore
└─ README.md
```

## 파일 설명

| 파일 | 설명 |
| --- | --- |
| `databases/address-book.accdb` | 주소록 데이터베이스 정리본 |
| `databases/sales-management.accdb` | 판매관리 프로그램 데이터베이스 정리본 |
| `docs/database-summary.md` | 데이터베이스 구성 요약 |

## Git 업로드 예시

```bash
git init
git add .
git commit -m "Add Access database project files"
git branch -M main
git remote add origin <REPOSITORY_URL>
git push -u origin main
```

## 참고

`.accdb` 파일은 바이너리 파일이라 GitHub에서 코드처럼 변경 내역을 자세히 비교하기 어렵습니다. 그래서 `.gitattributes`에서 Access 파일을 binary로 지정했습니다.

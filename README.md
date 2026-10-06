# Week06 - 파이썬 성적 관리 프로그램 (GradeBook)

파이썬의 모듈, 서브패키지, 단위 테스트(unittest) 및 CSV 파일 입출력을 실습하기 위한 프로젝트입니다.

---

## 📁 프로젝트 구조

```text
week06/
├── project_root/             # 기본 모듈 실습 파일들
├── project_root_pkg/         # 패키지 구조화 실습 폴더
│   ├── gradebook/            # 메인 패키지
│   │   ├── io/               # 입출력 서브패키지 (csvio.py)
│   │   ├── __init__.py
│   │   ├── __main__.py       # CLI 실행 진입점
│   │   ├── cli.py
│   │   ├── models.py         # Student, GradeBook 클래스
│   │   └── utils.py          # 평균 및 학점 계산 유틸리티
│   ├── tests/                # 단위 테스트 폴더
│   │   └── test_utils.py     # unittest 실행 파일
│   └── students.csv          # 테스트용 CSV 데이터
└── .gitignore
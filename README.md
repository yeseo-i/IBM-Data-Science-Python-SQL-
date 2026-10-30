IBM Data Science Professional Certificate – Python & SQL 실습

IBM Data Science Professional Certificate 과정에서 진행한 실습 노트북 모음입니다. 과정 커리큘럼에 포함된 랩(실습)이고, 직접 기획한 프로젝트가 아닙니다.

파일 구성

1. Python 데이터 수집 (API / 웹 스크래핑)

파일	내용
Jobs_API.ipynb	API로 채용 관련 데이터를 받아오는 실습
Web-Scraping-Lab.ipynb	웹 페이지에서 BeautifulSoup으로 표 데이터를 수집하는 실습

2. SpaceX 데이터 실습 (Falcon 9 / Falcon Heavy 발사 데이터)

순서	파일	내용
1	jupyter-labs-spacex-data-collection-api.ipynb	SpaceX 공개 API로 로켓 종류, 페이로드 질량, 궤도 등의 정보를 받아 pandas DataFrame으로 정리
2	jupyter-labs-webscraping.ipynb	위키백과의 Falcon 9 / Falcon Heavy 발사 기록을 BeautifulSoup으로 수집
3	labs-jupyter-spacex-Data_wrangling.ipynb	Falcon 9 데이터만 걸러내고, 결측치를 확인하고, 착륙 성공 여부를 1/0 레이블로 변환
4	jupyter-labs-eda-sql-coursera_sqllite.ipynb	정리한 데이터를 SQLite 데이터베이스에 저장하고, SQL로 발사장별 기록 조회, 고객사별 페이로드 질량 합계 등을 조회
사용한 도구

Python, pandas, requests, BeautifulSoup, SQLite, SQL, Jupyter Notebook

참고
노트북은 IBM 과정 순서에 따라 진행한 실습입니다.
각 단계(수집 → 정리 → 저장 → 조회)의 흐름을 이해하는 데 중점을 두었습니다.

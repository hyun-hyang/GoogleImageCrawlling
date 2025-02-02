# GoogleImageCrawlling

## 구글 이미지 크롤링 스크립트

이 저장소는 구글 이미지를 크롤링하고 다운로드하는 Python 스크립트(`googleImageCrolling.py`)를 포함하고 있습니다.  
이 스크립트는 간단한 설정만으로 원하는 이미지를 대량으로 다운로드할 수 있도록 설계되었습니다.

## 주요 기능
- **자동 이미지 검색**: 검색어를 입력하면 관련 이미지를 구글에서 자동으로 검색합니다.
- **일괄 다운로드**: 실행 시 여러 이미지를 한 번에 다운로드합니다.
- **사용자 설정 가능**: 다운로드 이미지 개수, 저장 경로 등을 간편하게 설정할 수 있습니다.

## 필요 조건
이 스크립트를 사용하려면 아래 환경이 필요합니다:
- **Python 3.x**
- 필요한 라이브러리 설치:
  ```bash
  pip install -r requirements.txt
  ```


## 사용된 주요 라이브러리
-	requests: HTTP 요청을 처리.
-	BeautifulSoup: HTML 콘텐츠 파싱 및 스크래핑.
-	os: 파일 작업 처리.

## 사용 방법
1. 저장소 클론
```bash
git clone <저장소 URL>
cd <저장소 폴더>
```

2. 필요한 라이브러리 설치
다음 명령어를 실행하여 필요한 라이브러리를 설치합니다:
```bash
pip install -r requirements.txt
```

3. 스크립트 실행
아래 명령어로 스크립트를 실행합니다:
```bash
python googleImageCrolling.py
```

4. 입력 제공
스크립트 실행 중에 검색어와 다운로드할 이미지 개수를 입력하라는 메시지가 표시됩니다.
예:
```
검색어를 입력하세요: 고양이
다운로드할 이미지 개수: 10
```


## 설정

스크립트 내부에서 다음 항목을 수정하여 원하는 대로 설정할 수 있습니다:
- **저장 경로**: 다운로드한 이미지를 저장할 폴더 경로.
- **이미지 개수**: 기본 또는 최대 다운로드 이미지 개수.
- **검색 URL**: 구글 이미지 검색 URL (지역화된 URL로 조정 가능).

## 주의사항
- 구글의 HTML 구조 변경 시 스크립트가 작동하지 않을 수 있습니다.
- 스크립트 사용 시 반드시 구글 서비스 약관을 준수하세요.

## 라이선스

이 프로젝트는 교육 목적으로만 사용되며, 사용자는 모든 관련 법규 및 서비스 약관 준수에 대한 책임이 있습니다.


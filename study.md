파이썬 설치 

파이참 설치 

pip install django # 장고 설치 

django-admin startproject config . # 장고 프로젝트 생성

python manage.py runserver # 가상서버 실행, 서버 중지는 CONTROL-C

projects/mysite/config/settings.py # 언어와 시간을 한국인에 맞게 설정
LANGUAGE_CODE = 'ko-kr' # 한국-한국어
TIME_ZONE = 'Asia/Seoul' # 아시아/서울시간

django-admin startapp pybo # 프로젝트는 이미 설치했으니, 앱을 설치해야 한다. 

# Django에서 urls.py 파일은 URL 매핑을 설정하는 데 사용됩니다. 이 파일에서 URL 패턴을 정의하고, 각 패턴과 일치하는 뷰 함수를 지정합니다. 뷰 함수는 views.py 파일에서 정의되며, 해당 URL 패턴에 대한 실제 로직을 구현합니다.

# 요청된 URL이 urls.py의 정규식 패턴과 일치하면, 해당 뷰 함수가 실행되어 요청된 데이터를 처리하고, 클라이언트에게 HTML 화면을 반환합니다. 이 HTML 화면은 뷰 함수 내에서 생성되며, Django의 템플릿 언어를 사용하여 동적으로 생성된 데이터를 포함할 수 있습니다. 이렇게 생성된 HTML 페이지는 클라이언트 웹 브라우저에서 렌더링되어 화면에 표시됩니다.






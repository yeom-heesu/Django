# Django

## Django는 MTV(Model-Template-View) 개발방식

  - 프로젝트 뼈대 : 개발에 필요한 디렉터리 및 파일 생성
  - 모델 코딩하기 : 테이블 관련사항 개발 (model.py, admin.py)
  - URLConf코딩하기 : URL 및 뷰 매핑관계를 정의 (urls.py)
  - 뷰 코딩하기 : 애플리케이션 로직 개발 (views.py)
  - 템플릿 코딩하기 : UI개발 (templates/ 기타 html파일)
  
### Settings.py
  프로젝트 설정파일
  - 처음 프로젝트를 생성하면 장고가 기본사항을 자동으로 등록
      -> 추가필요사항이 있다면 등록
  - 데이터베이스 설정
  - 정적 파일 항목 설정
  - 애플리케이션 등록
  - 타임존 지정
  
### Views.py
  - 뷰 로직 코딩
    - 함수형 뷰
    - 클래스형 뷰 (장고에서 주로 사용하는 뷰 방식)
          
### Models.py
  - 테이블 정의 파일
  - 장고의 특징중 하나인 DB처리를 ORM기법 사용
  - CRUD(create,read,update,delete) 기능을 클래스에 수행 -> 장고가 내부적으로 DB에 반영
  - DB table 신규 생성, 정의 변경 등을 위한 파일
  - make migrations 및 migrate명령 제공 (DB에 실제 변경사항을 적용)
  
### Runserver
 - 개발용 웹서버
  
### URLConf
  - URL + View = urls.py

### Templates
  - 템플릿 디렉터리
      - 프로젝트 DIRS
      - 앱 templates/.....

### Admin.site
  - 테이블 내용 열람, 수정 가능
  - 테이블 내용을 편집 기능 제공
  

* Supports - UI관련 이미지 소스 및 딥러닝 모델을 모아둔 폴더
* Tkinter.py - 프로그램 진입점이자 응용프로그램 UI 코드 관련 클래스
* ScrapingToFile.py - 트킨터에서 사용자에게 키워드를 입력받아 웹크롤링을 한 후 csv파일로 저장하는 클래스
* FileToOracle.py - csv파일에서 오라클로 csv정보를 저장하는 클래스
* OracleToMongoDB.py - 오라클에서 데이타를 뺀다음 한국어긍부정 딥러닝 모델을 load한 후 여러 데이터를 정제해서 몽고DB에 저장하는 클래스

네이버 영화평점사이트에서 원하는 영화를 검색 및 선택하면 해당 영화에대한 긍부정 정보를 딥러닝 모델로 판별한 후 디비에 저장하는 흐름으로 구성하였습니다.  
디비에 저장뿐만 아니라 바로 UI를 통해서 보기 쉽게 분석된 결과를 볼 수 있게 작성해놨습니다.

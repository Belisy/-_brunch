## brunch 웹 스크래핑

fastcampus 한상현 강사님의 강의를 수강하면서 웹 스크래핑을 실습했습니다.  
brunch1.js파일은 puppeteer를 이용하여 무한스크롤을 구현하였고,  
brunch2.js파일은 axios와 fs모듈을 이용하여 스크롤을 한 후,  
필요한 데이터를 추출하여 brunch_article.json 파일을 생성하고,  
이곳에 저장하는 기능을 구현했습니다.  



## 배운것들

[웹 스크래핑 정리](https://velog.io/@belisy/series/%EC%9B%B9%ED%81%AC%EB%A1%A4%EB%A7%81%EC%9B%B9%EC%8A%A4%ED%81%AC%EB%A0%88%ED%8D%BC)

웹 크롤링: 웹 크롤러가 일정한 규칙으로 웹페이지를 브라우징 하는 것 (구글, 네이버와 같은 검색 포털에서 수행)  
웹 스크래핑: 웹 사이트 상에서 원하는 정보를 추출하는 기술  
타겟 사이트/robots.txt : 정책상 스크래핑/크롤링 할 수 없는 정보인지 확인하는 방법  


크롤링에 사용되는 모듈
- axios + cheerio
- selenium, beautifulsoup, scrapy
- puppeteer(가장최근)

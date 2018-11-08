# Python-Web-Crawling
Practice Python Web Crawling and Conduct Project


## Practice Web Crawling with Python
I studied about couple of modules that can be used in the Web Crawling.
- BeautifulSoup
- Selenium


## Conduct Project
I conducted project using modules which i studied to master web crawling.<br>

### 1. Web Crawling Project 1 : 중고나라에서 스노우보드를 판매하는 게시글 크롤링

1. Login my account into 'www.naver.com'.(네이버)
2. Search '네이버' on the search window.
3. click '네이버' web page.
4. Go to '스키/보드/의류' category and search '데크' on the search window(search option = '제목만')
5. Crawl Posts title, uploader, upload time, number of clicker about 10pages.
6. Convert them to Pandas DataFrame and save to csv file named '중고나라_데크.csv'

**You can see the full code in the file I uploaded 'Web Crawling Project'**

### 2. Web Crawling Project 2 : Naver뉴스 기사 크롤링

1. Go to Naver news category.
2. Search the company i want to know.(ex. 아모레퍼시픽)
3. Enter each news by clicking news title and script the contents.
4. Crawl news title, data, context.
5. Convert them to DataFrame and save to csv file '아모레퍼시픽'.

### 3. Web Crawling Project 3 : Nate뉴스 기사 크롤링
  - Same as upper project 'Naver뉴스 기사 크롤링'
 1. Go to Nate news category.
 2. Search the company i want to know about(ex. 아모레퍼시픽)
 3. Enter each news by clicking news title and script the contents.
 4. Crawl news title, data, context.
 5. Convert them to DataFrame and save to csv file '아모레퍼시픽'
  - Because of limit number of page of searching, I convert the type of searching to period.
  - When the page is at the last, i update the start period with last news date on the page.
  


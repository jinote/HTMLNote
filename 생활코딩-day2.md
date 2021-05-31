## Day2 Summary - 생활코딩
5/31/2021

**Contents for today**<br>
7. 줄바꿈 (line-break)<br>
8. HTML이 중요한 이유<br> 
9. 최후의 문법 속성과 img (advanced version)<br>
10. 부모 자식과 목록<br>

**html new line tag**
- using 'br' tag
- no closing 

**paragrahp**
- using 'p' tag
- with closing
- more meaningful when dividing paragraphs
- Here, we can add CSS in 'p' tag such as 'p style="margin-top:45px"'

For example with 'br' and 'p' # PLEASE SEE THE CODE
- <p>Hypertext Markup Language (HTML) is the standard markup language for creating web pages and web applications.
  Web browsers receive HTML documents from a web server or from local storage and render them into multimedia web pages.
  HTML describes the structure of a web page semantically and originally included cues for the appearance of the document.</p><p style="margin-top:45px">
  HTML elements are the building blocks of HTML pages.
  With HTML constructs, images and other objects, such as interactive forms, may be embedded into the rendered page.
  It provides a means to create structured documents by denoting structural semantics for text such as headings, paragraphs, lists, links, quotes and other items. HTML elements are delineated by tags, written using angle brackets.

**Inserting an image**
- using 'img' tag
- 'src' is short for source
- ex) <img src="smile.jpg", width="100%">
<br>
<img width="300", src = "https://images.unsplash.com/photo-1595420832643-faf4aaf65c5b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1868&q=80"/>
<br>
  
- Here, we call 'src="smile.jpg"', 'width="100%"' as Attribute
- The order of attributes doesn't matter
  
**Creating list(list dot)**
- Parent/Children structure
- Using 'ul' at the beggining, '/ul' at the end (parent) and 'li' tag (childern) between 'ul' and '/ul'
- 'li' tag needs the parent tag for grouping
- 'ul' is short for Unordered List
- 'li' is short for List

  
**When we do coding, we need to think that there are 1 million data(Real world situation)**
<br>To solve this problem 
- We use 'ol' tag istead of 'ul' tag for automatic numbering
- When we use 'ol', we don't need to code the numbers (1,2,3,...)
- 'ol' is short for Ordered List
- ex) # PLEASE SEE THE CODE
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ol>

**HTML Study plan for next time**<br>
11. 문서구조와 슈퍼스타들<br>
12. HTML 태그의 제왕<br>
13. 웹사이트 완성<br>
14. 원시웹<br>
15. 인터넷을 여는 열쇠: 서버와 클라이언트<br>

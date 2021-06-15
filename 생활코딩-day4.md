## Day4 Summary - 생활코딩

**Contents for Today**
<br> 16. Web Hosting (Github pages)
<br> 17. Web Server 운영하기 (Mac)
<br> - Installing Web Server on Mac
<br> - Web Server & http
<br> - Communication btw Web Browser and Web Server
<br> 18. 수업을 마치며1
<br> 19. 수업을 마치며12
<br>
>**Web Hosting (Github pages)**

- How to set up "master branch"
<br>settings -> GitHub Pages(scroll down) -> Source (select "master branch") -> Save
- 이론적 정리<br>
<img src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7778.jpeg" width="500">

- static web hosting recommendation (subject to change)
<br>1. https://bitballoon.com
<br>2. http://neocities.org
<br>3. Azure Blob
<br>4. Google Cloud Storage
<br>5. Amazon S3


>**Web server**

- Web browser is not a product name, but a cateogry.
- Same as web server
  - In the web server category, there are several options such as Apache, IIS, Nginx
  - Here, we are going to use "Apache", open source and free.
  - Let's install "Apache" for the next step 

How to install Apache
- Install "bitnami mamp stack" first and the Apache will be automatically installed
- After installing/closing it, find it again by searching "manager - osx.app" on your dex

How to find Apache
- go to "Applications" -> click "mampstack-8.0.7-1" -> click "apache2" -> click "htdocs" -> now, you can see "index.html"
- if you change "index.html" to "index2.html", you can't find the link named "http://127.0.0.1:8080/index.html" 
  - "http://127.0.0.1:8080/index.html"
    - Here, what is "127.0.0.1"? -> this is "Internet Protocol Address" which is IP Address (unique address)
    - What is "8080" -> Port 
    - what is "http"? -> short for Hyper Text Transfer Protocol


# <u>Web Scraping</u>
Web Scraping is used to extract the data from any websites on the internet that allows their users to scrape information and data within certain boundaries. We can think of this technology as a grey area which means the extraction of data is legal until that extraction follows all that rules stated by the website in their "/robots.txt" file.
<br><br>Talking about the "/robots.txt" file it is always advisable to look into a website's robots file and identify the scope of scraping. This means we need to distinguish the paths that are not prohibited by the website and the ones that are prohibited. We can access the file by simply appending "/robots.txt" at the end of the website URL.
<br><br><b>Example</b>:
<br>http://www.flipkart.com/robots.txt
<br><br>In this repository we will be scraping data from the famous Indian E-commerce website "Flipkart". We will mainly focus on a single product which is "Mobile Phone" the following attributes of the product is our key interest for extraction.<br>
⦁ Mobile Name<br>
⦁ RAM and ROM Specification<br>
⦁ Ratings and Reviews<br>
⦁ Stars<br>
⦁ List and Sales Price<br>
<br>Thus, for the same we make use of python libraries such as Requests, BeautifulSoup, and Pandas to extract the data and build data frames for analysis.

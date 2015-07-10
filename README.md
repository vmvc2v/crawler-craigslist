# crawler-craigslist
A **crawler** for searching housing info on Craigslist.org
-------------------------------

1. Basic Info

	* Date: June 24, 2015
	* System: Windows 7, Python 3.4.3
	* IDE: PyCharm [Community Edition]
	* Package: urllib2, BeautifulSoup, Requests
	* On Server: /opt/data/PRJ/Crawler_Craigslist
	* On Windows Server(140.x.x.194): F:\Work_Share\Craig_Daily_Download
	* Github: [github.com/vmvc2v/crawler-craigslist](https://github.com/vmvc2v/crawler-craigslist)

2. Goal

	* Target URL: chicago.craigslist.org/search/hhh
	* Target area: title and posting info

3. Step
    * Step 1: Download and install [Python 3](https://www.python.org/downloads/)
        * ![Download and install Python 3](https://github.com/vmvc2v/crawler-craigslist/blob/master/doc/img/01.PNG?raw=true)
    * Step 2: Download and install Python IDE [PyCharm [Community Edition]](https://www.jetbrains.com/pycharm/download/)
        * Instruction: [Installing PyCharm](https://www.jetbrains.com/pycharm-educational/quickstart/installation.html) [[Video]](https://www.youtube.com/watch?v=-s4wKoLO520)
        * ![Download and install PyCharm](https://github.com/vmvc2v/crawler-craigslist/blob/master/doc/img/02.PNG?raw=true)
    * Step 3: Import Packages in PyCharm
        * Instruction [[Video]](https://www.youtube.com/watch?t=156&v=XjNm9bazxn8)
        * Click menu "**File**" -> "Settings...", "Project: crawler-craigslist" -> "Project Interpreter", choose 3.4.3 or later
        * ![Choose interpreter](https://github.com/vmvc2v/crawler-craigslist/blob/master/doc/img/03.PNG?raw=true)
        * Click ":heavy_plus_sign:" button to add "**beautifulscraper**" and "**requests**" these two packages, and install them.
        * ![install two packages](https://github.com/vmvc2v/crawler-craigslist/blob/master/doc/img/04.PNG?raw=true)
        * After all, click "**OK**" to finish setting parts.
    * Step 4: Run code
        * Click menu "**Run**" -> "**Run...**", or right click ":arrow_forward:**Run 'crawler'**" in crawler.py file editor



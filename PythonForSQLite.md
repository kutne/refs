# Python & SQLite

Now that you've learned a bit about relational databases, I recommend learning a bit of Python for 2 main reasons:
1. Automation. You can use Python to do pretty much **anything**, but it's particularly useful or things you find yourself doing over and over and over again.
    1. [insert information](https://www.sqlitetutorial.net/sqlite-python/insert/) into your database for you
    1. [Update records](https://www.sqlitetutorial.net/sqlite-python/update/) in your database (maybe you want to keep track of when a record was last modified and don't want to manually type out the date and time)
    1. scrape web content with [BeautifuSoup4](https://programminghistorian.org/en/lessons/intro-to-beautiful-soup) (which you might then want to insert into the database)
    1. rename and/or many files 
    1. combine [images into a single PDF file](https://www.geeksforgeeks.org/python-convert-image-to-pdf-using-img2pdf-module/) **much** more quickly than with something like Adobe Reader
    1. open local files on your computer relevant to your database without you having to find them
1. You can build a user interface with [Django](https://www.djangoproject.com/)

<p align="center">
<a href="https://xkcd.com/353/"><img src=https://imgs.xkcd.com/comics/python.png></a>
</p>

But let's not get ahead of ourselves. First we need to set up Python and play around with it a bit...




### 1. Getting Set Up
   - Follow these instructions to install [Python 3](https://realpython.com/installing-python/)
   - Choose and install a [text editor](https://realpython.com/python-ides-code-editors-guide/#general-editors-and-ides-with-python-support) to write and save your code in. (I use and recommend [Atom](https://atom.io/), which is free.)

### 2. Get Started Immediately with Practical Skills  

<p align="center">
    <img src="https://automatetheboringstuff.com/images/automate2_small_cover.png">
    </p>
    
I cannot say enough good things about Al Sweigart's website [Automate the Boring Stuff](https://automatetheboringstuff.com/).   


All of the lessons and related files are available 100% for free on his website. I return to this resource over and over again. Since DOING ALL THE THINGS is probably intimidating, I've flagged below the tutorials that will most effectively help you get your Python sea-legs IMHO. I recommend completing these brief tutorials **in the order given below**.

- Select portions in Part 1: Python Programming Basics
   - [Basics](https://automatetheboringstuff.com/2e/chapter1/)
   - [Flow](https://automatetheboringstuff.com/2e/chapter2/)
   - [Functions](https://automatetheboringstuff.com/2e/chapter3/)
   - [Lists](https://automatetheboringstuff.com/2e/chapter4/)
   - [Manipulating Strings](https://automatetheboringstuff.com/2e/chapter6/)
- Complete select portions in Part 2: Automating Tasks
   - [Reading and Writing Files](https://automatetheboringstuff.com/2e/chapter9/)
   - [Organizing Files](https://automatetheboringstuff.com/2e/chapter10/)
   - [Web Scraping](https://automatetheboringstuff.com/2e/chapter12/)

### 3. Build and manipulate your database with Python 

#### If you do NOT plan to use Django
I recommend making use of these two tutorials together to create and manipulate a SQLite database file:
- [SQlite Python](https://www.sqlitetutorial.net/sqlite-python/)
- [A thorough guide to SQLite database operations in Python](https://sebastianraschka.com/Articles/2014_sqlite_in_python_tutorial.html)

<p align="center">
<img src="https://cdn.sqlitetutorial.net/wp-content/uploads/2016/01/SQLite-Python.jpg">
</p>  

#### If you DO plan to use Django  
While it is possible to use Django with a pre-existing database, I've found it a million times easier to use Django when I used Django to create the database. I recommend completing [this tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django) through the end of the Part 4.

<p align="center">
<img src="https://miro.medium.com/max/1400/1*8Ya6KbfaTyDOSTwyY6kvug.png">  
</p>  

### 4. Use the above tutorials as the foundation to create your own custom research database  
- Take a look at your database original diagram. Based on what you've learned completing the above lessons, do you want to make any changes to it? If yes, do so now!
- Using your diagram as a guide, create your database
   - Remember, even though you've made it through a tutorial following their examples step by step, now comes the real trick: going off script. It will be tricky and that's okay!
   - Use DB Browser open and view yourdatabase so you can spot check to see if it reflects the changes that you expect.
   - Keep in mind things will go wrong.  
   - You'll get error messages. Read the error messages- usually they will tell you which line in your code Python barfed at. Google error messages liberally - you almost certainly aren't the first person to be stumped by it.

<p align="center">
    <a href="https://getpocket.com/explore/item/learning-to-code-is-easy-here-s-how-to-teach-yourself"><img src="https://pocket-image-cache.com/direct?resize=w2000&url=https%3A%2F%2Fwww.scotthyoung.com%2Fblog%2Fwp-content%2Fuploads%2F2019%2F07%2Fcoding-perception-vs-reality.png"></a>
    </p>

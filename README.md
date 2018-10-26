# Simple-Crawler
This crawler was built using BeautifulSoup's simple web scraping ability of web pages.

### About the website
This website is an Australian citizens only help forum, designed to help people in a state of despair, depression or anxiety.
Thus, if you are currently not in Australia, you cannot have any access to the website outside of seeing user's posts.

##### Dataframe
The DataFrame created in the end is comprised of the following:
1. User_ID - user's IGN
2. Post_Title - a string made out of the post's title
3. User_Post - a string containing the entire body of the user's post
4. Num_of_Comments - integer specifying the number of comments on that specific post
5. Date - the date the user posted
6. Url - post's url

##### Package Requirements:
- Python 2.7 or higher
- numpy version 1.14.3 or higher
- pandas version 0.23.0 or higher
- bs4 (BeautifulSoup) version 4.6.0 or higher
- urllib3 version 1.22 or higher

###### TODO:
 - Add option to select which features will be placed in the final DateFrame
 - Figure out how to improve efficiency of the code by having it iterate faster through the posts

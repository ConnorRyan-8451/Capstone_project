# Capstone_project
This is the repo that will hold the code for Senior Design

The goal of this project is to make an anti cheat systetm that will allow teachers to upload and scan a test to see if there are any answers online.
The script will mark where the asnwers where found so teachers can double-check what the script found.
At the end, the test will get a score with how easy it is to "cheat" on.

This is similar to turnitin.com

Things to look into
* google dorks
* Web Crawlers

## Resources
- https://www.reddit.com/r/learnpython/comments/kswa60/google_dork_using_python/    (exploit DB)
- https://www.scrapingbee.com/blog/crawling-python/
- https://www.geeksforgeeks.org/performing-google-search-using-python-code/
- https://www.quickprogrammingtips.com/azure/how-to-upload-files-to-azure-storage-blobs-using-python.html
- https://apitracker.io/a/chegg
- https://apitracker.io/a/quizlet
- https://apitracker.io/a/coursehero

# Future things to maybe add
Build the application interface with C# Visual Studio and have that run Python within the C#
Have Python read a file systems where teachers uploaded there test and scan each test

## Base code part 1
* A place where Teachers can upload a document (Need to decide what type of document teachers can upload)
* The scan each question within the test
  * figure out how to scan and search question by question
  * this part will need to be asynchronous
* The web scrapping part takes place after this
  * Figure out how we are going to web scrape
  * can we spawn and browser within the script and use that to search?
  * 



## base code part 2



## base code final



## Everything that needs to happen
1. What type of app do we want to make?
   1. Do we want a HTML based webpage?
   2. Could an azure function app work?
   3. Do we need to code in HTML and CSS for the webpage?
   4. We could build the website with flask or Django (Django would be the better choice)

2. Teacher uploads a file
   1. How do they upload a file?
   2. Where are we going to store the files?
   3. Azure could be the back end?

# drug_web_scraper
web scraper for website that lists medications to search for adverse drug reactions

## Instructions
1. clone repository
2. run `npm install`
3. go to the login page of epocrates, https://www.epocrates.com/login?refernext=https%3A%2F%2Fonline.epocrates.com%2Fdrugs
4. create an account and login
5. insepct the login page to view the cookie that has been created in the development tools tab
6. create a cookie.txt file and copy and paste your cookie into the file 
7. run `node scrape.js`
8. after running scrape.js, drugs.html will be created which is the scraped version of the website

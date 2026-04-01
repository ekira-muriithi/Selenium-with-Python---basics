Selemium webdriver --the selenium API that provides you with commands that you will write in your script for commanding your browser when your test script runs.
Driver --browser dependent, i.e., Chromedriver; executes those commands because the webdriver can't
Example
  You write: driver.click()
  WebDriver says: “Click this element”
  ChromeDriver receives it
  ChromeDriver clicks in the browser
When you write a test script, you are not communicating with the browser directly, the Webdriver is

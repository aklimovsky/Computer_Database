This is an autotest suite for testing http://computer-database.herokuapp.com/computers

The tests are written for Robot Framework 2.7 and older, but not 3.x. Selenium library is used. Test are run under Chrome browser.

Before you start make sure that you have a proper environment installed.

1. Install Python 2.7

2. Install pip

3. Install Robot Framework: run 
pip install robotframework

Please consult with https://github.com/robotframework/robotframework/blob/master/INSTALL.rst for details on above 3 steps

4. Install robotframework-selenium2library: run 

pip install robotframework-selenium2library

Please see https://github.com/robotframework/Selenium2Library for details

5. Install Chrome

6. Install chromedriver: download latest version here https://sites.google.com/a/chromium.org/chromedriver/downloads
Unzip the driver and move it to a directory you like. Don't forget to add this directory to PATH environmental library.


Obtaining the tests:

1. Download or clone this repository


Running the tests:

1. Runninng all test cases from all suites: execute "pybot test_suites" from Computer_Database directory.

2. Running a certain tests_suite: execute "pybot <suite_name>" from Computer_Database/test_suites directory.

For example: pybot Update.txt

3. Running a number of test_cases from a certain suite: execute "pybot --test <test_name> <suite_name>" from Computer_Database/test_suites directory.

For example: pybot --test *valid* Fields_validation.txt


Analyzing the result:

1. Open log.html in the directory where you previously executed the pybot

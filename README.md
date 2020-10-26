## SeleniumIDE
### Website Automation Using Selenium IDE Scripting

#### Step 1: Install Selenium IDE Browser Plugin
**Chrome(_recommended_):** 
https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd
* Click the button "Add to Chrome"
* Pop-up will be displayed. Click "Add extension"
* Click the extension icon to open the extension menu
* Click at the "pin" icon
* From now Selenium IDE can be run from the extension toolbar

**Firefox(_unstable_):**
https://addons.mozilla.org/pl/firefox/addon/selenium-ide/
* The steps are similar to Chrome installation


#### Step 2: Run the Tests
1. Launch the Selenium IDE Extension
1. Select Option: Open an existing project
1. Load the .side file
1. Click the Run All Tests button
1. Sip coffee while the machines do all the work

##### Common Error:
* Selenium Browser may lock up after running the testbefore the page loads, displaying the text "Preparing to run your test", this happens more commonly in the Firefox browser
* If you encounter this error:
    * close your Selenium generated browser windows
    * reload the file and run the test again

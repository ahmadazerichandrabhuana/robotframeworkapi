# API Test Automation using Robot Framework 
This is a (very) simple sample of API Test Automation using Robot Framework.
API Collection retrieved from this Website : https://thinking-tester-contact-list.herokuapp.com/ (credit to [Kristin Jackvony](https://thinkingtester.com/about/)).
You can check my GitHub Repository [here](https://github.com/ahmadazerichandrabhuana/postmanapitest) for API Collection on Postman.

## Requirements

1. Install [VS Code](https://code.visualstudio.com/) or any Code Editor you're comfort with.
2. Install [python](https://www.python.org/), preferably version **3.9.10** (that's the one I used and having no issue).
3. Make sure `pip` also installed together with python. If it is not automatically installed, refer to [Python Crash Course](https://ehmatthes.github.io/pcc/chapter_12/installing_pip.html).
4. Update python to your PATH file. Refer [here](https://realpython.com/add-python-to-path/), this website covered configuration for Windows, Linux, and MacOS. Or, if you prefer using python version management tools, refer to [this article](https://medium.com/@zorozeri/how-to-install-pyenv-and-manage-pythonversion-on-your-local-machine-241b119b7ae9) for using [pyenv](https://github.com/pyenv/pyenv).
5. Install [NodeJS](https://nodejs.org/en/download/prebuilt-installer), this is necessary because NodeJS is needed by [Browser Library](https://docs.robotframework.org/docs/different_libraries/browser). 
7. Download and open this code repository on your local Code Editor and run these 2 commands :
   ```
   pip install -r requirements.txt
   ```
   If the pip process is failed, try to downgrade your python version. I used python `3.9.10` when creating this repository (that's why I suggest it on requirements above). When I tried on different local machine with python `3.13.0` somehow the pip process is error.

## Run Tests
   ```
   robot tests
   ```

## Open Test Report
   MacOs : 

    open report.html
   Windows : 

    start report.html
   Or just drag and drop file `report.html` into your Browser.

## Open Test Log
   MacOs : 

    open log.html
   Windows : 

    start log.html
   Or just drag and drop file `log.html` into your Browser.

## Short Repository Explanation

This sample Test Automation only consists of 1 folder : 

* tests
   ```
   Contains test cases with inside it I put all variables and settings needed
   ```
   
## Requests Library Keywords Documentation

https://marketsquare.github.io/robotframework-requests/doc/RequestsLibrary.html

# OpenSourceWorkshop - Coderage
<img src="https://github.com/shakedkialy/Coderage/blob/main/html_files/logo.png?raw=true" width="250"> 
Coderage is a package that allows running tests and code coverage in comparison over time.
The purpose of this project is to enable easy and efficient analyzing and conclusion drawing regarding software testing.

# Project license:
#### MIT

# How to run:
#### 1. Packages to install (inside terminal):
    pip install pytest
    pip install pytest-cov
    pip install pytest-html
    if produced an error "Could not install packages due to an EnvironmentError" then try pip install --user <package name>
 #### 2. add __ init__.py file to the code package you want to test. 
 #### 3. name your test files *test.py 
 #### 4. go to command line and run the following:
       python main.py module=module1,module2 tests=test1,test2 out_dir=results
## To run our tests (result is in Results folder):
    Go to Coderage directory inside command line and run the following:
    python main.py module=. tests=Tests_Examples
    
     

# Project Information

  - This project is used to for performing unit test cases in FastAPI


## Commands for executing this FASTAPI application
* $ uvicorn app.main:app --reload   => For Executing FASTAPI application


## Commands for executing unit test cases in this FASTAPI application
* $ pytest              ===> For executing all test cases of application
* $ pytest -k test_create_user -v           ===> For executing test case to specified method



For the tests we'll use a separate file "test_app.db" instead of "app.db" which is used for main application.
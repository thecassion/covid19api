#### Covid19api for MLHaiti

virtualenv covid19api

source covid19api/bin/activate

### Terminal commands

    Initial installation: make install

    To run test: make tests

    To run application: make run

    To run all commands at once : make all


### Viewing the app ###

    Open the following url on your browser to view swagger documentation
    http://127.0.0.1:5000/


### Using Postman ####

    Authorization header is in the following format:

    Key: Authorization
    Value: "token_generated_during_login"

    For testing authorization, url for getting all user requires an admin token while url for getting a single
    user by public_id requires just a regular authentication.



### Contributing
If you want to contribute to this project, clone the repository and just start making pull requests.

```
https://github.com/MLHaiti/covid19api.git
```

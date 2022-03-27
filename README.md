# How to deploy the production environment

- Push the code to the **test* branch and test it here after pipeline succeeded: http://34.135.14.133:3000/
- Create merge request to the main branch and merge it, if the code is acceptable
- After pipeline succeeded, production environment can be tested on: http://34.69.102.155:3000/


# Structure

- **main** branch for production environment
- **test** branch for test environment
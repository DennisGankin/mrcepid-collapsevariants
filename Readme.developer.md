# mrcepid-collapsevariants Developer Readme

## Testing

Note for development: this applet has now been set to work with local unit tests, to ensure
robust CI/CD. Due to size, this test data cannot be pushed to GitHub. Please ge in touch with 
Eugene Gardner for any further information.

### System Requirements

In order to run the unit tests, you simply need to install uv:

`pip install uv`

Then run a uv install: 

`uv sync`

Double check that pytest is installed: 

`pytest --version`

And run the tests in the `/test/` directory:

`pytest`

### Simulated Data

Test data has been simulated. For more information regarding this process, please get in 
touch with Eugene Gardner.
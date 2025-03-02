# AlteryxDeploy
This is working solution utilizing related Alteryx server API, on automating Alteryx workflow deployment onto Alteryx server environments through CI/CD.  Workflows release needs to be set up dev/qa/prod deployment and configured to accomodate CI/CD server environment, e.g. Octopus.
Alteryx server needs to be set up to use the existing server Web API, along with required system configurations.
Octopus server need to set up all the required binding variables used in PowerShell code, including API Tokens.
The code has been tested both independently from server host machine and GitHub deploy, with a unique workflow id generated and workflow content published onto the related server.
Run code on desktop FIRST with hardcoded access token to test out.

# shyamrachchh1
some online articles that identify what makes "quality" code.

# [Article 1: Introduction to SonarQube](https://www.tothenew.com/blog/sonarqube-all-in-one-code-quality-manager/#:~:text=Introduction%20to%20SonarQube%3A&text=This%20one%20place%20is%20SONARQUBE,Potential%20bugs%20and%20Code%20complexity.)

## Starting Up SonarQube:

  - Download and unzip [SonarQube](https://www.sonarsource.com/products/sonarqube/?gads_campaign=SQ-Hroi-PMax&gads_ad_group=Global&gads_keyword=&gclid=CjwKCAjwr_CnBhA0EiwAci5sipEVYEDoYZmM3_0UTMhm9WReJHDz1YuW55OEsCzYCKMwU2X338FgCBoCAnUQAvD_BwE) and SonarQube Runner from the official Downloads page.
  - Setup database settings by indicating the database type and credentials in the sonar.properties file.
  - If necessary, modify web server information, including HTTP port and logging.
  - Launch SonarQube by executing the proper script.
  - Visit [SonarQube](https://www.sonarsource.com/products/sonarqube/?gads_campaign=SQ-Hroi-PMax&gads_ad_group=Global&gads_keyword=&gclid=CjwKCAjwr_CnBhA0EiwAci5sipEVYEDoYZmM3_0UTMhm9WReJHDz1YuW55OEsCzYCKMwU2X338FgCBoCAnUQAvD_BwE) to access the SonarQube web interface. then sign in using the Administrator (admin / admin) username.
  - Using Settings > Update Centre > Available Plugin, install plugins for your projects that are language-specific.

## Configure Sonar-Runner:

  - At the project's root, create a sonar-project.properties file.
  - For your project, define sonar.projectKey, sonar.projectName, and sonar.projectVersion.
  - Define your project's source directory and encoding.
  - Mention the programming language that is being used.
  - Set up any extra project-specific settings.
  -  Ensure that the code coverage plugin is installed in your project to generate coverage.xml.
  -  Generate the coverage.xml by running tests with coverage.
  -  Execute sonar-runner from your project root to analyze your code.

## Dashboard check:

  - Visit the SonarQube dashboard at  [SonarQube](https://www.sonarsource.com/products/sonarqube/?gads_campaign=SQ-Hroi-PMax&gads_ad_group=Global&gads_keyword=&gclid=CjwKCAjwr_CnBhA0EiwAci5sipEVYEDoYZmM3_0UTMhm9WReJHDz1YuW55OEsCzYCKMwU2X338FgCBoCAnUQAvD_BwE) after executing sonar-runner.
  - Examine project specifics on the Dashboard page, including technical debt, code complexity, duplications, and unit test coverage.
  - Look into more metrics and personalised rules using the Measures tab.
  - Develop action plans to address concerns that have been identified.



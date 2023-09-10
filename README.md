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

# [Article 2:How to Improve Your Code Quality Skills in Information Technology](https://www.linkedin.com/advice/0/how-do-you-improve-your-code-quality-skills-information-technology)

  ## Writing Clean and Simple Code:

  - Give variable, function, and class names that are meaningful and descriptive.
  - Create concise, well-defined functions that adhere to the "Single Responsibility Principle."
  - Keep your code free of extraneous complexity, repetition, and ambiguity.
  - Use nested, lengthy conditional statements and loops as little as possible.
  - Explain the logic and function of your code through comments and documentation.
  - Regularly rework code to reduce duplication and enhance readability.
 
## Testing Your Code:

  - Use unit testing to evaluate distinct parts or functionalities.
  - Run integration tests to ensure that various parts or functions perform as a unit.
  - Perform system testing to assess the entire application or system as a whole.
  - Incorporate user testing to make sure the system satisfies user expectations and requirements.
  - Automate and simplify your testing process using appropriate testing tools and frameworks.

## Using a Coding Standard:

   -  Choose or adopt a coding standard that suits your programming language.
   -  Configure tools like [linters](https://www.npmjs.com/package/eslint), [code formatters](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) , or code analyzers to automatically check and enforce your coding standard.
   -  Regularly review and update your coding standard as needed.
    
## Reviewing Your Code Regularly:

  - Conduct self-review by inspecting your own code before submitting it to others or deploying it to production.
  - Engage in peer review by reviewing the code of colleagues or teammates and providing constructive feedback and recommendations.
  - Utilize code review tools like [GitHub](https://desktop.github.com/), GitLab, or Bitbucket to streamline and automate aspects of the review process.



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

# [Article 3: PHP Code Quality Tools to Check and Improve your Code](https://thevaluable.dev/code-quality-check-tools-php/)

## Code Quality:

  - Use PHP CodeSniffer to find coding standards breaches (https://sourceforge.net/projects/php-codesniffer.mirror).
  - To automatically correct some of the code standards problems, use PHPCBF.
  - Take note of elements like typical class and method lengths.
  - Save abstraction for certain cases only.

## Complexity and Bugs:

  - Examine the intricacy of the code using tools such as PHP Mess Detector.
  - Address problems like cyclomatic complexity that is too high.
  - To find mistakes and confirm that the code is accurate, use PHPStan for static analysis.
  - Set the strictness level in accordance with the demands of your project.

## Coding Formatting:

  - To preserve code uniformity, use a coding standard.
  - Use coding standards-compliant code formatting tools, such as PHP-CS-Fixer, to format your code automatically.
  - To guarantee consistency, format your code frequently.

## Unit Testing and Code Coverage:

  - Put your codebase's unit tests into practise.
  - For unit testing, use PHPUnit.
  - Calculate and examine the CRAP metric to spot dangerous and complicated code.
  - Check the code coverage of your tests to make sure it is adequate.
  - To evaluate the effectiveness of your tests, use code coverage reports.

## Metrics and maintainance:

  - Examine measures like coupling, cyclomatic complexity, and lines of code.
  - Use analytics to pinpoint areas that need reworking and improvement.
  - Run code analysis programmes on a regular basis to spot problems early.
  - For thorough quality assurance, combine code quality tools with a strong testing plan.
  - include these tools for code quality into your development process.

# [Article 4: The Engineer’s Complete Guide to Code Quality](https://stepsize.com/blog/the-engineers-complete-guide-to-code-quality)

## Duplication of code and refactoring:

  - Using [code analysis tools](https://checkmarx.com/checkmarx-dast/?utm_source=google&utm_medium=cpc&utm_campaign=NA-AD-20230514-ALL_LEVEL-GOOGLE-DES-PER-SEARCH-DAST&utm_search_query=DAST&utm_keyword=dynamic%20code%20analysis%20tool&utm_campaign=NA-AD-20230514-ALL_LEVEL-GOOGLE-DES-PER-SEARCH-DAST&utm_source=adwords&utm_medium=ppc&utm_term=dynamic%20code%20analysis%20tool&hsa_acc=2852355864&hsa_cam=20137732541&hsa_grp=154844307764&hsa_ad=673007635610&hsa_src=g&hsa_tgt=kwd-349427435897&hsa_kw=dynamic%20code%20analysis%20tool&hsa_mt=b&hsa_net=adwords&hsa_ver=3&gclid=CjwKCAjwr_CnBhA0EiwAci5siqawFCwh0pedWo7sNTogcHTSG0cFVY9je3gDEsvebCBf5n4OBGYslhoCaKgQAvD_BwE), locate and remove duplicate code.
  - Refactor your code frequently to enhance its quality and maintainability.
  - Put your attention on streamlining the code and enhancing its organisation.

## Analysis and Management of Dependencies:

  - Analyse and successfully manage project dependencies.
  - Keep the interaction between afferent coupling and efferent coupling under check.
  - Identify and fix dependencies-related instability problems.

## Static and security analysis:

  - To find security flaws, use techniques for static code analysis.
  - When writing programming, address security concerns immediately.
  - Make sure the code is secure and that it doesn't have unexpected repercussions.

## Maintaining Continuously:

  - Include [code quality tools](https://www.codacy.com/signup-codacy?utm_term=code%20quality%20tools&utm_campaign=Quality+-+Use+Cases+Global&utm_source=adwords&utm_medium=ppc&hsa_acc=9882323101&hsa_cam=20519036842&hsa_grp=158738021688&hsa_ad=672459033111&hsa_src=g&hsa_tgt=kwd-327625427670&hsa_kw=code%20quality%20tools&hsa_mt=p&hsa_net=adwords&hsa_ver=3&gad=1&gclid=CjwKCAjwr_CnBhA0EiwAci5siiYlo9RqMvaPDFUJE0R5Ao0QSjyvnE59_hY3qvUw84cZ4g5PZujEEBoC-HAQAvD_BwE) in your pipeline for continuous integration and delivery (CI/CD).
  - Analyse code metrics often to find areas for development.
  - Make continual code maintenance a priority to avoid building up technical debt.

## Code Quality Instruments:

  - Investigate and employ code quality tools like linters, static analyzers, and Stepsize.
  - Automate your development workflow by integrating code quality tools.
  - Utilise these technologies to make code review procedures more efficient.


## comaparison:

  - Testing of a code repeatedly, quality of a code and maintainance of the code plays a really big role everytime in code quality as we have seen this in all      the articles. In every article this above points which I mentioned are almost similar.

## Evaluation:

  - Evaluating my work on a 4 point scale, I rate myself with exemplary work. I spent almost one fourth of my day for it as it was staring of the course and I wanted to start on a good knot. It felt really good working and honestly did a good hard work for this article. Happy and highly satisfied.

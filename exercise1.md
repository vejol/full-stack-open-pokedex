# Exercise 11.1: Warming up

Let's assume we have a Python application. There are numerous tools for linting, testing, and building, and here I will select my favorites. I would use Pylint as the linting tool because it is widely used and comprehensive. For testing, it would be feasible to use unittest, which is part of the Python Standard Library. Pytest is also a good option. Since the team plans to release the application soon, linting and testing tools may have been selected already, and there may be no need to choose them again.

As Python is an interpreted language, the application does not need to be built. However, if there are plans to distribute the app to people as an executable, tools like PyInstaller, py2exe, or cx_Freeze may be used, although I have never done that myself.

According to Google, a variety of CI tools are available. Some possible cloud-based environments include GitLab CI/CD, Travis, CircleCI, and Azure Pipelines. If a self-hosted CI tool is preferred, options include the self-hosted version of GitLab CI/CD, TeamCity, and GoCD.

There are many factors to consider when selecting between cloud-based and self-hosted CI tools. Web-based tools require less configuration, making them a potentially better choice if the application is straightforward and has no special requirements. Additional benefits include automatic scalability and integration support with other cloud-based services. Nevertheless, self-hosted CI tools provide full control over the data and infrastructure, making them a more suitable choice for projects where high security is essential. Furthermore, self-hosted tools might be more cost-effective, especially if the team already possesses some infrastructure for the application.

# php-assignment

For the simplicity, we are going to use **Symfony framework**. Use latest version please.


The goal will be to create a simple database of articles and comments.

The article will contain:
- title (varchar)
- text (text)
- date of publication (datetime)
- contributor name (varchar)

The comment will then contain:
- contributor name (varchar)
- email (varchar)
- text (text)
- date of publication (datetime)
- id of the comment to which he/she is responding (int, optional)

Implement a simple project that will allow you to display a list of articles, article details, add a new article, and similarly work with comments. The functionality and architecture design is important, you don't need to do frontend, design and implement only REST API. Use PHP at version at least 8.0 please.

Create a repository on github.com and commit the source code there to a separate branch (e.g. feature/cms) on an ongoing basis, then commit that branch as a pull request to the master and add the Reviewer role to the following account for that pull request:


- Pavel Kraus: https://github.com/pavlix98

Don't forget to invite these accounts to the project/repository at the beginning, so we can look at the code continuously and then adding the reviewer role works. 

Using other tools or libraries like Docker, PHPUnit, formating tools,... is up to you

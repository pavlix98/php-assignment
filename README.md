# php-assignment

For the simplicity, we are going the pure PHP way.


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

Implement a simple service that will allow you to display a list of articles, article details, add a new article, and similarly work with comments. The appearance of the resulting page **doesn't matter**, the functionality and architecture design is important. Do not use any external libraries - everything should be written in pure PHP (preferably version 8).

The goal is to practice class structure design, i.e. focusing on design patterns. Also note that any data that will be transferred in the application should be in the form of an object, not an untyped array (if possible, of course). The resulting complexity of drafting and using more complex constructs is entirely up to you.

Create a repository on github.com and commit the source code there to a separate branch (e.g. feature/cms) on an ongoing basis, then commit that branch as a pull request / merge request to the master and add the Reviewer role to the following account for that pull request:


- Pavel Kraus: https://github.com/pavlix98

Don't forget to invite these accounts to the project/repository at the beginning, so we can look at the code continuously and then adding the reviewer role works. 

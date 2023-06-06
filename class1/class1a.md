## class(2) <a name="Express,NPM,TDD,CI/CD"></a>
 

 Reading:
An introduction to NodeJS and Express:
1. Explain middleware, answer as though I were a non-technical recruiter.
 It is a software layer that sits between the web server and the actual application logic,
 in other words,its a function or set of functions that handled between the request and response.

2. Express is the most popular web application frameworks for Node.js.
3. Express is “unopinionated.” What does that mean?
means that it provides a minimalistic and flexible approach to building web applications,and 
 there is no one right way to do things that Express will force you into.
 
4. What is a module and why is modularity useful to us as developers?
Modularity is the concept of breaking down a complex system into smaller, manageable modules.
It is a way of organizing and structuring code into separate components that can be developed,
 maintained, and tested independently.
___________________________________________________________________________________________________________________ 
What is NPM?
1. What version of npm are you running on your machine? 
9.5.0
2. What command would you type to install a library/package called ‘jshint’ into your node project?
npm install jshint
___________________________________________________________________________________________________________________
What is TDD?
1. Explain why tests are important. Please explain as though I were your non technical elder.

It helps to ensure all the components are working properly.
It also enables you to easily identify bugs. 
Therefore, you can quickly take the necessary steps to fix issues.
in other words ,it helps ensure that the code behaves as expected and produces the desired output.

2. What are three expected benefits of testing?
a-early discovery of code bugs.
b-validation of your design and code structure.
c-cost and time savings in catching and fixing issues early.

3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

a-Failure to consider all scenarios and not writing tests to cover them can lead to insufficient test coverage and missing errors.
b- Creating the tests in  complex functionality way , It can indeed make the tests difficult to understand.
____________________
a- When team members fail to communicate effectively about testing strategies  it can result in inconsistent test coverage, duplication of effort, or gaps in testing.
b-Maintaining and updating tests as the codebase evolves is crucial to ensure the effectiveness of the test suite.so 
Outdated or broken tests can lead to false positives/negatives and reduce the effectiveness of the test .

___________________________________________________________________________________________________________________
CI/CD:
1.What are three benefits of Continuous Integration?
a-Early detection of issues.
b-Smaller code changes.
c-More test reliability.

2.Continuous delivery automates deployment of a release to an environment
for staging or testing. Continuous deployment automatically deploys every
 release through your pipeline (including testing) and to production
 
 
3.Explain how GitHub fits into this process assuming the listener comes from a non-technical background?

a-Version Control: One of the main features of GitHub is version control. Version control is like a time machine for your code. It allows developers to keep track of every change made to the project's codebase over time. This means that if something goes wrong or if you want to go back to a previous working version, you can easily do that.
b-Repository: In GitHub, a repository, often called a "repo," is a place where the project's code and all its related files are stored. It's like a folder that holds all the project's resources. A repository can be either public, meaning it can be accessed by anyone, or private, meaning it can only be accessed by authorized users.
c-Collaboration: GitHub enables collaboration among developers. Multiple people can work on the same project simultaneously without conflicts. Each developer can create their own copy of the code, make changes, and propose those changes to be merged back into the main codebase. GitHub provides tools to track and manage these changes, making collaboration smooth and efficient.
d-Pull Requests: Pull requests are a way to propose changes to a project. When a developer makes changes to their own copy of the code and wants those changes to be reviewed and merged into the main project, they create a pull request. Other team members can review the changes, provide feedback, and discuss any potential issues. Once the changes are approved, they can be merged into the main project.
e-Issue Tracking: GitHub also provides a system for issue tracking. Issues are used to report problems, suggest enhancements, or discuss ideas related to the project. It allows team members and users to communicate about specific tasks or topics within the project. Issues can be assigned to specific individuals, labeled, and prioritized to help with organization and project management.
f-Documentation: GitHub can also serve as a platform for hosting project documentation. Developers can write and maintain documentation within the repository itself, making it easily accessible to everyone involved. Good documentation is essential for understanding how to use the software, contributing to the project, and troubleshooting any issues.

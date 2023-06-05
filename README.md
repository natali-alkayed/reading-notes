# reading-notes
This site includes my notes for each lecture that is collected from several resources.
# Table of contents
1. [Node Ecosystem](#NodeEcosystem)
2. [Some paragraph](#Express,NPM,TDD,CI/CD)
3. [Data Structures and Algorith](#DataStructuresandAlgorith)


## Class - 1 - Node Ecosystem <a name="NodeEcosystem"></a>
The Node.js ecosystem is a vibrant and expansive community of developers, libraries, and tools that revolve around the popular JavaScript runtime, enabling server-side and command-line application development with a rich selection of modules and frameworks.

Reading:

1.How would you describe Node to a non-technical friend?
Node.js is a powerful platform that allows you to run JavaScript code outside of a web browser.
It basically lets you use JavaScript to build applications that can do things like
 interact with databases, handle server requests, and perform other tasks typically done on the server-side of a web application. In simpler words,
Node.js enables you to use JavaScript to create server-side applications and perform various operations efficiently.
___________________________________________________________________________________________________________
2.What does it mean that Node is a JavaScript runtime?
it means that Node.js provides an environment for executing JavaScript code outside of a web browser,meaning it can be executed directly 
on a computer or server without the need for a browser.

___________________________________________________________________________________________________________
3.What is Node used for?
Developers use Node.js to create server-side web applications,
it is commonly used to develop real-time applications,Streaming applications and other appicatins.
resources:
https://brainhub.eu/library/what-is-nodejs-used-for

___________________________________________________________________________________________________________
Additional Questions:
1.I am looking forward to building a full stack web applications with powerful backend and modern front end
including authentications,algorithms,oop and data structure. 

2.Learning what is a Node ecosystem, TD, CE/CD , what is the
utility of them,importing and exporting Modules.
writing of modular code using commonJS modules, writing tests to assert code quality,
 setting up and working in a “CICD” environment (Github Actions).



 ## class(2)  <a name="Express,NPM,TDD,CI/CD"></a>
 

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

_______________________________________________________________________________________________________
## Prep - Data Structures and Algorith <a name="DataStructuresandAlgorith"></a>

1. What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?
 to pick the best data structure to solve a particular problem, we have to take into account what are the operations we are going to perform and how often they are going to be executed


2. How can we ensure that we’ll avoid an infinite recursive call stack?
every recursive function should has tow parts : the base case and the recursive case , the recursive case is wjen the function calls it self.The base case is when the function doesnt call itself agian...by dividing the function to tow these ats,the infint lopp wll not exsist.

___________________________________________________________________________________________________________
### Recursion : is used in many algorithms ,is abuilding block.
recursion has tow parts: base case and recursive case .
## psoudo code : is a high level describtion of the problem ,you are trying to solve in code..its written like code ,but its meant to be closer to humen speech.
people use recursion since it often makes code easier to understand and look cleaner.
___________________________________________________________________________________________________________
### Data structer: 
1. linked list : is something called an (node) which contains a value and apointer ,the value is something as simple as a number.and that number will simply connect you to the next node.
the first node in the list is known as a (head) while the last node known as (tail).

2. array.
3. hash table,it is an object in javascribt.
4. stack and queue: they are similler and they are both kind of built on top of arrays with a few additional features.
5. graphs and trees: basically they are kind of similar to a linked list where you have nodes that are pointing to other nodes.
___________________________________________________________________________________________________________
### Big O :
is assentionally an equation that describs scales with respect to some input variables.
___________________________________________________________________________________________________________
### Things I want to know more about: knowing all data sturcter types to solve algorithems
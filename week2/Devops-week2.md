# 1:Extreme Programming Framework:
Extreme Programming also called XP. XP is a lightweight methodology for small to medium-sized teams developing software in the face of vague(unclear meaning) or rapidly changing requirements. Extreme programming is an agile software development framework that aims to produce higher-quality software and higher quality of life for the development team. We are still talking about methodology and as you can see we are still talking about the methodology so we are not just talking about going out and just starting to write software. These are principles and there we need to follow. XP is: i) lightweight: it does not overburden the developers. ii) Humanistic: it is centered on people, developers and customers. iii) Discipline: Practices that we need to follow. iv) Software Development: Key point. We have to follow the mentality of sufficiency: How would you program if you have all the time in the world? i) write tests ii) reconstruct often iii) talk with fellow programmers and with the customers.
Values:
The 5 values of XP are communication, courage, respect, simplicity and feedback.
Communication Software development is inherently a team sport that relies on communication to transfer knowledge from one team member to everyone else on the team. XP stresses the importance of the appropriate kind of communication - face-to-face discussion with the aid of a whiteboard or other drawing mechanism.
Simplicity means "what is the simplest thing that will work?" The purpose of this is to avoid waste and do only necessary things such as keep the design of the system as simple as possible so that it is easier to maintain, support, and revise. Simplicity also means addressing only the requirements that you know about; don't try to predict the future.
Feedback Through constant feedback about their previous efforts, teams can identify areas for improvement and revise their practices. Feedback also supports simple design. Your team builds something, gathers feedback on your design and implementation, and then adjusts your product going forward.
Courage Kent Beck defined courage as "effective action in the face of fear" (Extreme Programming Explained P. 20). This definition shows a preference for action based on other principles so that the results aren't harmful to the team. You need the courage to raise organizational issues that reduce your team's effectiveness. You need the courage to stop doing something that doesn't work and try something else. You need the courage to accept and act on feedback, even when it's difficult to accept.
Respect The members of your team need to respect each other to communicate with each other, provide and accept feedback that honours your relationship, and work together to identify simple designs and solutions.
XP's Practices:
Incremental programming 2) small releases 3) simple design 4) Test first 5) Refactoring 6) pair programming 7) continuous integration 8) onsite customer.



# 2:Pair programming:

Pair Programming means all production software is developed by two people sitting on the same machine. The idea behind this practice is that two brains and four eyes are better than one brain and two eyes. You effectively get a continuous code review and quicker response to nagging (constantly telling someone to do something) problems that may stop one person dead in their tracks.
Teams that have used pair programming have found that it improves quality and does not take twice as long because they can work through problems quickly and they stay more focused on the task at hand, thereby creating less code to accomplish the same thing.

# 3:Git Repository Guidelines in Agile Development:

In agile development, Git repositories play a crucial role in version control, collaboration, and continuous integration. Best practices include frequent commits, meaningful commit messages, pull requests, automated testing and deployment, code reviews, and issue tracking. Implement continuous integration by pushing small code changes to an application's Git repository, which allows teams to detect and fix issues earlier in the development process.

##4: Working in batches in Agile:
Working in batches in Agile refers to breaking down work into small, manageable pieces. And completing work in chunks rather than working on a large project all at once. By working in branches agile team can focus their efforts on a specific task. This can help to improve the team's velocity and overall productivity, as well as lead to better quality work, as team members can focus on specific tasks and ensure they are completed to a high standard before moving on to the next set of tasks.

# 5:MVP(Minimum Viable Product):

Origins:
2009: The concept of MVP gained popularity after Eric Ries described it in his book The Lean Startup
Definition:
Eric Ries, defined an MVP as that version of a new product which allows a team to collect the maximum amount of validated learning about customers with the least effort. This validated learning comes in the form of whether your customers will purchase your product. A key premise behind the idea of MVP is that you produce an actual product (which may be no more than a landing page, or a service with an appearance of automation, but which is fully manual behind the scenes) that you can offer to customers and observe their actual behavior with the product or service. Seeing what people do with respect to a product is much more reliable than asking people what they would do.
Expected Benefits:
The primary benefit of an MVP is you can gain an understanding about your customers' interest in your product without fully developing the product. The sooner you can find out whether your product will appeal to customers, the less effort and expense you spend on a product that will not succeed in the market.
Potential Costs:
Proper use of an MVP means that a team may dramatically change a product that they deliver to their customers or abandon the product together based on feedback they receive from their customers. The minimum aspect of MVP encourages teams to do the least amount of work possible to useful feedback (Eric Ries refers to this as validated learning) which helps them avoid working on a product that no one wants.

## 6:TDD and BDD:

Test-Driven Development (TDD) :
Test Driven Development (TDD) is a development technique which focuses more on the implementation of a feature of a software application/product. Mainly it refers to writing a test case that fails because the specified functionality doesn't exist and after that updating the code that can make the test case pass and as a result, we get the feature implemented in the system. It is a development practice in which the developers are involved in it.
Process of TDD :
TDD methodology follows a very simple 6-step process:
      Write a test case: Based on the requirements, write an automated test case.
      Run all the test cases: Run these automated test cases on the currently developed code.
      Develop the code for that test case: If the test case fails, then, write the code to make that test-case work as expected.
      Run test cases again: Run the test cases again and check if all the test cases developed so far are implemented.
      Refactor your code: This is an optional step. However, it's important to refactor your code to make it more readable and reusable.
      Run all the test cases: Run these automated test cases on the currently developed code.
      Repeat steps 1- 5 for new test cases: Repeat the cycle for the other test cases until all the test cases are implemented.

Behavior-Driven Development (BDD) :
Behavior Driven Development (BDD) is a development technique which focuses more on a software application's behavior. Mainly it creates an executable specification that fails because the respective feature doesn't exist, then writes the simplest code that can make the specification pass and as a result, we get the required behavior implemented in the system. It is a team methodology where Developers, Customers, and QAs are involved in it.
Process of BDD :
The process involved in BDD methodology also consists of 6 steps and is very similar to that of TDD.
     Write the behavior of the application: The behavior of an application is written in simple English-like language by the product owner or business analysts or QAs.
     Write the automated scripts: This simple English-like language is then converted into programming tests.
     Implement the functional code: The functional code underlying the behavior is then implemented.
     Write the automated scripts: This simple English-like language is then converted into programming tests.
     Check if the behavior is successful: Run the behavior and see if it is successful. If successful, move to the next behavior otherwise fix the errors in the functional code to achieve the application behavior.
     Refactor or organize code: Refactor or organize your code to make it more readable and reusable.
     Repeat steps 1–5 for new behavior: Repeat the steps to implement more behaviors in your application.

Differences:
  i)TDD Stands for Test Driven Development. BDD Stands for Behavior Driven Development.
  ii)In BDD the participants are Developers, Customers, and QAs. In TDD the participants are developers only.
  iii)In BDD the process starts by writing a scenario as per the expected behavior and in TDD the process starts by writing test cases.
  iv)BDD focuses on the behavior of an application for the end user and TDD focuses on how the functionality is implemented.
  v)In BDD the process starts by writing a scenario as per the expected behavior and in TDD the process starts by writing test cases.
  vi)Test cases are written in a programming language whereas Scenarios are more readable when compared to TDD as they are written in simple English format.
  vii)In BDD collaboration is required between all the stakeholders. In TDD collaboration is required only between the developers.
  viii)Test cases are written in a programming language whereas Scenarios are more readable when compared to TDD as they are written in simple English format.
  ix)BDD's main focus is on system requirements and TDD's main focus is on the unit test.
  x)Some of the tools used for BDD are Cucumber, Dave, JBehave, Spec Flow, Concordia, BeanSpec etc. Some of the tools used are JBehave, JDave, Cucumber, Spec Flow, BeanSpec, FitNesse etc.

# 7: Cloud Native Microservices:

Microservices refers to dividing applications into smaller and loosely coupled units. Microservices are a core component of cloud-native computing. Cloud-native microservices are an architectural approach to building modern, cloud-native applications composed of small, independently deployable services that are loosely coupled and interact through a shared fabric.
Cloud-native applications are designed to run on cloud infrastructure, and they leverage cloud services such as containers, Kubernetes, and serverless computing to provide greater agility, scalability, and reliability.

# 8:Designing for Failure in DevOps:

We must design for failure. We must embrace failure. We must change our thinking, from moving from how to avoid failure to how to identify failure when it happens, and what to do to recover from it. Designing for failure is a critical aspect of DevOps. According to the DevOps philosophy, we must embrace failure, design for failure, identify failure when it happens, and take steps to recover from it.

# 9:Taylorism:

In the context of DevOps, Taylorism has been criticized for its focus on standardization and division of labour, which can lead to working in silos(Working in silos describes a situation when individuals and teams are working on the same objective but don't communicate enough), bottlenecks, and delays. Working in silos can also result in mistakes that can be costly to correct. DevOps, on the other hand, emphasizes collaboration, continuous feedback, and embracing change to push small releases faster, minimize risks, and maximize learning.

I'm the guy who is tired of working in a startup and at the moment I'm thinking to change my life and I want to work remotely in a large, world-class distributed software development company. I've researched information about Docler and I can say that it will be a pleasure to work in your company and to become your next Senior Front End Engineer.

My MSC is not connected with IT, but I'm working in the industry since 2012 and for the first 3 years I was working completely alone (in the tech field), so I can say that I'm a definite easy-learner and always achieve the required goals no matter what. And I hope that my work experience is equivalent to MSC in Computer Science.

During my nearly 8 years of career in the IT industry, I understood that my real passion is the automation of the development process and I believe I will be really useful for your company: I have not only a development experience, but a huge organizational and team management experience also.

I have 5 years of experience in writing modern frontend applications. One of the examples is Trucknet: trucknet.io, app.trucknet.io. If you are looking for an open-source example of my frontend code you can check my discourse-frontend repository on GitHub: https://github.com/Discours/discours-frontend. This is a pet project in Russian which I've abandoned, but it illustrates my passion for code design, automatic development tools, and Component Driven Development.

Clean code is the most important principle for me and I believe that code quality is not about tabs/spaces or indentations of functions. Those problems can be easily fixed by code linters on the CI/CD level. But code quality is the design and organization of the code and the ability to separate code to different isolated business domain scopes.

I have a comprehensive experience in React (using it since 2016) and a little of experience with AngularJS (v1) from 2014 till 2016, but I'm thinking right now about trying Angular (new) and starting my future projects based on this framework.

I'm a CLI fan and I'm using Linux and Mac since I'm 14 years old. Therefore I do most of my work using CLI and I love to develop CLI tools.

I'm a TDD fan and I'm writing all my code in TDD style since 2018. I love to test and I believe that integration tests are the most useful for frontend projects because they test the integration between your code and the frontend library/framework you use, but they do not bring additional time cost. I have a huge experience of using testing-library (https://testing-library.com) by Kent C. Dodds, which brings SSR integration tests for all modern frontend libraries and I'm following Kent to get regular updates from the world of modern frontend testing. E2E tests are also important, of course, but they cost much more, therefore they should be used to test predefined user-behavior scenarios.

I love Webpack and I configured it always manually to have absolute control of the project bundling process. I've used Gulp in the times it was popular. And I honestly can say, that I do not like Babel: I believe that it brings more problems than it is trying to solve and it is too slow for the work it is doing. So I'm using Typescript Compiler as a transpiler for all my frontend projects. But I am familiar with Babel in case it will be handy).

Additionally, I have a comprehensive NodeJS experience (on my current occupation I'm am responsible both for frontend and backend projects), React Native, Typescript (I really love it with strict config), NoSQL (MongoDB), SQL (PostgreSQL) and GraphQL.







------------------------\\


First of all, I’ve passed a lot of tests recently, but your test is my favorite one. It is a unique mix of good development questions and code practice challenges. The 90 minutes time frame is perfect too: an attendee is not such tired or bored, as on a 4 hours test.

The questions (1 - 18) were great. The only question description of which did not give me enough confidence is question number 14 (if I remember correctly). It is a question about calculating Fibonacci numbers from an array of numbers. I believe, that the description of the task should specify if the Fibonacci function is async or not.

If it is async, then you can use `for..of loop` or `.map()` with a callback function, for example:

```typescript

const fibonacci = async () {}
const arr = [1,2,3];
for (const n of arr) {
void fibonacci(n); // Will run in parallel
}
```

On the other hand, if I write Fibonacci function implementation, I should make it synchronous. There is no IO, only mathematics to implement. That is why I expected the Fibonacci function to be synchronous and this is why I’ve chosen “WebWorkers” only (this is the only way to parallel synchronous code in modern ECMAScript running in a browser).

But to help future attendees it is better to explicitly specify the synchronous or asynchronous nature of the function, in my opinion.


There is another issue: the time. To do time management properly it is important to understand the scope of all the tasks together. When I’ve started the test, I’ve started from the quiz section (I have read, that I better start with the code challenge, but from the index page it was not obvious enough where it is). And because I spent too much time on questions, I did not have enough time to finish the last code challenge (I had to have just two more minutes to solve it, I was absolutely close to the answer). So I believe it is better for attendees to make task number 19 the first one, task number 20 the second one, and the quiz after them. So everybody will start from the hardest. It is better to specify, that you will need no more than 30 minutes to do the quiz, so the attendee will be able to make the time management correctly.

[...]
P.S. This is my final question result three minutes after time run out:
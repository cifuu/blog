### Dec 2020
---
#### [Node, Express Testing: Jest + Supertest](/blog/node-express-jest-testing)
##### [@admin](/whoami)
###### Sep 19, 2020 12:13PM
###### [#react]() [#express]() [#jest]() [#supertest]()
With a multitude of testing framework available for JavaScript and Node.js in specific, it can quickly become overwhelming. For the seasoned, the choices usually narrows down to [Mocha](https://mochajs.org/) paired with assertion library like [Chai](https://www.chaijs.com/). Although Mocha can also be used for testing on the browser side, I have found having a uniform test framework across the Node.js and browser (React) environment to be more rewarding, and there’s no other choice that can rival [Jest](https://jestjs.io/). The beauty of Jest is the out-of-the-box support on React and zero configuration almost elsewhere
[Read more](/blog/node-express-jest-testing.md)

#### [React Hooks I: An In-depth Look](/blog/10002)
##### [@admin](/whoami)
###### Sep 19, 2020 12:13PM
###### [#react]() [#hooks]()
React hooks is a god's sent feature that was introduced in React 16.8. In old days, if your component did not handle any local state, then you would normally write it as a stateless functional component. Simple and elegant. Now the problem came if you decided to introduce state to the said component. You would need to refactor your functional component to a class based component to enjoy the state & the lifecycles. Now with the Hook API, you can easily use state, introduce side effects and so much more. React provides a handful of hooks, but the most widely used are:-
[Read more](/blog/10002)

#### [Server-less emailing](/blog/serverless-emailing)
##### [@admin](/whoami)
###### Dec 15, 2020 10:13PM
###### [#react]() [#email]() [#serverless]()
Can you really send an email from Javascript (React) without a backend server? Well, you could.. sort of. In my quest of building a [server-less]() blog, I went looking
for a mailing solution that didn't require a server setup. What I found was [emailjs](https://www.emailjs.com/).
[Read more](/blog/serverless-emailing)

### Nov 2020
---
#### [React Testing: Mocking axios with axios-mock-adapter](/blog/10003)
##### [@admin](/whoami)
###### Nov 30, 2020 11:13PM
###### [#react]() [#axios]() [#axios-mock-adapter]()
Unless you fancy the built-in `fetch` API, chances are that you are using or have used axios as your HTTP client. If so, when writing tests you may need to mock API requests. You could of course use mock functions provided by your test library in this case Jest, but I have found a nifty package called `axios-mock-adapter` to be excellent and natural when testing codes with axios implementation.
[Read more](/blog/10003)

#### [Node: Testing with Jest](http://github.com)
##### [@admin](/about)
###### Nov 30, 2020 12:13PM
###### [#react]() [#Hooks](react-hoos.com)
We’ve often had to maintain components that started out simple but grew into an unmanageable mess of stateful logic and side effects. Each *lifecycle* method often contains a mix of unrelated logic. For example, components might perform some data fetching in `componentDidMount` and `componentDidUpdate`. However, the same `componentDidMount` method might also contain some unrelated logic that sets up event listeners, with cleanup performed in `componentWillUnmount`. Mutually related code that changes together gets split apart, but completely unrelated code ends up combined in a.
[Read more](/blog/10004)

### Oct 2020
---
## [Lo-fi Beats compilation](/blog/10005)
###### Some beats to chill to as you code.
###### [@admin](/whoami)
###### Oct 10, 2020 9:50PM
###### [#music]() [#lofi]()
So, some days back I went looking for the best Low Fidelify sounds aka *Lo-fi* beats. (I am lover of lofi, if can't tell already and do enjoy them especially 
when coding). Fist, I wanted to know more about their origin and was suprised that they go way back to 50's. I will not bother you will all the history, but 
here is a nice [entry in Wikipedia](https://en.wikipedia.org/wiki/Lo-fi_music) you can read. I didn't know Lo-fi is a *music quality* in which
[Read more](/blog/10005)

### Very Old
---
## [JavaFX Multi-screen Manager](/blog/javafx-multiscreen-framework)
###### [@admin](/whoami)
###### Oct 10, 2016 9:50PM
###### [#java]() [#javafx]()
Long, long time ago while working with JavaFX, I decided to create a small framework/library to managing multiple screens or views (.fxml files). Here is my effort, 
and although
[Read more](/blog/javafx-multiscreen-framework)

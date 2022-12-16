 my answers for frontend [questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/main/src/questions/general-questions.md)
 
 ## General questions

- **What did you learn yesterday/this week?**

Well I learned how to write an e2e test with a playwright for my npm pet project. And configure the ci testing process with github actions. Last month I tried a new library for charts for my main job project.

- **What excites or interests you about coding?**

I really like frontend and developing interesting and convenient interfaces, adding some animation and transition effects to interfaces. I am also interesting in optimization and tools for developing processes, making utils, scripts etc.

- **What is a recent technical challenge you experienced and how did you solve it?**

Our team update kit component and we face to necessity of updating project dependencies main and transitive, we have to solve a lot of error related to new version of **node js** and **babel**

- **When building a new web site or maintaining one, can you explain some techniques you have used to increase performance?**
- configure cache
- optimize images (use webp)
- optimize bundles and loading (bundle splitting)
- lazy load for lists
- server pagination
- ` `**Can you describe some SEO best practices or techniques you have used lately?**
- use og tags
- feature substantial content
- alt text for images
- enable mobile version
- enable fast load times
- use https
- **Can you explain any common techniques or recent issues solved in regards to front-end security?**

We parse html tags in our custom wysiwyg editor for secure app against Cross-Site Scripting XSS. Checking vulnerabilities in used libraries. Use https.

- **What actions have you personally taken on recent projects to increase maintainability of your code?**

Refactoring huge components, using hooks, react context.

- **Talk about your preferred development environment.**

VS code, only.

- **Which version control systems are you familiar with?**

git, git only

- **Can you describe your workflow when you create a web page?**

Start with a boilerplate, which exists in my company or my own. Repo with base webpack, react config. After building, routing and publishing I deal with base routing.

- **If you have 5 different stylesheets, how would you best integrate them into the site?**

It could be integrated by webpack import. Or using **link** tag in html head

- **Can you describe the difference between progressive enhancement and graceful degradation?**

Progressive enhancement, an approach to design web application, sets the motion vector html -> css -> js (step by step) and in every steps app could be used by the user. Progressive enhancement insists on the importance of content.

- **How would you optimize a website's assets/resources?**
- Optimize images with compression services, optimize svg. 
- use cdn 
- use cache
- **How many resources will a browser download from a given domain at a time?**

For chrome 10 files.

- **Name 3 ways to decrease page load**

For perceived cases could be used loadable components (skeletons), before images will be loaded.

- **If you jumped on a project and they used tabs and you used spaces, what would you do?**

Configure VS code to tabs.

- **Describe how you would create a simple slideshow page.**

Use library

- **If you could master one technology this year, what would it be?**

Node js,  Playwright or puppeteer. 

- **Explain the importance of standards and standards bodies.**

Standards provide solutions and best practices that make user experience more comfortable and safe. 

- **What is Flash of Unstyled Content? How do you avoid FOUC?**

**FOUC** - is transition of interface after first load (if cache enable) in case of loading images fonts. To reduce its limit using fonts, optimize it and set a similar font to css font rule to reduce trembling. Defer scripts.

` `*font: italic 1.2em "Fira Sans", serif;* 

- **Explain what ARIA and screenreaders are, and how to make a website accessible.**

Screenreaders help disabled people interact with interfaces. Usually it’s additional software, that can parse markdown and special fields as aria, and pronounce result to user. Accessible suggest approaches for developing interfaces mor friendly for vision disabled persons. Font size, color, proper html, access form keyboard also important.

- **Explain some of the pros and cons for CSS animations versus JavaScript animations.**

Css animation hase easyer api, fit for simple transition. Js used  for more complex animation. It more gives control. Js animation has a powerful native api as requestanimationframe and plenty of libraries such as green sock, anime js  and for react - React Transition Group, React Spring, React motion.

- **What does CORS stand for and what issue does it address?**
**
`	`Cross-Origin Resource Sharing ([CORS](https://developer.mozilla.org/en-US/docs/Glossary/CORS)) is an [HTTP](https://developer.mozilla.org/en-US/docs/Glossary/HTTP)-header based mechanism that allows a server to indicate any [origins](https://developer.mozilla.org/en-US/docs/Glossary/Origin) (domain, scheme, or port) other than its own from which a browser should permit loading resources. It helps to avoid access from third part sites to server data and predict DDOS attacks

- **How did you handle a disagreement with your boss or your collaborator?**

I discuss it at a retro meeting and we find a compromise. If it is important for project growth and development I will insist on my suggestion and try to put it in our sprint schedule. 

- **What resources do you use to learn about the latest in front end development and design?**
**
`	 `I listen to web standards podcasts, read dev.to, medium, and watch conferences. 

- **What skills are needed to be a good front-end developer?**

A lot actually. Basic fontend skills as HTML CSS, and form js to modern framework, browsers api, web technology and protocols, have an idea about design and server part of web app. Love to learn and like to deal with new things.

- **What role do you see yourself in?**

`	`Now I’m satisfied with the developer role, further maybe teamled.

- **Explain the difference between cookies, session storage, and local storage?**

Cookies are used to exchange information with the server and send to it with every request, local storage and session is stored on the user device. Local storage persists data between sessions (browser tabs  in this case), and it keeps data longer.






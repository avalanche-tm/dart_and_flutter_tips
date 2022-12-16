# Dart and Flutter tips, tricks and guides

## General tips for developers

### Keep it simple and stupid - The Golden Rule

- Do not overcomplicate things, simplest solution to a problem is the best solution in most cases.
- If solution to a problem seems to get more complicated over time, you probably need to break it down into more simpler parts and then compose them together.
- Get familiar with all the features of your programming language, especially the new ones

### Improving and continous learning

- Software development is a craft that keeps evolving each day. It is software engineer's responsibility to periodically check for new features of programming language, framework and tools.
- Good software engineer will continously try to improve productivity by exploring new features of language, third-party packages, frameworks or tools.
- The worst thing software engingeer can do is get too comfortable with current level of knowledge, stop learning new things and being stuck with ideas, tools or frameworks that by this time might be outdated or obsolete. Things move very fast these days.
- Good software engineer is not afraid of changes or learning new things.

### Keeping up with with trends and technology

- The easiest way to stay in touch with the current technology is to subscribe to good quality YouTube channels like [Fireship](https://www.youtube.com/c/fireship). Depending on programming language and framework, you should also discover and subscribe to similar channels that cover your topic.
- Twitter is another good source of information. Many high profile developers use Twitter to post their ideas, tips and tricks. Here are some Dart/Flutter related accounts: @SandroMaglione, @remi_rousselet, @filiphracek, @FlutterComm, @dart_lang, @FlutterDev, @biz84. If something new happens in the community, you'll get a notification.
- You don't have to check it every day, but once per week would be a good start.

### Getting your questions answered

- StackOverflow, maybe someone already solved it. Don't forget to check dates and responses from the other people, sometimes accepted answer is outdated or there is a better solution down in the comments.
- One of the most underrated source of information is project's Github repo. Always check for project's Github or GitLab repo! The chances are project has issues section where people might have posted similar issues to yours and had them solved. If you can't find a use case that applies to your situation, check project's repo for folders like "examples". Chances are you might find your use case there.
- Ask your senior developer, if you have any. Don't bother seniors if you can easily find answer on StackOverflow first. It's ok to ask senior for advice if you have doubts about the quality of the code.
- If you weren't able to get answers from any of the sources above, you can open issue on project's Github page. Sometimes it turns out you have discovered a bug! Yes, third party libaries often have bugs, and it's up to us, ordinary developers to report them. Make sure your question is clear, on point and minimal code for reproduction is attached. Also keep in mind you are using someone's code free of charge, so be polite and constructive. It is not their responsibility or full-time job to solve your problem.
- When working with specific technology, check for their Discord or Slack channel. Can't find answer to your problem on StackOverflow? Just post a question in appropriate channel on Discord or Slack.

### Writer's block

- Sooner or later you'll find yourself in situation where you can't solve a task just because your brain isn't working. You might be tired or just isn't your day. The important thing is to take breaks during development. If you realize you got stuck or blocked, take a break. Walk, have some food, stare through window, do anything to relax your brain. Just don't play any competitive games that require extra attention from your brain. When you come back chances are you'll see solution straight away. Don't push yourself by staring into the screen because most likely you won't unblock until you take a break. All the time you spend staring into the screen will be wasted and you'll just get tired and frustrated even more.
- Good developer will identify this problem early and take a break to save time
- It is recommended to take 5-10 min break after every 60 min of work, or anything close to this. It's not an exact science but having some breaks is still beter than having none.
- Do not underestimate this advice!

### Filtering information

- There is a lot of information on the Internet and it all varies in the quality. You should always look for the best quality information. Reliable sources like official websites and API documentations should always be your starting point. Documentations are often versioned so make sure you are looking at the right version.
- Pay attention to dates and versions
- If third party library you are using doesn't have homepage or API docs online, it most probably have them in Readme file on their Github page.
- Be careful when getting your information from random YouTube videos. Literally anyone can post anything on YouTube and give you an impression they know what they are doing. If you are not a senior developer stick to official sources.
- Video material can often be outdated which is another reason to stick with written official documentation
- Always opt for written sources first as watching videos is more time consuming
- Always opt for official sources first

### Third-party libraries

- "Reinventing the wheel" is something you usually don't wanna do.
- Before implementing solution yourself, look for existing open source libraries
- There are situations where using third-party library is almost a no brainer, for example, payments with Stripe, Github integration, Firebase, etc. In one word, anything that is associated or backed up by big or well known company like Microsoft, Apple, Google, etc. Another case when you can trust the library is when the author is well known and established developer in the community. For example in Dart and Flutter community that would be Felix Angelov, Filip Hracek, Remi Rousselot, Sandro Maglione and Andrea Bizzotto.
- When using other third pary libraries always make a good research before just blindly installing them into your project. Are they still relevant, is there a better solution, developer satisfaction, number of Github issues in their repo, reliability, when was the last version released, how often they fix bugs, which platforms are covered. Those things can tell you a difference between stable reliable project and dead or badly implemented one. You don't want to introduce those kind of dependencies into your project!
- Don't be shy to peek inside code of the library, especially if you are a senior developer. If you get feeling like, "I could code this better" or "This code looks bad" you are probably right and maybe you shouldn't use it. Just because someone published a library doesn't mean code is good.
- You might not want to introduce third party library to your project when:
  - implementation is so simple you can literally code it yourself in under minute or so
  - library needs to be modified to fit your case
  - library is doing more than you need
  - has bad or no documentation at all
  - has a lot of Github issues that are not being taken care of
  - has PR's that are not being reviewed or merged for a long time

### Typing and productivity

- As developers we tend to use our keyboard a lot. Or do we? If you find yourself using mouse more than keyboard you might want to do the opposite as it will boost your productivity. A lot!
- If something can be done by using the keyboard, leave the mouse alone. Hitting keys is almost always faster than reaching for mouse and clicking around.
- Learn keyboard shortcuts of your operating system to get more productive. Good developer should be able to open browser, switch tabs, open file explorer or terminal, switch between screens and apps just by using keyboard. If you are still doing those things with mouse you should really learn the keyboard shortcuts.
- Learn keyboard shortcuts of your IDE. Mouse usage in your IDE should be down to minimal.
- It is true that most of the time you spend developing comes down to thinking and researching things on Internet. The third thing that comes on the list is typing. Make sure you can type confidently with accuracy and solid speed. Practice typing on sites like https://www.keybr.com/ whenever you have nothing better to do. Sometimes your speed and accuracy will drop with time, so make sure you practice sometimes.
- Make sure your finger positioning on keyboard is [correct](https://www.computerhope.com/issues/ch001346.htm#:~:text=Your%20left%2Dhand%20fingers%20should,lightly%20touching%20the%20spacebar%20key.)
- You should be able to type without looking at the keyboard.
- Old habits can be hard to change, so make sure you pause for a second every time you feel your fingers are not in correct position or you start looking at the keyboard and start again. Don't give up as it might take weeks before you get comfortable.
- As you start using keyboard more you'll start noticing some keyboards fit you more than other. At that point it might be a good idea to invest into a mechanical keyboard as it allows you to type faster.

### Templating and code reusability

- If you find yourself writting same code over and over, it might be a good time to create a library or a snippet.
- Consider publishing your library to open source repo
- If you have some workflows that repeat very often you should automate or script them. It could save you a lot of time.
- Don't waste your time automating things that gonna be one time or two time things.
- Check out [mason](https://github.com/felangel/mason) for code block reusability
- Create project templates when you have well established workflow and enough projects to make time you've spent on creating templates pay off. Otherwise, just c/p stuff from one project to another as needed.
- Maintaining templates might not be worth it if your tech stack is evolving very fast. Templating is recommended for tech stack that is in stable version and doesn't get breaking changes every month.

### Mentality

- Open up your eye for details
- Always be eager to learn, don't get lazy
- Always prefer quality over quantitiy if not constrained by deadlines
- Listen to advice, don't be stubborn
- Do research before you make a claim
- Don't repeat what other devs say, create your own opinion based on facts, research and experience
- To become a good developer you'll have to sacrifice some of your free time
- Be polite to other developers and non technical staff

### Other tips

- Get familiar with your IDE. If you are using VSCode (recommended) which is very flexible and extensible IDE, learn how to customize settings, themes and discover extensions that might help you with your workflow.
- Learn how to use terminal and its basic commands. Some operations can be completed much faster through terminal than GUI. If you are on Windows, activate [WSL](https://learn.microsoft.com/en-us/windows/wsl/about).
- Learn how to issue basic git commands in terminal, don't be dependent on GUI tools
- Sitting in front of the screen for a long time can make your eyes dry and iritated. Make sure you take pauses and look into distance for a while.
- Blue light from the screen can make you fall asleep harder. If you experience this issue, activate "night light" option in your OS.
- Get a good sleep whenever you can
- Don't forget to have fun or do some physical activity in your free time

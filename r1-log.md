# #100DaysOfCode Log - Round 1 - Osamu Morozumi

The log of my #100DaysOfCode challenge. Started on [October 1, Monday 2018].

## Log

### R1D1 
Joined the 100 days of code challenge.  Finished styling my react markdown previewer and deployed it to Github pages.  Now updating log using markdown which is a little ironic.

This seems an appropriate place to state some goals and reasoning behind joining this challenge:

1. I have a goal to start freelance developing by the end of the year (31/12/2018).  I think this challenge will help me progress mmore quickly towards this goal.
2. I feel my progress has slowed somewhat since starting full time work so I want to give my motivation a boost.
3. I enjoy seeing people's posts and progress on twitter and I'd like to join in properly rather than be an observer.

### R1D2
Worked through the redux tutorial on free code camp in the morning.  Continued this at night.  Also added a new video to my wife's website and made a mock-up of the drum-machine project for free code camp.

### R1D3
I got up early and started my drum machine app on codepen.  I'm thinking I'll use a map function to create the pads.  In the afternoon I reworked a checkio algorithm: [navigation.js](https://github.com/ozmos/javascript-algorithms/blob/master/checkio/escher/navigation.js) based on someone's recommendation.  Discovered a new javaScript maths function: `Math.abs` which can be used to get the difference between 2 integers, previously I had made my own function to do this simple operation.

Tried out a new git command: `git stash` which didn't go so well.  I'll need to do a proper git tutorial at some point to learn the more intricate workings of git.

### R1D4
Tried working on my drum machine on codepen.  I managed to render the keys based on a mapped array but got very stuck and frustrated trying to find a website to load sounds off directly.  Ended up posting for help on the fcc forum.  Really didn't get much coding done at all, just googling around.  Really hope someone points me in the right direction on fcc.  Pretty angry right now.

### R1D5
Today I got a bit side tracked and thought I'd give codewars a whirl.  I used to think I was pretty good at solving algorithms but then I got stuck on a 6th kyu algo.  Just couldn't think of a way to preserve the white space! I think I know the answer now.  I'll use a replace function that replaces any whitespace character **After** any other whitespace character with an empty string.  Anyway I feel a bit guilty because I'd have better spent my time working on my drum machine. 

### R1D6
Got up early and solved the codewars algorithm.  Can't remember how I did it now.  I now have a partially working drum machine.  It updates state, displays the right message and plays audio if the mouse is clicked in the right place.  I just need to add the keypress event listener.  I have a feeling this will be challenging.  I originally had the onclick button manipulating the DOM directly instead of using state to play the right audio.  I've changed it now to follow correct React practices.

### R1D7
**One week in!!!** Today worked on my drum machine.  It now has keypress functionality, however it is failing 1 of 7 performance tests.  I will put it on the forum and see if I get any  useful suggestions. I had some trouble separating the `playAudio` from the `handleClick` and `handleKeyPress` methods.  Mostly because I forgot to use the `this` keyword!!

I also edited my portfolio page.  I noticed that the animations are not performing well on the hosted page.  Is this because of a lack of caching?? It definitely performs better as a static page.  Will have to look into this.

### R1D8
This morning started a coding puzzle for codewars.  This one is pretty tricky.  It asks you to join a string which has been broken up at uneven parts.  I have the function working for a one line string.  I now need to make it work for multiple lines.  I also applied for a couple of developer positions in Perth.

### R1D9
Continued working on the fullScan (hand held scanner) algorithm I started on yesterday.  Getting it to work with multiple lines was not as easy I thought it would be.  I need more practice working with nested arrays.  One thing that got me stuck was the ternary operator in my regex function.  The order of operations is just as important in logic as it is in arithmetic!!

### R1D10
Continued work on drum machine project.  Having difficulty targeting the child component for id.  Will keep trying.

### R1D11
Still trying to get drum machine to pass performance tests.

### R1D12
**Finally got the drum machine to pass performance tests!!!** I need to learn about propagation and bubbling in regard to DOM event listeners.  It seems because I hadn't initialized the event listener with a second argument of false to prevent default behaviour, there were `keydown` event listeners in all components! I think that's how it works.  Anyway, now I need to make a drum machine in a local development environment.  I also did a codewars algorithm today called 'Persistent bugger'.  I used recursion for this one and learned how to implement a count in recursive functions.  It took less than 25mins to complete!

### R1D13
Today went over some of the redux tutorial in **Freecodecamp**.  I want to incorporate this technology when I rebuild my drum machine with `create-react-app`.  Also did some **Enki** exercises this morning in the physio office.

### R1D14
Finished the redux tutorial on free code camp taking notes.  Also went through a nice beginners tutorial on youtube to reinforce the basic concepts.  Tutorial on [https://youtu.be/wZVzeob4ywc](https://youtu.be/wZVzeob4ywc).

### R1D15
Started the React Redux tutorial on free code camp.  I'm glad I build my first two apps as React only so I could familiarise myself with the React development process.  Redux adds yet another layer of complexity which is probably only necessary to employ for apps with complex state.

### R1D16
This morning I did an easy algorithm on codewars and started a more difficult one.  In the afternoon I finished the React/Redux tutorial on FreeCodeCamp.

### R1D17
Today I did the advanced pig latin algorithm on codewars.  I've done an algorithm like this one for freeCodeCamp a while ago but I did it quite differently if I remember.  I need to brush up on my vim skills again.  

### R1D18
Today going through another `react-redux` tutorial on youtube.  Taking a little while as I'm coding along and taking notes.  It is useful as he shows how to set up the file structure and what modules to import.

### R1D19
Worked through a bit more of the `react-redux` tutorial this morning.  In the evening too tired after nearly 13 hours of hard labor so started another codewars algo.

### R1D20
I attended our monthly free code camp meetup today.  I always value these meetings as I get the opportunity to discuss programming and web technology with like minded people from diverse backgrounds.  Today there were some new faces which is encouraging. There is talk of building a website for the local group together which is exciting.  

In the evening I finished part 3 of the `react-redux` tutorial and started work on rebuilding my drum-machine in the local environment.

### R1D21
Today I worked on rebuilding my React drum machine with `create-react-app`.  It plays drum sounds now with both mouse clicks and the keyboard.  The next step is to build the display panel and have it display a description of each sound as it plays.  I also did a little bit of work on a new codewars algorithm: hex converter.  

### R1D22
This morning I completed the *RGB to hex* challenge on codewars.  It used fairly simple maths and a bit of tricky logic.  In the afternoon I continued work on my drum-machine.  I am now at the point where I need to move the state and methods into the redux store.  It is proving a bit difficult.

### R1D23
This morning I wrestled with `mapDispatchToProps` in my react-redux drumkit.  I found the problem this evening and it was all due to a missing closing `}`. At least `mapStateToProps` is working and the UI displays the default message.  Now I need to get the message to update on clicking.  

### R1D24
Today I got a working drum-machine with `react-redux`.  It updates the display on both click and keyboard events.  I mapped the keys and sound clips together as an object (using a for loop not `map`) and used that to access the message on the keyboard events.  I also passed that object down as props then extracted the arrays separately so they could be mapped to each component. I feel like I had a good coding day with some victories. 

### R1D25
Today I got beaten by a regex algorithm on codewars.  I can pass 17 out of 18 tests.  The problem is it doesn't supply the test that I'm failing so I have no idea what to test for.  Going to put this one aside for a while.  It may come to me later.

### R1D26
This morning I continued work on my drum machine.  I've imported a new kit and now have to create a function to switch to it.  In the afternoon I passed the regex algorithm I was stuck on yesterday.  This was after some encouragement from fellow coders on twitter.  The power of the internet.

### R1D27
I have a partially working toggle button to change kits.  Now need to modify it so it actually toggles.
 
### R1D28

I got a bit distracted today playing a new mobile game.  I did manage to fix the toggle button and add 2 more sound banks.  I also started styling the app.  I think I'll need to use `CSS` files instead of inline code so i can target id's.

### R1D29

This morning read a bit about CSS modules.  I decided to style my drum machine with plain css. I figure one new technology per app is enough.  This evening started styling the app.  I noticed that using plain css the styles are global so I'll need to be a bit careful with className delegation.

### R1D30
Today I continued styling my drum machine.  I introduced four color schemes which change when a new drum kit is toggled.  Also read a bit about the fetch API.

### R1D31
This morning I continued styling my drum machine. In the evening attempted a codewars algorithm.  Got close but needs more work.

### R1D32
I had to work in the evening so I only got half an hour in this morning.  I finished the codewars algo I was doing yesterday and did a little bit of styling on my drum machine.

### R1D33
This morning I continued styling my drum machine.  This evening started a codewars algorithm.  This one is a cracker.

###R1D34
Today I got the drum machine to a point where I could deploy a production build.  It's still a draft but I have achieved the main functionalities I wanted including:
-multiple drum kits
-changing color and font schemes

I also completed the _codewars_ challenge I started last night.  I was close, just needed to tweak it a bit.

###R1D35
I fixed up some style bugs in my drum machine and started work on the calculator.  I now have a basic view of the calculator and a function to evaluate the string mathematically.

###R1D36
I continued work on my calculator.  It should be passing 13 of the tests now.  Just need to add a few more features to get it passing all tests.  

###R1D37
My calculator now passes all tests!!  I styled it quickly and handed it in.  One more front end project to go!!!

###R1D38
I started work on the pomodoro clock today.  I had to google around a bit to see how to use the set interval method as I'm pretty unfamiliar with it.  I found a simple count down function which I should be able to adapt for my own use.  Moving it to react should be fun.

###R1D39
Not much to report today.  Kept working on my pomodoro, following a tutorial to set up a basic countdown timer.

###R1D40
Still struggling with the pomodoro timer.

###R1D41
Had a small breakthrough with the pomodoro timer this morning.  Attended the monthly meetup which was enjoyable.  While there compared algorithms and made some small modifications to my roman numeral converter.  Scaffolded my pomodoro project with `create-react-app`.  Now off to bed.

###R1D42
This morning I did a codewars algorithm to wrap all odd numbered digits in dashes.  I also worked on my pomodoro project and now have the basic user interface without interactive elements.

###R1D43
Continued work on pomodoro timer.  Introduced most basic timer functionality. 
####Still to do for this project:
    -enable pause functionality
    -break to start automatically when session finishes
    -adjust session and break lengths with button clicks
    -sound to indicate end of session and break

###R1D44
Continued work on pomodoro timer.  Now have working pause and reset button.  Still need to have break start automatically.

###R1D45
Still working on pomodoro timer.  I think I need to change the basic count down function as there are sometimes lapses and it fails the performance tests set by FCC.

###R1D46
This morning kept working on pomodoro timer, added functions to adjust session and break time.  In the evening started a codewars algorithm.

###R1D47
Just did a couple of codewars puzzles.

###R1D48
Followed along a tutorial for a React pomodoro.  Have picked up some useful tips.  Will incorporate `moment.js`.  Also picking up some new syntax and development patterns.

###R1D49
I finished the tutorial on the React Pomodoro.  Based on this I introduced `moment.js` which provides a saner way to count time.  Counting down using the simpler method of simply subtracting 1 from the current time every second renders a smoother countdown than the method I was using previously which calculated the difference between the current time and a set time in the future. There is still a delay of one second or so between when the start button is pressed and when the timer starts.  I may need to read more tutorials to see how to fix this.

###R1D50
This morning I kept working on my pomodoro timer, refactoring some of the functions.  In the evening started a codewars algorithm.

###R1D51
Just did some codewars and enki.

###R1D52
More codewars.

###R1D53
Codewars and medium

###R1D54
Just put in a half hour. Codewars and a bit of medium.

###R1D55
Finally continued work on pomodoro.  I need to move the handle click methods into each component as my one stateful component is getting very bloated and hard to read.  Also did a bit of codewars.  Now that I've leveled up to 5th kyu the puzzles are getting really hard.

###R1D56
Today updated my portfolio and did some php on sololearn.

###R1D57
I worked on my pomodoro clock today, fixing some of the functionality and refactoring some of the code to unclutter the top level component.  Feels good to be working on the project again.

###R1D58
Kept working on my pomodoro clock and reading medium.

###R1D59
More pomodoro.  Having trouble with `moment-duration-format`.

###R1D60
Today kept working on the pomodoro timer.  I successfully integrated `moment-duration-format` and altered the increment/decrement functions.  I basically have it working, just need to add the audio bit.

###R1D61
I continued work on pomodoro, getting all tests except for audio to work and also did some sololearn php and read some more of the javascript handbook.

###R1D62
Wrestled a bit with the html5 `audio` element.  I discovered that audio files must be imported into the component file.  Now need to create the function to make the audio play when the timer is complete.

###R1D63
Finished coding my pomodoro!! All styled but something went wrong with the deployment.

###R1D64
Tried various things to get the production build to work.  I have a feeling it has something to do with momentjs.

###R1D65
I posted a help query on FCC forum last night and low and behold this morning there was a helpful reply! Turns out the problem was one line in my `package.json` file.  I had given the incorrect address for the homepage.  So now my pomodoro has been deployed!!  I fixed a niggling bug this afternoon and claimed my front-end libraries certificate.  This is a milestone for me in my codeing journey.  I would like to go deeper into javaScript and React although I would also like to start getting paid as a developer!!  I will learn how to use wordpress and php, with the goal in mind to return to javascript and react and possibly other frameworks.  Today I found a cool `nodejs` based CMS called **apostropheCMS**.  Will keep this CMS in mind for future reference.

###R1D66
I decided to make some improvements to existing `Reactjs` projects, starting with the calculator.  I refactored the components, separating them into different files. I also added some extra functionality.  Currently trying to add a square root function.  I realised there is a lot of duplicate code which I will refactor later.

###R1D67
Today spent a lot of time refactoring the components in my calculator and implementing the square root function.  I learned how to use unicode in javascript strings.  The code looks a lot cleaner now and the buttons on the calculator are more organised.  Also did some php on _sololearn_ in preparation for learning _wordpress_.

###R1D68
Started the day with some `php`, doing a simple algorithm on _codewars_.  I found that `php` has many features in common with `javascript` including `filter` and `reduce` functions as well as a ternary operator.  The syntax differs in many aspects, for example parenthesis are often necessary where they would not be in `javascript`.  Callback functions are placed in quotations which I found quite counter intuitive.  The rest of the day was spent working on my calculator.  I found that a lot of the refactoring I did yesterday was unnecessary as it made styling the buttons with `CSS` grid much more difficult.  I had to put those nice neat components back into the `Inputs` component so all the buttons would be direct children of the container. 

###R1D69
Finished styling my calculator app.  Had some trouble on deployment as most browsers don't recognise look behinds in regular expressions.  Managed to fix the offending function with a work around.  Thank goodness I did all those algorithms!  Later had a bit of trouble with the footer but found a neat way to fix the footer at the bottom without overlapping. Went over some boostrap exercises last night as I'm finding vanilla CSS too time consuming.  Also practised some php.

###R1D70
Did another simple php algorithm in the morning.  Discovered there was a trojan in my firefox cache so spent quite a bit of time googling and testing to get rid of it.  Still need to do another full scan to verify it's gone.
Started a 4th kyu javascript algorithm but got very stuck.  Putting it aside for another time.

###R1D71
Took it pretty easy today.  Went through a few of the D3 exercises on FCC and read some of the documentation.  Finished the sololearn php module.

###R1D72
Fixed a style bug in my pomodoro app, learned how to overlay a tint on a background image and applied it to my pomodoro app.

###R1D73
Continued restyling my pomodoro app in the morning.  Added a separate bell for breaks and played around with fonts and margins.  In the evening went through some more D3 exercises taking notes and had another crack at the 4th kyu algorithm "recover secret string".

###R1D74
This morning had another crack at _recover secret string_.  I think I'm making progress with it.  In the afternoon and evening finished styling my pomodoro app.  

###R1D75
More d3.js and php.

###R1D76
This morning I went through some more php exercises on w3schools. I am noticing quite a few similarities with javaScript:
    -user defined functions look identical
    -for, while and do while loops look identical
    -switch statements also look identical
    -they share some in built functions
In the evening I worked on my portfolio, adding a new project and adding some media breaks for larger screens.

###R1D77
Did some codewars puzzles in the morning then started a WordPress course in the afternoon.  Realised I now need to learn how to set up LAMP stack on my linux machine.

###R1D78
Went through a bit more of the D3.js tutorial on FCC in the morning.  Spent most of the afternoon/evening trying to get the LAMP stack set up.  I think I'm getting closer.

###R1D79
Successfully set up the LAMP stack and installed WordPress!!! The process was a little bit intense but also enjoyable. I'm tempted to take some linux courses and gain some sys-admin skills.  Also reviewed some php lessons and read a great article on medium.

###R1D80
Spent some time this morning trying to solve an algorithm in php.  Will try again tomorrow.  In the evening did a little bit of the wordpress course on udemy and found the commands for starting and stopping the server and mysql.  Also updated the media breaks on my official portfolio.  Contacted a possible lead for paid work.

###R1D81
This morning I think I went through some of the wordpress tutorial, although I can't clearly remember.  I think I spent too much time in the sun today!  This evening did an easy php algorithm and worked on _longestConsecutiveString_ which has been stumping me for a while. Leaned that I could run php scripts in the terminal with a simple command.

###R1D82
Did a bit of wordpress in the morning and reviewed php in the evening.  Updated portfolio at night.

###R1D83
Went through a few more lectures in my wordPress course.  Did a couple of algos on hackerRank.

###R1D84
More wordpress lectures.  Read up a bit about the JAM stack and static site generators.  I've decided to keep learning wordpress as it will allow me to quickly set up client web sites and add dynamic features, as well as allowing the clients to edit content easily themselves.

###R1D85
Did some wordpress lectures and hackerRank algorithm in the morning. Spent the afternoon working on a client's website.

###R1D86
Today learned about php superglobals, array sorting and form handling.

###R1D87
Spent most of the day working on a client's website using WordPress.  Did some of the `D3.js` exercises in free code camp in the evening. 

###R1D88
Finished the d3.js section of free code camp.  Looking forward to the projects.

###R1D89
Very productive day.  Spent about half the day trying to get a contact form to send to an Office 365 email.  In the end set up SMTP with _SendGrid_.  Still waiting back from the client to see if the tests were successful.  Completed the JSON APIs and AJAX section of Free Code Camp.  Now can start the data visualisation projects.  Did a bit of my WordPress course and a bunch of _hackerRank_ algorithms.

###R1D90
Today mostly did wordpress tutorial.  Picked up some good tips about image resizing and how to structure an about page.

###R1D91
Went through navigation and security in WordPress. Made a small start on the bar chart project in FCC.

###R1D92
Did some more tweaks to [antiques.com](https://antiques.com) including some custom html and CSS.  I'm glad I learned how to code before starting WordPress.  Went over some of my notes for `d3.js` and played around with the code in _Visual Studio_.  Figured out how to use modules without webpack or `node.js`.

###R1D93
Continued udemy wordpress course and found some useful command line tools for compressing and resizing large numbers of images.

###R1D94
Spent a lot of time optimizing images, looking for plugins and setting up photo galleries.  Made some progress with _forming a magic square_ challenge on hackerRank

###R1D95
This morning I solved the _forming a magic square_ challenge. Hooray.  Made some more tweaks to [antiques.com](https://antiques.com) and went through some more lectures in my wordpress course.

###R1D96
Today went for a day trip to Mandurah/Pinjarra area with my wife.  It was good to get away from the house and computer for a while.  Still did an hour of code when we got back, going over `d3.js` notes.

###R1D97
Set up hosting for my business website and made a new email address.  Feels good to have a personalised business email.  Got a chart happening in my _bar chart_ project.

###R1D98
Today I finished all lectures in my wordpress course on udemy. Just need to review notes and resources.  Learned about form validation and date functions in php.  Php has some really useful inbuilt date functions.

###R1D99
Spent the afternoon hardening security on my client website.  No actual coding, unless PHP myadmin counts.

###R1D100
Well, I finished the 100 days of code challenge.  Yesterday I read some tutorials and today I made more tweaks to my client website and learnt about the date functions in PHP.

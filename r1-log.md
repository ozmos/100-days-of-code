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

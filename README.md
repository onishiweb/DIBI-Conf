# DIBI 2012

## Seb Lee-Delisle - Design it and Build it

[@sebly](http://twitter.com/#!/seb_ly)

[seb.ly](http://seb.ly)

Combining art and design with code...

*  Projecting things on buildings!
*	Pixel phones!

[CreativeJS.com](http://creativejs.com)

People tend towards specialising in either Coding or Design. The graph dips.

Combining a coder into a designer - a Creative Coder!

**Live coding on a commodore 64 emulator!!** 1 line of code to draw hearts...

**Why combine coder and designer?**

For ideas - A designer coming up with ideas and not knowing how to build it.

### Hybridify yourself!

#### Designers

Learn to code... Like, right now!

Seb showing everyone how to code with canvas and JS, making a square animate and now onto particles...

**Discovery** By doing this you can discover more for yourself.

#### Coders

Play with visual stuff!

Enjoy and understand the creative process

Asteroids - does exactly what it's meant to do... but it's rubbish, "it feels like shit"

Play with things until they feel better, experiment, don't just do what it's meant to do!

Experimenting can lead to good stuff...

### Will people pay for this?

Probably not, but they might in the future, do this for fun and hopefully something will come of it.

Do you always want to be making "other peoples stupid ideas"? (_probably not_)

### Play. Create. Share.

Work on small, fun projects if you can, basically finish the things you start!

## Paul Annett & Tim Paul - The Challenges of designing for everyone

[@nicepaul](http://twitter.com/#!/nicepaul)

[@timpaul](http://twitter.com/#!/timpaul)

Building the new government digital service.

So many different services/transactions to run on one website for the government.

A lot that can be done online already but not all - their job to redo the ones that are already there and digitise the rest.

A wide varience in transactions - low frequence, mandatory.

First draft of [design principles](http://digital.cabinetoffice.gov.uk/2012/04/03/introducing-the-design-principles-alpha-for-gds/) launched last month.

1 in 5 phone calls to government were because of a failed digital transaction!

Save *£1 Billion* a year by fixing the digital transactions!

**1,500 websites closed so far** - working on a single website replacement, prototype was [AlphaGov](http://alpha.gov.uk)

Work now started on the beta: [gov.uk](http://gov.uk) (released in Jan this year)

Taking a deeper look at the design principle:

*	Start with needs: what do people need from the service. Created a prioritised list of services to base the design of gov.uk on based from common searches on the direct gov website.
*	Do less: focusing efforts on what needs to be done - Why focus on things like "How to keep bees"? Gives more time to focus on the important stuff.
* 	Design with Data: establish what people need, then design round that actual data - gathering data from the alpha & beta sites, but also the call centres which are constantly dealing with problems from digital services.
*	Do the hard work to make it simple: it may take more time to make it simpler, lots of process/issues with simple services. No competition with services only offered by gov so the thinking has been "Why try harder"!
*	Iterate. Then iterate again: Releasing the Alpha to get good feedback from quick stints of work! 
*	Build for inclusion: Inclusive design - some people don't have the best access to the internet, some people don't have a home address! Accessibility, don't just tick the boxes! Using ARIA roles on the Beta release. Some people will never have used the internet, "the fold still exists"!!
*	Understand Context: Responsive design is great but it's not enough, context is important - emotional context matters, using video to help.
*	Build digital services, not websites
*	Be consistent, not uniform: can't always rely on rules, need to look deeper and go back to principles rather than using the same pattern over and over.
*	Make things open, it makes things better: That's why the alpha and beta have been openly released already - the community is helping to shape the new government site, all sharable via [github](http://github.com/alphagov) follow [@alphagov](http://twitter.com/alphagov) on twitter

The future is good, the site is being constantly iterated on, and they are still hiring for people to help!!

## Brian LeRoux - Mobile Web Programming is a Bloody Mess!

"Debugging in the shit!"

[@brianleroux](http://twitter.com/#!/brianleroux)

Mobile programming is a messy environment - PhoneGap!

Loads of different languages to work on mobile apps, phone gap was accidently conceived?

To be a native programmer you need to know 8 languages and multiple SDKs... as well as multiple devices etc

Started rolling own jQuery - XUIJS

Offline web apps - storing data is somewhat fragmented:

*  localStorage 
*	webSQL - not a great idea! (deprecated)
*	indexedDB - possible solution, in some browsers, not in phones
*	"IE has it's own Fucking thing of course!

**Apache Cordova** - Phonegap rebranded for Apache

There are lots of webkits! 

### Devices and their capabilities

#### Android

*	Touch events are a lie!
*	CSS performance is awful
*	Transforms can be hardware accelerated but hardly work
*	Only the bleeding edge have SVG
*	Default browser is being dropped, chrome a download

#### iOS

*	localStorage randomly gets dropped
*	position: fixed (fucked) onlt recently implemented

#### Blackberry 6+

*	Scores the best for default browser

#### Windows

*	no touch
*	no localStorage
*	no webSQL
*	FAST SVG and canvas

#### Common 

*	scrolling is dodgy
*	Fixed positioning isn't quite there

**If your doing mobile development, a client is bound to have one of the crappy devices**

### Performance tips

"Your finger does not click" - there are loads of libraries around to solve this problem... (Paul Irish on Github)

"CSS Effects are slow" - your app will be slow!

"PostMessage Hack" - postMessage can be used in modern mobiles today! 

"Production code always has a build step!" - Concatenation, minifying, pre-processors, JSLint

### Debugging

Most people -> alert("Here") now > console.log("here!!")!!

**On Mobile:** 

Test test and test again - unit testing!

QUnit - cool article [here](http://javascriptplayground.com/blog/2012/04/javascript-testing-qunit-1) by [@Jack_Franklin](http://twitter.com/#!/Jack_Franklin)

**Remote debugging**: Web inspector remote (weinre), adobe shadow, chrome remote debugger!

**Weinre** - debugging with remote web inspector, you also get a console! Similar to Paul Irish demo'd at jQuery UK can debug on debug.phonegap.com? (Double check that someone)

"Mobile is a bloody mess" - Help fix it!

_Will update with link to slides later when Brian uploads them!_

## Rob Hawkes - HTML5 Games - Not just for Gamers

[@robhawkes](http://twitter.com/#!/robhawkes)

Notes online soon...

Games are important - their universal, not just computer games...

**Paperboy - Bomberman - Lylat Wars - Sim City - Red Alert**

Games are fun! - Games make use of the topics/subjects that provoke an emotion in us _Fruit Ninja_

Games push boundaries - They deliberately use as much power as possible _Battlefield series_ In 9 years the minimum requirements have exploded!

Games mean a better web - Better features, better performance - the web technologies are being pushed by game development. 

**Play more games!** It helps make the web better!

### New technologies

#### Existing HTML5 games

*  HTML5 Quake II
*	Cut the Rope
* 	Bejeweled
*	Command & Conquer
*	GT Racing (3D tech) - on the Chrome web store!
*	Browser Quest (Mozilla) - (All open source, it's on Github)

#### Canvas

*	2D Graphics platform
*	Image manipulation
*	Silk demo...
*	Drawing curved lines (it's not always the obvious stuff)

#### WebGL

*	3D graphics rendering
*	Uses the Canvas element for output
*	Hello Racer demo - Rome video?
*	Tinker CAD - 3D modelling using Canvas - can be printed using 3D printers :)
*	Google Maps & Nokia WebGL Maps - completely 3D rendering in some cities
*	three.js Mr Doob

#### requestAnimationFrame

*	Managing animation in JS
*	Better than using something like setTimeout...
*	Shim by Paul Irish for cross-browser use

#### HTML5 Audio API

*	Sound effects and background music
*	Audio data API by Firefox & Web Audio API by Chrome devs
*	Audio API is pretty straight forward, wrapper tag and source elements (similar to video) - then access through JS

#### localStorage

*	Store data local to the browser - much larger data than a cookie!
*	Can remove the need for constant connection to the net...

#### WebSockets

*	Real-time communication - data being pushed in and out of the server
*	All in JS

#### Web Workers

*	Background JS
*	Working with large quantities of data in the background and not slowing down the website
*	Similar to WebSockets, all set up in JS, set it up and wait for data to come back...

#### Full Screen API

*	Expand *any* DOM element to full-screen!! 
*	Canvas full screen! BOOM!
*	There is some security around it, full-screen access has to seek permission first (similar to Geolocate)

#### Screen Orientation API

*	Lock orientation on devices from JS 
*	Not in all browsers yet

#### Node.js

*	Game servers...

#### Web Applications

*	An app-like experience... remove the browser chrome!

### Keeping up on latest tech

[Mozilla Wiki](https://wiki.mozilla.org/Platform/AreWeFunYet) (Are we fun yet!) - Info on what's coming up/being done
[Mozilla Are we Mobile yet?](http://arewemobileyet.com/) Boot to Gecko (is awesome by the way!)
[Mozilla general wiki](https://wiki.mozilla.org/Main_Page) - more general info on the latest stuff, road maps etc

Try it: Firefox Aurora or Nightly!

## Paul Boag - Client Centric Web Design

[@boagworld](http://twitter.com/#!/boagworld)

How many of us feel the frustration of clients? There's blogs out there dedicated to it! And a post like Why we gave up client work after 10 years.

We can all associate with the frustrations of working with clients.

The *trendy* solution is to go work on our own projects - client work is just for paying the bills!

Client work shouldn't be the second rate option.

### The principles of client centric web design

*  We provide a service
*	The client must be involved in the process
*	It's about the client, not the user (as much as we might dislike the thought) - sometimes business needs will out-weigh the user needs, we need to find a balance without pissing off the user.

### The benefits

*	It produces better websites
*	It makes for happier clients - they feel engaged
*	Generates repeat business
*	Increased job satisfaction - you're happy when your clients are happy

### What is it?

#### Mutual Respect: it works both ways

Change our attitude to clients - they're not stupid, their knowlesge sits in their business, and we need that knowledge. They know about their users/customers. Ultimately they want a good website as well, their view of what that means is just not necessarily the same as ours...

How do we earn their respect - we are proffessionals, we need to show them we are experts in our field. Confident, not arrogant. Associate yourselves with expertise - show you can demonstrate your knowledge with examples. You can show your expertise through process and past experiences.

Define your roles - you each have your own responsibilites - client finds problems, we find solutions.

#### Good communication

Avoid where possible, misunderstandings...

Clients won't respond well to surprises!

Good communication gives the client the sense of control, if they don't know what's going on they feel it's out of control.

Don't always use digital communication! It can lead to mis-interpretations.

Regular communication. Honest communication - don't hide possible issues.

Make it about more than business... If there's a good relationship it becomes more personal.

Empathy is powerful, get to know what their motivations are, is their job on the line for this project?

#### Education 

Again it works both ways.

We need to understand their business, so we can work to their business needs and justify our motivations for doing things.

Stakeholder interviews - understand the motivations behind everyone who has a stake in the project.

Educate the client - make sure they understand your process. Don't always reject their ideas.

#### Collaboration

Show progress little and often.

Swallow your pride - sometimes the client can have good ideas, don't ignore them because you didn't think of it yourself.

Involve them in the process, don't just take them from requirements to final design.

#### Getting sign off

Don't just send a PDF - send a video explaining the design

Ask the right questions - avoid the "I don't like the green"

#### Dealing with disagreements

Pick your battles.

Ask why? Why don't they like something, again finding the problem not the solution.


## Dan Rubin - All of this has happenend before

[@danrubin](http://twitter.com/#!/danrubin)

### A Rant!

"We don't try hard enough" - We try to do all the stuff we're meant to, but do we try hard enough? There are far too many excuses not to do the things we *should* be doing.

Constraints are good but they become an excuse to lower our targets...

Doing things the "old way" instead of the things that we should be doing - the resistence to change.

Do we afford ourselves enough time to do the right things?

Are we doomed to repeat our mistakes.

### We've seen this before

What are these simple things not being done:

*  Web standards - people still fight this?
*	Accessibility - why is it not taken seriously enough
*	Usability - !!

### Why?

It's how we think:

**De Bono's 6 thinking hats** - Our communication is based on a natural argumentative style - even if we agree "Aggressive disagreement"

Focus on changing the thought process...

### Defining failure

If we are still making mistakes we need to know how to identify the risks and failures.

Embrace failures - becoming a more popular idea - why do we view mistakes as bad things, the language of failure is negative so we naturally take on that negativity.

### It all boils down to language!

*	**Fail vs. Experiment**

*	**Mistake vs. Try**

*	**Poor planning vs. Spontinaity**

**Personal experience - We learn because we make mistakes**

### How do we use what we've learned

**Our responsibility is to know our job better than our clients/bosses** - we need to be the best that we can be at what we do!

It's important to experiment within organisations and take new approaches to things, learn from the experimentation and not continue to do everything the same all the time.

Use mini-projects to try out new work, use them as case studies - it helps introduce new projects, new directions.

We can't solve every problem - we still try though, we just have to be aware that it's not the end of the world if we can't solve it.

Find something to try -> **Try one thing this week!**

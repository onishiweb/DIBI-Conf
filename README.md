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


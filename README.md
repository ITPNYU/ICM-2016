# Intro to Computational Media (Fall 2016)

## Listserv
- [Sign up for the ICM google group](https://groups.google.com/a/itp.nyu.edu/group/icm/)

## p5.js
- This year we are using [p5.js](http://www.p5js.org/), a JavaScript framework for creative coding.  Stay tuned for a link to the web editor.

## Section specific info
* [office hours, scheduling, and contact info](https://github.com/ITPNYU/ICM-2016/blob/master/sections.md)

## Homework Wikis
- TBA

## Videos
- [Kadenze course](https://www.kadenze.com/courses/introduction-to-programming-for-the-visual-arts-with-p5-js/info)
- [Shiffman YouTube playlist](https://www.youtube.com/user/shiffman/playlists?sort=dd&view=50&shelf_id=14)

## Books
- [Make: Getting Started with p5.js: Making Interactive Graphics in JavaScript and Processing](http://amzn.to/1PmztVt) is probably your best bet for now if you are looking for a book.
- If you are interested in some supplemental reading on HTML and CSS, The [HTML & CSS book](http://www.htmlandcssbook.com/) is a nice one.

## Extra Help
- [Research Resident Office Hours](http://itp.nyu.edu/residents/contact-the-residents/)
- ICM Help Session

## Inspirational Projects
- [Help contribute to this wiki!](https://github.com/ITPNYU/ICM-2016/wiki/Projects)

## Resources
- [p5.js reference](http://p5js.org/reference)
* [p5.js forum](http://forum.processing.org/two/)
* [p5.js tutorials](http://p5js.org/tutorials/)
* [Getting Started with p5.js](http://amzn.to/1PmztVt) - O'Reilly book
* [Intro to Visual Programming with p5.js](https://www.kadenze.com/courses/introduction-to-programming-for-the-visual-arts-with-p5-js) - online video tutorials (free with signup)
- There are [many additional resources on the Resources wiki page](https://github.com/ITPNYU/ICM-2016/wiki/Resources).

## Syllabus

### 1 -- Introduction and Drawing
* What is computational media?
  * What is programming?
  * How can I apply programming to _____________?
  * As a ____________, why would I want or need to write software?
  * [Example projects].
* Programming language discussion
  * General discussion of programming languages
  * History of creative coding frameworks
      * Processing and p5.js (and what's processing.js?): [What is p5.js video]
      * openframeworks, cinder
      * max/msp dataflow programming
      * How does arduino fit in?
* p5.js in the context of the browser
  * Landscape of HTML, CSS, and JavaScript
  * Other JS frameworks
  * Server-side vs. client-side
  * What is the difference between p5 and JavaScript?
* Participating in an open-source community
  * What are git and github?
  * When should you post to a forum vs. file a github issue?
  * Who makes these things?
  * [p5.js working group mailing list](http://groups.google.com/forum/#!forum/p5xjs-working-group)
* Getting started, your first program
  * [Download Examples]
  * Drawing with numbers: [video tutorial]
  * Shape and color functions: [video tutorial]
  * `setup()` and `draw()`
  * Downloading p5.js
   * Start by [downloading the p5.js editor](http://p5js.org/download/#editor).
  * [p5.js reference](http://p5js.org/reference)
* [Uploading your sketch]
* <a id="optional-1">Optional viewing / reading:</a>
  * Casey Reas [Eyeo 2012 talk] on Chance Operations
  * [Introductory p5.js videos]
  * [FORM+CODE: Introduction and What is Code?](http://formandcode.com)
  * [As We May Think](http://www.theatlantic.com/magazine/archive/1945/07/as-we-may-think/303881/), Vannevar Bush
  * [Long Live the Web](http://jblomo.github.io/webarch253/slides/Long_Live_the_Web.pdf), Tim Berners-Lee

### 2 -- [Animation]
- Program flow (what's a function?)
  - Setup, draw, and other events
  - Variation: mouseX and mouseY
  - [video tutorial]
- More about variables
  - make your own variables (numbers and strings), [video tutorial]
  - JS objects (variables inside variables), [video tutorial]
- [random()](http://p5js.org/reference/#/p5/random), [video tutorial]
- [map()](http://p5js.org/reference/#/p5/map), [video tutorial]
- [Simple loading and displaying image]
- [Download all examples]


### 3 -- [Interaction]
- Conditional Statements
    - Boolean expressions
    - if statement
    - relational operators
    - [video tutorial]
    - Case study, bouncing ball: [video tutorial]
    - else, else if, and, or [video tutorial]
    - buttons, rollovers, switches [video tutorial]
- Loops (while and for)
    - while and for [video tutorial]
    - nested loops [video tutorial]
- [Download all examples]

### 4 -- [Functions: the basics]
- [Download Examples]
- Calling vs. defining
- Modularity: [video]
- Arguments and parameters
- Re-usability: [video]
- Return types: [video]
- Recursion
- Functions inside objects: [video]
- Optional Readings:
  - [Work of Art in the Age of Mechanical Reproduction](http://www.berk-edu.com/VisualStudies/readingList/06b_benjamin-work%20of%20art%20in%20the%20age%20of%20mechanical%20reproduction.pdf), Walter Benjamin
- Homework: TBA (but something like use a function to draw a design different ways, multiple times.  Make a previous sketch modular.)

### 5 -- [Objects and Arrays]
* [download examples]
* Review object literals:
  * properties - name/value pairs
  * functions inside objects
  * `this` keyword
* What is an array? [video tutorial 6.1]
  * declaring, initi
  * numeric indices
  * arrays and for loops: [video tutorial 6.2]
  * `length` property
* An array of objects! [video tutorial 6.3]
* Constructor function! [video tutorial 6.4]
* Adding and deleting from an array, `push()` and `splice()` [video tutorial. 6.5]
* Multiple JS files [video tutorial 6.6]
* Clicking on objects [video tutorial 6.7]
* Checking objects intersecting with other objects [video tutorial 6.9](), [video tutorial 6.10]
* loading images for objects [video tutorial 6.11]

### 6 -- Synthesis -- **October 2nd, 11am - 2pm**
- **Meet in the ITP Lounge**
- **Bring your Arduino**
- **[All details here]**
- Serial input with a callback workshop
- "One button experience" exercise

### 7 -- [DOM: events and callback function]
- [Download all examples]
- Review events -- mousePressed, keyPressed
- [Tutorial: Beyond the Canvas, using p5.dom](https://github.com/processing/p5.js/wiki/Beyond-the-canvas)
- [Tutorial: Intro to HTML/CSS basics](https://github.com/processing/p5.js/wiki/Intro-to-HTML-and-CSS#css)
- DOM elements - [p5.dom reference](http://p5js.org/reference/#/libraries/p5.dom)
    - `createP()`
    - `createButton()`
    - `createSlider()`
- Callbacks
    - `button.mousePressed(callback);`
- `style()` -- low key intro to CSS
- [CSS Reference](http://www.blooberry.com/indexdot/css/propindex/all.htm)


### 8 -- [Data]
- [Download all examples]
- [Tutorial: loading external data with p5.js](https://github.com/processing/p5.js/wiki/Loading-external-files:-AJAX,-XML,-JSON)
- [Tutorial: more about data and APIs](http://shiffman.github.io/A2Z-F15/week4/notes.html)
- JSON and APIs (and more on callbacks!)
- Word Counting
- Tabular data
- Optional Reading:
  - [Art and the API](http://blog.blprnt.com/blog/blprnt/art-and-the-api), Jer Thorp
  - [The Anxieties of Big Data](http://thenewinquiry.com/essays/the-anxieties-of-big-data/), Kate Crawford

### 9 -- [Video and Sound]
- [Download all examples]
- [p5.sound reference](http://p5js.org/reference/#/libraries/p5.sound)
- [Video/capture: p5.MediaElement reference](http://p5js.org/reference/#/p5.MediaElement)
- Sound
- Live capture
- Movie playback
- Video Assignment

### 10 -- [Mobile]
- [Download all examples]
- Workflow and process, get a previous sketch running on a device
- Touch interaction
- Sensors
- [More mobile examples from Jia](https://github.com/OhJia/p5MobileWebExamples)
- [p5 mobile workflows by Jia](https://github.com/OhJia/p5Mobile/wiki/Workflows)
- [Using the viewport meta tag to control layout on mobile browsers](https://developer.mozilla.org/en-US/docs/Mozilla/Mobile/Viewport_meta_tag)
- [Hammer.js](http://hammerjs.github.io/)
- Homework: Prepare a final project proposal.  See you section's wiki.

### 11 -- Other Topics + Final Project Proposals
- **See your individual section's proposal schedule on your wiki**
- Possible topics
   - more on pixels
   - more on data
   - setTimeout, setInterval
   - WebGL - [tutorial](https://github.com/processing/p5.js/wiki/Getting-started-with-WebGL-in-p5)

### 12 -- Beyond p5.js + Final Project Proposals
- **See your individual section's proposal schedule on your wiki**
- Life beyond p5.js
  - Take ICM into the spring semester courses
  - Other JS libraries?
  - Coding outside the p5 IDE? ([local server tutorial](https://github.com/processing/p5.js/wiki/Local-server))
  - [local server tutorial](https://github.com/lmccart/itp-creative-js/wiki/SimpleHTTPServer)
  - [More HTML/CSS](https://github.com/processing/p5.js/wiki/Intro-to-HTML-and-CSS)
  - What is server side programming for?
  - [Processing](http://processing.org)
  - Open source
    - How do artists make and adapt tools for themselves and their communities, like Processing, p5.js, openFrameworks, etc?
  - How do you  get involved with this?

### 13 -- One on one speed user testing / feedback
- This week you will "user test" your project with fellow classmates. You must have some implementation that you can test completed by this time.  User testing can mean different things for different projects. For a game, it can mean that the user tries to play it. For an art piece, it could mean showing it to a classmate and asking for them to say what they think it is about or how it made them feel. We'll show projects in a "one on one" / round robin / speed dating-style session. 5 minutes then switch. You cannot not explain your project, just show and let the user try it and give you feedback. Then you can answer questions.  User testing schedule will be provided on a wiki.

### 14 -- Final Project Presentations
- Please add your link to your final project documentation on your section's wiki.


# Policies

##Evaluation

Grades will be determined according to the following breakdown:
* Regular Assignments 40%
* Participation and Attendance 40%
* Final Project 20%

Please see ITP's statement on [Pass/Fail](http://help.itp.nyu.edu/academic-policies/pass-fail) which states that a "Pass" is equivalent to an "A" or a "B" while anything less would be considered a "Fail".

We will have weekly assignments that are relevant to material from the previous class. These assignments are required and you should be prepared to show/talk about them in class. It is expected that everyone in the class will create and maintain a blog for their assignments.

Attendance is mandatory. Please inform your teacher via email if you are going to miss a class. Two unexcused absences is cause for failing the class. (An unexcused lateness of 10 minutes or more is equivalent to 1/2 an absence.)

This class will be participatory, you are expected to participate in discussions and give feedback to other students both in class and participate with their projects. This (along with attendance) is 40% of your grade.

Class will culminate with final projects. You are expected to push your abilities to produce something that utilizes what you have learned in the class that is useful in some manner to yourself or the world. This will comprise 20% of your grade.


Mantras By James
----------------
- "Practice is the best of all instructors." - computation requires practice
- "An agreeable companion on a journey is as good as a carriage." - look to your classmates for help too
- "While we stop to think, we often miss our opportunity." - sometimes you need to take a leap of faith
- "When two do the same thing, it is not the same thing after all." - encourage students with similar ideas
- "The bow too tensely strung is easily broken." - don't get too stressed out
- All of these are from Plubius Syrus.(42 B.C.)

Previous Years
--------------
- [Old 2015 Syllabi and links](https://github.com/ITPNYU/ICM-2015/)
- [Old 2014 Syllabi and links](https://github.com/ITPNYU/ICM-2014/)
- [Old 2013 Syllabi and links](https://github.com/ITPNYU/ICM-2013/)
- [Old 2012 Syllabi and links](http://itp.nyu.edu/varwiki/Syllabus/ICM-All-F12)
- [Old 2011 Syllabi and links](http://itp.nyu.edu/varwiki/Syllabus/ICM-All-F11)
- [Old 2010 Syllabi and links](http://itp.nyu.edu/varwiki/Syllabus/ICM-All-F10)
- [Old 2009 Syllabi and links](http://itp.nyu.edu/varwiki/Syllabus/ICM-All-F09)
- [Old 2008 Syllabi and links](http://itp.nyu.edu/varwiki/Syllabus/ICM-All-F08)
- [Old 2007 Syllabi and links](http://itp.nyu.edu/varwiki/Syllabus/ICM-All-F07)

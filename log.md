# 100 Days Of Code - Log

### Day 27 August 31, 2018

**Today's Progress**: I mashed together a very inelegant solution to my "Array Array Array" problem, that involves running a while loop with only one record.  But it outputs actual data, which is what I needed.  I also had trouble with a corrupted table and then I couldn't repair it, or rebuild it, or replace it, so I ended up deleting the whole database and rewriting it.  So all of the structure is there now with no data in it. I did export the tables to a spreadsheet first, but then it didn't record the field names, so I had to figure out what each of the boolean fields were again.  And now I can't figure out how to import the data from the spreadsheet.  That is kind of depressing.

**Thoughts**: I'm sure there is a much more elegant way to create my search and output pages.  I have a page for each table I might want to search.  And that silly while loop has got to have a better answer.

**Link to progress**: [Eltara repo](https://github.com/segwyne/Eltara/commit/3468f57114d11a106565ff9cf3202b70778432b9)

### Day 26 August 30, 2018

**Today's Progress**: Today I created a page to look up Player characters.  The page queries the database and returns all the results.  I have the page now display the query results in alphabetical order by last name, then first name.  The results are clickable so that each result can take you to a page created for that player.  Working on getting the results to display actual data rather than "Array Array Array".

**Thoughts**: Every time now that I want to design something, I find myself wishing I could just do it with CSS.  That happened today at work when I was trying to create admission tickets.  "Why can't I just make a division here and style it?" Because LibreOffice Writer doesn't use divs.

### Day 25 August 29, 2018

**Today's Progress**: I now have the relationships established between my various tables (Players, Characters, Skills, Spells, Racial Traits, Plot stories). I finished creating the pages for the game's site, even if many pages have "Check back later" messages.  I put previous and next navigation buttons on the lore pages.  I fumbled around with the database some more.

**Thoughts**: I am haivng trouble figuring out how to build a form in LibreOffice Base that will pull data from lots of tables instead of just two.  I want it to show the character statistics, that character's skills (I've got that done), the players name (as referenced by a separate table, not yet done), any spells that character has learned (through another reference table) as well as the plotlines the character is involved in (from yet another table).  I suspect I can do it through an HTML form, but when I tried connecting HTML to MySQ last night, it really bogged down my machine, to the tune of waiting 3-5 minutes to see my mouse move, just like loading web pages in the early 90s over 28k modems.  I was cleaning the kitchen and checking in to see if it had moved yet.  So I need to figure out what I'm doing wrong there.

**Link to work**: [Eltara game](saunderstechnology.com/Eltara/)

### Day 24 August 28, 2018

**Today's Progress**: Today I broke down the rulebook into individual sections for easier development and updating.  I slightly expanded the database and created some forms for data management.  I also started creating some web pages for database management.

**Thoughts**: This rulebook has way less info that I originally thought.  What it does have is pretty well fleshed out, and the rest of what is missing is easily recreated.  

**Link to work**: [Eltara repository](https://github.com/segwyne/Eltara)

### Day 23 August 27, 2018

**Today's Progress**: I got LibreOffice Base to connect to the MariaDB that my husband had installed on a jail for me.  I now have a form to show the characters that will cross reference various tables to show all of a character's information.  For example, I have a table of Character information (including name, ID#, player#, race, level, etc.), a table of different skills that are available (including skillID#, skill name, purchase cost, description), and a reference table that holds just the Character ID# and skill ID#s.  I use this to pull it all together and create a full picture of the character.

**Thoughts**: I have forgotten so much in 20 years.  I remember having lots of different features that I have to relearn how to create.  I will get there.

### Day 22 August 26, 2018

**Today's Progress**: Continued populating database.  Spell table is now 80% done.

**Thoughts**: Pretty much a continuation of yesterday.  Once I get all the skills and spells populated, I can begin with the coding necessary to create characters.

### Day 21 August 25, 2018

**Today's Progress**: I began populating the spell table of my game's database.  I got 40% done.

**Thoughts**: Data entry isn't quite as exciting as coding, but I need the tables populated so I can do all the fine-point coding later.

### Day 20 August 24, 2018

**Today's Progress**: While rummaging around on our home file server, I discovered a roleplaying game I had written about 20 years ago and never playtested.  I fell in love with it all over again and created a database with LibreOffice Base to start making the game playable.  I created tables for players, characters, skills, spells, and items.  I populated the entire skills table.  I made my husband put the kids to bed so I could immerse myself in this project, promising that I would not be up all night long.  I also started the SQL lessons on W3Schools, and learned about syntax, select, select distinct, where, and, or, not, order by, insert into, null values, update, delete, select top, min, and max.

**Thoughts**:  I feel like I have found a long-lost child.

**Link to work**: None yet.  It is all on my hard drive.

### Day 19A August 23, 2018

**Today's Progress**: I learned about booleans, comparisons, conditions, switch, and loops.  I added code to my dice page to allow the user to roll multiple dice at the same time.  It also documents on the screen what it is doing.

**Thoughts**: I was really itching to make multiple dice possible.  That's why I did a couple more hours here tonight.

**Link to work**: [Dice page](https://saunderstechnology.com/dice.php)

### Day 19 August 23, 2018

**Today's Progress**: Today I learned about the random function in Javascript, so I got the great idea of creating a character generation page for table-top RPGs (such as Dungeons and Dragons).  So far, my page will roll one die of a user-entered size.  But I've got big plans for it!  If only I had a group to game with again, I might actually be able to put this to use.  I miss gaming.

**Thoughts**: I would like to expand this into a complete character generation and storage system, so that gamers can quickly create characters, store them online, update them, and print them out for gaming sessions.  

**Link to work**: [Dice-rolling page](http://saunderstechnology.com/dice.php)

### Day 18 August 22, 2018

**Today's Progress**: I did this a day early since I won't have any time tomorrow (August 22) to sit and code.  I made the navigation responsive, and I also made the animations page responsive.  I made the animations themselves smaller in scope to be easily viewed on a phone, but then the in between sizes of a tablet were throwing me for a loop, so I decided to just offer the animations on large screens, and put a message to show on smaller screens asking them to view the animations on a large screen.  I also switched all of the files on the live site to PHP, even though I am testing them using HTML on my local machine.

**Thoughts**: I understand the responsive navbar better now.  Even though I had deployed one before, that was pure copy-and-paste code that I didn't fully understand.  Now I understand how the checkbox method works, and how to hide the ugly checkbox.

**Link to work**: [Saunders Technology](https://saunderstechnology.com/animations.php)

### Day 17 August 21, 2018

**Today's Progress**: In Javascript, I learned about strings, numbers, arrays, and dates.  I created a box to display the current date at the bottom of my front page.

**Thoughts**: The arrays were very confusing to me.  I couldn't see the "how" behind the methods, specifically the comparisons.  I can see that it does work, I just don't understand how it works.  I was also a little frustrated that at one point the lessons said, "You do x this way, but don't do it that way because it complicates the code and slows it down."  Then why did you say I can do it that way?  And then later, "This is how y works.  There is no reason to use it in your code."

**Link to work**: [Saunders Technology](https://saunderstechnology.com/index.html)

### Day 16 August 20, 2018

**Today's Progress**: I worked on the JS lessons for 45 minutes and learned about assignments, data types, functions, objects and events. I then moved the silliness items from my sewing page to a demo page on the tech site, where it makes much more sense for them to be.  I also used the JS I just learned to make the buttons change the class of the animation box so I have one div that applies different animations instead of having different divs that either display or don't.  Now it is one div, and the button changes its class.  I also changed the buttons to call functions instead of having the JS written right into the HTML of the button.  I also took my face off of it and just used a colored block div.  The face was actually a little scary, according to my kids.

**Thoughts**: Spelling matters!  Typing "dispaly" instead of "display" will make the entire function fail.

**Link to work**: [Saunders Technology](https://saunderstechnology.com/animations.html)

### Day 15 August 19, 2018

**Today's Progress**: I started the Javascript section of W3Schools, then to put that into practice, I wrote some JS buttons to turn the animations from yesterday on and off.

**Thoughts**: I'm having just a little trouble with the box animation and making it mobile-friendly.  I want it to go right down to the top of the footer (with some margin), but it is using way too much margin unless I put in absolute distances.  I tried using "top: calc(100% - 100px)" but that wasn't giving me the results I wanted.  It is like there is another section between the division the animation is in and the footer, but there is nothing there that I can find.  I tried shutting off the padding, but that didn't help, so I am using "top: 350px" instead, which isn't so friendly for phones.

**Link to work**:[Segwyne's Needle: Silliness](https://github.com/segwyne/segwynes-needle/commit/47ef90f41d7ab5427fad440be96a0148805cc843)

### Day 14 August 18, 2018

**Today's Progress**: I finished all of the CSS exercises on W3Schools.com.  There was more CSS after that, so I went ahead and got to work on that.  After a few hours, I realized I hadn't done any coding at all yet, so I created some silliness on my page.

**Thoughts**: Coding after 3 shots of Schnapps leads to some interesting ideas for demonstrations.

**Link to work**:

On Github: [Commit 17 on Segwyne's Needle](https://github.com/segwyne/segwynes-needle/commit/5bb2b24d06545e14826229d246e906534b7952f1)
Live Site: [Segwyne's Needle: Silliness](http://segwynesneedle.com/cssplay.php)

### Day 13 August 17, 2018

**Today's Progress**: I conquered the multi-slideshow challenge!  I got four slideshows on one page, two portrait oriented and two landscape oriented.  I made them so they won't pile on top of each other, I tweaked the JS to include the extra slideshows, I made them stack vertically on small screens and in a grid on large screens.

**Thoughts**: I am very proud of myself for getting this done.  I still want to make the slideshows shrink to fit on tiny screens without scrolling, so I will start there tomorrow.  Then I will figure out how to merge branches.

**Link to work**: 

On Github: [Commit 16 on Segwyne's Needle](https://github.com/segwyne/segwynes-needle/commit/4a3c9b102a00b574c6fa454d3e528682a1251869)

Live site: [Segwyne's Needle Showcase](http://segwynesneedle.com/showcase.php)

### Day 12 August 16, 2018

**Today's Progress**: It doesn't look like I did anything at all today except copy my php file into html so I can run it locally. I experimented with flex-box for my slideshows, but I still have some debugging to do before I can really try it again.  Some issues I encountered in my experimentation today included having one slidedhow sit on top of the other, and having the "next" buttons decided to align to the right of the screen instead of the right of the division while the "prev" buttons behaved just fine.

**Thoughts**: I'm tempted to throw in the towel on this and choose a different way to display the shows, but the whole point of this is the process not the product, so I need to stick with creating my original vision until I make it real instead of giving up and creating a different look that is just "good enough for now".  No, I need to go with exactly what I envisioned.  I'm way more product-oriented than process-oriented, so this is good practice for me.

**Link to work**: [Commit 14 on Segwyne's Needle](https://github.com/segwyne/segwynes-needle/commit/9ebbf7557ca3c8cce67e537e165fc0b53e280df8) I did create a branch for slideshows - my first attempt at branches.  I'm not sure why it is still the same commit number as yesterday.  

### Day 11 August 15, 2018

**Today's Progress**: I fixed the sticky-outy part of the caption on my slideshow by removing some padding.  I added a second slideshow, just because.  I did have to look up how to make the same JS work for both slideshows, and it took me a while to discover that I had one extra tweak to make to make each set of advance buttons work on their own slideshows.  All the buttons were working for one slideshow, and ignoring the other, so I got that fixed.  At the end of the hour, I was still working on getting the slideshows to sit nicely on the page.  I got them to sit side-by-side instead of above/below, but they are squished up against one side for now.  I guess that's where I'll start tomorrow.

**Thoughts**: Yes, I like to do things simply to see if I can.  I want to explore having portrait-oriented slideshows and landscape-oriented slideshows on the same page.  I currently have one of each, and they need a lot more styling work.

**Link to work**: On Github: [Commit 14 on Segwyne's Needle](https://github.com/segwyne/segwynes-needle/commit/cc82177cc911b15b3e1d41b3637f847e75c49360)
Live site: [Segwyne's Needle: Showcase](http://segwynesneedle.com/showcase.php)

### Day 10 August 14, 2018

**Today's Progress**: I want slideshows of my work on my Showcase page, so I began by creating one.  Or mostly creating one.  I am using placeholder photos of the autumn beauty where I live until I get nice photos of my clothing.  The caption bar sticks out a bit on the side, but after spending an hour and a half sifting through my Google Photos, and then another hour and a half coding (since sifting through photos doesn't really count as coding), I am exhausted.  So I will fix the sticky-outy bar tomorrow.  I blatantly copy-and-pasted the JavaScript portion, and tweaked it to remove the parts I didn't use, and change to the names I did use.  This will be unallowable once I start learning Javascript.

**Thoughts**: I probably over-documented the Media section of my stylesheet.  But this is a section I am still learning, so I want to know exactly which line does what at this point.  I am hoping to make multiple slideshows on this page and am wondering if flexbox would be helpful since some photos are landscape, and some are portrait orientation.  Now that I actually think about it, each slideshow should probably be put on its own page, linked to from a thumbnail photo to preserve bandwidth and load time.

**Links to work**: 
On Github: [Commit 13 on Segwyne's Needle](https://github.com/segwyne/segwynes-needle/commit/8929e526ac313f905fb450bf0a20509ae9084022)
Live site: [Segwyne's Needle: Showcase](http://segwynesneedle.com/showcase.php)

### Day 9 August 13, 2018

**Today's Progress**: I created a Price List for my sewing business, thought the prices themselves need to be updated.  I just brought the content over from my original weebly site and then formatted and styled it.  I used :first-child and :last-child to set the widths on my table because I didn't want to apply a class to every single data cell. I also figured out why my footer wasn't showing up properly on my About page.  I was missing the initial < sign to open the php tag.  Fixed that, too.

**Thoughts**: I don't like tables, but they seem to be a necessary evil sometimes.

**Links to work**:
On Github: [Commit 12 on Segwyne's Needle](https://github.com/segwyne/segwynes-needle/commit/169747e4d61fb202c870c5f74afb92e387f34d8b)

The actual site so far: [Segwyne's Needle: Price List](http://segwynesneedle.com/price-list.php)

The original weebly site that I am converting from: [Segwyne's Needle](http://segwynesneedle.weebly.com/)

### Day 8 August 12, 2018

**Today's Progress**: I focused on the CSS class at W3Schools.com today.  I learned about rounded corners, border images, backgrounds, colors, gradients, and shadows.

**Thoughts**: Much of this I had already been exposed to through my Frankenstein method of website building for the Fort, but I want to go through the whole class in order, without skipping anything.  I don't want to be arrogant and think I already know what the lesson is going to teach me.

**Link to work**: Again, none.  I just worked through the tutorials.

### Day 7 August 11, 2018

**Today's Progress**: I didn't do much actual coding today.  I decided to finish up the CSS course at W3Schools that I had begun and learned something so I went to go make a fix to the website I built for my work and discovered that my boss had made some changes because that I thought were ill-advised.  I had specifically kept the dropdown menu a different color from the main menu so that there would be a visual distinction when viewed on a phone, but that meant that on the larger size screen the dropdown menu items were the same color as the body background.  I was going to adjust the borders so that it had side borders, but she changed the background color instead.  So I changed it back and added the side borders.  Since this is not the first time she has altered the site (and slightly broken it) since it went live a couple of weeks ago, I decided to back up all the files to my own server.  Just in case I need them later.  :)  Since I haven't figured out how to use FTP, I had to do this manually by downloading every file one at a time.  Altogether, it took up the whole hour.

**Thoughts**: I really want to get on to learning PHP , but it looks like I really should finish CSS and Javascript first.  I already finished the basic HTML course, and was well over halfway through the CSS, so I am going to plug away at those some more.

**Link to work**: None, really.  I suppose I can link to [my work website](http://fortat4.org), the one I just fixed again and backed up.  

### Day 6: August 10, 2018

**Today's Progress**: I actually put in two hours today, not one.  I probably did on some previous days, too.  I worked on the processing page for my contact form.  It is coming along.  It mostly functions.  It gets the data to me, but it isn't validating anything yet.  Looks like that will be tomorrow's project.  I also switched all of my placeholder pages from html to php so I can work with just one file for making changes to the header or footer.

**Thoughts**: I think I need to start setting a timer for myself so I know when my hour is up.  Taking the time to actually type the code instead of copy/pasting it really does make a huge difference in learning it.

**Link to work**: [Commit #11 for Segwyne's Needle](https://github.com/segwyne/segwynes-needle/commit/ca36b8c0bef3ac6c806cb58f85813e82262ecda5)


### Day 5: August 9, 2018

**Today's Progress**: I created a contact form page, but not the processing page to go with it.  I also created my About page.  When I tested my contact page in mobile view, I noticed that my fixed footer obscured the bottom of my content, including my Submit button, so I added padding to the bottom of the content division to counteract that.  I also tried unsuccessfully to make my navbar sticky when it hits the top of my page.  I see lots of JS methods to do it, but I'm not familiar enough with JS and I thought that position: sticky was supposed to work for that.  But it won't for me.

**Thoughts**: Honestly, I didn't expect to get an hour of coding in today once I completed my other obligations.  But once the kids were in bed, I sat down, deciding that a half hour was better than nothing, and I think I coded a full hour or more.  My hubs will be getting up in an hour and a half, so I need to hasten off to bed before that.  The running dishwasher will still give me away in the morning, but I won't go to bed with a kitchen full of dirty dishes.  I also decided to change the orientation of this log so that I do not have to scroll to the bottom to update it each time.

**Link to work**: [Commit #10 for Segwyne's Needle](https://github.com/segwyne/segwynes-needle/commit/ab00f525a8990e953e499612d30639f6c909a53c)


### Day 4: August 8, 2018

**Today's Progress**: I worked on finishing up my navigation menu and created a footer.  Both sections use flexbox.  I adjusted the navigation so that the mobile version has a pull-down menu instead of taking up half of the screen's real estate with the menu, and rearranged a couple of items.

**Thoughts**: I'm understanding the flexbox system better now.  I can write the code now without having to look it up so much.  As I work on this site, I start to wonder what content I will use to actually fill the pages.  I guess my favorite part is making the theme.

**Link to work**: [Commit #9 for Segwyne's Needle](https://github.com/segwyne/segwynes-needle/commit/ef439723a56f335c6c1386630af7f4dbc1b4145d)


### Day 3: August 7, 2018

**Today's Progress**: I spent quite a while wrestling with background images before finally deciding to just use a solid background color instead.  I used both CSS and GIMP in the wrestling process.  I also looked up the answer to get rid of the ridiculous amount of white space I had all around my header, and did that.  I pored over fonts to decide which one I liked and would play nicely with me and integrated that, too.

**Thoughts**: The mobile-first approach is much easier for me to do when I open a second browser and just reduce the size way down to 360 px.  Otherwise I get to imagining the full screen version first instead.  I know it doesn't look like I did a lot with my coding, but that is because I kept having to undo what I tried.   I was failing my way to success.  "Nope, wrong road again!"

**Link to work**: [Commit for Segwyne's Needle](https://github.com/segwyne/segwynes-needle/commit/bf43530aae4e0bb3db5c62e9713cdd9d6f33faaa)


### Day 2: August 6, 2018

**Today's Progress**: Started working on my sewing website so I can save working on the tech site to do with Btechie. I created the repo, uploaded the very base files I had already.  I worked on making the flexbox navigation work, and worked on the background for the header using GIMP.  

**Thoughts**: I get frustrated with the git commands, particularly when I hve existing files and can't reconcile them with the repo.  I resorted to moving the files I had just worked on to a holding space, then deleting and remaking the folder for them, pulling the git from Github, and then adding the updated folders back into the new folder and then I was able to push them.  Very frustrating.  But I finally got it accomplished and I can focus on just the actual coding part in the future.

**Link to work**: [Commit for Segwyne's Needle](https://github.com/segwyne/segwynes-needle/commit/3bcf4768a2ecb2c9cbdd2b5e5b0806b33f10cc3f)


### Day 1: August 5, 2018

**Today's Progress**: Went through multiple tutorials on how to use GitHub so I can get started with this.  Created repo for our tech website and began building that.

**Thoughts:** I feel like I have done so much just to get started, without actually creating anything (aside from useless example repos).  It felt silly to have a nice public webpage in which I built link to a lameass site for ourselves, so I started on our own site now. I created the header and navigation bar and also created a template css sheet for myself to stay organized.

**Link to work:** [Saunders Tech Site](https://github.com/segwyne/Saunders-tech-site)  I'm not sure how to link to a specific commit yet, or even if that is possible.

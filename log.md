# 100 Days Of Code - Log


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

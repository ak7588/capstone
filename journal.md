`Write when it's impossible not to; make when you can't stay silent.`

---

# Spring Semester

## Pre-Installation Notes:

- [x] Fixed audio
- [x] Fixed sizing and animations
- [x] Polished the form
- [x] Edited text on the last page
- [ ] To add app image   

## Week 10, due April 12th - Last Stretch!

### Intro

Hello-hello, it is the final stretch before the showcase!

I am preparing my paper, which I had a major breakthrough about this week and last (thanks to my advisor!).

Today I've fixed the Notion page and a form, and now it looks pretty like this:
![form](/media/website.jpeg)

The user will be transferred to this page on the iPad, after finishing the story. I tested this with QR codes during the Health Center event and have observed the following: participants would scan the QR code even before reading the story and see the notes, which I thought kind of defeated the purpose of this shared archive. I.e. the participant is supposed to see this only _after_ reading the story, so this explains why I chose to place the button where it is.

Please note that this website and journaling is not the _main_ purpose of the Capstone, so I am paying less emphasis on its design and UX, although I _do_ want it to look good and fit into the theme!

I've also checked out the iPad Pro from the IM Lab, have installed my software in it, and have successfully tested the project -- all works as expected!

Other than that, I am continuing writing my paper and doing the final fixes before the showcase. Let's goooo!

### How am I planning to undergo message moderation / spam / profanity check in Notion database?

So there is no straighforward answers. My process will be manual, but because sharing these messages is not the primary goal or my research, I have created a simple workaround. So the user submits to one Notion database, from which I just copy-paste the message (if approved -- and the approval process is very simple, I just want to make sure there are no spam texts, swearing, etc).

Here is how it looks behind the scenes:

![form](/media/profanity-check.png)

### Some of the ideas for future steps

- Change animations based on the lean touch input data. For example, when the user taps on the screen, the animation state changes from the deafult to walking to that specific touch point etc.
- How do AI characters change this dynamic? Because Unity characters already have this capability

### Updates on the fixes:

- [ ] Chapter 3: Polish lean touch
- [ ] Re-record sound professionally
- [ ] Make the worlds smaller / better UX for the bigger iPad
- [ ] Draw a reply button background in illustrator
- [x] Astronaut animations
- [x] Chapter 9: remove cards part and add a button to go to the form

## Week 9, due April 4th - More Making

### Updates on the below:
- [x] Created a URL button on the last chapter for call to action
- [x] Created an MVP version of the form and gallery page in Notion

To Do:
- [ ] Edit the button to fade in/out
  - https://stackoverflow.com/questions/39336423/fadein-fadeout-ui-button-in-unity-5 
- [ ] Make prettier UI
- [ ] Fix the Notion form page and gallery view UI

![form](/media/archive-gallery.png)

A small note on responses: I guess my assumption was that people with use this space to open up (because it's anonymous). But there still seems a barrier to that. People tend to reply in more detail on postcards on average compared to the electronic version. But that was worth trying to move things online.

--- 

Same week, previous updates:

I found myself browsing the internet at 2 AM in the morning, waiting to close my fast this Ramadan when I came across Notion forms... Fast-forward, I've spent exactly 30 minutes, and...now I have a mini-server that I do not even have to maintain to create a public archive for my Capstone journaling responses! Yay!

The form is accessible to view here: https://notionforms.io/forms/a-sentence-for-your-inner-child

I am yet to create a visual output for the responses, though it will probably be designed in the theme of my Capstone.

Why Notion? I chose Notion because the process of response moderation and database maintanance is suuuuper easy and straightforward. I do not have to constantly run my own server in the background, don't have to use a separate Google form -- all of the responses are saved automatically and can be pulled by Notion itself to a Notion-based web-page...isn't it just great?!

Here are some screenshot examples:

![form](/media/form.png)
![database](/media/database.png)

I will use a Unity API to forward the participant into the URL once they finish the AR experience and will need to think of a way to display all of it when the exhibition time comes. Other than that, again, yay!

### List of pending fixes:
- [ ] Chapter 3: Polish lean touch
- [ ] Chapter 4: Stop any music before playing new one (from paper cranes in ch 3)
- [ ] Astronaut animations
- [ ] Chapter 9: remove cards part and add a button to go to the form

## Week 8, due Mar 28th - Updated Paper & User Testing
[Google Doc](https://docs.google.com/document/d/1w4QObAJVXVTigxJ1-uqA5EBQ5lAudDxXf_65hORyUvQ/edit?usp=sharing)

## Spring Break and User Testing

Over the spring break, I had a chance to get some advanced user-testing feedback from fellow students, health center professionals at NYUAD, as well as MY FUTURE GRAD SCHOOL PEERS and ADVISOR (what?!). Some overlapping themes were adding more interactivity onto the app screen with lean touch, rendering/baking the light properly into the scene (so it doesn't lag in the app), and participation UX.

As there is only three weeks into the project left, I will prioritize:
- improving lean touch
- fixing last animation and storytelling bugs
- writing the paper

For next Tuesday's class, the goal is to have my advisor give some feedback on the paper + app functionality.

I also still have to go print the book. Wasn't able to do that due to final touches to the illustrations and text. Estimated deadline: by April 1st-5th.

---

## Some feedback notes for myself

Letter UX:
- It's not obvious when it starts --> the design, audio and visuals do change; but the text itself and the illustrations are unclear.
- Diversifying journaling promots? "What words of encouragement would you say to your younger self?" --> Could be something that more students can relate to / depending on the age and context. For example:
  - What words of encouragement would you give to a friend at the beginning of the semester?
  - What words of support would you say to yourself before entering college?
  - Perhaps make the responses digital. Ask Katie about the server and input/output. What if the app would take them there after the last experience? That would add more interactivity AND be more sustainable/cohesive for the project overall.

# Week 7: Mar 1-7

## Software Updates:

- [x] Added LeanTouch lib
- [x] Added sound for paper unfolding
- [x] Added pinching and dragging paper crane size when calling to action to read the letter

## General thoughts and reflections:

I can improve the technical functionality later on, since very little depends on images there. BUT, I need to start thinking about printing / finalizing graphical stuff by the end of next week, as I will only have so much time to finish technical parts during spring break.

## To-Do before Tuesday:
- [ ] Finish card design
- [ ] Print around 5-10 cards for user-testing
- [ ] Research printing options for the book
- [ ] Start prepping the book for printing  

# Week 6: Feb 21-28

## User-testing

**Testers**: Dr. Vedrana (!), Aiya, Indira, Seoyoung, Dhabia, Joseph

Before I talk about everything else, I wanted to recognize that I had a real therapist from the NYUAD Health Center test my Capstone and comment on the concept -- thank you, Dr. Vedrana! Because the concept of my capstone is loosely related to well-being and mindfulness, it was important for me to get some feedback from a field professional to make sure I am not creating bluff. To my relief, the feedback was great and the journaling prompt at the end is very on-point for my purpose. I will now try to work with the Health Center to see if we could collaborate in March to promote journaling among the NYUAD community!

/ Back to user-testing /

**Procedure**: All of the participants were given an iPad and a book prototype. They were instructed to use the iPad to augment the book experience. No context or project descriptions were given outside of that. Participants were free to view the content in horizontal or vertical modes. They were also free to move in space (360*) or remain sitted. After

**General remarks and observations**:
- only 1 person out of 5 viewed it vertically;
- all participants stood up or moved around the space while viewing the experience;
- people stop reading the text after page 1 or 2, OR read first and then use the app to flip through pages the second time;
- other remarks are noted below

**Conceptual/spatial suggestions of the users**:
- Make AR scenes a little smaller, as it is "tedious to constantly zoom in/out and move around";
- "Add variety" to the planets and scenery (will see if it fits into my concept, though);
- Add interactions on the screen or camera, as all participants were trying to find "hidden" interaction options;

**Small fixes based on feedback**:
- chapter 9 hand recognition --> for now it pops out text without intentional interactions;
- chapter 8 --> rocket animation goes way too fast for participants to observe;
- chapter 7 --> fix animations colliding with neighboring objects;
- chapter 6 --> shader length makes it unclear if it's sunny or raining
- chapter 5 --> shader lagging
- chapter 4 --> fix animated person walking in space
- chapter 3 --> add lean touch to interact with letters on the iPad screen
- chapter 2 --> fix animated person walking in space

**Participation/journaling experience survey:**

After completing the experience, participants were surveyed if they would stay to write down an encouraging letter to themselves or others. All of them noted that they would, although the length differed. Some described they would write something really short and leave (a few words to a sentence), while some wanted some dedicated time (5-10 minutes) to reflect at the end.

Given these suggestions, I decided to move forward with the following format for exit-participation. I will design postcards that will have space for 1-2 sentences to write. The card design will be similar to that of a coloring book, so that each participant could customize their design if they wish to do so. I will purchase coloring pens and pencils and might print out small stickers to be placed on the card. After that, participants will have an option to display their card anonymously on the exhibition wall to create a wall with kind and encouraging messages related to the theme of the book.

![](/media/user-testing.JPG)

## Printing notes

- Can print A5 cards in the library
- Will print the books at Desco

## Making

It is week 6, ladies and gentlement! And I am finally-FINALLY done with my minimum viable capstone! :D

Over the past 2 weeks I've finished all of the basic animation flows, illustrations, and audio narrations. Everything is packed into the iOS app for iPad. Now is the time to get feedback, refine, and improve! Let's gooooo

A few concerns before the round of user-testing:
- Do animations correspond to the illustration and narration in the book?
- Does the sound convey the full story I am intending to tell?
- Is the app experience / UX of the project intuitive enough?
- Should I prepare coloring books and journaling spaces for people to participate at the end?

A few improvements that are still pending and are more of "nice-to-have":
- [ ] Add audio effects like folding/opening paper
- [ ] Fix people animations and make them more defined
- [ ] Make the transition from letters back to real world more profound
- [ ] Print and test on laminated sheets!!!
- [ ] And anything else that comes up in user-testing

---

Some of the notes this week:

_Update:_ and...the below did not work. Apparently sending emails through an AR iOS app causes a whole lot of build errors outside of the editor. I suspect that some of the packages (pointing at MimeKit and MailKit) just don't work with iOS. So I am considering other participation options. Perhaps I should go back to the idea of paper/pen participation and just leave an option to place a custom planet at the last scene with no mail interaction.

P.S. I am very bad at documenting my failures on time...I usually fix the error and forget to document it or do something else and again forget to write about it. Here are the pictures at least:

![](/media/send-email-code.png)

![](/media/email-received.png)

After that I had to stash my changes and delete installed packages for the app to build and run again.

---

I have figured out what I want to do with the last chapter of my project / participation part. All users will be able to send emails to themselves at the end of the book experience. To do that, I have imported MailKit and MimeKit into my Unity project. I have used SMTP functionality in Outlook to be able to send emails directly from Unity.

Idea:
- Users will write a message and their email
- Users will customize a planet
- Their planet image and text will be sent to their address

In addition to that, I have finilized MVP for all chapters and will now improve this last part's UX before finally doing the official user-tests!

# Week 5: Feb 14-21
- [x] Recorded all of the sounds
- [x] Illustrated all of the chapters
- [x] Finished AR for chapters 1-6

Pending:
- [ ] Printing laminated A4 / cards to test the format instead of the book
- [ ] Chapter 9 technical functionality
- [ ] Polishing AR animations for chapters 1-6
- [ ] Adding AR for chapters 7,8

P.S. Most of the updates now are happening in the iPad app. I will include some video demos and screenshots as proofs. I show the app updates weekly to my advisor.

![](/media/feb-15.png)

![](/media/mvp.JPG)

PDF prototype: [click this link.](https://drive.google.com/file/d/1b1OL1DAj4rcsVy79v7Dd6xScTcFIxtLJ/view?usp=sharing)

# Week 4: Feb 14

Progress:
- [x] Added Home button functionality
- [x] Added responsiveness to the UI
- [x] Finished the script/conceptual framework
- [x] Fix Ch3 illustration (make more profound from Ch2)
- [x] Re-imagined the space design from chapter to chapter (look at hand-written notes, will add here later) 

Pending:
- [ ] Add Ch4-10 illustrations + sound + AR
- [ ] Fix Ch1 AR (make consistent with text and sound)

# Week 3: Feb 7

## Building UI Menu

For this week's progress, I have a UI menu scene done + some updates to chapter 3 of the book (out of 10). Chapters themselves do not take that much time to get done, but I need them all together before I do the playtest of the whole project and future iterations (if I decide to add more interactions, enhancements to animations, sound, etc).

I also did a draft design of the front book page according to the menu and AR design.

What happens when you forget to plan for the screen layout and dimensions?

This:

- Expectation:

![](/media/expectation.png)

- Reality 😂:

![](/media/reality.PNG)

Video demo: [view here](https://drive.google.com/file/d/1IK52CNPcJjBESajBlU1lsxRyONLU6jtR/view?usp=sharing).

Current progress:
- [x] Chapters 1-2
- [x] Menu UI
- [x] Chapter 3 in-progress (illustration+AR done, sound pending) 

To-Do:
- [ ] Ch. 4-10 illustrations
- [ ] Ch. 3-10 audio
- [ ] Ch. 4-10 AR scenes
- [ ] Refine UI responsiveness
- [ ] Add more interactions once all chapters completed

# Week 2: Jan 31 - Feb 7

## Making

I have spent a big chunk of this week to do a book MVP and chapter MVP (example of AR, sound, and animations). The end result ended up looking like this: [a video demo link](https://drive.google.com/file/d/1bh7Mg15OM-dsmHn4IwSJq5nvxQVQokAw/view?usp=sharing). To make this happen, I used Adobe inDesign for book prototyping. There, I added a dyslexia-friendly font to add accessibility into the project. I drew illustrations on my iPad using Procreate software. On the AR side, I am using Vuforia and Unity to make everything move, animate, and be in 3D. Below are a few screenshot examples.

Current progress:
- [x] Book MVP

![](/media/book-mvp.png)

- [x] Chapter-1 illustrations, audio, and AR animations

![](/media/ch1.png)

- [x] Chapter-2 audio

In progress:
- Chapter-2 AR. Exploring packages and resolving bugs

To-Do:
- [ ] Ch. 2-10 illustrations
- [ ] Ch. 3-10 audio
- [ ] Ch. 3-10 AR scenes

Resources for AR scenes:
- Ultimate pack: https://assetstore.unity.com/packages/3d/props/low-poly-ultimate-pack-54733
- People: https://assetstore.unity.com/packages/3d/characters/humanoids/low-poly-animated-people-156748
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/low-poly-animated-animals-93089

# Week 1 - due Jan 31

Exhibition space:

I plan to have a wall-space (approx 2x2 meters) with a small pedestal to showcase the book and hold iPad/iPhone to see the AR animations.
I will hang some AR posters on the wall and will place the printed copy on the table/rectangle space for visitors to see.

SketchUp Sketch:

![/media/sketchup.png](/media/sketchup.png)

Real-life example:

![/media/IMG-9191.jpg](/media/IMG-9191.jpg)

---

# J-term

# Jan 22nd:

Sound resources:
- https://freesound.org/people/Robinhood76/sounds/58244/

Cool read:
- https://archive.nytimes.com/www.nytimes.com/news/the-lives-they-lived/2013/12/21/red-burns/

# Week 14.2:

## Jan 15th, 2023

Leaving links to AR book implementations I liked the most:
- https://www.youtube.com/watch?v=F2ieduC3wCI
- https://www.youtube.com/watch?v=NT_YBTyMN_4

Mixamo selected animations:
- Orc Idle
- Jump
- Petting animal
- Standing Idle
- Waving Gesture
- Sitting

Character creation for Mixamo with Adobe Fuse CC:
- https://www.youtube.com/watch?v=FrPjNYk_JQ0
- https://www.youtube.com/watch?v=-uapfgMPoAw

Vuforia AR tutorial by Unity:
- https://www.youtube.com/watch?v=9XikHnTiukk&list=PLX2vGYjWbI0Thl0pOCbKWrbbiw7RWiRG7

## January 13-14th, 2023

Prototype aka Working with Image Tracking:

![](/media/jan-14.gif)

- completed image recognition tracking training on LinkedIn Learning
- above seems limited in terms of recognizing an image and just placing a prefab on top of it; no space to add scenes or animations, which leads me to make a decision:

**focus on animations** and go for using Unity AR tools like Vuforia and Artivive, or
**focus on technical aspects** and see how Unity with no additional frameworks can help.

My intuition tells me to check Vuforia, which is what I'll do next.

What other book page formats are possible to animate in AR?
- Wood printing
- Laser printing

What is different? 
- interactive and immersive journaling; people might be more prone do it compared to usual journals

# Week 14.1: January 8th, 2023

Happy new year! I am back from the winter break with exciting updates for my Capstone project.

i) There've been some updates to the storyline. I have added the missing scenes and details to the initial script. Now the story is more cohesive with the title - The World Within - and is based on a character's life journey. The journaling prompts at the end are also more clearer now.

ii) I am currently doing research on how to animate scenes with AR. Google suggests using Unty's AR Image Recognition Tracker, but some results also suggest Vuforia. I am unsure about Vuforia for now, but will keep iterating on Unity.

iii) I have started a course on LinkedIn learning on book illustration and have set up a coffee chat with a student who managed to publish a children's book in the UAE. Hoping to get more insight on how to illustrate and publish mine!

Let's goo!

# Week 14
Feedback:
- how the story informs AR
- the main focus/intro was a bit unclear
- how the final experience is delivered w audio/visuals
- guest-book and explanation of interactions / storybook
- which artists informed, positioning of myself, collective knowledge (?) more in detail, what is the role of the audience
- proof of concept

# Week 13

- [Revised Final Paper](https://docs.google.com/document/d/1w4QObAJVXVTigxJ1-uqA5EBQ5lAudDxXf_65hORyUvQ/edit?usp=sharing)
- [Revised Final Presentation](https://docs.google.com/presentation/d/1h_YWVdZJ8y8nihlqCL_BJ1np3v7kP9AybfErnURPGig/edit?usp=sharing)

To check:
- image recognition tutorial: https://www.youtube.com/watch?v=o_z_Eb8Yh2g&ab_channel=DineshPunni
- https://arkidsbook.com/

# Week 12
- [final paper](https://docs.google.com/document/d/1w4QObAJVXVTigxJ1-uqA5EBQ5lAudDxXf_65hORyUvQ/edit?usp=sharing) + [presentation](https://docs.google.com/presentation/d/1h_YWVdZJ8y8nihlqCL_BJ1np3v7kP9AybfErnURPGig/edit?usp=sharing)
- budget (to be submitted)
- to-read: https://fsstudio.com/ar-and-vr-in-education-how-are-kids-learning-better-with-immersive-experiences/

Free animations and graphics:
- Figma community by Alzea
- getillustrations.com by Blue Ill
- opendoodles.com by Pablo Stanley
- notioly.com by Mary Amato
- wannathis.one by Wannathis

# Week 11

It's Week 11...crazy!

![](/media/plane-ar.gif)

## AR Debugging 101:
- [Untrusted Enterprise Developer on iPhone issue](https://support.workeq.com/untrusted-enterprise-developer)
- [Black screen Unity AR Foundation - camera not working](https://stackoverflow.com/questions/71895548/black-screen-unity-ar-foundation-camera-not-working)

Possible issues identified: downgrade to 4.2.6 versions of ARKit and ARFoundation in Unity.
Solution: update Xcode on iMac.
Source: https://docs.unity3d.com/Packages/com.unity.xr.arkit@4.2/changelog/CHANGELOG.html

````
You are now required to build iOS players with Xcode 14.0 or newer, a necessary requirement to support iOS 16 devices. Please note that Xcode no longer supports building iOS projects with deployment targets for the armv7 and armv7s architectures.
````

## Making

Learning of the week: Consistency is key. 

I've been doing some more AR practice in Unity this week. Here's one of the scenes I created:

![](/media/week-11.png)

The scene instantiates objects on tap, and that made me wonder if similar logic allows drawing in AR possible? If so, this can be something I look into after rolling out the basic features and scenes in my Capstone.

Unfortunately, there is a bug somewhere in the system that I am yet to solve to test on a device. Seems like a camera is not starting up on my phone, so I am unable to test that. However, this weekend I will get myself full on practicing more AR and debugging, so hopefully that will be out of the way!

And a settings reminder to myself:

![](/media/xcode-settings.png)

## Budget

In terms of the budget, Prof. Slavica gave great points about looking into buying QR generating software license, as the free ones tend to expire quickly. Sound and audio libraries is also something that might come up in the process. Before Tuesday, I should look more closely into:
- specific assets and physics
- qr software
- sound libraries

## AR Research Continued

Upon continuing my research, I was really surprised to see that AR children's books are not trending on YouTube's algorithms. The most popular and recent ones are dated 3-4 years back? Why is that?

![](/media/youtube-search.png)

# Week 10

## Elevator Pitch

In my Capstone, I am interested in exploring the topics of developing self-awareness skills through immersive technology. With the use of mixed reality and Unity, I intend to create a digital story that takes a person on a learning adventure and prompts to reflect and journal at the end. I am investigating how an immersive experience, namely an augmented reality narrative, has capacity to foster a poetic/cinematic experience, in which emotional education becomes a by-product of interaction and immersion. I intend to use immersive sound, storytelling, and elements of play to convey this theme.
 

## Budget + Plan Draft

Access budget [here](https://docs.google.com/spreadsheets/d/1wMKmMN8XcIAWAY4fyRhDEI2DbxHBaqgY/edit?usp=sharing&ouid=108294349221841699767&rtpof=true&sd=true).
Access planning draft [here](https://docs.google.com/spreadsheets/d/1P_I0XYq6-4NpeSPrvVDrXZUWy1X2qTYh/edit?usp=sharing&ouid=108294349221841699767&rtpof=true&sd=true).

## Exploring education technology children's books...

I stopped by the IM lab today to work on a project for another class and have luckily come across Ivory Lee's cookbook and some other exciting books that the lab monitors were about to throw away! (What?!) Among them, I found the booklet for the Abu Dhabi Ideas Weekend 2018 and a bunch of children's educational books from the Karkhana Initiative. I saw those and couldn't stop flippiing through them and getting more insights for my research.

Some of the questions that arised as I was reading the books:
- When teams of designers and educators were making those books, did they take the audience into account? Have they tested them before?
- If so, how did kids react? Did this stuff really engage them in learning?
- For the books that don't have the age group specified, what audience's age did it consider?
- Lastly, I can easily imagine each of them being more engaging and interactive (especially the science books!) with mixed reality. Just imagine reading about an experiment and then performing it in AR or seeing it come to live without needing to spend additional resources on (sometimes) heavy/inaccessible equipment!

I will keep reading through and getting ideas from those. Will update you on where it takes me!

## App Demo's!

I have completed the LinkedIn Learning AR course and am happy to share the progress:

![iPhone Unity Scene](/media/ar-app.gif)
![iPhone Unity Scene](/media/unity.gif)

I created two Unity scenes (the first app demo is above and the second one is below), then exported them into XCode, and then hap an opportunity to export that either into my iPhone or device simulator on Mac. This all looks extremely fun and also not entirely new as I have used Unity before, so moderately challenging!

## Post-AR Reflections:

It's so much fun! Taking a short course was beneficial for both (1) Unity practice and remembering all of its features, and (2) learning AR and XCode integration. I feel hopeful and grateful about the opportunity to use Capstone funding for the things that I haven't done before, i.e. AR development and journal/book creation, as compared to developing another VR application. Let me explore this option further this weekend and see where it takes me!

Notes to self when building from Unity / troubleshooting:
- Check for Simulator or Device build
- When doing device build, check AR settings enabled in project settings for iOS builds

## Researching AR

This week I'm taking [this AR course](linkedin.com/learning/ar-development-techniques-01-basic-concepts/) on LinkedIn learning to explore an interactive AR book avenue for the project. Compatible software for Apple devices:
- ARKit
- Vuforia
- SparkAR

Process goes as follows: Unity -> Project Build -> XCode -> Phone (:0)

### Oh, the excitement!
First works in progress:

![iPhone Unity Scene](/media/AR-build.png)
![iPhone Unity Scene](/media/course.png)

What I did:
- [x] Created a 3D Unity scene with UI and animation script
- [x] Exported the scene to be played on iOS device simulator
- [x] Created account on TurboSquid.com for assets
- [x] Added files to the repo (check the AR Build folder) 

To-Do for next time:
- [x] Finish the first part of the AR course
- [ ] Budget draft
- [x] More practice with the iOS part and the ARKit

![iPhone Unity Scene](/media/ar-animation-build.png)

# Week 9

## Question for AMA:
For those IM faculty who went through a PhD program, what advice would you give your younger self a year before starting your graduate journey? PhD is definitely a long road, so how did you keep pushing through and stayed resilient?

## Reflections on Making

This weekend I've spent a few hours drafting my project and interactions in Unity. I've checked out the Oculus Quest 2 headset from the IM Lab and followed the [keyboard in VR tutorial](https://youtu.be/PyKW9kecyqg) along with remembering all of the C# coding that goes with it. Not surprisingly, after about 11 months, it was challenging to get back to the Unity learning curve, especially with all of the additional settings for VR. I've worked on one VR scene with interactions, in which the user can approach the keyboard and type, with the text displayed on the virtual screen. Apparently, this can be done in multiple ways; first, as I am doing it; and second, by using Oculus' native keyboard, which can be invoked using [this tutorial](https://stackoverflow.com/questions/67080676/opening-keyboard-while-clicking-inputfield-in-vr-oculus-quest-2-and-xrit#:~:text=Just%20add%20this%20Showkeyboard(),And%20you%20are%20done.).

Link to Unity scenes and work in progress: https://drive.google.com/drive/folders/10hSWBSLEW5nja7qzJcX

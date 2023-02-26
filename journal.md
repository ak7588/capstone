`Write when it's impossible not to; make when you can't stay silent.`

---

# Spring Semester

# Week 6

_Update:_ and...the below did not work. Apparently sending emails through an AR iOS app causes a whole lot of build errors outside of the editor. I suspect that some of the packages (pointing at MimeKit and MailKit) just don't work with iOS. So I am considering other participation options. Perhaps I should go back to the idea of paper/pen participation and just leave an option to place a custom planet at the last scene with no mail interaction.

---

I have figured out what I want to do with the last chapter of my project / participation part. All users will be able to send emails to themselves at the end of the book experience. To do that, I have imported MailKit and MimeKit into my Unity project. I have used SMTP functionality in Outlook to be able to send emails directly from Unity.

Idea:
- Users will write a message and their email
- Users will customize a planet
- Their planet image and text will be sent to their address

In addition to that, I have finilized MVP for all chapters and will now improve this last part's UX before finally doing the official user-tests!

# Week 5
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

# Week 4

Progress:
- [x] Added Home button functionality
- [x] Added responsiveness to the UI
- [x] Finished the script/conceptual framework
- [x] Fix Ch3 illustration (make more profound from Ch2)
- [x] Re-imagined the space design from chapter to chapter (look at hand-written notes, will add here later) 

Pending:
- [ ] Add Ch4-10 illustrations + sound + AR
- [ ] Fix Ch1 AR (make consistent with text and sound)

# Week 3

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

# Week 2

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

# Week 1

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

Link to Unity scenes and work in progress: https://drive.google.com/drive/folders/10hSWBSLEW5nja7qzJcXEvx8jkycpc4vJ?usp=share_link

![](/media/unity-project-1.png)
![](/media/unity-project-2.png)

While coming across these technical challenges, I began to wonder if those are the challenges that I should choose to solve with my Capstone. I am worried about getting trapped into solving technical difficulties instead of conveying the project's idea. My Capstone is about stories, learning & exercising self-awareness through immersion and participation -- and that can be conveyed in multiple technical experiences, perhaps in more flexible environments than VR.

What I think I need at this stage is:
- Troubleshoot and discuss project again with Slavica
- Reach out to other students doing VR/AR Capstones (it's easier to solve technical challenges together)
- Keep pushing and overcoming the curve...it will get better with time, I hope!

# Week 8

## Amina's Pecha Kucha

As a technologist and aspiring researcher, I am interested in creating projects that touch upon themes of time and transformation. Technology is rarely thought of as a medium that can foster and promote mindfulness. In my Capstone, I am investigating how an immersive experience, namely a gamified virtual reality narrative, has capacity to foster a poetic/cinematic experience, in which emotional education becomes a by-product of interaction and immersion. I intend to use immersive sound, storytelling, and elements of play to convey this theme.

## Capstone Updates

### I. Theory

Over the break, I continued to read Jaron Lanier's "Dawn of the New Everything" to understand the theory and meaning behind VR. I know that I want to create a poetic immersive experience, and after discussing it with Prof Slavica, I am set to creating an interactive VR piece. I am also reading chapters on VR cinema from "Remediation: Understanding New Media".

### II. The Story

Just a few days before the break, I have come up with the narrative that I plan to convey in the VR experience. As discussed in class before, it will encompass a few therapeutic methods to bring up memories, savoring, and grounding. With these themes, I intend the experience to be a space for emotional learning happening as a by-product of user interactions.

Narrative draft open for feedback and comments: https://docs.google.com/document/d/1l4XEmVogyfyKl-tg2vu4GUgE0bVsHYSt_7lMLVtgoGM/edit?usp=sharing

### III. Implementation

In this second half of the semester, it is good to start drafting the VR environment in Unity. I will plan this in more detail this week with Slavica. For now, I have done some brief research on assets and libraries I can use for implementing the narrative. At the end of the experience, there will be a call to action prompting the user to leave their own story. This can be done through knobs, pictures, or other VR-specific interactions. Some artists and software that I draw inspiration from for this specific part:

- TouchDesign for projection mapping;
- Typewriter assets for VR interactions;
- "Beyond Pages", 1995, by Masaki Fujihata.

### IV. Making Reflections

Over the past 7 weeks of making and ideation, I have tried different technology and alternative media to make the capstone. I used pencil and paper, AR animations, and open-sourced the interactions to the public; by doing all of these variations of my project, I came to realize that I was focusing too much on the execution and not enough on the project and its message. What helped me narrow down the scope is this precise testing and writing inspiration paper for the class. After many conversations with Slavica, I was finally able to tap into my own artistic voice and come up with the story that I was intending to tell from the very beginning. This story is about using technology as a positive change and tool for learning and embracing mindfulness.

### V. Next Steps
- Research Unity assets
- Record story voice-overs
- MVP with voice-overs story only
- First Unity scenes

Unity assets:

1. The Typewriter Effect https://assetstore.unity.com/packages/tools/gui/typewriter-ticker-71390
2. Show text/UI on trigger https://youtu.be/CNNeD9oT4DY
3. Object interaction system https://youtu.be/THmW4YolDok
4. Getting text input https://youtu.be/guelZvubWFY
5. VR keyboard https://youtu.be/PyKW9kecyqg, https://youtu.be/jJnjpU_rKKQ

Weekend To-Do:
1. MVP narration recording (important element of immersion and storytelling)
2. Unity START!!!
3. Can I save the data from each player and store it somewhere?

### Rough Schedule:

- by Nov 1 - Narration MVP
- by Nov 8 - Begin drafting the first scene
- by Nov 15 - First scene MVP + Oculus testing
- by Nov 22 - Begin adding interactions
- by Nov 29 - MVP testing interactions
- by Dec 6 - continue refining the basic flow


# Week 7

## Revised Paper
Find revised midterm paper [here](https://docs.google.com/document/d/1w4QObAJVXVTigxJ1-uqA5EBQ5lAudDxXf_65hORyUvQ/edit?usp=sharing).

## Concept Updates

As soon as I re-framed my Capstone to a *gamified* experience, the story that I was trying to tell finally came up!

Narrative draft open for feedback and comments: https://docs.google.com/document/d/1l4XEmVogyfyKl-tg2vu4GUgE0bVsHYSt_7lMLVtgoGM/edit?usp=sharing

What I am trying to do through the narrative is (1) foster an experience for reflection, (2) create an environment for expression, (3) show how each one of us is capable for using mindfulness techniques when things get hectic in life; how one can learn to slow down and help themselves navigate through a rough patch with the skills and experiences learned in the gamified immersive narrative.

Because the story and the experience rely heavily on senses -- with audio and visuals -- it might be helpful to have it in VR as it allows for more immersive experiences. I also envision it on the web, but it might be less powerful in environmental storytelling.


# Week 6

Find the midterm paper draft [here](https://docs.google.com/document/d/1w4QObAJVXVTigxJ1-uqA5EBQ5lAudDxXf_65hORyUvQ/edit?usp=sharing).

# Week 5

## Making

My project is about sharing stories and meaningful memories from life. Anonymously or not, with and through technology. This week I created an AR prototype of such a "story", a quote from Bradbury's Dandelion Wine. I've used app called Artivive and Canva to create the graphics + animations.

![](/media/1.png)
![](/media/2.png)
![](/media/instructions.jpg)
![](/media/quote.gif)

The idea is that people see a poster (right now it's in a low-fidelity test version -- will probably be iterated over), see the instructions on how to scan it, and then scan it to see the hidden message.

I have tested it with one of my friends before leaving the posters in the Library. The feedback I got was that it's a bit unclear what they're supposed to do and how to scan. So I added extra steps in the instructions mannual on how to download the app and scan it. Perhaps the AR animation needs less text and slower speed for better comprehension. I can fix that in the next iteration should I choose to stick with AR.

A good thing about Artivive is that I can track the metrics of people who scanned the image to see the AR pop-up. So if I leave the posters, I will be able to see how many people have scanned it, which is good for research and citing purposes.

## Revisions
- [bio](https://github.com/ak7588/capstone/blob/main/journal.md#bio)
- [personal statement](https://github.com/ak7588/capstone/blob/main/journal.md#personal-statement)

# Week 3-4

Date Sep 21:

Reflections: political situation in the world since Jan 2022 [deadly and violent protests in Kazakhstan] had a huge impact on my life, and I can't stay silent about it. Central Asian politics is complex, and with the invasion of Ukraine and Kyrgyzstan, it is even more so...As a creator, how can I make space to honor people going through these experiences?

## Capstone Ideation Progress

Date: Sep 18

→ Root project on the experience itself. perhaps not so much on storytelling and learning. learn by doing. not learn by learning.

→ Website: bottles and shelves. clicking on bottles. it opens up. you read the story. perhaps the story is voice-narrated. the story is about opening up and vulnerability. a childhood memory. a happy moment. an intimate moment. a sad moment. letting go. sharing. amplifying. savoring.

→ What do I want to foster post the experience? Sense of relief. Sense of belonging. Joy. Ease. Betterment. Love. Sharing. Feeling something from reading the posts of others. Empathizing. Being compassionate. **Responding?** Dialogue? Interactions with each other?

Idea: what if there is a physical component to it as well? after completing the first stage? Like a small room in which there are the same bottles with the main note + any of the responses from the audience. How would that change the feel of the experience?

## Reflectons on IM and artist/work journey:

→ My journey to IM has not been linear. I took classes from different majors here and there, but always had this passion for something not related to one particular theme. I liked design, colors, and was decent with STEM, and decided to try IM because I’ve heard it combined all of those things. It was love at first sight. From the very first class of Intro to IM, I was very much hooked into the process. Although it happened more intuitively at first, I think now I begin to realize why. I have always struggled with expressing myself verbally to the outside world (personal reason to me), but with interactive experiences, it feels easier. **Colors, sounds, code, input and output** — all of these things are so multifaceted and create so much room for exploration. I love creating, exploring, researching — letting the process immerse me — and that brings joy. This is what IM does to me.
→ What I like is problem-solving and intentional decision making

### My life

- I was born in Astana, Kazakhstan. Central Asia. Post-USSR. Post-colonialism. New country. Nomads. Islam.
- I have lived in Astana, Tennessee, Abu Dhabi, New York, Los Angeles / California, London
- I consider myself a **creative technologist.** Sometimes, a software engineer, experience designer, educator, VR programmer, HCI professional, researcher.
- I studied IM with coursework in computer engineering and math.
- I was first introduced to art at elementary school, but more informally, I was introduced to web-design and programming (unknowingly) as a teenager when I was exploring the idea of having and curating an online web page. This was later dropped as any career idea until NYUAD, where I found that I can combine art and technology — and many other things — for my enjoyment and **greater good**.
    - Elaborate on this idea of social impact.
- Major obstacles — speech impediment. Growing up in Central Asia. Learning to navigate non-inclusive world before finding more belonging and acceptance elsewhere.

### My "art"

- Themes present in artwork — emotional education, VR, empathy, compassion — trying not to limit myself here. Perhaps many more, just need to dig and reflect deeper. Expression!
    - education, psychology, social good in my works. Fun interactive technologies. Games.
- What is unique about my technique is that I express myself and my background while also creating tools for others to express themselves. I like to explore the themes of education, psychology, social good in my works. Fun interactive technologies. Games.
- Topic that I want to convey to my users — empathy, compassion, reflection and understanding, self-expression, emotional education. I want to make experiences that are inclusive and accessible, too.
- The first thing people notice about my art — VR and empathy.

### Accomplishments

- Google scholarship
- Internship with Goldman Sachs
- Fellowship with TOM
- Microsoft Learn + Women @ Dior
- Multiple VR projects and research while at NYUAD — IM showcase
- Media talks and interviews on Kazakhstani resources

## Bio

Amina is a creative technologist with professional experience in Kazakhstan, the United Arab Emirates, the United States, and the United Kingdom. Graduating from NYU Abu Dhabi with a B.A. in Interactive Media, Amina is interested in fostering learning experiences through her work with technology. She creates applications that teach empathy and compassion in virtual reality and is involved in research on inclusive and accessible human-computer interactions. Amina is also an experienced engineer who worked with companies like Goldman Sachs and imagiLabs as a web- and iOS-developer. Her projects are grounded in coding, design, robotics, and education.

## Personal Statement

Can technology help us live more mindfully? How can I, as a technology-maker, create experiences that foster spaces for empathy and compassion?

These are the guiding questions in my work as a researcher, designer, and engineer.

I grew up with a speech condition that affected my ability to socialize and communicate from the early age. I quickly learned that if I want to be heard, I must find a way to communicate differently. Through learning the art of self-expression, I have found my way to creative technology. 

Expressing myself with alternative forms of communication media carried me to pursue my studies in Interactive Media at the New York University in Abu Dhabi and to finding my passion for technology design and making. From creating storytelling art projects to virtual reality games with code, I have learned to embrace my curiosity and life experiences to enable expression.

Fostered empathy and compassion through my personal circumstance has opened up many professional opportunities to me. Aside from being a software engineer and a creative technologist, I like to work with disability communities across the globe to make accessible and open-source technology solutions for a better, more inclusive living. This is something I focused on as a 2021-2022 Tikkun Olam Makers Fellow in Abu Dhabi and New York City and want to continue doing throughout my education in the greater community.

In addition, I have discovered that concepts of empathy, along with other frameworks used in positive psychology, run through most of my work. After reflecting on why that happens to be the case, I came to realize that I refuse to simply make technology for the sake of it. It needs to be intentional, and I see it at the intersection of education, technology, and expression.

For me, expression comes in writing and sharing, too. Because my career has led me to live, learn, and work from different locations, I have a privilege of getting a greater perspective on inclusive education and workspaces across the globe. Born and raised in Kazakhstan, I went off to the United States and the United Arab Emirates as a student to learn more about inclusive education, and later to the United Kingdom to experience the accessible workspace culture. It is my honor to contribute to the world of diversity, equity and inclusion with my column on Women Rewriting the Code and share my learnings in hopes they will bring value and ease to people going through similar experiences. 

In my work, I explore themes of empathy and compassion nurtured through technology. Expressing myself was a challenge when I was growing up, and my academic career is centered around that. I want to create products that are not just beautiful, fun, and engaging — I want to intentionally craft experiences that are meaningful and are bigger than myself.


# Week 2-3

## Sep 10-13

Prototype 2:

**Open-Sourcing Capstone!**(kind of)

![](/media/amina.JPG)
![](/media/board-1.JPG)

After observing not-so-much participation with the Prototype 1 (even from my own roommates!), I've decided to try a different approach. What makes a fun interactive activity? I asked this question on a public white-board near the IM lounge in the Arts Center. Near this space, I've also placed a version of my previous prompt -- How are you feeling today? -- instead of "What's been a highlight/challenge of your week?"

Soon as the audience has identified their emotion, it’s easier to elaborate on it, providing better context and info for savoring. This is “preparation” / “nudging” for the main experience…

Now, jokes are funny, but my project isn’t about humor. So the concept of *fun*, in this sense, is better referred to as “engaging”? “interactive?” “captivating?” — but these are now philosophical experiences…what is a **captivating** experience?

Topics to explore:

- social-emotional learning
- [Immersive experience](https://www.google.com/search?q=dreamscapes+slc&sxsrf=ALiCzsZxvdPPNjzHhS6AUUigKql1lT7oQQ:1662802624852&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjvpKS-9on6AhVDy6QKHXw0BTYQ_AUoAXoECAIQAw&biw=1440&bih=690&dpr=2) - from places like Meow Wolf or other theme parks

My notes:
## **what is fun?**

- **emojis**
- notion
- habit tracker
- texting
- public displays
- body interactions
- drawing
- pets
- Arduino buttons
- electronics input/output
- music
- symbols
- games
- **seeing aesthetic animations**
- **following a storyline**
- forest app

# Week 1

## Sep 4

Prototype 1:

For this week's prototype, I've decided to test a low-fidelity idea of my Capstone proposal.

I asked myself: _What's the simplest form my initial idea can take?_ The answer came from plain journaling -- a paper and a pen.
Since I wanted to make this public, I have chosen two spaces to put up journaling prompts and plain stickers for others to write on -- our dorm room's common area and A5C 4th floor.

The goal is to get other people curious about some stickers on the wall, read the responses of others, and leave a response of their own.

Questions asked:
1. **What has been a highlight of your week?**
2. **Any challenge that you wish to share?**

Another task of this is to foster a "comfortable" (need to think of a better term) space for others to express themselves honestly and freely.
A hope for this public journaling prototype is rooted in the concept of "sentimental education" -- when others learn from each other emotionally.
What kind of emotions does the text evoke? Can we empathize with others? How does reading about others' highlights and challenges make us feel?

Things to reflect upon further:
- Can I potentially collaborate with Health & Wellness or REACH with this? What about my classes? Can this be added to any of my class curriculums?

![](/media/a5c.JPG)
![](/media/common-room.HEIC)

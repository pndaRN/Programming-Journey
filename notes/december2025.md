---
nav_order: 9
---
# November/December 2025 Wrap Up

Where did these last two months go??? The holidays really make time get away from you. By the time I realized I hadn't written anything for November, it was almost halfway through December! Time flies when you don't know what day it is half the time. Anyways, enough talk about time—it's *time* to talk about coding.

## Merry Bootsmas

In November, I really didn't feel like I made much progress in the Go courses, but after looking back at the last wrap-up, I was only starting them. Now here I am with the first two done, and I'm starting SQL/Pokedex. When I get to a guided project, I still like to have at least one course I'm going through because that allows me to learn while at work—I can only work on guided projects at home. So far, the Pokedex project is pretty easy in my opinion, but I'm sure it'll ramp up as I get into sections 2 and 3.

SQL is really interesting! So far I like working with it because it just makes sense to me, lol. I'm ~40 out of ~120 lessons in, so I'm sure it'll ramp up as I get deeper into it. Maybe the combo of working in Go and SQL is where it gets spicy. However, learning SQL has gotten me excited to finish the Go courses and backend work because I'm ready to start building the backend for the app I'm making!

## [ComplyHealth](https://complyhealth.vercel.app)

This is wild to say and think about—I have a functioning app that's in beta testing! It took about a month and a half of a mixture of vibe coding and actually coding to build this. It was actually pretty cool to see what Claude Code could produce. I've only heard negative things about vibe coding since I started learning programming, so I was wary about it. However, because of my hesitancy, I think I ultimately had a good experience with it. I still checked all the code it wrote to make sure it made sense, but overall I was able to make this app way faster by mix coding (that's what I'm calling it) than just hand-rolling it. I'm sure there are some inefficiencies and better ways of doing things within the code, but since I'm using Flutter, it's already inefficient, and I'm not doing anything graphically intense, so I figure it's fine.

All that to say—we need beta testers! If you're interested in testing our app, sign up on the website. Invites come out every Tuesday!

### What is DevOps and I Think I Am One

So with completing the beta of ComplyHealth, I had the *pleasure* of learning DevOps, and wow, that was a lot. If you've been following my journey, I do all my dev work on Linux, so finding a way to port to iOS was... **challenging**. What I figured out is that I have to rent a Mac online to build the app on an Apple device, then download the IPA file to upload to Firebase/TestFlight. That was too many steps, so I automated it using [CodeMagic.io](https://codemagic.io).

This took a couple of days to set up because I had to set up both my Apple Developer account and my Play Store Developer account. Then I had to figure out how to properly write the codemagic.yaml. I first just tried to vibe it out, and needless to say, it **FAILED**. I then decided to use my brain and read the docs. Wouldn't you know it—it worked (with minor changes that I then vibed out). I now have automation where when I push to my develop branch, it sends to CodeMagic to build and send to internal testing (the team and close friends) via Firebase. Then when I push to my main branch (which I'll rename later), it pushes to the closed beta, which is everyone who signed up on the website.

## C is My Love Language

I'm back writing in C! So besides everything I wrote about above, I decided to learn more about gamedev specifically. The reason is because I think games are so cool, and the idea of building my own is exciting! So I'm making a Galaga clone that's going to be bacteria and antibiotics. I'm using SDL2 as my library to interact with the computer. So far, I have a black box on a screen!

![it_aint_much](https://pndarn.github.io/Programming-Journey/assets/img/oct/it_aint_much.jpg)

I really enjoy the simplicity of writing in C. Everything is what it is and not hidden behind complexity. If it's there, it's because you want it there. Yes, it creates more "work," but you know exactly what's going on because there isn't much under the hood. Basically the complete opposite of what I was doing with Flutter, lol.

## Gaming

Lastly, I'm visiting some old friends in the gaming world and taking a break from Lies of P—Dead Cells and League of Legends. About once a year I get this kick to play League. It lasts only about a month, and I have a great time with it. So currently just enjoying my time playing that. I play Dead Cells when I truly want to turn my brain off because for me that game is just all reactionary, no thinking, lol.

## Conclusion

The past two months have been great! I've learned a lot and am more motivated than ever to keep learning and keep going. I feel like I'm getting a good mix of learning on my own, building something with a team, and having a personal project to work on. I feel like having all three is a great way to stay motivated to keep going. I've noticed when one feels sluggish, the others feel motivating, so you keep going.

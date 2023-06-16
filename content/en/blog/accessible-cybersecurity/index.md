---
title: "Accessible Cybersecurity"
description: "Let's examine why there are so few disabled people in cybersecurity."
lead: "Where are the disabled people?"
date: 2020-11-04T09:19:42+01:00
lastmod: 2020-11-04T09:19:42+01:00
draft: false
weight: 50
images: []
contributors: ["Ana Batranovic"]
---

I've been in tech spaces for a few years now, mostly cybersecurity spaces, and more often than not I stick out like a small car in a sea of two-legged mammals. This is because, usually, I am one of very few femme-presenting people, and always the only disabled person in the room. You would think an industry such as tech, where it’s common to work from home in perfect individually-configured conditions, would be ushering in hoards of disabled people. All we hear about is the lack of people in cybersecurity roles, it would make sense to tap into the group of people who are desperately seeking employment. This is not the case, as we can see if we look at the group photos of any conference ever. 

So this begs the question, where are the disabled people?

## A QUICK PREFACE

Disability is a complicated and nuanced issue. I cannot speak for others, as my experiences are individual and only my own, however, I can present some theories and observations. These are silly thoughts I have spent very long churning over in my head, and while I'm sure they have merit and are worth thinking about, they are also inherently incomplete. I am only one person and cannot cover every single experience - if you would like to know how you can create a more inclusive space for a specific marginalised group, the best thing you can do is ask a member of that group. 

If you're someone in a leadership role or with the power to change how things work at your job, take the initiative and talk to a marginalised member of your team. The biggest experts on any specific flavour of disability are the people with that flavour of disability.

## THE 4 GATES OF INACCESSIBILITY

When we're thinking about WHY there are very few disabled people in tech, we can think of it in the context of gates. Each gate marks an important obstacle that may stop a disabled person from proceeding further. As we delve deeper and deeper, the obstacles become more specific and manageable, and maybe even fixable. 

Note: The hell allusion is not lost on me, and I think it is very funny

### GATE 01: SYSTEMIC ISSUES & STAIRS (OR, VERY NARROW DOORS)

This one is pretty simple - if a person does not have the equipment they need, their performance and their opportunities will suffer. This is not something one person can fix. Systemic discrimination and injustices are a lot better than they were 30 years ago, disabled people are treated as actual human beings and not bags of meat, and we have movements such as the ADA ([Americans with Disabilities Act](https://www.ada.gov/)) to thank for that. 

The ADA fundamentally changed how legislation approached disabled people, and it ensured that those who were previously ignored finally gained the right to school and work. It was a cornerstone in disability rights, and is now regarded as the international standard. Despite this, many people still simply do not have access to the equipment they need to use a computer. Solutions exist always, but whether or not that solution is feasible (or covered by insurance) is unfortunately a matter of luck. 

This gate is also dedicated to all the stairs in my life. Again, I feel like this one is pretty self-explanatory, but if a person can't enter a building, they can't interview for a job. It does not matter if they're the most qualified candidate ever, if the interview is not online, it is very difficult to have it 4 floors away from the interview room. I can count on 10 hands how many times I've had to be quite literally carried up the stairs, and it is never a good time! If you're so inclined, consider investing in a ramp, or an elevator. They're wonderful, I highly recommend both.

It's a bit disheartening, but in my opinion, this is the biggest obstacle disabled people face - navigating a system not built for them and, in the context of job hunting, competing in that system. Something as simple as going to a conference and networking might be derailed because of insurance issues. This might explain the intense willpower of disabled people, it's ingrained in many to fight very very hard for what they want, and I see this as our greatest strength. System issues are also the hardest obstacle to fix, systemic change is a long and arduous process. 

The good news: by fighting the system, we can change it for the better.

### GATE 02: SOCIAL ABLEISM

I say “social ableism” instead of just “ableism” to distinguish it from the previous gate. Similarly to the systemic issues that plague disabled people, social ableism can isolate or alienate disabled people from tech spaces. I would argue [hustle culture](https://themighty.com/topic/adhd/hustle-culture-adhd-disability-community/), and “try harder” culture, are forms of social ableism - they are very unhealthy in their own right, but they're also almost always unfeasible for someone with a disability. 

Setting reasonable expectations (no "grinding") can ensure that everyone can stay on track, at their own pace. The tech industry is guilty of this, with employees often being forced to work overtime. This is more so a consequence of capitalism than anything else, but I do think it can be minimised if everyone does their best to do so.

The most important thing to keep in mind here is communication and listening. Talk to a disabled person, check your assumptions (this will tie back to gate 5), and if a disabled person calls out something you said or asks for a change, consider it.

### GATE 03: INACCESSIBLE TOOLS / CHALLENGES

Now that the unfixable stuff is out of the way, we can focus on the extremely fixable. In her article, [Making Hacking Accessible](https://skerritt.blog/making-hacking-accessible/), Autumn (also known as Bee online) talks about the dire state of cybersecurity tools. More often than not, cybersecurity tools are extremely inaccessible - which is funny considering they're all text-based. You'd assume screen readers would work fine (or at least I did).

The main issues are:
- ASCII Art
- Text embellishments
- Lack of adequate “silencing” options

Something like this would not read well in a screenreader - and I apologise to anyone using a screenreader right now: 
```
    __             __               __
   / /_____  _____/ /_  _______  __/ /____
  / //_/ _ \/ ___/ __ \/ ___/ / / / __/ _ \
 / ,< /  __/ /  / /_/ / /  / /_/ / /_/  __/
/_/|_|\___/_/  /_.___/_/   \__,_/\__/\___/
```
note: this kerbrute logo shows up at the beginning of every kerbrute command, and as far as I know cannot be disabled.

Similarly, challenges that involve something like steganography are inherently inaccessible. Unless you have a very, very good reason for a challenge that involves images, best to avoid making them the crux of the challenge. For example, I think reconstructing a PNG is reasonable, but I think challenges where you have to look through footage for a frame that has the flag in the very corner, are not.

Here's where I think the magic lies. Most hacking tools are open source, by the people, for the people. If, for every project, someone added a `-quiet` flag, the experience would be miles better for all. UX and usability are often underestimated, despite being extremely powerful. 

Hear yee, hear yee, fellow developers. Add a flag (`-quiet`, for example) which removes ASCII graphics and elements, enabling easy screen reader use.

### GATE 04: LACK OF EDUCATION ABOUT DISABILITY

We have reached the final gate! I find this one the most interesting because of how widely misconceptions vary. The list here is very long and uncoverable by only me because I am only privy to the misconceptions I have experienced. 

I do think that this is a bit of an insidious phenomenon. Because of the gates we've already covered, many people simply do not have a chance to interact with a disabled person at a technical level, or even a casual one, and as such are not sure how to carry themselves. The answer is pretty simple: don't overthink it, ask questions, communicate.

The main misconception I’ve experienced is the fundamental difference in the perception of disability between someone who isn’t disabled and someone who is. Disability is inherently an **EXTERNAL** issue, whereas many ableds (people who are not disabled) think of it as an **INTERNAL** one. This can best be explained and demonstrated through the following analogy:

Imagine you wake up one day, and you find that everyone around you has grown wings. You have not, but that’s fine, you feel pretty neutral about it. There are things you can’t do with your loved ones now, sometimes they go and fly around and you don’t, but there’s no change to your relationship nor is there a difference in how you live your day to day. You’re the same as you were the day before, when no one had wings. Then you go out. You try to, at least, only to realise that you can’t, because the owner of the building got rid of the stairs for “ease of flight”. This is a problem. You now have to go back inside and get one of your fellow winged housemates to carry you to the ground floor. You’re a little worried now, and this worry grows exponentially as you realise that every single building is like this. You could buy prosthetic wings, but they’re really expensive and absolutely not anywhere near what you can afford. In this context, you are disabled, despite your body not having changed at all. The issues that come with your disability are not internal, you don’t feel any different, but external, the way you’re forced to go through the world.

No matter what, the human body will always slowly fall apart, so you cannot expect humanity to “cure” disability, nor should you. Disability is a part of life, it is not a defect, it is extremely neutral. What we need to focus on is making sure that accessibility is a priority, making sure that we aren’t cutting out a group of people who can and will positively impact society.

I also think the benefits of disability often get overlooked. There are certain skills that many disabled people have that ableds generally have fewer opportunities to cultivate. A couple of examples come to mind:
- Good time management - Disabled people have to learn their limits in order to function, and have to plan out their day accordingly. This is something that comes naturally after a while.
- Clear, succinct communication - If you need help to do certain things, you get very good at giving instructions and explaining what you need, and you get very good at working in a team
- Adaptability & Problem-solving - Navigating a system not built for you means adapting to that system, or adapting the system to you. Flexibility and the readiness to solve problems are natural consequences of that. 

These are all skills that are extremely useful in a professional environment. Disabled people need to be given the opportunity to showcase, explore and develop these skills. 

## WHAT DOES IT MATTER, REALLY?

So maybe, if you're a little evil (that's okay, we all are), you're thinking, who cares? Well, you will, my dear abled, in about 20-30 years once your body starts giving out. I'm not going to make an argument detailing why “disabled people are deserving of opportunities, actually” because it is common sense and basic human decency. I will, however, explain why inclusion in cybersecurity really matters.

The bottom line is, for it to work, cybersecurity needs to be something everybody can participate in. [A strong cybersecurity program should be comprehensive in scope](https://blog.lastpass.com/2023/05/the-importance-of-accessibility-in-cybersecurity/). Creating accessible cybersecurity resources, materials, and training programs ensures every person can make informed decisions about their own security. It also allows a very big group of people, with a very different perspective on the world, to shape these materials for the better. This means incorporating accessibility standards and guidelines during the very early stages of development to ensure that security features and controls are usable by all. A way to make sure of this is to implement certain accessibility standards by law. Some countries already have laws that prevent inaccessible buildings from being built, the digital should be no different. 

Think about the ways people interact with your product. Consider what the options for interaction are, and incorporate as many additional ones as you can. Accessibility is by no means easy, often it is akin to pushing a boulder up a very steep hill, however unlike Sisyphus, we actually might be able to reach the top.

## ADDENDUM

This article was originally written for an [inclusivity panel at Athen’s 2023 BSides](https://www.bsidesath.gr/index.php). I wanted to share some thoughts about disability in cybersec. I hope you found it interesting! 

If you have anything to add / want to contact me (i’d love to chat more about this!), you can find me at ana.batranovic@gmail.com, or if you want to buy me a coffee (i don’t like coffee, so it will actually be tea), I have a Ko-Fi which you can find [here](https://ko-fi.com/aquilosec). I’m definitely hoping to write more disability-related content, as well as more technical red-team stuff, so check back soon! 🙂 

Thanks for reading - till next time! ♿

Ana
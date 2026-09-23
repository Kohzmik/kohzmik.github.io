## Overview

I passed the Hack The Box Certified Penetration Testing Specialist (CPTS) exam in August 2026. Since then, quite a few people have asked me how I prepared and what the exam was like. Instead of answering the same questions over and over, I thought I'd put everything into one blog post and keep my notes and resources in one place.

## My Background

I wasn't starting completely from scratch. I'd taken part in a few CTFs, earned the Practical Network Penetration Tester (PNPT), and picked up certifications such as CompTIA A+ and Microsoft Azure Fundamentals (AZ-900) along the way. I'm also currently in my final year of studying Information Technology.

That background helped, but the CPTS still pushed me. It wasn't just about getting shells or finding flags. I had to become more methodical, take better notes, and explain what I'd found in a proper penetration testing report.

## Preparation

### HTB Academy

The CPTS path on HTB Academy is huge. It starts with basic enumeration and eventually gets into full Active Directory compromise chains. I completed it over roughly five to six months, although my studying was a bit on and off.

Completing the Academy path isn't optional. You need to finish 100% of the Penetration Tester job-role path, including the hands-on skills assessments at the end of each module, before you can start the exam.

If you take one thing from this post, let it be this: **don't skip modules or look up answers just so you can move on. Get comfortable with being stuck.** Every section is there for a reason, and the exam has a way of finding the gaps in your knowledge. The module you skim could easily contain the exact concept you need later.

Take your time, do the exercises, and make sure you understand why something worked instead of just copying commands until it does.

### Additional Resources

People often say the course material is all you need to pass. That's probably true, but I still found extra practice useful. It helped me reinforce what I'd learned and feel a bit more confident before starting the exam.

- **HTB CPTS Track:** I used this alongside the Academy material because the machines mostly line up with the CPTS curriculum. A lot of them involved Active Directory Certificate Services (AD CS). My exam voucher was getting close to its expiry date, so I didn't finish every machine. I went as far as I could on each one and then moved on.

- **HTB Pro Labs:** I spent about a month on Pro Labs and completed roughly 25% of Dante and 50% of Zephyr. They're chained environments where you pivot through multiple machines to reach an objective, so the experience is quite similar to the kind of thinking you need for the CPTS. If you have the time and money, they're worth doing. If you don't, the CPTS Track is cheaper and takes less time.

## The Exam Experience

The CPTS exam gives you ten days to work through the environment and submit your report.

When you click **Start Exam**, you receive a letter of engagement that explains the scope, objectives, and rules. It feels similar to the start of a real client engagement. The assessment is black box, so you're not handed an obvious route through the environment. You need to enumerate properly, identify vulnerabilities, and work out how the different pieces fit together.

I started my exam on 16 August and captured the first flag in under 24 hours. I was honestly ecstatic because the first flag has a reputation for being one of the harder ones. By the end of day two, I'd managed to capture four more.

Things slowed down after that. One stage took me around two to three days to solve, and a later stage was easily the hardest part of the exam for me. Looking back, the technical problem itself wasn't impossible, but it felt much worse while I was watching the clock and wondering whether I'd have enough time left for the report.

I went back through the relevant Academy material, checked my methodology, and kept working through what I had. Eventually, I found the path forward.

At that point, I had plenty of screenshots and rough notes but hadn't written any of the actual report. I decided to stop working on the environment for a while and start turning those notes into proper findings. After that, I completed a few more objectives, finished the report, and submitted it in time. Then came the good news: I passed.

The biggest thing I learned was not to panic when I got stuck. The environment is supposed to challenge you. Being stuck doesn't always mean you're completely lost; sometimes you just need to slow down, revisit your notes, and enumerate again.

## Writing the Exam Report

The report is a major part of the CPTS. It isn't something you can rush through at the end and hope for the best. Even if you compromise the whole environment, you can still fail if the report isn't good enough.

I used the following tools while writing mine:

- **SysReptor:** This is an open-source penetration testing reporting tool. It helped me organise the findings, keep the formatting consistent, and export everything as a clean PDF. I found it much easier than trying to build a report from scratch in Word. HTB also has a SysReptor reporting guide that's worth reading.

- **Claude:** My notes can be very rough, so I used Claude to proofread parts of the report, especially the executive summary, and catch spelling or grammatical mistakes. The technical work, evidence, and findings were my own; I used it to help make the writing clearer.

At a minimum, your report should include:

- An executive summary
- The attack chain, showing how you moved from the initial access point towards the final objective
- Individual findings with severity ratings, screenshots or other evidence, and remediation advice

My advice is to write your findings as you go. Don't do what I did and wait until you're stuck before starting the report. I was so focused on following leads that I didn't want to break my momentum, but it cost me time later. Even writing a rough finding while the details are still fresh will make the final few days much easier.

## What I Took Away From It

The CPTS helped me improve more than just my exploitation skills. I got better at approaching a network systematically, following attack paths through Active Directory, pivoting between hosts, keeping useful evidence, and explaining technical issues in a way that both technical and non-technical readers can understand.

It also taught me a lot about managing my time and staying calm when an approach wasn't working. Those aren't flashy skills, but they matter during a real engagement.

## Final Thoughts

For me, the CPTS lived up to the hype. It's one of the best entry-level offensive security certifications available, and the practical format makes it much more interesting than an exam based on multiple-choice questions. It was stressful at times, but looking back, I genuinely enjoyed it.

Would I recommend it to beginners? Yes, as long as they're prepared to work through the full learning path and spend time building a proper methodology. The recent HTB price increases make it harder to recommend if you're on a tight budget, but if you can afford it, I think the experience is worth it.

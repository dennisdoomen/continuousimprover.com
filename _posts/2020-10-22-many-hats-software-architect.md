---
title: "The many hats of a software architect"
excerpt: "After a discussion with some folks on what being a software architect really means, I decided to capture the many hats you have to wear"
tags:
- collaboration
- software-architecture
---

Recently, at a tech conference in the Netherlands, I had a discussion with some folks on what being a software architect really means. Some people see it as some kind of authority that makes all the decisions about what the architecture should look like and what technical guidelines should be used. Others treat them as the folks that draw PowerPoint pictures from their ivory towers. And the most negative developers see them as an impediment for any kind of creativity. This triggered me to try to capture the many hats a software architect must wear.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2020-10-22/stephen-hocking-unsplash.jpg" class="align-center"/> 

## Be a tactician
Being an tactician is definitely the first thing that comes to mind. You need to protect the balance between the internal quality, pragmatism in solutions chosen and the pressure being put on the system by the business. And that balance can be different per code base and the phase that code base is in. For instance, something that's still in development may live with a slightly lower quality than something that's already in production. Especially when you're working towards a Minimal Viable Product, the rules can be bend for a while, provided you catch up after that. But anything that's in production, must live up to the highest standards. 
 
Being pragmatic is also far from trivial. Developers love to build spaceships that to go to Mars, even though it's fine to target for the Moon first and learn from that. But what are we targeting for? The moon or Mars? That's why an architect must also work closely with all other stakeholders inside and outside the organization to understand their needs, expectations and time lines. So whatever decision you made, you need to ensure you clearly communicate the plans, ideas and global time lines through a fully transparent technical roadmap. This avoids confusion, unrealistic expectations and keeps the conversation going. 
 
## Be a coach
Another big part of being an architect is to coach the developers you work with to work to align them with the architectural vision. But people are different, so you need to accept that different people learn things in a different ways. This requires you to keep sharing your vision through different channels such as blog posts, code reviews, pair programming sessions and regular technical meet-ups. You also need to realize that depending on the maturity level of the developers involved, you need to adjust the boundaries and goals that you define for them. 
 
For relatively unexperienced developers, you define standards and rules that they have to follow. At that stage, they may not fully understand why they are needed (even though you keep explaining it), but it will provide them with the necessary boundaries to be successful. When that developer gains experience and becomes more mature, those rules change into guidelines that provide sufficient room for them to fail safely and learn at the same time. Eventually, for the senior developers. the focus will move from guidelines (that remain) to goals. 
 
Finding that balance between coaching and being a police officer is something I'm still struggling with. On the one hand, you want to create a sense of ownership that can fuel the passion developers already have. But on the other hand, you want to help them avoid fall in the traps you fell yourself. I often compare it with with small children running around a low table with a large glass of water. You know that at some point they will cause the glass to topple causing all that water to spill on your table and that expensive wooden floor. You can tell them that, but they won't truly realize it until it goes wrong. 
 
So finding that sweet spot between enough progress on the development work and empowered developers is very hard. This will require you to understand the developer's strengths and weaknesses. What drives them? What annoys them? Where are they on the maturity level? Are they still learning skills like TDD, SOLID or DRY? Have they mastered them, but ended up in a place of dogmatism where everything needs to be DRY? Or do they truly understand that every principles, pattern or tool has context, purpose, pros and cons? 
 
## Be a negotiator
A tactician? A coach? Does it stop there? No, it doesn't. A good architect is also a negotiator that works to get buy-in from the teams he works with. This is something that feels very political to me some times. It involves working with groups of people on sound technical proposals and then driving that proposal into a decision or consensus. You need to realize that you will never satisfy everybody, but still to try get everybody's opinions and concerns in the final proposal. 
 
Sometimes, when you discuss a proposal with a bigger group, you may discover that the participants are not even communicating at the same channel resulting in unconstructive debates or a scope that goes out of control. In those cases, it's better to form a smaller group to have a more constructive discussion. Another reason why I see discussions going awhole is that people are looking at different horizons. A proposal for a short term solution may be looked at as a long-term solution, or vice versa. A quick-and-dirty solution might be totally fine, as long as it is crystal clear to everybody that this is indeed a short-term solution. If the participants don't realize the time lines, you may end up in a debate with somebody that proposes a solution that everybody else treats as over-engineering. 
 
And for those people that keep opposing to a plan, it is often worth your time to sit with them privately and to try to understand where there opposition is coming from. Maybe a slight adjustment in the proposal is what it takes to get them on board after all. And if that doesn't work, having the majority of the group on-board can be enough to convince or coerce that last person to support the plan. 
 
But don't be afraid to be decisive when discussions become fruitless. In the end, you want consensus and give everybody a chance to be part of the decision making process, but if that's not giving you a solution within an acceptable time frame, force a decision. We're not in the business of never-ending discussions. You may disagree with a decision, even after all these debates, but as a professional you still commit to the decision and promise not to undermine it. 
 
## Be a partner
The architect in an organization is just one of the many roles people have to fulfil, so it's crucial to understand and maintain healthy and respectful relationships with the other roles. Obviously, the exact set of roles highly depend on the structure of your organization, but it's not hard to identify stakeholders like tech leads, product owners, managers, but also other teams and departments. Your job is to be a partner to all of them and ensure you take into account their opinions, wishes, but most of all, their frustrations. 
 
For instance, you work with the managers to understand the business strategy and organizational vision and to map that to an architecture vision that will support that. But you also need to try to defend the technical debt the teams have been accumulating and how much capacity is needed to keep that under control. And don't forget the other teams and departments that work with the results of your architecture. You definitely want to understand their needs, frustrations and wishes. Especially if the teams you work with don't put things in production directly, it's crucial to ensure a continuous feedback loop that brings in real-world experiences back into the development teams. 
 
With all that knowledge, you work with the product owners to translate that architecture vision into the epics and stories that are needed to realize the right milestones at the right time. Then you talk to the tech leads to understand their technical challenges in adopting the architecture vision and to help them build the right thing the right way, right now. In other words, you help them to find the balance between what's good enough right now and what the solution may look like in the future. 
 
## Be a protector
Most of what I described up to know is about collaboration, consensus and empowerment of people. But sometimes you have to be the guardian of the architectural and technical quality. That requires you to take the lead in introducing industry best practices and common design heuristics and principles, but also helping people to not go overboard with these and thereby shooting themselves in their own foots. 
 
You need to be the conscience that ensures technology is used as a means to solve business problems and not as a goal on itself (which happens too often), without foregoing the room for innovation. And don't let developers reinvent the wheel by solving problems that have already been solved by off-the-shelf or open-source solutions. But even there you need to find the balance. Even open-source software is not truly free. It comes with quite some legal consequences around licensing and you still need to consider the costs and impact of somebody abandoning that project. 
 
People come and people go, especially in the current IT landscape. Making sure new joiners can quickly get familiar with the code-bases, whether or not they truly joined the company as a new employee or moved between teams, is crucial for scalability and continuity. This involves training developers how to write code that is discoverable, testable, readable and works in isolation, or in short, to write maintainable code. But it also is about creating awareness of how important it is to capture decisions and their rationales in architectural decision logs, and to ensure the source control history is clean and understandable. These topics are often opinionated and cause heated debate, but still need to happen. Doing pair programming coaching sessions, code reviews in groups, technical presentations, refactor-by-example and introducing coding and design guidelines are necessary evils you can't avoid. 
 
## In short
The gist of this post is that a great software architect knows when it's the right time to be a tactician, a coach, a negotiator, a partner and occasionally, if the situation requires it, a police officer. It means that this role requires a unique blend of skills that not only includes deep knowledge of architecture styles, technology and industry best practices, but also strong soft skills, the ability for empathy and the skill to create bridges between techies and non-techies. Does that make sense to you? Do you agree or disagree? Any specific angles I missed? I would love to hear your thoughts by commenting below. Oh, and follow me at [@ddoomen](https://twitter.com/ddoomen) to get regular updates on my everlasting quest for better solutions.
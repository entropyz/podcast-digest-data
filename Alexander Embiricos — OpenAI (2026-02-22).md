---
type: 20vc-episode
guest: "Alexander Embiricos"
company: "OpenAI"
role: "Codex"
episode_type: interview
date: 2026-02-22
youtube: "https://www.youtube.com/watch?v=S1rQngjpUdI"
transcript: "https://20vc.substack.com/api/v1/file/980ea825-af7e-47e3-bb9b-ac87a48b3325.pdf"
newsletter: "https://20vc.substack.com/p/20vc-newsletter-22nd-february-2026"
tags:
  - 20vc
---

# Alexander Embiricos — OpenAI

> Codex @ OpenAI | 20VC Interview | 2026-02-22

## Key Takeaways

---

## Links
- 🎬 [Watch on YouTube](https://www.youtube.com/watch?v=S1rQngjpUdI)
- 📄 [Full Transcript (PDF)](https://20vc.substack.com/api/v1/file/980ea825-af7e-47e3-bb9b-ac87a48b3325.pdf)
- 📰 [Newsletter](https://20vc.substack.com/p/20vc-newsletter-22nd-february-2026)
---

## Full Transcript

[00:00:00] Welcome to 20 Product with me, Harry Stabbings. Now 20 Product
is the monthly show where we sit down with the best product leaders to reveal
their tips, tactics, and strategies to scaling the best products and product teams.
Now, the real question is, who's gonna win? Is it Codex? Is it Claude Code or is
it Cursor?

Well stay joining us in the hot seat. We have Alexander and Kos product lead
for Codex at OpenAI. This is an incredible discussion. Time to get the notebook
out. I want your feedback. Let me know what you think. Harry, at 20 vc.com.

But before we dive into the show today, the early story of Atlassian is probably
very similar to your own. Atlassian knows firsthand the challenges that startups
face every day and that the right tools are essential to go from MVP to IPO.
That's why Atlassian for Startups gives eligible companies up to 50 seats free on
the premium addition for products like Jira, confluence, loom, JIRA, product
Discovery, compass, and Bitbucket.

So your team can use the. [00:01:00] Best in class tools to plan, track, and
collaborate on work, whatever that work may be. Many of today's most
successful startups like CloudFlare, Canva, and Rivian relied on Atlassian for
their growth trajectory, and Atlassian wants to give that same opportunity to the
next generation of.

Builders and investors, we know how important it is to focus on building the
right things early. Whether you are in the sticky note stage or well on your
journey, teams at any stage can work smarter together. It's never too early to
start with Atlassian. Head on over to atlassian.com/startups/harry for more
details and eligibility.

After Atlassian helps your team build and ship great products, Intercom helps
you support the customers using them. If you are looking for a way to transform
your customer service, let me introduce you to Fin Baby. Fin is the number one
AI agent for customer service. Resolving up to 93% of customer queries.

Automatically. There is no other agent that can do that. Not 93% of customer
queries, okay? No other agent [00:02:00] can do that. So why choose fin? FIN is
the best performing AI agent for cs. FIN doesn't just answer questions. It takes
actions. It automates the most complex customer queries like refunds,
transaction disputes, technical troubleshooting with speed and reliability.

I wish my team was speedy and reliable. Beats every competitor in. Every head-
to-head bakeoff completely configurable and code optional. Setup my word. I
mean the benefits just go on and on. It's easy and efficient implementation. It
works on any help desk with no tedious migration needs. It's trusted by over
6,000 customer service leaders, including top AI companies like Anthropic,
lovable Synthesia, clay, Vanta.

So if you are ready to transform your customer service team, scale your support
and give team members time to focus on the really high level strategic work.
Learn more about fin at fin.ai/two zero vc while fin scales your support without
losing speed. Reforge shows you how to translate that scale into [00:03:00]
durable product-led growth.

Everyone shipping faster than ever. Cursor Claw code Codex. AI is making
code and writing code faster than ever, but here's the problem. Speed means
nothing if nobody uses what you ship. That's where Reforge comes in. Reforge
is building a product discovery engine that sits upstream of your coding agents,
not another prototyping tool, research repo or AI interviewer, but a product that
will ingest your customer data.

Generate variations of product solutions. Validate the solutions before code is
written and hand off winning directions to your team. Reforge kills product debt
before it starts because every unused feature you ship isn't just wasted
engineering time. It's a maintenance burden, complexity, tax, and surface area
that you cannot shrink used by product teams at companies like.

Toast, Vimeo, Klaviyo and many more. Reforge helps teams ship more features
than actually get used. Try Reforge at [00:04:00] reforge.com/build and use the
Code two zero vc. That's 20 VC for one month. Free of Pro. You have now
arrived at your destination.

Alex, I'm so excited for this. Dude, I told you I've been at a PE conference and
all I could think was, thank God I've got Alex next. 'cause this is gonna be a
great one. So thank you so much for joining me, man.

So excited to be here. Thank you.

Now this is a weird first start, but roll with it. You'll, you'll understand my
British intricacies. I'm fascinated by people's motivations. Aren't you motivated
more by the fear of losing or like the thrill and excitement of winning?

I, I'm a maximalist. I'm definitely much more motivated by the idea of winning
than the fear of losing, but I'll admit to you something. One, I was running a
startup before joining OpenAI, and one of my darkest moments, and there were
many dark moments while I was running the startup, was recognizing that I had
spent the fast few months trying to avoid losing,

all of a sudden I was like, oh my God, that is why I'm so unhappy, and that's
probably why this startup isn't going well.

you know, I, I basically, every now and then I have [00:05:00] to cash myself
and like flipped back into this idea of winning. But really what motivates me
even more than that is I think I just love building things and building things for
people. And man, I'm so excited for this year because many amazing things that
don't exist yet are gonna be built and given to a lot of people.

 I'm diving right in. Elon said that coding is one of the first professions to be
largely automated. you agree, given your position and what you see day to day?

for sure. I would agree that coding is one of the first domains where LLMs are
really good. But you know, what does it mean for coding to be automated? It's
like kind of a heavy statement, right? for example, now that we no longer write
assembly, like when that change happened and we moved to higher level
languages, did we say coding is automated?

Not really, right? We were just able to write much more code and then as a
result, actually. There was much more demand for code and there were many
more software engineers required. But yeah, part of what they used to do was
automated in the same way that like, do you know the origin of the word
computer?

No.

I might pronounce the location wrong, but I think it was at Bletchley Park.
There were all these machines for like decoding German enigma and like
[00:06:00] there were humans who would like punch out punch cards and like
put them into the machine and do a bunch of like tabulated math, I'm probably
butchering this, but basically there was an intensely manual part of work.

And even like the first spreadsheet software was kind of loosely based off this
idea that you would have an office full of desks arranged in a grid and people
doing tabulations and then passing their sheets to the next person. And so all
these things, like those specific tasks have become automated, but every time
that's happened, there's been an explosion in demand for the output.
And so you need many more people actually to do that kind of work, even if the
specific task has changed.

So you think we'll have more engineers in five years, not less.

Yeah. And I, you know, sometimes we change what terms mean, right? Like the
term computer now refers to something else, but the, now we have the term
software engineer and so I definitely think we'll have many more builders. And
you know, something interesting that I'm observing now is like there's this
compression of the talent stack.

you know, you still need software engineers today, you still need designers. I'm
a pm Do you need PMs? You know, you can have a fun, fun, some fun jokes
about that. I don't think you need them. but maybe when you say engineer, you
might be thinking of [00:07:00] someone who's like much more full stack than
has been true before. Like even if you go back a few years, you had many more
places where there was like the backend engineer and the front end engineer.
Whereas like now, at least if I think about the Codex team, like that's much less
the case and things are much more full stack.

Right. And so I think this, this talent stack will compress, but we'll still have
people building.

 Why do you think we don't need PMs in this world? You, you, you dangled the
carrot.

Yeah. Yeah, it's, it's my fun joke. I think, well, first of all, I think it's incredibly
hard to define what a PM is, what a product manager is. I kind of think of the
role as like actually explicitly undefined. And your goal is just to adapt to
whatever the team or business needs. often if you have a bunch of people, like
trying to build as quickly as possible, then what a, what a product manager can
do is spend time like taking a few steps back and trying to look around corners
and figure out what to do.

You know, collaborate with the, the folks in go to market and maybe be the, the
team's like greatest cheerleader and quality raiser. But like all of those things I
just described, which are maybe my current role could be done by a really
strong eng lead or a designer who thinks [00:08:00] a lot about product. And so
I think it's like often useful to have product managers, but you probably don't
want many of them until the team is really large.
I was stalking the shit out of you for the last few days, which was a very fun
expedition into your writing, into your tweets, into your prior interviews. And
you said that human typing, speed and validation work is the key bottleneck to a
GI not model compute or architecture. And it kind of left there and I was like,
help me understand why human typing, speed and validation work is the key
bottleneck and what you really meant by that.

For sure. Okay. That's a, that's a fun one. I think there are multiple bottlenecks,
but that's maybe the most sort of clickbaity one. So, if you don't mind, we'll do
this slightly socratically, like how many times would you say you use AI today?

30 plus times a day.

Okay, cool. How many times do you think, assuming it was like zero energy
expenditure from you, how many times do you think AI could help you per
day?

I mean, I, in, in everything, I think we'll

Yeah.

running 24 hours a day across every single thing.

Exactly. And like I hear things now [00:09:00] from engineers like at OpenAI
and also outside who, who were telling me like, you know, I constantly have
Codex running. I never close my laptop and if it's not running while I'm in a
meeting, I'm like wasting my time. I need to make sure Codex always has work
for me that it's doing.

And that's like super cool and super exciting, but that's a lot of work, right? To
like manage these agents and make sure they're always working and going back
to the 30 times per day thing. Yeah, like when we look at how often, codex
users are using Codex, it's like kind of this like tens of times kind of range.

And I think AI should be helping us tens of thousands of times per day. You
know, compute, budget, permitting will, and we'll get there over time. but the
problem is like, at least if I think of myself, like I work on this stuff, I know I
should be using AI for everything, but I'm too lazy to like type out that many
prompts and I am too uncreative to figure out all the ways that AI can help me.

And so I end up kind of at a similar number as you. you know, I still am at the
point where when I use AI to do something cool like prep for this conversation
with you, I'm like kind of proud of myself. I'm like, oh, cool. I managed to use
AI in this new way. that's fine for people like you and me who are like
[00:10:00] really interested in this topic, right?

But I don't think most people we should expect in order to benefit from, a GI
should need to like, put so much effort into how to use this tool. It should just
be effortless for them. I think the world we want to get to is one where, to use ai
you don't read and need to like figure out the right way to prompt.

It's just super easy for you and you don't even need to recognize that AI could
help you. It's just like knows you connected to your context and chimes in
helpfully.

that's where I think like Claude has done well in terms of the packaging they've
done, like Claude for legal, Claude for Excel, where you can implement it and
have a DCF model.

I'm not into models, but like better than one could do before. you think it is your
job then to productize the prompts and the human actions to remove that
bottleneck?

Yeah, totally. So I think that it is our job to make sure that we have the models
with the, with amazing capabilities, and then eventually to get to a world where
this is like highly productized. And so you just have this like magic text box or
audio input or whatever, [00:11:00] or you can just add AI to your like group
chat and it just starts to help.

But I think there's quite an interesting InBetween stage and I think that that is
actually where the most value lies right now. So here's what I mean. you could
try to productize. Like a specific feature of AI for a specific market. And I, you
know, the many companies are doing this, but I think it's a little bit hard to
know what exactly will work, what is the right form factor.

And someone was on your podcast earlier, and I, they said something that I
thought was quite interesting about how, you know, you cannot adopt AI at
Enterprise without fds.

Yeah, it was Matt

Fitzpatrick from, um, invisible ai.

Yeah.
So, so even though I am literally hiring fds, and if you're an FD please apply for
a job with me. I actually disagree with that entirely.

so what I think we need to do is build tools for people. Like you can use fde, as
Fitzpatrick said on the podcast, like to automate workflows, right? But then
you're limited by like what you, from your top down perspective can do, and
what you, from your FDE staffing can, can staff to be built, right?

But for me, the most exciting future with [00:12:00] AI is one where everyone
just feels like a superhuman. Or a God just like empowered by ai. And for that
we need tools that are for people, for individual users and that everyone feels
fluent with.

I think the, the phase that's most interesting that we're at now is building for the
kind of people who are interested in figuring out how to use ai. So what we
need to ship, and I think this was like the genius of like when Cloud code first
shipped, what they really got right, was they had this tool that was super easy to
use in whatever context you want just in your terminal.

And people started experimenting with where to use it. and so I think as we
think about AI being used outside of coding work, one of the most important
things we can do is not overly build it. Like, okay, this is. AI capabilities, but
only specifically for finance. Only for specifically for this workflow, but
actually build a much more open-ended tool that someone can just use for any
given task

creatively.

Yeah.

does that not put the onus or the effort back on the user? Back to the point of
your bottleneck of human action and lack of activity on them. If you don't
define the task, you put the responsibility on them [00:13:00] for the defining
the task, which humans lack the ability or inclination to do.

Yeah, so that's why I think it's the bottleneck. So basically, here are the three
phases in my mind. First, let's have agents work really well for software
engineering and coding because LLMs happen to be good at that. Next, let's
realize that for an agent to be useful more generally it using a computer is super
valuable.
And also we'll realize that all agents are actually coding agents. 'cause coding is
just the best way for an agent to use a computer. So let's take that same super
flexible idea, but make it available to anyone who's excited to explore and
tinker. We're already seeing people start to do this with like the Codex app, like
Codex app is built for soft for builders, but we're seeing builders use it for all
sorts of non-coding tasks.

Yeah.

Then finally, once we see what's working, let's build that like productization
that you were talking about, where you have highly specific features that just
work immediately out of the box for people. And I think we're gonna speed run
this entire like 1, 2, 3 journey, in the next month.

My challenge with what you said about kind of FDS and implementation
within enterprise is data security sensitivity.

Permissioning [00:14:00] access provisions is really freaking hard and people
are much less intelligent and, uh, confident than we give them credit for. I think
especially in large enterprise. Sorry. and I think you actually need an FDE to go
in and custom fit a lot of the different horizontal solutions to make it work. Am
I wrong?

I think you're right. If you're trying to go like all the way from zero to one and
you have this like, and I said, I don't mean grand negatively here, but if you
have like a grand vision for some like ultimate workflow automation system,
then yeah, you're gonna have to clear through all of these security hurdles, all
these like compliance hurdles that are really real, right?

Build connections to all these data systems and like systems of record and
action. yeah, so you're gonna need nty to, to do that. what I've seen is that when
we do these things top down, we're we end up like massively underleveraging
the potential of AI and like helping that company.

Whereas you can maybe do that in parallel, right? But if you can just give AI to
the people like actually doing the work, they can start to like get a mental model
for how [00:15:00] AI can help and then they can start pulling AI into their
workflows at the same time. Here's just like an analogy or, or something here is
like, imagine if, um, you work in like a customer support role and AI is being
brought into your role and starting to automate like meaningful chunks of your
work, but you've never heard of Chacha, nor are you allowed to use it, So in that
scenario, you have like no intuition for what this thing is, whereas. In a world
where actually you've been using cha piti for work at the same time as like parts
of your work are getting automated by an LLM, you have much more intuition
for how this works. And you know, I would argue you feel much more
empowered about this idea that it's being accelerated and you have some degree
of control to steer like where these automations are built as opposed to like, it's
like this complete like X Mackinac kind of thing.

that is quite disempowering. So bringing this back, like I think there is a way to
do this because the data control issues you mentioned are real, But at the end of
the day, every tool, every feature, every workflow is for a human who is
somewhere, An employee somewhere. And that employee's accessing that
tooling [00:16:00] via their browser or via their file system, like at the end of
the day, And so at the end of the day, everything comes to an interface that an
agent running locally on your computer can work with. And I think it's quite
unusual. Like an open, I we're building a browser atlas, And you might wonder
why. there are many reasons why, but I think one of the key reasons is that by
building a browser, and by controlling it like tightly end to end, we can build
like safe agentic browsing for enterprise.

That is a way to access things genetically, that is, that are otherwise not yet built
out by fds.

There are so many questions that I have to ask you. I I want to go back before I
lose thread. You mentioned about engineers, like not closing their laptops 'cause
they don't actually wanna lose productivity and time with, with Build and with
Codex, you partnered with Cereus and Cereus is the fastest provider obviously
of inference out there. Amazing win I think for both Bluntly, how important is
speed for developers when using Code Ice and in the future of AI code?

I mean, these simple answers, it's, it's super [00:17:00] important. we

have.

an inference monopoly, like you have it now and competitors don't?

this is just my opinion, but I don't think we're gonna end up in like this kind of
monopolistic world. I think, there's so much competitive pressure that there'll be
like multiple answers to this. But I will say that we have like news coming out
about that partnership soon, and I'm very excited for these kinds of things to
ship.
It's, it's gonna be awesome. But even so like, you know, with, uh, GPT 5.3
Codex, that model is like significantly, more efficient than prior models. And so
we, in the feedback we've heard is that people actually feel like now this is like
a very competitively fast model than before. So there's a lot of things you can do
just in terms of the model.

There are also things you can do like improving, how you do inference. So we
recently rolled out a change where in the API, like those models are served like
40% faster. And in Codex they're served. 25% faster. So I think like speed
matters a lot and we're kind of approaching it from all angles, like both the
hardware, how you do inference and the model level.

mentioned earlier about kind of putting it in the hands of users, [00:18:00] and
we talked about inference there. One of my dear friends is Jason Lemkin from
Sasa, and he says that actually inferences the new sales and marketing.

Instead of sales and marketing teams, you are paying for inference so users can
onboard quickly, easily see value, and you will actually see the removal of sales
and marketing teams. It's kind of like next gen of PLG.

 I don't know. I think I struggle with that. I think, you know, fundamentally in
this new world where anyone can build and it is increasingly easy to build
things. What, what is hard, right? I think having a good relationship with a
customer, knowing what they need is as hard as ever, maybe even harder as, it's
just like, there's just more stuff in the market to choose from.

you know, the other things that are hard are like building the right thing, having
a really high quality thing. But going back to the sales and marketing thing, like,
I don't think that goes away because I think that's as, like I said, I think that's
just gotten harder as the, as the markets, any given market gets more
competitive with more software out there.

how much of internal code for you today is produced by Codex? I remember
like Claude for work, Boris said was like a hundred percent or nearly a hundred
percent. How much [00:19:00] is internal Codex used?

So I'll speak for myself and then for the team, I would say like, most people that
I know are basically not opening editors anymore. and this was a step function
change that happened in. It, it's been happening gradually, but I'd say the key
external market touchpoint for this was like GPD 5.2 codex,
all of a sudden the model was like way better at running for longer, handling
tasks end to end, managing its its context, and following instructions.

And so we kind of saw this inflection point, and that's actually why, part of why
we built the app. so, what I think before GPD 5.2 codex, the, the kinds of AI
features we were using to write code were like tab completion, or maybe you
were pair programming with the model. And in my mind, you know, you still
needed to be at your laptop with your hands on the keyboard ish and like it
might go off and do a little bit of work, but you know, you, you kind of still
need to be there and like drive.

It's just like candling these small things for you. And then at the time of GPD
5.2 codex in December, we kind of switch to like actually. I'm just gonna fully
delegate this task. It's like, you know, I'm [00:20:00] gonna do a plan with it,
make sure we like the spec that it's gonna do, and then I'm just gonna let go, let
it cook.

And this is quite a different way of working. So it's like, it's changing, like
literally as we speak. And so part of why we, we built this code app that we
released last week is because we wanted to build like a form factor or user
experience where it felt like very ergonomic to be delegating instead of pairing
with an agent.

and so like delegating to multiple agents at once. And so even at Open ai, this is
changing massively. I don't have a percentage stat for you, but I would say like
the vast majority of code is written by ai. And I would say that now probably
like most people are not even like opening IDs may maybe if they are opening
IDs to like, maybe you wanna own the interface, right?

So you'll like help flesh out like the interface between like two modules and
then like AI fills it out. Or maybe you wanna like collaborate on a plan, but then
have AI fill it out. The code itself is not being written by humans anymore.

Well, we have IDs as a part of the stack in 24 months time.

It depends how you define IEE. so the, the formal definition, right? Integrated
development environment, I mean, that, that phrase is so squishy that like
[00:21:00] literally anything could be an IDE, right? So I don't think that's very
useful. If that's the answer, then yes.

You could even argue the Codex app as an IDI I don't think it is. Like, for me, I
think of an IDE as like a, a really powerful editor. and we explicitly didn't build
editing into the Codex app because we wanted it to be really clear how you're
meant to use it. So, you know, it has a lot of affordances for managing multiple
agents, for delegating, for, for reviewing changes.

it has really prominent skills, which are an open standard that are really useful
for doing non-coding work. Stuff like, you know, triaging tasks, or monitoring
deploys or something, but it doesn't have text editing.

if we assume a large percentage is done by Codex in terms of the code
produced, how. Do you do coding reviews? And is AI responsible for internal
coding reviews?

there are a few things here. first off, the spec for what you want to do or the plan
becomes more important than ever, think like architecturally, like how should
this code work?

you know, we recently shipped like a very prominent plan mode that works a
little differently than others where you have the agent go off and like propose
how it's gonna do something.

It's like quite a long [00:22:00] plan and then asks you questions about if you
agree on how it wants to do it or, or if you wanna have input. And this is very
similar to like if you had a new hire who was new to your code base you know,
they had to present a sort of req, a request for comments to the rest of the team
before they started doing the work.

So even though that's not formally code review, I would say review of the plan.
Is actually something that's becoming more important because we're entering
more of this like delegation phase of working with agents. So that's an
underrated thing. then okay, there's actual code review. I think a problem that I
hear a lot of people talking about, especially in the open source world, is like a
lot of AI swap.

Like people will just be submitting PRS to these open source repos and they're
trash. And like maybe the user hasn't, even the person submitting the PR hasn't
even tested them or definitely hasn't reviewed the code. I think this is a problem.
And so a common practice with Codex is to have Codex like review its own pr,
or its own change.

And Codex is actually incredibly good at this. We've explicitly trained the
model to be good at code review. and you know, that included things like
making sure it's like really good at, creating like high signal feedback. So it'll
[00:23:00] like basically have few false positives of criticism, which means you
can really trust when it has feedback and so.

not only do we encourage people, like on the team and elsewhere, like to like
just ask Codex to review, you can then also set it up to just like automatically
review. So like nearly all code at OpenAI is reviewed by Codex automatically
whenever you push it to a good repo. Actually, like one, one fun thing, for
people who haven't tried Codex yet or didn't try it recently sometimes the way
that people like see how good our models are is by asking Codex to review a
different models code.

and basically they're like, oh shoot, I should probably just be using Codex to
write my code in general.

You said something really interesting that you said, for those that maybe haven't
tried it yet or uh, you know, are coming back to it, how do you think about
retention with this category? I remember Tom Blomfield, who's a YC partner,
tweeted months and months ago, but it stuck with me a weird brain, about the
ease of transition between different providers, whether it was car or core code,
or.

Code. I can't remember which one it was to be honest, but how sticky are users
and how do you think about retention?

 we've taken this like kind of counterintuitive approach with Codex to
[00:24:00] just build it super openly. So like the Codex core harness is open
source, and we're always trying to make it easier for people to switch. So for
instance, when we first launched Codex last year, we created like, created as
even a heavy word.

It was just, we just established convention, which is called Agents md. This is
basically a file that you can put instructions for the agent in. We didn't call it
Codex md. We just wanted it to be something that all agents can use. And pretty
much every agent except Claude, uses Agents md, which is awesome.

And then just last week actually, we helped push for putting skills, which are
our standard for like giving the agent instructions and scripts. We pushed for
those to be sorted in sort of a neutral named folder called agents, instead of in
like Codex or something. And again, everyone has jumped on it except the
usual suspect.
I think it's really great for the developers to have a lot of choice, and we're
trying to make it even easier for people to try different things. Now that said,
these coding tasks, right, where you're asking an agent to write some code,
they're quite hermetic. And what I mean by this is maybe an analogy in TV
would be like episodic, right?

Like you can come [00:25:00] in and you've got this like open-ended like
agent's file that like any agent can read from, you've got these skills that any
agent can use. You can ask the agent to write some code and it produces a patch
and that patch goes into gi. So kinda like both ends of this are pretty neutral,
vendor neutral.

So very easy to move between for now as agents start to do work that is not
writing code, but more general work. Again, for software engineers or beyond
for any builder, they're gonna need to start interfacing with other systems, So as
they start, maybe your agent is talking to Century, right? Or it's talking to your
Google Docs or something, then I think these agents become much stickier
because actually deciding to to connect an agent to that system is a sticky
decision.

And if you're an enterprise, really trusting that the agent is gonna have access to
these tools. But there are really good secure guardrails and sandbox and like
controls over how the agent works with these systems, I think is critically
important. And that's not something that you're gonna want to, to do multiple
times.

And so, you know, we've been kind of building Codex knowing that this is
coming. and so we have like the most conservative sandboxing approach.
[00:26:00] Sandboxing is kind of like a set of controls, os level controls over
what the agent can do.

I'm, I'm, I'm, I'm a fan of Seven Powers, this brilliant book, which talks about

Hmm.

seven ways of business. Is accrue value and sustainability and like, you know,
your stickiness or your retention is one. If we're on the same team with Codex,
how do we create retentive patterns, behaviors, programs to ensure that people
stay with Codex and they don't flip to cursor when there's a better model or claw
code?

When there's a better model.
Yeah, I mean, it's interesting because I think on the one hand, like we, we think
about this, obviously we're running a business, but you know, our, our mission
here is to like ensure that like we safely deliver the benefits of a GI to all
humanity. And so something that's like unintuitive to people about, like the
Codex team

Alice, do you actually I'm I'm I know, but your job is the success of Codex.
Well, I

actually our job is the distribution of intelligence. and so we're obviously
building out Codex, and this is really unintuitive to a lot of listeners, but like we
put all this effort into training these models and then we serve these models to
our competitors, And from our [00:27:00] perspective,

This is

the competitors,

for me as a venture capitalist to understand you are aware of this.

yeah, I'm totally aware of. It's like we're open eyes is like a really interesting
and unusual place to work. But basically because we're playing such a long
game for us, if the competition gets better, we learn, it's actually helpful for us.
And so we're pushing really hard at growing Codex

do you learn Because if if, if they're closed

and they improve, you don't learn.

I don't think so. for example, there are a bunch of recent launches, like even
today, I literally just like quote tweeted a thing this morning about a launch
from Warp, no particular affiliation, right? And there are a bunch of cool ideas
in there about how they like framed up the way that their agent can work in the
cloud at the same time as working locally.

and for me that's like inspiring and I think I see all these things from various
companies and like one of the coolest things about the space is this. Like we're
all kind of inevitably reaching the same conclusions together and then building
things out. And so, you know, on the Codex team, I think we have some
massive advantages, right?
We have the massive distribution advantage with chat pt. We have the
[00:28:00] massive like capability advantage of training our own models to be
good in our harness and building our harness to be good at the new models and
like, no, what else has early access to those, and so I think we're, we're playing
to win and we have a, a really big advantage or a number of advantages, but
we're also playing this long game where, you know, again, we serve our models
to everyone, where we push for open standards so that everyone can use like all
the things that we're pushing for as well.

Can I ask you what will be the defining factor of winning? And I, I know I'm
using venture language and

Yeah, sure.

brilliant and kind of much more free and open. Uh, but it was like the defining
factor of winning. Again, if I push you, is it like GTM, which is like the biggest
enterprise in the world, do wanna work with OpenAI? I have many friends in
your sales team, the. Inbound that you get from the largest brands is incredible.
So GTM, because of the incredible brand product execution and just Codex
being a fricking awesome product compute inference, speed, actual advantage,
which one is the defining [00:29:00] winner?

Okay. So I think if we're gonna talk about it more from an open AI perspective,
obviously this is way above my pay grade, but I would say it's compute
advantage and having the best models, And in order to achieve that, we then
need to build businesses that generate revenue. And also that something we've,
that's really interesting, we noticed with having the Codex team, which is a sort
of combined team of research and product, is also by building these, these
successful products, we create a lot of pressure to improve the model in sort of a
faster way.

that's maybe the company perspective, right? If we come to the product
perspective, I think the single most important thing we can do is build a, a really
good product that people want to use. And like I was saying earlier, I think we
really wanna build products for individuals and then allow the, like people to
become fluent in those products and then like pull in automation.

And I, I think that may be counterintuitive, but will result in way more impact
than anyone purely approaching it from like the enterprise workflow
perspective. you know, I think that's mostly a question of product execution.
And then that works for, say, like prosumer when it comes to [00:30:00]
enterprise.
The go to market side is really important. something that I've learned the hard
way is if we go to an enterprise and we're just like, Hey, we're here. Like feel
free to use the stuff that doesn't work. There's actually quite a lot of education
that needs to be done and there's a lot of like configuration that we need to
support and sort of like education of the broader team.

So like that motion looks much more like coming in, pitching, meeting the head
of developer experience or whatever, understanding how they want their team to
operate and then giving them tools to like propagate that mechanism of
operating to the rest of the team.

You said the word revenue there, which is one metric to measure a business
against. When you think about like your metric of success, which you. Sit down
with Za or Brad or whoever it is and say, Hey, this is what we're optimizing for.
What is the metric that you use as the defining North Star for your progression?

It's actually not revenues. The primary, the primary is active users, uh,

which, you know,

measure active users, say

okay.

users?

Yeah, we, so we measure weekly active users and it's um, you know, did this
person like actually do a turn in our [00:31:00] product? You know, did they
send a prompt?

Is weekly active a frequent enough metric, do you think? Sounds nice, but if this
is actually replacing the IDE is daily active, not better.

I think daily active will be better soon. We just happened to use weekly active,
it's like a standard here and I think as we were getting started it made sense, but
I, I, I actually agree with the, the, the criticism there. It's like we should
probably just be a daily, like I think we, we need to be getting to a world where
for any given task that you have, your first instinct is to ask an agent to help.

Right? It's kinda like, you know how, like with Google search, it's just like,
okay, anything I need to do, I just like go into this text box and I can get,
navigate it to the right location. Then you had chat. Bt it's like, for any
information I need, I can go into this text box, type it out and get information
that helps me.

I think the next phase that we'll see this year is like for any task I need to do as
opposed to just get information, I go to this text box or this input and something
happens that helps me, even if it's not the full task, even if it's only a small part
of it,

you said about kind of chat that again, I jump around. Sorry. My brain,

it's

all good. I jump [00:32:00] around too,

has to walk with me around London and she like deals with this manic, episodic
brain. but you said about chat and the interface there. I'm, I'm really fascinated
by this because it, it, it is a seemingly incredibly efficient input function for
busy humans. But I, I spoke to Anish Akaya who's a GP at Andreessen and it
came out the other day and he's like, no, no, no. This was created by Sam and
Elon and it works for very efficient people, but most of the planet want
browser-based discovery interactions. Ui. Do you think that chat will be the
enduring in the next wave of AI interaction with humanity?

 The simple answer is yes, but actually I think there's two components here. If
we, if we just imagine the future, like, just like, let's think of some sci-fi movie,
right? Like, what does AI look like? I believe that sci-fi is a really good
predictor of what the simple, the future should look like.

And usually it's pretty simple 'cause it's a story and I think simple is usually
right. it's gonna be some just like entity that I can talk to however I want about
whatever I want, right? I felt like I shouldn't have to navigate to a place where I
work with like my coding ai and then I [00:33:00] have this like different place
for my like, sales ai and I have to like, be like, Hey, I'm now talking to sales
thing.

And like, do that. It's just like, I'm just gonna talk to a thing and it's just gonna
help. so I think what we're gonna have is that we'll have chat or voice basically.
Conversational interface will be sort of the, the pillar of everything that you can
talk to about anything. and that you can add into any group chat or whatever so
it can like discover how to help you.
But then if you are like a power user and you're very good as at a specific thing,
you probably don't want to be disintermediate by having to talk to another
person. It'd be like if you had an executive assistant, but you can only work by
talking to them. That's like super annoying, right? So at some point you want to,
you wanna get to the show notes and like look at them yourself and like edit
them yourself, right?

You want to edit the thing yourself. So I think we'll pair chat with like
functional, like graphical interfaces that are bespoke to like what someone
needs. So like in my case, I will probably chat to like do my, you know, podcast
prep. But when it comes to like actually looking at product and code, I probably
want like the Codex app that I can go into and get deep in, right?

Whereas maybe if we're talking to a marketer, maybe [00:34:00] that marketer
will like chat to ask questions about the product. They're not gonna download
the Codex app just to ask questions about the product, but maybe they'll have
like a super custom gooey for like ad analytics or something that they go into.

I totally get that and it, it kind of wrongly assumes on my behalf a consumer
interaction at some point in that journey. And I wanna ask you, how do you
think about like agent to agent experiences and designing experiences for agents
like we spoke about, for example, going to large enterprises and how you can be
helpful. I'm just using the most boring thing ever. Expense approval. You could
have agent submission of expenses on my behalf for my trip to San Francisco.
And then the agent on the flip side doing approvals for that from open AI's
compliance department How do you think about that and that paradigm shift?

That's interesting. You know, to be honest, I'm not sure what that's gonna look
like. my, like, quickest answer to this is that like we've noticed as we build
Codex that the best interfaces for Codex to do work. Also tend to be the best
interfaces for humans. So like when people ask like, oh, like how can [00:35:00]
I make my code base like more efficient for the agent to work with?

The answer is often like, well, have you looked at it yourself? And is it, is it
easy for a human to work with? So like a very specific example would be like
running tests in the code base. naively if you just like set up most test runners,
they just like emit all the outputs of all the tests. And so like as a human it's
really annoying 'cause you have to go in and like find the one that failed and it's
like you've gotta read hundreds of thousands of lines.

Turns out that's terrible for AI as well. But if you filter it down to just only emit
the failed test, better for humans, also better for agents. So probably the agent to
agent interaction points will be very similar to like if there was a human in the
loop. And that's nice 'cause it means you can kind of atomically replace
individual systems.

I mentioned our show on LinkedIn and, uh, a wonderful investor from a
different company. It's that Harry Potter, you know, Voldemort. And it's like,
you know, he who shall not be named,

I don't want Sam to kill me, but from

another company, okay. gotta, you ask him, ask him, how do you think about a
coding data moat? And does Anthropic have all the data now?

[00:36:00] I definitely don't think they have a significant advantage in terms of
data, on coding. I think that from what we've seen, and, you know, and I'll, I
would defer to my research team on this, but I feel like we, we feel like we have
plenty enough data to build really good coding models. I actually think the, the
place that's more interesting for getting data now is like, as we get into like
knowledge work tasks, that's kind of data that's like not really like available
most places on the internet.

And so you start to have like really interesting brainstorms. For like how to help
a model be good at it. Like maybe you have to like pay people, to like simulate
doing tasks so that you can like learn these trajectories for the model. Maybe
you should acquire startups, you know, that are no longer in business but have
have a lot of like data like say their slack or something.

yeah, I think that that kind of knowledge work task distribution is like much
harder than coding.

So interesting. You said there about kind of the, the data that doesn't exist, so to
speak.

Yeah,

think about your interactions with the data providers, your Macaws, your
Turings, your invisibles, your of [00:37:00] the world? Like will your span
Tanex there or will you. Go. We are spending too much on data. We should do
it ourselves and do data acquisition.

yeah, I mean, I think the way that we think about these things is just like, how
do we move as quickly as possible? And so, becoming able to set these things
up in-house is like very expensive in time. And we're a small team. So what I
have observed so far is that if we need to run a data campaign at scale, we're
usually gonna enlist help from one of these companies.

 on the consumer side for Codex, we've spoken about like enterprises and going
into them, how to engage in terms of developer experience, developer
operations. Do you compete with a lovable and a rapid on a like low end
consumer basis in a year or two's time? Is that a business where you're like, you
know what, codex is not for every person to create an about me or a small
business to create their own site. How do you think about consumer in that
way?

Yeah, I would say that right now it doesn't feel like we're competing super
directly. but you know, I don't know if you saw our Super Bowl ad, the tagline
of which is just you can just build [00:38:00] things. with the app we noticed
that like many people who are less technical are starting to build things.

And so the kinds of things they're building are much more Hello worldy. And so
I think that we will see some overlap in use cases, where you have. People just
pulling up Codex because they have it as part of their cha. Bt actually like a big
announcement, um, last week was that we're now offering some codex to people
even on free cha BT plans or on the Go cha bt plan.

So this is, this is massive just in terms of like bringing availability to everyone.
and so I think we're definitely gonna see people with like a free cha PT plan
coming in and just like building simple things where they otherwise might have
gone to a specialized tool.

What would you most like to do differently, but for whatever reason, you can't.

I feel like it's been a very good few weeks for us. so we're very, I'm pretty
jazzed by everything that's happening, feeling that I have the most, yeah,

that's really interesting. You said it's been a very good few weeks for us, and I
feel that, the team feel the changing winds of momentum, both in positive and
negative cycles?

absolutely. we are very [00:39:00] attuned to it, right? Like if you look at the,
the history of Codex, the first thing we launched last year was like this amazing
idea that people were super excited about. It's like, Hey, we're gonna give the
agent its own computer in the cloud. You can have as many of them as you
want, work for you in parallel on tasks.
Super great idea. To be honest, it didn't work as well as what we shipped later.
It was not the best. and then since August with GPT five, we started pushing
really hard on interactive coding, which is where most of the competition in the
market is. You know, we went on an absolute tear. I feel like the public metric
we had was like, since August we grew by like 20 x and then like even like late
in the year, we like doubled from December to now.

I forget the exact number there, but like, that was competing neck and neck. But
the shift that we feel last week is, you know, we ha we felt like we had the most
intelligent model that was cemented with five three codex. We had feedback
around our model being slower and like maybe less fun to work with and like
being less good at communicating with you while it was working.

We addressed that feedback. and that's true even compared to like the, the other
competitor model [00:40:00] that launched like 20 minutes before us and was
like, maybe this is spicy. It was like soda for 20 minutes. Soda means state of
the art. and then, we'd always been getting a lot of feedback on like the quality
of the user experience in Codex.

our most popular surface was the IDE extension and our CLI, which is the
command line interface was less polished. With the app, the feedback has been
like resounding from the market, that this is like a really high quality
experience. It's like simple, like un intuitively simple, and people are just loving
using, even our biggest credits are converted.

So yeah, and then we, and then we had the Super Bowl ad and then we went to
free. And so going back to your question of like, what do I most wanna do
differently?

 I have two things for you The first is I actually wanna get back to cloud. when
we pivoted our strategy from like focusing on the cloud agent last year to
working interactively, the thinking was very simple. It was just, and it's kind of
like what I was telling you about FTEs actually.

if you go too far ahead to workflow automation before your end user is fluent
with the tooling and can get it to work simply. There's like this disconnect and
you just have this pipe dream idea that's not like effective except for the most
power [00:41:00] users. But once you have this base where people are using
your tool every day, and they're configuring it and every time they use it, it gets
better.
Then like the step up to like letting it run independently in the cloud is a much
smaller step up. so I think it's time for us to like get back to like building out the
cloud product and making it super tightly integrated with the local product. It
already is somewhat integrated. And the other thing I wanna do differently is,
um, start thinking more about the bottlenecks.

Like code gen writing code has become like, basically trivial now, the hard part
is like what you were talking about with like code review, right? Like how do
we know the code quality is good? How do we know we're doing the right
things? And those bottlenecks, I think are under underappreciated still and
under invested in.

So like, I think we wanna get to a world where you can have an agent that is un
bottlenecked, That you trust to like own an entire microsystem or internal tool
or whatever. And can do the full iterative loop, including feedback from users
without having to go through human review. And that is a really hard problem
to solve, both from an intelligence perspective, but also from like a safety
perspective and a controls perspective.

How much weight should we place on benchmarks and [00:42:00] evals?

probably, uh, this is an annoying answer for you. It's like some, right, like they
do tell you, in my mind, they give you a good measure of intelligence, and so
you can put weight on those for intelligence. and especially before evals are
saturated, I think when you see meaningful progress in those benchmarks, it's
like very, very helpful.

and then I think you have to pair that though with like what it feels like to use
the model. And that's, that's a vibes thing. Like whenever I talk to any, even
internally or even talking to like customers of our models, I'm always surprised
by how vibes based the, uh, evaluation of how it feels to work with the model
is.

How vibe space life is. People

wanna work with people they like, is

Yeah,

that I give to

exactly. People wanna work with models they like.
Yeah.

matter. Um, can I ask you, I think that Casa will lose half of their revenue this
year. I think we'll go from a billion to 500 million. There's a bold statement.
Agree or disagree.

Oof. Can I just like, no comment.

yeah, [00:43:00] you totally can.

I don't know. I, I think it's really hard to say, like, like more serious answer here
is just like, I think they've built a really successful business. We see them a lot
when we're in enterprise.

yeah,

or is it just crco? 'cause I don't know anyone

no, I see Krista a lot more than Claude Coat and it makes sense to me, my sort
of narrative for this is that you have to meet people where they're at, For most
people, like they're used to using an IDE, they're, they've been used to using
TAP completion even before there was ai, right? Like tap completion existed
pre AI and then AI just made it better. And so I think what's like coolest about
Cursor from my perspective is that it meets developers exactly where they are.

And it's a sort of a switch. It's like you used to be using VS code or something,
switch to Cursor. Almost nothing is broken about your workflow. Everything
works. Just certain aspects got better and obviously VS code i I still use VS
code. There's like reasons you might like it more. and you know, they're
improving rapidly as well.

But I think that pitch from Cursor Lands well with a lot of people. And so, you
know, the bet on Cursor I think is that they can like continue meeting people
where they are and [00:44:00] then like ladder into these more advanced age
agentic features. you know that that relationship with the customer is valuable
and it's hard to, I don't think that goes, you know, it goes

away.

think it was the right strategic decision to start building their own models?
It's hard to say. But I feel like there is a bit of a, a gap in the market right now
for that kind of model. again, if we think about what is the thesis? At least my
thesis, you know, I, I'm not like super close to like working with Chris or
anything, but like my thesis for like how they win is that they meet everyone
where they are and they like make it really easy to like step up into using more
advanced agentic workflows.

maybe they noticed that, the models that, for example, we were putting out, or
some of the competition we're putting out were like kind of slow relative to
what their customers wanted. You know, my, my first magic moment in cursor
was like when I hit Command K the first time, that's like a feature that lets you
select some code and just like edit it in line.

And I was like, this is incredible. Right? And so if they noticed a lot of their
customers want to be able to, to kind of pair with the AI and then maybe after
pairing with the AI for a while, then they start doing more delegation and then
they move it to the cloud. Then there is a gap for that [00:45:00] fast model, but
they trained.

So I think that makes sense in that context.

in terms of like market composition as an investor, I have to think through how
do I think about the eventual state of this given market? Kind of a, a terminal
stage. How do you think about that? Is it like Uber and Lyft and like the
majority of the market will be on Codex or Claw Code, or is it like a AWS
Azure, Cloud and a 33?

33. 33?

Okay, so I think this might end up with fewer providers that are capturing a lot
of value in the long run. And here's why, like, and maybe this is a bit spicy, but
I think that we are kind of in this temporary phase where we have agents that
are really good at coding, right?

And, and if you look back last year, like maybe more people thought we would
have agents that are good at other domains too. But that didn't happen last year.
So we're, so we only have PMF for coding agents, like in the industry overall I
would say. Right? And then there's some like very narrow, narrow other use
cases like customer support, et cetera.

but I think that's probably temporary. And then over time we're gonna end
[00:46:00] up with agents that kind of can do anything for you. This is kind of
what I was saying earlier, like there's just like a super assistant, you talk to it
about anything and then there is like specific UI that you can go look at if you
happen to be deep in a specific function.

So in that world, I don't think you want like 12 agents at the company and you
have to like go, your employees have to go figure out the right one to talk to
because then they won't achieve fluency. And if they don't wanna achieve
fluency, then they will also won't like pull automation into their roles.

But if you have this one thing that you can talk to about anything, right? So
your onboarding is just like, go talk to this thing about anything you need, then
people will develop muscle memory to go to it. It'll become the center of gravity
of work and people will pull an automation. So I think that that future makes
much more sense.

And I think like. As the people building chat, PT we're like really well set up to
deliver that. This, this is kind of a stretch, but an analogy here is I used to work
at Dropbox and for a while, this is before Slack was big and for a while we
thought, we wondered if people should like go comment on like documents in
Dropbox or, or if they should like go talk about the documents in Slack.

And it was like [00:47:00] obvious that it was like more optimal for people to
like put comments on the right timestamp in the video in Dropbox or like
comment on the document in Dropbox, right? So it was more optimal.
However, what we saw is that Slack is just such a, a center of gravity of people
just like talking to each other.

Like nobody wants to comment on the document, I just wanna slack you. And
so we saw that like there was this really big pull towards things happening in
Slack, even if it was less efficient. And I think we're gonna see something
similar at work where if there is a single agent you can use for nearly anything,
it there will just be this giant pull and everyone will talk about how they use that
one agent for things.

teams will share best practices with each other. There'll be hackathons around
how to use that best thing. yeah, and you'll end up with just a handful of these.

You said about kind of agents not really proliferating in terms of usage other
than coding and actually maybe this being the time and, and you know,
customer support is one of the examples. My question to you is, I'm an
ambassador today. I'm looking for companies which will accrue value over time
and provide incredible products to customers. There is a belief that the
durability of revenue of large SaaS companies today is [00:48:00] zero and that
SaaS is dead because the model providers, you andro, others are going to come
for our lunch, so to speak. What would you advise me?

 like things are built for humans. Like otherwise, what's the point? Right? Even
in, even SaaS tools are built for humans. So for me, I think my question is like,
does this SaaS company own a relationship with a human on the other end of it
of things?

And if it does, then I suspect it's, it's not going away. you know, or does the
SaaS company own some like really important system of record? It's probably
not going away. Maybe those, both of those top, the two things, the interaction
with the human and the system of record are like more important than ever.

Actually, on the other hand, is the SAS company like a kind of a glue layer? but
it doesn't own either of those two things. Well, I'm not the expert here, but I'm
more nervous about that kind of company.

if we take that stance, Salesforce and ServiceNow, you know, they're down 20,
30, 40%.

I

be.

don't think they should be.

I dunno. What do you think? I, I would love to hear your take on this.

I think it's massively exaggerated. I, I think there are some companies
[00:49:00] that legitimately should be respectfully. I think Dropbox is in a very
difficult position. and I think your, I think your Monday dot com's of the world
though, for the majority of SMBs and consumers who use it, which is the large
majority of their market actually, could they vibe code A to-do list?

Yes. Would it be cost efficient to do so? Not really. Actually by the time you
customize it and perfect it. And to be honest, the to-do list is generally pretty
bland in terms of what you need to do. Add task, complete task, show historical
tasks assigned to new members. It, it's not very difficult. And so actually I think
you just keep it. I think it's massively overblown. and I think that's the classic
knee-jerk reaction from markets.
I completely agree. I mean, if anything, like now that it's so much easier to
build,

But I do think, sorry, I, I do think, like I think you are gonna come for customer
support and I wouldn't want to be in that category.

I think this maybe changes what kind of founder you invest in, right? Like I
think there was this maybe temporary phase where that, I liked [00:50:00]
personally as a product builder, there was this phase where you would invest in
like the, the person who can just like build good product and you could kind of
ignore if they had a good thesis around a customer or go to market or
distribution or anything like that because it was so hard to build good product,
right?

And I think that was a, that was an anomaly, if we look at where we are now,
like maybe that kind of founder is not the founder you should invest in 'cause
it's like kind of relatively easier to build good product and you need to go back
to like investing the founder who's like thought through distribution, who has a
good, good domain expertise of what to build for a specific customer, et cetera.

So again, if you were on my team as an investor, how would you think about
interesting areas for us to invest in in companies that will accrue value and not
be threatened by model providers? Because again, mate, you're going into
health, you go into code, obviously code is very clear. You're going into
customer support where are you not going and where is code not going?

I'm tempted to just say like, I don't know. I couldn't, I, I think it's a hard time to
be an investor. It's, uh, the market is so dynamic. It's hard to say.

It's a really tough time to be investing today.

Yeah.

my, my answer is kind of [00:51:00] twofold actually, which is like, number
one, I look for things with physical infrastructure.

 I don't think you are going into energy supply And then two is like the FinTech
and banking integrations, gnarly financial products. I don't think OpenAI is
gonna go into building 500 relationships with banks in Southeast Asia.
tend to agree. I, I, I, again, comes back to are you going into like a gnarly,
complicated market where customer relationships and like knowledge of the
market are everything? That still seems great.

How bad is the war for talent from the uk? We look at SF and I say to
companies, it's better to build in Europe 'cause it's impossible to acquire talent
and it's impossible to retain it. Am I wrong?

I think that the war for talent is incredibly fierce right now. You know,
obviously at Open ai we have an incredibly strong brand, and so we're able to
attract a lot of talent. but even so, we put a ton of effort into like closing
candidates that we're really excited about. Like, even we feel that it's not like
you don't just get whoever you want for free.

Can I ask, at the entry price that you get stock at, is it still attractive for the
[00:52:00] best talent?

I haven't had anyone tell me anything to the contrary.

to what extent do you think about like finding the perfect fit versus finding
someone who's good enough?

so, you know, earlier I made my joke about like PMs kind of being optional.

Yeah,

I think that's not actually true. You still need product people, but I do think that
they have to be the perfect fit. If you have someone who's like not the perfect
fit, they, they might just do more harm than good. it's kind of means that like
we're way more selective than I might have been in other roles.

I'm a CS student.

Yeah.

And I'm at Stanford. I'm an Imperial. I'm at Cambridge, I'm wherever. ETH,
institution. What would you advise me knowing all that you know now that
would help me navigate the next five years of my career?

 I want. To be valuable to the AI ecosystem environment as an engineer
entering the workforce in the next year
basically there's actually never been a better time to be an engineer because you
have incredible tooling available to you to [00:53:00] get incredible amount
done. Your ability to like ramp into like a complex code base that you might be
hired into has never been faster because you can go ask AI like a ton of
questions about the code base and you can ask it to plan out changes that would
otherwise take you like days to research maybe.

I think first off I would say like you should be like very optimistic, then of
course like about you what your abilities once you're at the job. Then now the
question is how do you get the job because it's never been like easier to build
things, the thing that becomes scarcer is like agency taste and like quality.

I would urge you to like, just build things and, demonstrate your agency and
your taste around what you build and like build things that are of high quality
and then share those things you know, we get a lot of inbound for from folks.
both applying for jobs through the careers page or also on social and.

this is just me, but when someone writes to me with like some interesting
thoughts and like a link to an interesting project that gets my attention much
more than like a normal resume does.

final question. So we do a quick fire. What has Claw code done Well that
[00:54:00] you sit back and you learn from?

Number of things. it's like I was saying, I think a way back last year, they made
something that was really easy to use and just like worked with all your tools
with Xero setup by running it locally in your terminal. when we, started
investing much more in the Codex CLI and you know, shipped great models for
it, like GP five, our growth exploded.

and so I think that idea of just like meet people where they're at, give 'em
something easy to use, let them ramp from there and like figure out how to use
it has been awesome. So, that's probably the biggest learning we've had from
them.

What mistake do you think they made that you've also learned from having had
the benefit of seeing them make it?

they over-indexed on their initial success with their command line interface
tool. I think at the end of the day, it's like not the friendliest ui. and it makes it
hard to extend beyond like, pure builders and it makes it, difficult to like truly
delegate to agents because like effectively to delegate through that kind of
interface, you have to be like kind of a power user of like your terminal or Team
X or something.

And so that's, that's why we built the app and I think the market reception
around the app, to me, like it was kind [00:55:00] of a risk when we started, but
it makes me like really feel good about that decision because it's the Codex app
is like a much more intuitive, simple interface to like, get started with.

It's like less scary, but then it naturally leads you to this idea of like, I'm gonna
take my hands off the keyboard and like delegate to the agent.

 You mentioned Dropbox earlier. the alumni from Dropbox is incredible. I mean
really like amazing to see the talent that's come outta Dropbox. what's your
single biggest lesson from Dropbox that has shaped some of your thinking now
with OpenAI?

Oh, I, I don't need to think about that one. That, that's kind of the thing I was
telling you about earlier, right? Like, when you're building tooling for people,
like for end users, you have to think about like that tooling as a system of
engagement, right? If people don't want to use your tool, if it doesn't like,
naturally feel like the easiest way to get something done, then people just won't
use it, again, I learned that from watching how Slack just absolutely took off.
and so I think about that a lot now when we're building these agents. I'm like, if
we build our agent purely is like. Workflow automation, then it's always gonna
be like pulling teeth to get that thing started, [00:56:00] right?

You're gonna need to hire Accenture or someone to come in. They're gonna
need to deploy FTEs. It's gonna be tough, but if you can build a system that like
people just love using, even if they only use it for partial tasks, over time, they'll
get better at, better at using it, and then you'll get connected to the tools you
want over time, and then you can start laddering in automation.

Obviously these aren't mutually exclusive,

How on earth do you reinvigorate growth at Dropbox today?

at least from when I was at Dropbox, the thing we were uniquely good at was
desktop software.

And desktop software it's, it's funny, it was never, not back, but anyways, it's so
back. basically because if you're solving for productivity and knowledge work,
yes, there are systems of record everywhere that you need to connect with, but
everything at the end of the day happens on the user's computer, either in their
browser or, you know, just like locally in apps on their computer.

I do think that the, the, the fastest way we're gonna see productivity gains from
agents at work is going to be at first meeting users on their computer, working
with the stuff that they have available to them, you know, without having
deployed FTEs to set anything up. Then over time you'll [00:57:00] connect in
these various systems.

And so if I was Dropbox, I'd be thinking about, how do we leverage our unique
domain expertise in like building really good like desktop software, and this sort
of collaborative layer on top of your computer. How do we leverage that to
enable productivity agents? It's a that's the angle you go

for.

it and I really appreciate the response.

Yeah.

one, before we do a quick fire

Yeah.

 I've been brought up in a world where margin matters, software margins are
wonderful, and that's what makes software a brilliant category to invest in.
We're seeing margin profiles that are very different in inference, heavy plays in
particular. To what extent should I put that out of mind and appreciate that costs
will come down. Cost of tokens will come down, actually it's about usage and
customer love. Margins will come or no, margins are actually fricking
important. keep that focus.

I think both costs are gonna come down significantly. and I also think that, you
know, if this is the year of agents being deployed, like broadly at work then this
is also the year where they're gonna have to be connected to all these various
systems. [00:58:00] And I think that's gonna be very sticky.

And so I view this year as a race, and so I think you wanna win that race and
you should be okay take, you know, taking some hit to margin in the meantime.
dude. Quick fire round. So I say a

Yeah,

statement. You gimme your immediate thoughts. Does that sound okay?

yeah.

What have you changed your mind on most in the last 12 months?

 when I joined OpenAI, I thought that this was a little longer than 12 months
ago, but when I joined OpenAI, I thought that we would all just be hanging out
with our computer screen sharing, but within a year from there, you know, we'd
have this agent that we're just talking to, that was completely wrong.

I think the rate of like progress and like multimodal models was like slower than
I expected. multimodal means, you know, like models that work with like video
and audio. so instead what happened was that we saw that like, agents that work
with your computer through code are the way. And so for me, that's being a
complete rethink in terms of like how we bring the benefits of AI to like just
people generally.

It's not, not through video and audio primarily.

Which lesser known competitor do you respect most? And why?

the first one that came to mind was amp, I think they're building [00:59:00]
Yeah. A MP. it's out of, out of the folks at Source Graph. Their product has a
great reputation of just being like, you know, punching way above its weight.
But I think the other thing that I really respect is that they helped initiate this
whole like, standardization around like agents, md and like DOT agents slash
skills, which are what I was saying earlier about like making it so it's easier for
users to manage all these different agents that they're trying.

we obviously put out Agents md, but they put out Agent md and basically
Quinn started this all by putting out a tweet that said, Hey, do you guys buy the
domain agents md we'll standardize to your, your spelling. And as small as that
was, that initiated this whole standardization that I think has been awesome in
the community.

Do you think the response to Philanthropics ads was the right response?
I mean, there were so many different responses. The one that I heard obviously,
I think was right. The one that I heard was, well, one company's being pretty
negative about the future and the other company, US OpenAI, is being really
positive and just telling people they can build things into dream. I, I thought that
response was brilliant.

Sam wrote an essay. [01:00:00] Do you think that was a good response?

I think so. I mean, I think as one of the cool things that I love about opening
Eyes is like people are like very unapologetically and authentically themselves.

and so for me that was just like a very authentic response and I like that we do
that.

What's the hardest product decision you've had to make since being at Codex?

well, I can tell you the most painful product decision we had to make.

for a while. codex Cloud was like effectively unlimited, not free. Like you
needed to pay for Chacha pt, but then you had unlimited usage. every day that
we left it that way, we knew that would be harder to wind back it being like
unlimited.

But we were just so focused on competing on our other things that had more
PMF, that we kind of punted that decision out. when we wound back, That
unlimited use to some like more reasonable limit. There was a lot of blowback
from users and it was a very small minority of users who like thought
everything should be kind of like pseudo free forever.

But that blowback affected us everywhere because like the social chatter doesn't
really distinguish, between these things. I think the lesson I learned the hard
way there is like, you can't make things unlimited for too long.

like [01:01:00] pricing, grandfathering pricing is

Yeah.

it's such a hard thing. What do we do today in engineering or product that in
five years time you'll look back on and go, oh my God, can you believe that we
did that?
Well one is just editing code by hand. I think probably, another one, this is
maybe spicier, but another one might even be, like actually managing the
deployment and monitoring of, systems by hand. Like I basically think that.
Probably big companies will take a long time to like deploy this, but many
startups might actually kind of start building on a completely new stack that's
like fully AI managed.

To be clear, the stack doesn't exist yet, but a fully managed AI stack where,
because basically it's been built to give you really strong deterministic
guardrails over what the agent can do and like control over to like world back
deploys and everything like that. And so we'll get to a world where the way you
start a company is you start by getting an agent and just asking it to build things
and then you get more agents than that.

And then maybe eventually you add, you add your co-founders to this service
that you use to work with agents. And so you [01:02:00] end up like maybe
your main communication tool is actually your agent communication tool. And
then maybe, you're not actually handholding this like very point painful CI and
deploy process, but you're just like having agents do things.

Weird question, but I am intrigued. Are you the one providing agent guardrails?
And what I mean by that is, you know, agents can go anywhere within an
enterprise. Are you responsible providing those guardrails or is there a third
party matter provider who is saying, Hey, or Alex, you can't go into that, that's
human resources or, or you can't go into that, that's marketing.

How do you think about guardrail provisioning and is that the role of the agent
provider or a third party provider?

I think we'll probably see both. Like we are putting a lot of effort into agent
guardrails. Like I said, we have, we're basically the only company that cares
about OS level sandboxing for coding agents, for instance. There's none that
exists on Windows. We're the ones building that. Uh, and we're doing it in open
source, so hopefully other people can use it.

we think about that a lot. chat, PT supports connectors, so you know, you can
talk to your like Google Docs or something and we put a lot of effort into
guardrails around what the agent can do with your [01:03:00] Google Docs.
Those are just two examples, but we think a lot about this and I think probably
though the way that we'll do it will not be sufficient.
Like there'll be third parties who provide like very bespoke things for very
bespoke, you know, company needs. And there'll probably be a mix of both.

Final one for you, my friend. What are you most excited about when you look
forward 10 years,

this

is probably gonna happen in much less than 10 years. But my mission sort of
personally when I joined the company was I just felt like even with the models
we had a year and a half ago, there was so much just capability overhang or just
like ability for these things to be useful, but we hadn't built the right products
around that.

And so people like me were getting more benefit than like people like my
grandma. What I'm most excited for is to get to like a form factor for ai. That
means that they're just helping everyone regardless of whether they're in tech
and especially if they're not in tech or especially if they're older.

and so, you know, the concrete vision I have is like at some point we'll like add
an agent to like our family WhatsApp or something, and it'll just start like being
useful, to the family without anyone having to think harder about [01:04:00] it
than that. there, there are many other ways that that could happen, but I think
concretely that's the most obvious thing we could do with like my grandma.

Dude, I so appreciate you. I so appreciate you putting up with my wandering
questions and my very, uh, episodic mind. You've been fantastic, man.

Thanks so much. I mean, I appreciate you putting up with my wandering
answers, so all good. We're two here.

But before we leave you today, the early story of Atlassian is probably very
similar to your own. Atlassian knows firsthand the challenges that startups face
every day and that the right tools are essential to go from MVP to IPO. That's
why Atlassian for Startups gives eligible companies up to 50 seats free on the
premium addition for products like Jira, confluence, loom, JIRA, product
Discovery, compass, and Bitbucket.

So your team can use the best in class tools to plan, track, and collaborate on
what. Whatever that work may be. Many of today's most successful startups like
CloudFlare, Canva, and Rivian relied on Atlassian for their growth trajectory,
and Atlassian [01:05:00] wants to give that same opportunity to the next
generation of builders and investors.

We know how important it is to focus on building the right things early,
whether you are in the sticky note stage or well on your journey. Teams at any
stage can work smarter together. It's never too early to start with Atlassian.
Head on over to Atlassian dot. Com slash Startups slash Harry for more details
and eligibility.

After Atlassian helps your team build and ship great products. Intercom helps
you support the customers using them. If you are looking for a way to transform
your customer service, let me introduce you to Fin Baby. Fin is the number one
AI agent for customer service. Resolving up to 93% of customer queries.

Automatically. There is no other agent that can do that. Not 93% of customer
queries, okay? No other agent can do that. So why choose fin? FIN is the best
performing AI agent for cs. FIN doesn't just answer questions. It takes actions.
It automates the most complex customer queries like refunds, transaction
[01:06:00] disputes, technical troubleshooting with speed and reliability.

I wish my team was speedy and reliable. Beats every competitor in every head-
to-head Bakeoff, completely configurable and code optional. Setup my word. I
mean, the benefits just go on and on. It's easy and efficient implementation. It
works on any help desk with no tedious migration needs. It's trusted by over
6,000 customer service leaders, including top AI companies like Anthropic,
lovable Synthesia, clay, Vanta.

So if you are ready to transform your customer service team, scale your support
and give team members time to focus on the really. High level strategic work.
Learn more about fin at fin.ai/two zero VC. While fin scales your support
without losing speed. Reforge shows you how to translate that scale into durable
product-led growth.

Everyone shipping faster than ever. Cursor Claw code Codex. AI is making
code and writing code faster than ever, but here's the problem. Speed means
[01:07:00] nothing if nobody uses what you ship. That's where Reforge comes
in. Reforge is building a product discovery engine that sits upstream of your
coding agents, not another prototyping tool, research repo or AI interviewer.

But a product that will ingest your customer data, generate variations of product
solutions, validate the solutions before code is written and hand off winning
directions to your team. Reforge kills product debt before it starts because every
unused feature you ship isn't just wasted engineering time.

It's a maintenance burden, complexity, tax, and surface area that you cannot
shrink used by product teams at companies like. Toast, Vimeo, Klaviyo and
many more. Reforge helps teams ship more features than actually get used. Try
Reforge at reforge.com/build and use the code two zero vc. That's 20 VC for
one month three of Pro.


---
type: 20vc-episode
guest: "Aaron Levie"
company: "Box"
role: "CEO"
episode_type: interview
date: 2026-04-26
youtube: "https://www.youtube.com/watch?v=qrxQikecJL0"
transcript: "https://20vc.substack.com/api/v1/file/2e31a1d5-d6ac-4274-aea4-282da56efe5f.pdf"
newsletter: "https://20vc.substack.com/p/20vc-newsletter-26th-april-2026"
tags:
  - 20vc
  - ai
  - saas
  - venture-capital
---

# Aaron Levie — Box

> CEO @ Box | 20VC Interview | 2026-04-26

## Key Takeaways

### 1. Why Dwarkesh Was Wrong and Jensen Was Right on Upgrading Systems
Upgrading software is a multi-year effort, not a “magical moment” where everything can be secured overnight. The reality of enterprise security is an ongoing, endless cycle of “leapfrogging” between defensive and offensive capabilities. Founders must realize that even with access to frontier models, the implementation cycle in the real world remains the primary bottleneck.

### 2. Why We Will Have More Lawyers in Five Years Not Less
The industry is myopic about job elimination; AI makes it easy to generate content, but it hasn’t made it easier to get that content approved by a court or a patent office. As clients inundate lawyers with AI-generated contracts and memos, the “ultimate constraint” becomes the number of qualified humans available to review and approve the output.

### 3. What Role Does Not Exist Today That Will Be Incredibly Common in Five Years?
We are about to see the creation of 500,000 to 1 million “Agent Operators”. These technical-yet-business-savvy individuals will be responsible for “care and feeding” of agents—writing skills, understanding MD files, and redesigning workflows for agents rather than people.

### 4. Will Massive Software Providers Simply Be Turned Into a Database That Agents Crawl Over?
While the user interface may shift to chat, the value is moving to the API layer and the “business logic” embedded above the database. Systems like ERPs are more than databases; they contain decades of complex logic for supply chains and accounting that agents must interact with, not replace.

### 5. What Everyone Thinks About Enterprise AI Adoption That They Get Wrong
The assumption that the massive gains seen in AI coding will immediately translate to all other knowledge work is a “misread”. Coding has specific idiosyncrasies that don’t always exist in broader knowledge work, where human collaboration and regulatory loops are more complex.

### 6. Where Would You Be Investing if You Were a VC Today?
Despite high valuations, Levie would still be “loading up” on frontier rounds. These companies have the potential to grow much larger because the ultimate market for AI is often larger than the industry currently realizes.

### 7. The Budget of Tokens Will Have to Move Out of IT Spend and Into Opex
Enterprise AI shouldn’t be treated as a tradeoff between software licenses. Instead, token budgets will move into regular operational expenditure (OPEX), where businesses trade off a marketing campaign for a more productive, automated marketing engine. This allows AI companies to tap into a massive pool of capital beyond the traditional, capped IT budget.

---

## Links
- 🎬 [Watch on YouTube](https://www.youtube.com/watch?v=qrxQikecJL0)
- 📄 [Full Transcript (PDF)](https://20vc.substack.com/api/v1/file/2e31a1d5-d6ac-4274-aea4-282da56efe5f.pdf)
- 📰 [Newsletter](https://20vc.substack.com/p/20vc-newsletter-26th-april-2026)
---

## Full Transcript

[00:00:00] I think I would still be probably loading up on all of, the, the frontier
rounds. these numbers could, could continue to get much larger.

what we are in is a commercial and economic race

we haven't removed humans from the loop. We've just changed where they
enter the loop.

everybody is so myopic about this. I wanna just like shake the industry.

there are gonna be more lawyers in the next five years than we have today

the workflow needs to be redesigned for agents, not for people

the budget of tokens will have to move out of it, spend. And into regular kind of
opex spend

Is your job harder than ever?

Yes.

if you're in software or infrastructure or building agents, it's a year of complete
unrelenting execution

This is 20 VC with me, Harry Stabbings. Now I think Aaron Levy is one of the
luminaries on AI pervading enterprise. And he did a viral tweet the other night
and I messaged him and I said, dude, we've gotta do a show on this. And I'm so
thrilled that he agreed to do it. So this is a show specifically on how AI will
impact the biggest enterprise in the world, how [00:01:00] agents will be
introduced into the large enterprises.

And we couldn't have anyone better than Aaron founder and CEO of. Box one
of the public companies of the last decade. This is an incredible discussion.

But before we dive into the show today, did you know that industry average for
booking a business trip is 45 minutes? That's a massive waste of your team's
time. Well, with Navan, your employees can book a trip in just seven on
average. Navan is the AI powered travel and expense platform designed for
companies that value efficiency.
It drives real business impact through high employee adoption and automated
policy control. Now the built-in AI approves in policy bookings and blocks the
rest automatically. This allows finance teams to stop chasing receipts and skip
the month end chaos. And you get this real time visibility that can save your
company up to 15% on your travel budget.

And that's why leaders like Visa, stripe, Figma, and even Anthropic rely on
Navan these days. Go to navan.com/two zero. Day to see for yourself, and you'll
get a chance to win two [00:02:00] business class flights anywhere in
Continental us. No purchase necessary rules apply. Head over to navan.com/two
zero. Now, where's Navan simplifies The Travel Air Wallet simplifies the spend
behind it.

Founders. Let's get real about the growth. Tax. You've raised VC funding and
you're scaling globally, and it's no longer about shipping product. It's about
orchestrating operations across continents. But suddenly your payments and
finance stack is choking your growth. You are logging into lots of different
banking portals, waiting days for transfers and reporting across entities.

It's operational drag, and it's at your scale. It's costing millions. That's why I'm
so excited. Partner with Air wallets. Air wallets are more than just a banking
alternative to HSBC or Citi Air Wallets brings you an intelligent financial
operating system that powers how global businesses operate and grow, allowing
you to manage and automate banking, treasury payments, and spend the most
exciting part for me.

They're heavily investing in a agentic. Finance. If you are scaling globally, you
need a banking and finance platform that's borderless real time and [00:03:00]
intelligent. Check out air wallets today and see how they're helping thousands of
businesses like Canva, McLaren, and Diehl scale@airwallets.com slash 20 VC
terms and conditions apply.

Your money's a safeguarded, not ffc. Protected. See air wallet.com for more
details. While Air Wallet helps your money move globally, Vanta helps your
security keep up. Security and compliance Done wrong is a giant headache.
Security and compliance done right though. Well, that's Vanta. Vanta helps you
earn trust and speed up growth.

No spreadsheets required for startups low on time and resources. Vanta
becomes your first security hire using. AI and automation to get you compliant
fast and unblock really big deals. And if you are big enterprises, Vanta is your
AI powered hub for compliance and risk, bringing together data from across
your business and automating workflows so you can prove trust at any moment.

Vanta scales with you at every stage. That's why top companies from startups
like Cursor to [00:04:00] Enterprises like Snowflake, choose Vanta, do security
and compliance right. My listeners can get $1,000 off Vanta by going to
vanta.com/two zero vc. That's vanta.com/two zero VC for $1,000 off. Vanta.
You have now arrived at your destination.

Aaron. Dude, it is so lovely to have you on the show. You know that we have
Rory on every week, and he's just like, Aaron is the greatest. I'm not gonna do
his accent because I suck at them, but he is like the

greatest.

can't, you can't easily do, uh, an Irish accent.

Well, you know, I, I can't really do the Irish accent so well, but, uh, that's why
exactly. Uh, but you basically, I'm sure, bought Rory one of his houses. So no
wonder he's grateful. Uh, but.

We, we r Rory, uh, we got more outta Rory than he got out of us, so, uh,

Exceptional man, but I wanted to start, and we were just chatting. I was running
around the pot listening to the Ddu and Jensen episode, and I was like, I don't
think Jensen came out very well. Do you [00:05:00] agree with me that Jensen
didn't come out very well from that episode?

I think this is like the greatest Rorschach test of all time, of, where, where
somebody is mentally on ai. so I happened to see a bunch of the tweets before I
watched it, and so I was a little bit, obviously biased in advance, but if I hadn't
seen any of the commentary and I had just watched it.

I would've been very confused by the, by the commentary post, you know, post,
uh, interview. And, to be clear, I kind of jumped to the more, salacious part of,
China and, and that topic. But I'm almost. Probably 80% with Jensen. my sort of
way of thinking through the logic actually works much closer to, uh, to Jensen.

the idea that we're in some kind of, Existential race where a month or two of
advantage is going to, you know, change the total outcome of, AI progress and,
and what everybody does between us and China. I, I just don't agree with, I
think what we are in is a commercial and economic race, obviously with safety,
built into that.

There's no question. and I think we actually have a lot more power globally. if
it's our technology stack [00:06:00] that's powering ai. And so I, I kind of am
more in the camp of, of Jensen on, on his lines of logic. And you know, DKE
kind of oversimplified a few, a few components, you know, he said, with
Mythos, if we get early access to that, then we can go and upgrade all of our
systems and, you know, with, with, again, great respect to esh, it's like,
upgrading software is a multi-year effort. So unless they somehow keep mythos,
closed for the next decade, there's not like some magical moment where you can
just secure everything.

This is an ongoing, endless. till the end of time you're always in this sort of
leapfrogging, you know, between the defensive side and the offensive side. and
so I just don't think these things are as binary, and so I, I actually more am
inclined to, uh, to, to jenssen's view of that. And then Jensen had a really key
point that was, didn't go viral yet, so maybe you could kick it off.

But he had this little small vignette about 90 seconds in the whole conversation
where he said. You know, we're gonna do ourselves a disservice if we scare
people out of engineering. If we scare people out of radiology, if we scare
people out of healthcare because they think [00:07:00] all these jobs are gonna
get eliminated with AI that is not helping us.

that is, uh, it's doing a disservice to the next generation. It's doing a disservice to
society as a whole. Like we, we don't yet know any way to use ai. In a capacity
other than augmenting our work where we still eventually have to go and
review the work in some, in some form. Maybe you don't have to review the
tiny little parts of it anymore.

You can review a, a bigger, you know, part of the, work product that happens.
but we haven't removed humans from the loop. We've just changed where they
enter the loop. and, uh, and I think that that Jensen has a more pragmatic view
of, of the technology. we should be, very thoughtful about how we make these
systems safe. But I'm much more Landon Jenssen's camp, on the overall kind of
contours of the debate. Eight

Okay. First disservice by discouraging people to go into categories like
radiology or engineering. Do you think you will have more engineers at Box in
five years time?
we will. everybody is so myopic about this. I wanna just like shake the industry.
we are so myopic and, and [00:08:00] self-interested and, and we think that the
entire industry is the tech industry. when you go around the country or world
and you go and talk to a tractor company and a bank and a pharma company and
you ask them, do you think you have enough engineers?

To go and automate what is gonna happen in your industry going forward. They
absolutely, unequivocally, universally, always say no. And so what, the
breakthroughs of cloud code or Codex or others are, are doing is it's making it
so those companies now. Can actually do the same kind of engineering that
Silicon Valley's been able to do.

And so we are myopic because we think that tech is the only use of, uh, of
engineers and tech is only, I don't know what the right, right number is, 8, 10,
12, 15% of of GDP in the economy. What happens when 85% of the economy
now gets access to engineering tech has always had? That is what will happen.

and, and so yes, maybe if you're graduating. You know, name your computer
science school today. You don't go immediately to Google, you go to literally
John Deere or Caterpillar or Eli Lilly. But the skills that you have are gonna be
[00:09:00] just as relevant in just a different domain. You're not gonna be
building a little app with little buttons.

You're gonna be automating pharmaceutical research. You're going to be doing
AI for the future of, farming and industrial equipment. So we're just too myopic
about, about how this works. and, you can already start to see this sort of
playing out. There was a really funny FT article, which is lawyers are being
inundated by all of these kind of AI responses that they're now getting from
their clients, saying, Hey, can you review this contract?

Or Can you review this memo? Or, can you look at this, this case? Well, guess
what happens when everybody thinks that they're a lawyer? Do you know what
the ultimate constraint is? The ultimate constraint is the actual number of
lawyers. that actually are able to go and review all of this stuff being produced.

So I would take the other side, I'd rather, like there are gonna be more lawyers
in the next five years than we have today because we've made it easy to
generate legal content, but it has not gotten any easier to actually get any of that
approved by any court system or file a patent or any of the things that law
actually ends up relating to.
[00:10:00] So these are, again, this is where I, I, I just differ from the rest of the
industry.

Do you really think so? With the greatest of respect?

we are seeing the eradication of kind of lower ranking legal positions.

And, and that, that is a different issue, which is how do you do the next
generation of mentorship and apprenticeship when AI does automate the maybe,
traditional tasks that those workers are doing. A big question. Facing every bank
in the world, every law firm in the world, anybody who had a, a sort of an
apprenticeship model.

I don't doubt that that's a real issue, but that's different from the constraints that
all of this work ends up resulting in that you still have not been able to
automate. We had a customer conversation. Two weeks ago, and, and, and this
is just gonna sit with me forever. I'm mean, I always have this example.

They've automated or they're working on automating patient referrals. When,
you know, when you want to go and see the radiologist or the, the high-end
doctor for whatever issue you have, they're automating that, which is awesome.
So now you don't have to be on the phone for, you know, a week or whatever.

Well, guess what? You can automate anything. But if it stills 18 months out
before an appointment is available. [00:11:00] your ultimate constraint is. Still
the healthcare institution and the amount of doctors we have, and actually the
amount of, real labor we have across those organizations. So yes, maybe, you
don't want to, you know, stake your career on being a frontline.

You know, customer ser service rep in healthcare right now. but first of all, that
same person will have a lot of other types of jobs that they'll have access to. but
you still will end up having all of these other constraints that, eventually we will
need to produce more and more jobs to go and resolve.

So automation is gonna actually just force us to see the next set of bottlenecks
that are in all of these industries that we didn't perceive that we had before
because everything was so slow and manual.

What job title does not exist today? That will be incredibly prominent in five
years time.
so I'm workshopping and, and a bunch of people are, are doing this. So this is
like, not my invention, but I'm, I'm workshopping.

Aaron, you, you've gotta take attribution as a venture investor,

it's all about coining a term. Okay? This was your original thought.

Okay. Had in the shower, Aaron Levies,

share it with me. I've been [00:12:00] influenced by nothing I've seen online.
Uh, this is all from me. so there's some kind of, and, and who knows if this
sustains as, as a full-time role or where it gets diffused into? I'm not, I'm not a
hundred percent clear on that, but there is a hundred percent a role right now
that there's gonna be.

500,000 a million jobs created for and it's basically some kind of agent operator.
and this person is actually gonna be needing to be, somewhat technical. They're
gonna have to like, be deep in the AI world. They're gonna have to understand
CPS and cli and they're gonna have to know how to write skills.

They're gonna have to understand agents, MD files. it's gonna be this group of
people. That will know how to go into your marketing team or your legal team,
or your operations team, or your life sciences research team and this is the
person that is basically going to. Enable that function to get leverage from
agents.

And, and the problem that the real world has, that startups and, and frankly
many of your guests don't understand, is that when, when you start a company
from scratch, you've got, like, [00:13:00] you know, the world is your oyster,
right? You can design your workflows however you want. There's really no risk
if you, if something goes wrong.

'cause you don't have much scale to begin with. There's no real regulator that,
that is sort of calling on you to say, Hey. You know, are you doing things the
right way? It's, effectively infinite upside in white space when you go into a
Fortune 1000 pharma company or bank or, you know, consultancy, that's just
not the case, right?

These guys have, they're regulated, they have data fragmented across their
organization. They have employees that are, that are sort of wired to do
workflows a particular way. So there needs to be somebody that can basically
say, Hey, if we actually want to get real leverage from automation. We need to
start to redesign the workflow that we're doing, and the workflow needs to be
redesigned for agents, not for people.

so what do you do when you reimagine a business process where the agent is
now doing much more of the work than what the human used to do in that
process? And that just means it's a, it's a very different sort of implementation
cycle. It's, there's real change management.

You've gotta get data organized in the right way. You've gotta connect up
systems in the right [00:14:00] way. Guess what? The second a new model
drops, your workflow probably breaks. because the way you prompt that agent
now is different. There's a different way that, that it wants, its synex to be, to be
handled.

So. it just requires care and feeding and, and, and a real level of kind of
technical and business process acumen. so I think we're gonna create, an untold
amount of jobs that look like that. Some of those people will come from it.
Some of those people will come from operations, some of them will come from
engineering.

if you're in a maybe more technically inclined company where it's like the next
generation of, there's a, a limit to, again, the number of software you need to
build, that looks like an app on your phone. There's an unlimited amount of
software you need to build. That looks like a background system process that's
connecting different data sources, automating workflows.

That's where the the work is gonna go.

This was really gonna be one of my main questions, which is, you know, Jensen
very clearly said, AI won't kill software. It will explode the amount of software
needed.

And when I thought about that, you know, the thesis there is obviously you kind
of, you have this kind of core AI that crawls over 15 SaaS [00:15:00] tools and
they really become databases that agents crawl on top of. Is that what it looks
like? And are they not just valueless SaaS tools then?

I think that, that I'm sympathetic to that argument in some, in some categories, I
think there's some software where, because the person was the user of the, of the
software and they were clicking all the buttons. That your sort of ratio of
buttons to underlying APIs was like more in favor of buttons.
And I'm, I'm oversimplifying, but there, there are some tools where you open it
up and there's like 93 features, that you're kind of clicking around on. And the,
and the user has been so accustomed to exactly how to do that. that the
software's value proposition was correlated to roughly that, that sort of mass in a
world of APIs and a world of agents being able to do more of the work that you
used to do on clicking those buttons.

then again the, the value goes more to the API layer. So then the question is,
how many APIs do you have? not in like a, you just need a thousand APIs, but
like. how robust and useful and, proprietary and how much business logic is
embedded in those APIs versus it's just calling a [00:16:00] database and pulling
a record.

does the API surround a a set of business logic of like, no, it actually secures the
data. Or it knows exactly what person, each piece of attribute should have
access to inside the organization. That's, Yeah, at the end of the day, all
software has a database behind it, so you could oversimplify it and be quite
reductive to that.

But there's a lot of business logic in the layer above the database that software
players have. Like if you're an ERP system, you know you're way more than a
database at this point because you've written a tremendous amount of business
logic of how your supply chain should be automated and work and how you
should do accounting.

None of that goes away. So then the question is, what changes is the user
interface that the, either the user or the workflow is interacting with? The user
interface might be, now you're just chatting with an agent. I think increasingly
the right way to do this is there's some kind of agent in the background that's
connecting multiple systems.

So you're, you're not even like the user's, maybe not even seeing half the value
that's happening, but the agent is sort of working across an ERP system, a CRM
system, an HR system, a, you know, a document repository, and then doing
work across those systems, which [00:17:00] means that the value proposition
has to be how good are your APIs?

How well designed are they? Are they ready for agents? And then can you
monetize that in some way? That makes sense. And, and we are treating
software too, too much like one gigantic sort of, monolithic industry. And it'd
probably be better to have some kind of two by two, which is like. How much
business logic is there, how much sort of human to agent, collaboration does
there need to be?

the reason I bring that up is the moment you have human and agent
collaboration, you need some kind of, usually you need something that the user
can pop into to, to experience the work that the agent did. And, and that
probably doesn't go away so much. and then you know, when more agents are
working on the software? Which parts of software do the agents need those
APIs even more than humans ever did. I think there's a lot of categories of
software where actually agents using the tools is a massive boon for the
technology as opposed to a dilemma.

Where will agents use the tools more than humans do, and those API calls
become much more frequent.

Yeah, So like an easy one is just [00:18:00] unstructured data. agents are going
to be this incredible consumer and creator of your unstructured data.

They're gonna. Read through every one of your contracts and generate all of
your contracts. They're going to generate marketing assets. They're gonna write
reports for you. And so when it becomes trivially easy for you to generate all
this new information or have agents review it all, well guess what?

You still need a backbone that kind of manages and coordinates and creates the
guardrails of those workflows and, and all the agents doing that work. So we're
about to see an explosion of unstructured data as an example.

With the greatest of respect. Aaron, can I just

interject,

does that increase the value of your business?

When I think about that, I, I asked Aaron from Monday, if you become, you
know, a data repository, which agents crawl on top of, how do you retain value
in that?

yeah, a hundred percent. It, it's, it's the question on the mind of every investor
on the planet right now. So we're, we're used to it. And it's not a, it's not, it's not
a scary question. Um. one thing that that helps us is we've always had a an API
maybe not first, but equal strategy. if I told you the number [00:19:00] of API
calls we did last year, you'd and, or you guessed first, you'd probably be off by
an order of magnitude.

so the volume of API usage on our system is already enormous and already, is
outsized relative to any of the end user interactions on the system. and that's just
a virtue of you use content in a variety of applications and workflows that, far
exceed what, what people, kind of, open up their finder and, and upload a
document into like, an ERP system generates files.

A, a wealth management portal. You have clients uploading documents into the
portal and they never see box. you have workflows of invoice processing that's
happening behind the scenes. So the headless version of Box has been alive and
well for, you know, almost since the day we started the company. And so agents
to me just again, represent a force multiplier on that.

So it's it's actually an exciting proposition for us. We already know how to
monetize it. The question is like, will the exact dollar and cents be the same
between an agent user and a previous application user? We don't know. But we
do know that if the number goes up by a hundred x or a thousand x, that's
actually more opportunity for us in the future.

Now, that's not all the same for [00:20:00] all software providers, but for where
we sit in the workflow where you just, you generate a document, it needs to go
somewhere, you have to secure that, you have to protect it. You, you have to
govern it over the long run. That's just more data going into our platform and
that's, you know, so that's why it's just all upside for us.

You said secure and protect it. We mentioned our mutual love for R or Driscoll.
I do

a show with Rory and Jason every week. Jason has bluntly said that this will be
the golden age for cybersecurity because the security threats are going through.

Roof. Are you concerned with the system vulnerabilities and the security threats
that are coming with ai?

And what do we not know about security that we should know?

I am concerned, but not, in any kind of like new concern sense. Uh, this, this to
me was kind of priced in the moment that we were generating code with ai. So
if you can generate code, you have two problems, one. You are gonna generate
way more code than anybody's ability to review that code. So, starting with
GitHub copilot six years ago or whatever the date was five years ago, like that
was just priced in, which is as [00:21:00] soon as, as AI writes most of the code
or, and then like 90% of the code and then 95% of the code.

Then by volume we're just gonna produce this unbelievable amount of code.
And, and any, any change in a system, you know, everybody kind of thinks
about security as like, you know, is there a zero day where there was an
unpatched, component of your technology or somebody. Found a clever new
package that, that, that you could kind of slip into.

every time you, you ship a new feature, you have a chance of a security
vulnerability because the, the AI could have written in, oh, you know, we want
to actually open up that port in the system because we need to do something.
And maybe that was the wrong decision for the agent to go and do So we are
gonna be living in this new world of, cyber risk, in the form of, using agents
more.

then on the other side. Obviously if you have the offensive side, able to use ai,
probably more in the form of open models and and whatnot, then they can find
more vulnerabilities. 'cause they can scan across the internet far faster than
before. So you actually have two new forms of risk in the development process,
and [00:22:00] you only have one benefit, which is agents can also review the
code and, and try and keep it secure.

So, it's gonna be a, very dynamic, um, period. I, I think. You know, for better or
worse agents are the solution to the problem that agents have caused. and, and
that's why there's gonna be a lot of money made in agent security, as well.

You said agents are the solution, to the problem that agents have caused. It
almost reminded me of when Janssen went on TV and was like, oh, every
engineer should be spending, I can't remember the amount. I think it was either
two 50 or 500,000.

Or like half the salary essentially.

Yeah, yeah, yeah. And it is kind of like, you know, drug dealer, you should buy
drugs.

Well, okay.

No shit.
I, again, I'm, I'm, you know, obviously Jen. I mean, listen, we love Jensen for
that level of, of, of, you know, grandiosity and, and charisma. So I, I actually, I,
I bet you know whether he's off by half or not. I mean, directionally the idea is
actually pretty salient, which is, you're gonna be spending more on compute per
person in the future than than you ever thought, and that you certainly are today.

What percentage of salary are you going to spend on compute [00:23:00] inbox
in five years?

great question. Uh, I don't think we've modeled that out in five years. And
obviously the joy of being

Well, this is

your chance.

No, no, totally. I, you know, I was told not to model long-term financial
projections on podcasts, so, yeah, it's a weird SEC

financial

so boring.

I say it's extremely boring.

Don't ever go public if you don't wanna model on, on, uh, on podcasts. So.

Live. This is why the Collisons don't, everything else is great. They just didn't
podcast. Yeah.

Cheeky pint. They

I don't know if you'd, I don't know if you'd be able to pin Patrick or John on the
same question for their five-year view, but, but you know, it'll be a larger
number for sure than it is today,

I'll smash them with four tequilas and then ask them, um, you said one of your
observations in your very viral tweet, was about token maxing and
kind of token allocations within enterprises. I'm really intrigued. How do you
think about advising CIOs on token allocation, token maxing, what we should
know that we don't know?

How do you think about that?

this one's tough. It's, you know, the general advice will end up sounding kind of
like, you know, kind of generic by definition. [00:24:00] it, you know, usually, I
mean, it's gonna have, it's gonna have something to do with. your tokens, we'll
have to correlate to where there is the most amount of, you know, value
generated for your company.

Like, like most bland statement of all time, but just obviously it has to be true.
in the software industry, we're into token maxing because guess what? Like
generally the value proposition of your company will correlate to how much
software can you produce. And so, If you're trying to drive a lot of change and
you want to make sure everybody's shipping lots of soft software and you
wanna be able to teach the best practices faster, then token maxing and
leaderboards are an interesting way to do that.

you know, it's not obvious that you're gonna see that across every industry.
we've seen a couple of interesting examples. One company had this sort of like
shark tank pitch, Aon type thing, which is, teams have to show up and they have
to go pitch compute, you know, token budget, and then you kind of allocate it in
some central fashion like a VC would.

And then you sort of, you know, I don't know their exact interval, but I would
imagine you review that three months, six months in being like, okay, did you
get the upside that you thought on that token usage? So that, that's an interesting
one. Another company had a kind of a view of like, it's some [00:25:00] kind of
like natural stratification of, 5% of your users are doing the most valuable
things.

20% are doing the next tier of most valuable things, and then everybody else is
sort of doing general productivity. I, I'm making up their numbers, but the idea
would then be like, well, for that five or 10%, give them the best models with
unlimited capacity. For the next 20%. Have some limits, maybe it's a, a little bit
more efficient of a model.

And then for everybody else, it's sort of like, we're gonna just use the cheapest
thing on the market. it's not gonna be like the game changer of the employee
productivity. and so I think everybody's kind of working their way through this.
The, the part that, back to Silicon Valley's again, kind of.

You know, sometimes more, let's just say like, like positively naive view is, is
like real world. They have like budgets and they have like annual budget
planning cycles. 'cause they have EPS numbers. They, they commit to Wall
Street. And so you don't get to just be like, oh, we're gonna token max across
the enterprise where everybody gets unlimited token budgets.

Because obviously then that company would just miss Their earnings
throughout the year. So you have to like, wait for the budget cycle. You
[00:26:00] have to figure out what teams, are most interested and, and have the
best use cases. That's a, that's a natural journey.

one, final bookmark. that I think is, is well understood now at this point is the
budget of tokens will have to move out of it, spend. And into regular kind of
opex spend. This can't be treated like a, oh, I'm gonna trade off between
Salesforce licenses or, compute tokens.

Like, it's gonna more be, I'm gonna trade off, this next marketing campaign. and
instead I'm, I'm gonna go and drive more automation in our, in our marketing
engine. Like, it's, it's gonna be that kind of, of set of trade-offs.

What happens to that token budget when it transitions to that different spend
category?

well first of all, it goes up because, it spend as a percentage of revenue, of, of
large enterprises is,

But is,

this the same as the kind of classic VC blog post, which every firm has written,
which is like, ai, it's moving from software budgets to labor budgets, and every
partner

goes and likes the tweet and there's like no fucking shit.

Like really?

yeah. Uh, I mean, if you do it in that voice, it [00:27:00] sounds, it sounds kind
of like, you know, simple, but like yeah, that, that, but like, that's just like a very
big deal in technology. We've never had. there's never slash rarely been a
technology that you could sell into an enterprise where you weren't capped by
that company's corporate IT budget.

And so now for the first time ever, you have a technology where you can go
into the line of business and you can say, I can now offer you a new tool in the
form of an agent that will augment a workflow that will make you 50% or a
hundred percent more productive. And so maybe I should be able to get 5% of
your OPEX budget this year to go and do that.

That is a new budget to tap into. And I don't think it, like, 10 x is the size of, of
it spend or, or technology spend globally, but it certainly doubles it.

I mean, Tarn, uh, enterprise technology spend is estimated between 10 and 12%.
To see that going to like 20% as you said there, it's like, I think relatively
feasible. You said about cutting companies being like based on earnings per
share and actually having budgets that they have to adhere to. Very strange not
to have venture funded companies.

Uh.

Yeah, don't VC to [00:28:00] this.

Can't we just go to a venture investor and ask for more money? the one thing
that I worry about is we see this insane demand side pull. Every company in the
world needs an AI story. Everyone wants to kick the tires with something. And I
think we project the same demand side pull and extrapolate it continuously. Do
you worry that we are in a momentary 18 month period on the demand side
pull? And that may not always be lasting.

 it is very possible. I should be more sensitive to that. but. I would take the
opposite side of, of that particular wager at the moment partly because we, I
already saw one diffusion cycle with cloud and actually how long that ended up
taking and the, the kind of spiky early nature, you would've just been like, oh
my God, this is, this is on fire.

It's, it's, and how could this last? And 20 years later it lasted and got way bigger
than we ever realized. if it works. The market's always larger than you ever
think. the only part why 18 months is like, not even a relevant window to me is
I think diffusion is gonna take a longer than Silicon Valley thinks.

And it's back to the very first kind [00:29:00] of that new role idea. When you
go to most companies, they can't yet just deploy an agent to do. you know,
financial proposals for all of their, their clients without a human reviewing the
thing. And because the SEC will just show up and be like, Hey, you just gave
this person bad financial advice and you're gonna lose your license.

Like. that will just start to happen kind of across the board. and so that, that's
why, you know, people take time. That's why there's a lot of regulatory controls
and compliance teams. Security teams have to figure this out. That just takes
time in the economy.

I had, I think, Matt Fitz Fitzpatrick. Invisible, which is like a Turing or a Macall
competitor, and he said, you cannot sell into enterprise. Without an FD, E
model, it is impossible.

I mean, it rounds to being true,

super interesting to hear that. 'cause we are seeing like the rise of, oh, we go
PLG and then we like seep up into enterprise

Well, I don't, think of those as, as mutually exclusive for what it's worth.

Um,

what I'm saying is when you think about adoption within the largest enterprises,
are AI services companies [00:30:00] the best positioned companies of the next
five years?

Well, as in you're saying like traditional professional services?

Yeah. I'm saying Accenture's AI team that

come into Bank of America.

a hundred, a hundred percent. these spaces are gonna be, again, both bigger and
more sustainable and robust than people realize. We, we are always, so back to
the myopic thing, we're so myopic. We're like, AI will replace all of this stuff
'cause it just does it for you.

And it's like. I'm trying to think of, um, you know, maybe my most recent
experience with the best models in the world, I, I probably had to go and change
15% of the thing. that was the output. we are nowhere near eliminating the
human from the workflow.
And so in a world where you don't eliminate the human, then there's a lot of like
real change management of like, where should the human enter that business
process? How would you want to review that, that work output? How do your
wire up your systems? To make them effective for a, for the agent and human
collaboration.

How do you connect all of these data sources together? One, one thing that we
see is, you know, if you wanted an agent right now in a Fortune 500 company to
go and, give [00:31:00] you an answer to where is the most risk you have in
your upcoming renewals for your contracts. That agent might find 10 different
systems that contain contracts in them, and half those systems will be like
legacy technologies that don't work well with the agent.

They're kind of low throughput or maybe you can't even wire them up. They're
on network file shares, they're in legacy document management systems. So
first of all, half your data estate. Is not even ready to work with the agent. The
other half of the data state is probably fragmented because you have two
decades of employees bringing in their own tools, and so the agent will just go
and find the wrong document or the wrong contract, or the wrong piece of data
because you never really cared to have some kind of standardized system.

For your contracts because people could just always go and find what they were
looking for. Agents can't do that. They, I mean, they'll find what they're looking
for, but they'll just as often find the wrong thing as the right thing. So they have
to be targeted. They have to have that information get curated.

They need to understand the context of, of what is the process that they're doing.
what I just described right now is 10 years of work for [00:32:00] Accenture in
every enterprise on the planet, or the next gen Accenture that does this, in
particular industries or workflows, like we have to go upgrade your systems.

We have to start to understand and organize your data in the right way. We have
to start to describe these workflows to the agent itself. We have to figure out
where the human is in the process. That is just real change management that
every organization will have to go through.

We also have to have someone to blame.

Correct? No, a
This is, this is why a lot of these industries last, which is like, I have lawyers
not, 'cause I can't necessarily ride an NDA. It's because it's your fricking fault if
anything goes wrong.

Yes. No, literally, and, and, and we don't know. like, I promise you, you're not
gonna be able to blame philanthropic when something goes wrong. And so if
you can't blame philanthropic when something goes wrong, then at some point
it, it doesn't really work to tell your customer well that sort of system that we set
up screwed up your data or it automated something the wrong way or create a
security vulnerability because the company will just say, well, I'm never
working with you again.

So then you have to have some accountability in your own organization for who
is [00:33:00] liable. when something goes wrong and, and the moment you have
to have any liability, you have to have some amount of ownership and
accountability and, and people have to have, they have to roll up to somebody
who has more liability and more ownership and more accountability like.

This hasn't really changed the fundamental pattern of, of human behavior and
contract law and, the regulatory regimes that everybody's a part of. We've just
sort of given our computers and machine gun to go generate way more
information and work with all of our data.

You said before when I've tried the latest model, it's got like 85% of the way
there. I speak to many of the best early stage and more mature, west Coast
based companies and they say, Hey, we use frontier models to set where we can
be and then we use open source Chinese models to get as close as we can to
that.

Frontier Benchmark is Silicon Valley being funded by a generation of open
CCP funded open models.

I mean, that, that must be kind of empirically true. I don't have the same kind of
like, uh, oh, that's so scary, you know, kind of element. [00:34:00] Now,
obviously, again, holding out some, some element of risk of, of some backdoor
weights that, that can get triggered at some moment or some parameters, but
like, that's not how I'm perceiving it. but also that's, I I would say that's kind of
orthogonal to my point about like the best frontier model still will go and do the
wrong thing. and so thus I have to be in the workflow loop to make sure that I
review.

Its, it's work.
You know, as a venture ambassador, I specialize at making bold statements with
little substantive evidence.

It's, it's worked, it's worked for the greats, so,

do you know what? I'm just following their lead.

Jason Lamkin, my dear friend, says, why is no public company created any
good agent product? Everyone creates 60% shit agents.

 But he's like the one person who's done. Its Palantir and no other public
company has

created a sufficiently good agent product. Why is that?

I guess, you know, I, I don't know that I can fully endorse the point, but can
give you the, because I, I, I would argue our agent is sort of the best agent for
working with content.

 you know, this is a very [00:35:00] fast moving, space, and you have to be kind
of wired in at a level that, that I don't think you've ever had to be wired in, in
tech, and, and the information sources aren't the classic ones. It's not the roll up
review two weeks later from your traditional news publication that is gonna
give you any kind of alpha. It's, it's the practitioner who's the. You know,
literally the engineer at the, agent Sandbox company and their, their long form
article on how they are handling, you know, memory and the harness.

 like if you're not wired into that ecosystem, it's very hard to then have. Your
team, be at the kind of forefront of all of what is happening. And so it just is a,
it's a different pattern than what we've ever had to do. Like, COVID was, was
pretty crazy.

Like we all had to kind of like hunker down and be paying attention to daily
news cycles on, COVID e stuff. but it wasn't like a tech problem. Like it wasn't
hard technologically. but there's not been a moment before. Where the speed of
change and responsiveness you have to have is quite [00:36:00] literally on a
multi, multiple times a week cycle.

Is your job harder than ever?

Yes.
Because of that speed of transience, of superiority of technology.

Yes. you basically have this, component of one. There's a tsunami of change
that you can just feel, and so you're, you're like, okay, we gotta like run faster
than ever before. and then there's just like the pure technical underpinnings,
which some of it has business and strategy implications.

Some of it is product implications, some of it as partner ecosystem implications,
because of that tsunami that you have to very quickly kind of wire up what you
are doing about that shift, and where the market is going. At the exact same
time, you have to also be like, you know, find a way to be a bridge for your
customers that, also don't want to get, crash into by the tsunami.

And they wanna be able to, to be able to have a bridge into the future. And so
there's just, you're juggling a lot right now.

You said your agent product is the best product. Again, Jason Am. Rory said
this, and Rory might kill me for this 'cause he gets a little bit more sensitive
about when I quote him or misquote him more appropriately, but like he
basically says it, [00:37:00] and this is Jason again. If you can't like charge way
more for your agent product, Wall Street doesn't give a shit like you have to re-
accelerate revenue with agent products. Can you charge significantly more for
an agent product?

The, the answer is yes, but, there's a little bit of nuance, which is our business
model is we we have a new, plan tier that we just introduced last year that
basically houses.

Our, best workflow capabilities, our business automation, you know, our
application development capabilities. And then the agent is sort of central to
that because it's gonna help you automate the work that, that you're actually
doing with your content. So it'll read a document and extract metadata from it.

It'll process information inside of a workflow. So that is actually causing a re-
acceleration of our revenue growth. Last year we saw an inflection in our
revenue growth and so that, that it's already happening in our business. and so
we are, we are doing, the thing that I think Rory is, is sort of probably saying is
the new benchmark.

 now, to be fair to what's, what's happening though is I think Wall Street still is
sort of saying. We kind of need to just step back and [00:38:00] see where
everybody lands in this because of how much change there is. so this is very
much a year where if you're in software or infrastructure or building agents, it's
a year of complete unrelenting execution.

Do you look at the ticker

Yeah,

every day?

yeah. But, but I was like a day

I've never met a public company, CO who hasn't, but, um, the Navan, CEO was
on the other day and he's like, multiple times a day, multiple, multiple.

No, a hundred percent I'm, but like, but like partly I just, I have like, A DHD or
something and so I just need like, I'm like, ah, is there.

It's, well, we look back on this period and be like, what the fuck? Companies
trading at three times cash flow way over exaggerated or not.

Three times cash flow is, is very much over exaggerated. I would say that we're
in a period right now where basically the market is being treated roughly. as a
kind of indiscriminately, you know, kind of bucketed sector and the next year,
two years or whatnot, you'll start to see some separation in parsing between the
[00:39:00] companies, because as I noted in the beginning.

Agents will be really good for some parts of software and agents will put
pressure on parts of software. So, and it'll mean some companies have to fully
pivot and some companies can just sort of ride their wave and, and if they
respond, you know, effectively, clearly three x free cash flow that seems like
aggressively low territory.

But I also think that at times in software, things have been aggressively
overvalued, beyond the, the realm of, likely what the terminal value is of
particular, you know, category or, company as well. So, I think there's just a
pendulum that needs to kind of find its equilibrium right now.

and that that'll play out over the next year.

 Do you think this generation of CEOs that you have around you though is
equipped for the AI transformation that is ahead? Because I don't like, I think I,
I'm, I'm not blowing smoke up your ass. You are. You're so versed in this.
You're so fluid. But a lot are like, now, one said to me the other day, no, we
don't have the AI chops in house.

We might need to bring it in.

 this one's hard. I think you still have a lot of kind of founder led or, tech, you
know, forward, [00:40:00] whether they were an engineer or just they're, they're
just very technical. category of folks that are, are pretty dialed in and like, I
have Slack channels and, and WhatsApp groups where people on the weekend
are, are just like working with Claude Code or Codex Building stuff they're
public company CEOs.

So, they are clearly wired in, tapped in. They, they can feel the technology. And
they're not gonna let their company lose. you know, assuming that, that as a, as
a category, they're in a spot where there's a lot of upside. so yeah, but like every,
every technology wave, there's winners and losers.

I don't know that the, this won't be any different. you just have to be super
dialed in and work through it.

Hard one before we do a quick fire.

Who has the world turned their back on? Who you think should be much more
appreciated.

Oh boy. Um, you know, I'll give maybe a shout out to like, Atlassian, as an
example. I think that that feels like, oversold territory. you know,

eight, eight.

78 percent's a bit harsh.

I think possibly. and you know, it's in the category of, they've been fighting this,
this narrative.

engineering gets commoditized. And so like, where in the [00:41:00] stack was,
was their engineering, you know, revenue generation. And again, with my
headset, I'm like, no, there's gonna be more engineers. And so. Now, does that
mean that Atlassian's product set will look exactly like it does today?
No. Like, obviously it's gotta evolve and whatnot, but, but I think if you're like a
company selling infrastructure for engineering to be more automated, that
seems like a good spot to be in. And, you look at what Linear is doing and it's,
it's fantastic and it's awesome to watch. but I think there'll be, you Multiple
plays in that space, just given how big the market is. I think right now, this is a
moment where you need to be deep in the workflow and you need to have data.
you have to have data. in your platform and you have to be the best place for
that data to go, and you have to be the best place where agents want to work
with that data.

That's like the mandate right now is if you are not the best place that an agent
would, intentionally choose for working with data of that particular category or
automating the workflow in that particular, you know, area. That's a tough spot
to be in, and that that's the, the job for all of us.

You know, if you're building software.

And the best place where [00:42:00] agents want to work is defined by great
API.

Great APIs, great pricing models. the surrounding features to the API. So if you
were to say, Hey, I want to be able to wire up a workflow where, um, this is the,
you know, the box sales pitch, I wanna be able to wire up a work. Flow where
an agent is interacting with FINRA compliant documents, you know, FINRA
compliant document means the things that gets generated or seen or shared with
the customer and it, it can't ever be deleted and and removed after, you know,
for a certain amount of time.

then on one hand, the APIs have to be super clean for the agent. On the other
hand, you have to have a bunch of surrounding capabilities to ensure that that
company can go to their regulator or auditor and say, yeah, we, we are
complying with finra. So that combination is what makes it so you would build
that kind of agent on something like box and that that persists across a variety of
industries.

I'm gonna do a quick fire round with you. you, you have to go and be a public
company. CEO. I know. so what have you changed your mind on in the last 12
months? Most significantly.

I, I do think that, I've become more convinced that software is headless. In the
[00:43:00] past year than I was maybe three years ago.
And it's because of the, the level of agentic capabilities on tool calling and
searching across systems and the accuracy of that. and that, that has happened
faster than I, I would've, perceived. So two to three years ago, if you were to
kind of. You know, wire up an agent and tell it, Hey, go work inside a box and
find a document to work with and do some process.

it would basically almost always find the wrong document and it wouldn't be
able to handle actually, like cracking open the file and reading through it. And
so thus, you know, going headless wasn't sort of the, most urgent priority, from
an ag agentic standpoint. And in the past year, those capabilities have just
absolutely accelerated to the point where I'm fully convinced that, you have to
be, you know, headless first as a software platform.

What acquisition did you not make that you wish you had made over the box
journey? Jensen said in the show, oh, I wish we'd invest in frontier models. That
was my big mistake. What acquisition did you not make that you wish you had
done?

I honestly don't. I don't think [00:44:00] I have any, uh, m and a regrets. I
actually, it's the deals that I wanted to do.

that we ended up not doing that I don't regret, is probably more the, the
situation.

which one is

that?

not gonna tell you those, but, but there are some where left in my own devices I
would've done and I look back and I'm like, oh, thank God that there was, uh,
there was more rational logic in the process.

Who is going to win the enterprise race? Open AI or anthropic.

Oh God, that, that's impossible. back to the cloud piece. I think it's, it's totally
fair to think about it as a race. And certainly if you're, if you're in either of those
companies, you have to treat it like a race because, because you know, like you
obviously want 80% market share, not.

55% market share, So like, you have to treat this as a, you know, we gotta
dominate. that's exactly how they, they should be executing that way.
Everything is going according to plan if you compare it to other areas of
compute. and, and I, I ran this analysis recently in 2010. not you know, maybe
you were 12, but like the rest of us, we were just like in companies doing things.

in 2010, AWS made [00:45:00] $500 million in revenue. Azure had just
launched and GCP was called Google App Engine, and it had a little like a
turbine logo, uh, with like wings or something. So that was the state of cloud.
Fast forward to this year, and it's a couple hundred billion dollars a year revenue
ecosystem, so in 15 years. Right. So, and we were in that moment being like,
who's gonna win AWS or Azure or GCP? What's, how's this all gonna play out?
And it just turns out. The market was so large, obviously it was due to their
execution that they kept it going and kept it large and the competition kept up,
but it, it just didn't really matter.

Like everybody, everybody kinda won. And so I, I sort of think of AI in a
similar fashion, which is. I can't predict if it's gonna be open AI 60% and
anthropic 40%, or it gets flipped or I'm off by another 10% here or there. but no
matter what, these markets are just fantastically large companies are, are going
to adopt multiple of these systems.

They don't wanna have single vendor in this stack. One service goes down or
one changes as APIs, or one has a new commercial model. You're gonna, it is
gonna [00:46:00] be a multi-vendor, multi AI world. and so that, that's why it's
like very hard to kind of like call it at this stage.

Everyone think they know about enterprise adoption with ai, that they get
totally wrong.

what they think is that, is that, the outcomes that you're seeing in AI coding will
quickly come for other areas of knowledge work. and that is a, a slight misread
on the other areas of knowledge work. and some of it is the idiosyncrasies of,
coding, and some of it is the.

Broad, kind of just elements of the rest of work and how it happens.

If you were a venture investor today, which category would you be most excited
to invest in? Obviously, I'm just hype,

speaking,

God, I would, I, I think I would still be probably loading up on all of, the, the
frontier rounds. it's, yeah, like these numbers could, could continue to get much
larger.
Could they get, I mean, much larger, I mean like this is where I might at eight
50 billion, you've got like a a three X to like a 2.1 trillion style

you know, I, I always think it's hard because, I kind of have said that on the
way up of many companies. [00:47:00] Like, like, like, you know, just like,

I did it with crypto, like how much further can it go? It's like.

yeah. Well, well that one, I'm gonna put it in a different category 'cause that's,
that can just sort of be MeMed to life. I,

No, but I actually, no, but I actually think, but like to the point on Atlassian and
bluntly, you and your whole category is the casino of the stock markets, which
is like if you're a momentum trader today, you still buy Palantir because the
market's a casino right now.

Yeah, well, to be a little bit more fair. I think you have some one-off companies
that have done a, a, you know, amazing job capturing the zeitgeist on that. I
think the broad story right now is the sector rotation story, Hey, this AI thing's
happening right now.

I can get a higher return if I, if I get closer to the semi stack and the kind of, you
know, where the workloads are going and where the data center build out is
happening, and I get less of a return if, if I'm in software, you know, with, with
kind of pure licensing. And so I think that that is probably more of the color of.

Of what we're seeing now. some of the data [00:48:00] center and infra, names
maybe have been mummified also. And so that's kind of helping the case. but
it's just a really weird time, you know, overall, uh, that that's, you know, hard to,
hard to think through.

So you would not buy Allbirds as an AI company?

I mean, maybe you would because of that exact point. So I think you'll have,
that will be in the kinda one-off category, so new bird AI or whatever it, it's
called. Um, but I think, no, I, I hear this is a generic statement. There will still
be a lot of money to be made in the companies that can take the innovation that
we're seeing in Silicon Valley and in the labs and apply it to the real world, you
know, work that happens inside of enterprises.

And whether that looks like vertical ai, whether that looks like, the new kinds of
tooling that, companies will need. there's a, you know, a company and a new
category merging on, on, agent observability and evaluations. I'll give a shout
out to Brain Trust as an example, not an investor.

where I can just kind of sit back and be like, shit, like we thought that agent
builders were gonna need evals. So that's like a Silicon Valley tam. And then
I'm like, oh, actually everybody [00:49:00] on the entire planet, if you're putting
agents into an enterprise workflow needs evals because you need to know if all
of a sudden your agent just stopped producing, you know, loan origination
documents the right way.

And so that's a category where, it's probably not gonna be owned by one of the
labs. You kind of want it to work across all the labs. it's a very relevant, kind of
new form of. of infrastructure for an ag agentic enterprise. I think you're gonna
see a dozen, two dozen, five dozen of, of things like that, that that start to
emerge.

I've known you for a while now and you've put up with me for multiple
different sessions. so I wanna finish on something a bit off script, but you're a
phenomenal CEO, you're a public company, CEO. The pressure that you have
on you is intense. You're also married and have a great relationship. Biggest
advice on marriage When it's super stressful, it's hard.

And you also have to show up and be a great husband. What, what's the advice
on marriage?

it, it feels dangerous if I actually acknowledge the Great husband, uh, piece and
other, other parts that were embedded in that, um, that, that feels like you need
like a full 360 eval. I will, uh, [00:50:00] I'll just say from my perspective, and
I'm very lucky to have, uh, an amazing wife and, and family and. you know,
you, you are, you're in a grind in one of these roles and so obviously having a, a
strong support base, you know, helps a ton. we try and make time, you know,
for, for the fun, side of life, as much as possible. But, obviously that gets
constrained in, in the kind of window that we're in.

But I've been with my wife for, I don't know. 15 years or so, uh, 16 years. And
so she's seen the whole, the whole grind, all, all the way. And, uh, she has her
own set of grind, uh, in her business. And so it's, it's just lots of fun.

Dude, you are my hair. I want to be when I grow up. Thank. You for being so
great. I really appreciate, and I was 14 in 2010

just as
an FYI.

it, I

almost called it,

But before we leave you today, did you know that industry average for booking
a business trip is 45 minutes? That's a massive waste of your team's time. Well,
with Navan, your employees can book a trip in just seven on average.
[00:51:00] Navan is the AI powered travel and expense platform designed for
companies that value efficiency.

It drives real business impact through high employee adoption and automated
policy control. Now the built-in AI approves in policy bookings and blocks the
rest automatically. This allows finance teams to stop chasing receipts and skip
the month end chaos. And you get this real time visibility that can save your
company up to 15% on your travel budget.

And that's why leaders like Visa, stripe, Figma, and even Anthropic rely on
Navan these days. Go to navan.com/two zero VC two. Day to see for yourself
and you'll get a chance to win two business class flights anywhere in
Continental US. No purchase necessary rules apply. Head over to
navan.com/two zero.

Now, where's Navan simplifies? The Travel Air Wallet simplifies the spend
behind it. Founders, lets. Get real about the growth tax. You've raised VC
funding and you're scaling globally, and it's no longer about shipping product.
It's about orchestrating operations across continents. But suddenly your
payments and [00:52:00] finance stack is choking your growth.

You are logging into lots of different banking portals, waiting days for transfers
and reporting across entities. It's operational drag, and it's at your scale. It's
costing millions. That's why I'm so excited to. Partner with Air wallets. Air
wallets are more than just a banking alternative to HSBC or Citi Air Wallets
brings you an intelligent financial operating system that powers how global
businesses operate and grow, allowing you to manage and automate banking,
treasury payments, and spend the most exciting part for me.

They're heavily invest. In finance, if you are scaling globally, you need a
banking and finance platform that's borderless real time and intelligent. Check
out air wallets today and see how they're helping thousands of businesses like
Canva, McLaren, and deal scale@airwallets.com slash 20 VC terms and
conditions apply.

Your money's a safeguarded, not FSC. Protected. See air wallet.com for more
details. While Air Wallet helps your money move globally, Vanta helps your
security keep up. Security and [00:53:00] compliance done wrong is a giant
headache. Security and compliance done right though. Well, that's Vanta. Vanta
helps you earn trust and speed up growth.

No spreadsheets required for startups low on time and resources. Vanta
becomes your first security hire using AI and automation to get you compliant
fast and unblock really. Big deals, and if your big enterprises, Vanta is your AI
powered hub for compliance and risk, bringing together data from across your
business and automating workflows so you can prove trust at any moment.

Vanta scales with you at every stage. That's why top companies from startups
like Cursor to Enterprises like Snowflake. Choose Vanta, do security and
compliance. Right. My listeners can get $1,000 off Vanta by going to
vanta.com/two zero vc. That's vanta.com/two zero VC for $1,000 off Vanta.


---
type: 20vc-episode
guest: "Anjney Midha"
company: "AMP PBC"
role: "Founder"
episode_type: interview
date: 2026-04-19
youtube: "https://www.youtube.com/watch?v=a1ymdW-h33E"
transcript: "https://20vc.substack.com/api/v1/file/9bb614c6-4195-4675-81c8-e6f65bd9463c.pdf"
newsletter: "https://20vc.substack.com/p/20vc-newsletter-19th-april-2026"
tags:
  - 20vc
  - ai
  - china
  - defense
  - founder-advice
  - fundraising
  - infrastructure
  - product
  - venture-capital
---

# Anjney Midha — AMP PBC

> Founder @ AMP PBC | 20VC Interview | 2026-04-19

## Key Takeaways

### 1. The Reason Why Mistral Will Be a $100BN Company
The US Cloud Act requires that any data workloads managed by an American company must be accessible to the US government. For European entities running mission-critical logistics or defense, sending that context across the border is a non-starter. This creates a massive opening for local, sovereign infrastructure partners like Mistral to handle mission-critical workloads at scale.

### 2. Why Every VC Missed Anthropic’s First Round
When Anthropic pitched their seed round, they got 21 “nos” from top-tier investors. The reason? A total lack of technical literacy. Most VCs at the time didn’t even know what GPT-3 was and couldn’t grasp the concept of “compute multipliers”: the idea that you could produce intelligence for 6x less cost per dollar of capital.

### 3. How a16z Became a Major Buyer of Compute
Early on, Anjney recognized that compute access was the primary bottleneck for new incubations. By using the A16Z balance sheet to procure compute through the “Oxygen program,” they built the deep industry relationships and infrastructure trust necessary to scale the independent ecosystem.

### 4. The CCP Has Done Such an Incredible Job in Catching Up
The AI race in China isn’t just about chips; it’s a full-stack systems co-design race. By integrating Huawei chips with localized compute and using “adversarial distillation” to capture gains from Western models, they are producing performance improvements that rival the best Western hardware.

### 5. We Are Not in an AI Bubble. We Are in a GPU Wastage Bubble.
The crisis isn’t a lack of AI capability; it’s a standardization crisis. Because compute is not yet fungible, meaning you can’t easily move a workload from an H100 cluster to a Blackwell cluster, billions of dollars in compute are currently sitting unutilized and “stranded”. We are essentially in the “1885 pre-standardization era” of the electricity grid.

### 6. What Makes Dario at Anthropic So Special?
Dario Amodei operates with the obsessive “truth-seeking” mindset of an applied physicist rather than a traditional computer scientist. His brilliance lies in an empiricist approach: running endless experiments to derive general laws of reality, combined with a “ruthless” mission alignment that refuses to take shortcuts for profit.

---

## Links
- 🎬 [Watch on YouTube](https://www.youtube.com/watch?v=a1ymdW-h33E)
- 📄 [Full Transcript (PDF)](https://20vc.substack.com/api/v1/file/9bb614c6-4195-4675-81c8-e6f65bd9463c.pdf)
- 📰 [Newsletter](https://20vc.substack.com/p/20vc-newsletter-19th-april-2026)

---

## Full Transcript

[00:00:00] Our guest today is the most prominent AI investor in the ecosystem,
an miter. Why is he the most prominent? Three reasons. Number one, he's one
of the founding investors of Anthropic. Number two, he led AI investments for
Andreesen Horace, where he made investments in Black forest labs, msra
sesame among others.

And then third and finally today, he's the founder of amp, where he provides
compute and invests in the world's best AI companies.

But before we dive into the show today, you have the idea, but often with AI
tools, you hit a wall. Well, base 44 is where that friction disappears. Turning
how you talk into how you build full stack web and mobile apps, sites,
autonomous super agents, all built in minutes, not weekend spent on damn
configuration.

Base 44 ships it all out of the box. The backend, the database, the
authentication, and the hosting. It handles the heavy lifting so you can just stay
in the flow. It doesn't just replace the busy work, it [00:01:00] multiplies you. It
makes you so much more capable and effective version of yourself. In this
market, being fast is the baseline, but to win you gotta be first and base.

44 is that edge. It's the move that lets you skip the troubleshooting and get
straight to the breakthrough. Launch your next big thing at Base 44 dot. Com.
That's base four.com after base 44 helps you launch Corgi, helps you cover
what comes next. My word, what An arresting first line. Get your ass covered
with Corgi Insurance and I'll tell you why.

If you are running a business right now, you already know this. Pain all too well
getting insurance. It's really slow. It's confusing. And my word, it's full of
paperwork. Well, that's exactly why Corgi is here to change the game. Corgi is
the first and only insurance carrier designed specifically for tech companies,
allowing you to get covered in minutes instead of days.

Corgi provides essential coverages for all growth stages such as d and o, e, and
O, liability, cyber, commercial, general liability, and more. [00:02:00] Get your
ass covered. I love the way we say asks. With Corgi Insurance alongside
thousands of other startups@corgi.com slash two zero VC today. That's
corgi.com/two zero vc.

You won't regret it while Corgi handles the coverage. Turing handles. The
talent. Frontier Labs keep facing the same limitation. Models perform well on
benchmarks, but they fall short once they enter real coding tasks, real tools and
real workflows. That disconnect between synthetic evaluation and actual system
behavior is now a core block off for Argentic models.

That's why Nvidia and. Philanthropic, Salesforce, Gemini and other leading lab
partners partner with Turing. Turing is the research accelerator focused on post-
training reliability. They build realistic RL environments. Next generation data
quality systems built from real world operational traces and coding data sets that
stress models under conditions where failures matter, state changes workflow.

Branching brittle tool calls and the coding errors that break [00:03:00] RL
agents, but never appear in benchmark reports. In reality, a model may
demonstrate correct reasoning in your evaluation setup, yet still select the wrong
parameter or mishandle a code update in a realistic interface, curing makes that
failure visible and gives teams the signal they need to fix it.

For labs, advancing AG agentic systems, Turing provides the structure required
to understand why these failures occur. To find out how. Visit turing.com/two
zero vc. That's T-U-R-I-N g.com/two zero vc. You have now arrived at your
destination.

And I am so looking forward to this. Dude, I have stalked the shit out of you for
the last three or four days. I spoke to Bing Gordon. I had a catch up with Bing
before this. Very nice to speak to him. so thank you so much for joining me.
Stay,

Thanks. Thanks for having me. It's too long. It only took us, what, eight years?
Nine years? I forget when it was.

I was 12 when we last did it. Yeah. Yeah,

Well, 12 in startup land is 25. Right?

dude, [00:04:00] I'm confused. Help me out. I had Demis on the show the other
day from DeepMind. He was like, nah, I'm not sure if we're seeing scaling laws,
but we are definitely seeing slightly diminishing like return slash performance
as we scale. So potentially

are we getting to a stage where increased compute is no longer leading to
increased performance?

Oh no, absolutely not. that's not true at all. in certain domains that are well
explored, like coding for example, yes, there's an increasing amount of compute
required to get an incremental gain in some eval that's super saturated. But if
you set an What about material science? You know, I'm sitting here at Periodic
Lab's office.

This is my latest incubation is called Periodic Labs. I spent three days a week
here in Mendel Park. We have a 30,000 square foot facility where we have
LLMs that then predict new materials, new superconductors. We then have
robots synthesize those new materials. And then we have, physical machines
like x-ray diffraction machines, validate whether those materials have the
properties that were predicted by the lms.

And then we pipe that verification data back into our training run. You
[00:05:00] know, how many ever times we. And I can tell you, throwing more
compute at the problem is probably having, yeah, super exponential gains right
now per iteration. So it depends on which domain you're talking about, which
modality.

There's no saturation in superconductor discovery, for example, at all. The bitter
lesson is holding is well in alive,

 when we look at the bottlenecks around performance and progression today,
What are the bottlenecks that really persist most significantly to you? Is it, is it
algorithms? Is it data?

Is it compute? Can you help me understand which is most lagging?

so there's four or five. It's context feedback, which I'm happy to talk about. It's
compute. There's capital which you need to like continuously sort of deploy the
compute and context feedback loops. And then there's culture. And I think that
culture actually might be the most important bottleneck of all time.

But those are the four I would say. Now, look, algorithmic innovation, I think is
a function of culture, basically.

because if you have the right culture, you get to attract the best researchers, the
best researchers, the best research talent then [00:06:00] wants to work on
pushing the frontier. And algorithmic innovation just falls out of having a really
good team that's very flexible on what kind of architecture they want to use.

if you have the right culture, the algorithmic innovation bottleneck solves itself
because then the, the researchers are not focused or like tied to one architecture
versus another. They're not going, I'm all in on LMS or transformers versus
diffusion models.

The best scientists and researchers just wanna solve the problem, the mission.
And if you have a very mission driven culture where they're like, we want to
move the frontier. Coding or the frontier of material science, the algorithmic
stuff takes care of itself. that's actually not the bottleneck anymore in my view.

Two, three years ago, that was a huge bottleneck where we were trying to figure
out which algorithm scale are there some limits to the transformer architecture
versus diffusion models? And what I've come to realize is if you solve the
culture problem, you can solve the research and the algorithmic problem.

Then the bottlenecks of context feedback, which is what is the data you need to
keep doing frontier research over and over again is step number one. Because
actually I think that is also where you have the most business and [00:07:00]
commercial advantage. there's lots of alpha and value to be gained in pre-
training, mid training and so on.

But you know, that last mile where you, you deploy a model or an agent in
some new domain and then you collect feedback on how it's performing in real
time. And then you, like I was saying here, we do physical verification of
material science at periodic, wherever there are some unique context feedback
loops that are missing today.

That's where you probably have the biggest bottlenecks on capabilities. And so
what you should be doing if you're trying to advance the frontiers, is going,
okay, you know, these models suck. For example, about a year ago as an
example, I realized there was a lot of talk about models being good at physics
and chemistry, AI for science.

And I was a visiting scientist at the applied physics department at Stanford and
we started benchmarking these models Claude Geminis and so on. And surprise,
they sucked. They were so bad. there's this disconnect between the marketing
hype of AI for science and the reality where these models are terrible at the time
at least They were starting to get good at code, but they were terrible at
scientific analysis. you know, the [00:08:00] conclusion was pretty simple.
They were just missing a lot of the, the physics and chemistry data you need to
reason about the physical world. But to do that, we don't have enough of that
data on the internet.
' cause the internet is mostly pre-trained data about, because things like blogs
and blah blah, blah and coding. But if you need physics and science, that's a real
bottleneck. 'cause that data is, is locked up in national labs and academic labs.
It's locked up in physical, semiconductor manufacturing plants.

How do you get that data? And that was the bottleneck I realized was really the,
the critical part of getting these models to reason about the physics and science
frontier, which is something I care about deeply. And so the way we solved that
at periodic was, you know, set up a physical lab with robots doing all that.

you could apply that same recipe to whatever domain where you wanna see
more and more progress. Then you ask, okay, how much compute and
infrastructure do you need? To keep that RL loop or the physical verification
loop scaling at bigger and bigger scale. And then you need the capital to fund all
this.

You need equity debt, a whole bunch of different structured finance vehicles to
get, you know, land power shell. So that's the [00:09:00] compute bottleneck.
And then lastly is the culture. 'cause if you have all of those three things, but
you don't have the right team and the right mission driven culture, the whole
thing falls apart.

 And, and so those in my mind are the four bottlenecks. I wake up, you know,
every day trying to figure out how we, we unblock for the best teams.

If we just go through them, when we look at that context feedback on the data
side, what we

see then a generation of vertically integrated foundation

Yes,

light periodic for a

yes.

things.

Yeah.You know, when I went to grad school, for machine learning, I, I, I went
to Stanford for bioinformatics, which was for machine learning applied to
healthcare. the space was not as good as marketing as it is today.
So, super intelligence, love it. at the end of the day, what are we talking about?
We're talking about very powerful models within some domain. and we are
seeing within distribution, very, very powerful capabilities that are, you can
definitely call 'em superhuman. 'cause there's no way, for example, I as a, in an
individual scientist, could analyze the reams and reams of data coming out of
the lab here.

Without AI models, there's just no chance. And so the fact that you can take all
of the data from, you know, training from a lab, a physical [00:10:00] lab, and
just throw it at a bunch of AI models and ask it to analyze things, is a
superhuman capability. We didn't have that before. Okay, fine. So let's call that
super intelligence.

Within coding, within material science, within each of these domain
distributions, we are seeing. Capabilities that are superhuman. We didn't have
them before. and in fact I would say we are even starting to see automation of
those tasks, especially where there's, there's coding involved starting to be
somewhat recursive, right?

Where if you have a good coding model, then you can say, okay, let me
automate like data analysis, let me automate like data cleaning and so on. Some
people would call that recursive self-improvement. Totally happening. But it's
not like I can just say to a coding model, please bootstrap a, a physical r and d
lab for me in Menlo Park.

Get all the permitting. go find orange to raise money from, go set up the
physical infrastructure and just like bootstrap all this data that's just an entirely
different kind of frontier and execution and sort of problem,

 my question to you then is like, how do I determine what is not going
[00:11:00] to get C Cloudified in that vertical model company build out?
Because

yeah,

at a cursor and say, well, they've built their own vertical model end to end,

it's been c cloudified. If we're being blunt, periodic won't be because of the
physical data that's being produced in the

right.
do I know what will be c cloudified versus won't in that model there?

Yeah. This is a good question.

okay, if we want to sort of unlock frontier progress generally across a bunch of
domains, then where are the bottlenecks and where will the value accrue,

 context is, is not necessarily the moat. I would not say yet. I think venture
capitalists are very quick to analyze moats, but I would say context feedback
loops where you have, you have unique and differentiated access is where
progress will be most legible to you.

And if there are other teams who don't have access to that context, it'll also be
where you have a superior business model. And so here's an example I give in
the class, right? Sovereign data. Are you familiar with the Cloud Act?

Yeah. Okay. the US Cloud [00:12:00] Act says that, hey, if there's any data,
workloads, cloud workloads running on infrastructure that is managed by an
American company, then the US government has to be able to access that data.

Now, if you happen to be running military defense mission critical workloads in
Europe on AI infrastructure that is managed by an American company, well that
context, which is super critical, can't be sent over across the border. That's an
example of a unique and sensitive context that needs to be run locally.

And so if you are a SML, your C-M-A-C-G-M that's doing logistics at scale and
some of this logistics is with mission critical supplies. You can't have your
supply chain data being processed by an AI bot that's running on servers that is
subject to the Cloud Act. So what do you do? You look for local infrastructure
partners.

You start going, Hey, who are the providers, AI infrastructure providers in
Europe that we trust? Well, it turns out there aren't that many who can actually
handle mission critical infrastructure at scale for ai. you call up someone called
Arthur Mech, who is a French [00:13:00] scientist from DeepMind turned
entrepreneur and starts a lab called Misra who is running massive workloads.

And you say, Arthur, would you actually build infrastructure that can be secure
locally? And that's why suddenly in July of at the, at Veeva Tech in Paris, you
have President Macron and Jensen standing on stage next to Arthur, a 33-year-
old scientist unveiling a gigawatt AI infrastructure facility in Paris.
Why? Because the context, the mission critical context of those workloads is so
important to be run locally that you can't run them on a Amazon A-W-S-G-C-P
or Azure. And it's the first time in 15 years that the sort hyperscaler dominance
is, um, up for grabs for startups

With the greatest of respect, is that the core investment thesis of Misra you?

for me. Yeah.

Independence at scale, at every part of the AI infrastructure stack, like land
power shell in Europe, that's sovereign, it's local compute infrastructure that's
local. And [00:14:00] models that are trained locally, by the way, fully open so
they can be deployed and customized globally, wherever needed.

But certainly in Europe, like the full independent stack is the, is the bet. Yeah.

Do anthropic and open ai, just accept that and roll over. I, I don't understand.
'cause government is a mega portion of their efforts and workload today.

I,

of them when I speak to them are like, oh, we are absolutely coming for Europe.
so how do they get

around that?

well I can't speak for OpenAI too much, cause I'm not involved there directly.
But Anthropic, I will say, you know, the mission and vision has always been
very, I think it's always been very American aligned, right? They've always
said, Hey, America is the crown jewel of the world in terms of innovation.

this is where we're located. Again, philanthropic is located in Silicon Valley.
and I think the company really, really wants to do what's best for the American
government and the American way of life, which is democracy and freedom.
Now, it turns out the world's largest enterprise customers are governments and
Fortune 500 companies, and many of those that are overseas need these
workloads to be running locally.

You [00:15:00] said

I,
obviously being involved with philanthropic since the earliest of days. I'm just
fascinated. I think people kind of about their early days almost.

People talk about like, oh SBF investing early and what a visionary he was,

what was philanthropic and Dario like in the early days,

well, so I've known Tom forever. Tom, you know, was one of the, the lead
authors on g PT three. we'd been friends for many years. And so Tom gave me a
call and said, Anj, for various reasons, we wanna leave and start this new lab
called philanthropic. We're gonna need, a lot of capital, we're gonna need
compute. I had already sold Ubiquiti six at that point, so I'd kind of gone
through the founder journey.

and so Dio, Tom and I started doing these weekly sessions in early 2021 to try
to figure out how to. Turn what was really a research hypothesis, right, which is
scale the scaling recipe into a business hypothesis. and look, I would say it, it
took like really 12 to 24 months. and they did a lot of the hard work on figuring
out how do we really sort of operationalize this.

The idea of this AI pair programmer, Where you take the context feedback loop
of the local repository, the files, the [00:16:00] directories of programming and
sort of in a, in a very methodical way, make predictable progress on the
capabilities of software engineering. if anything, my biggest flaw as an investor,
as a founder is being too early to things that was my lesson with ubiquity six.

I was early to the whole computer vision. Which is now, you know, obviously
blowing up the whole multimodal sort of generative modeling space. and since
then I have, I think, updated my strategy on how to get timing right. But at the
time, the recipe was pretty simple, right? raise some money, buy some compute,
get a little bit of context data on programming, put out a basic version of the
model, deploy it with teams that we trust who are doing coding, and then pipe
that feedback loop back into the training, run over and over again.

And when you do that with inference, inference gives you sort of two things, It
gives you revenue to buy more compute, and it gives you the context feedback
to keep improving the capabilities curve. And I was like, great, this makes total
sense guys. Let's go raise money.

 I invested a bunch of my money, that was just life savings, which was not much
given. I was a poor founder at the time, which where most of my net worth was
tied up in [00:17:00] Discord stock.
and, and, and it pains me sometimes to, to look back at the emails of friends.

So I introduced them to 22, you know, friends up and down Sandhill Road,So
there's some investors there, and we got 21 nos, And I was like, what, what are
you guys thinking? And they said, well, the orange, this, this, this recipe sounds
good in theory, but like, where's the proof?

And I said, proof. The, these are the guys who invented GPT-3. How much
more proof do you want? And they said, what's g PT three? I say, oh my God.
Like, how do you go about educating somebody who doesn't even understand
the technology and the breakthroughs that are happening in the machine
learning community?

Now, I was lucky 'cause I, I had that training from grad school. I'd started a
computer vision company. So something that was super legible to me just was a
completely different world. And then. For those investors. We were pitching,
remember we, we originally tried to go out and raise 500 million and then had
to reor only raising a hundred million dollars seed round, which at the time felt
like a lot, but of course was tiny compared to how much OpenAI had raised.

'cause by then, I think OpenAI already raised a billion dollars. And so the whole
idea of compute multipliers were, we could, for every dollar of venture
[00:18:00] capital raised, produce a unit intelligence for six times less, like the
VCs did not understand it, which is why, you know, over the next 24 months,
the people who got it were either people like, you know, some of the folks in the
ML community who also had an overlap with the effective altruist community
like SPF, but also Amazon, right?

This was very legible to Amazon because they were watching what was
happening with Azure and OpenAI and they were like, well, this is super
aligned. If you guys actually can create a bunch of state-of-the-art models that
are hosted on Amazon, that's super accretive To the AWS business. And that's
why, you know, it resulted in, this sort of, deep compute and capital E for equity
partnership with Amazon that was originally $4 billion.

You know, a lot of this is public now, but at the time it was, it was a really
tough journey. And I would give Dario Tom the other co-founders, you know,
Daniella, Jack, Sam McCandless, Jared Kaplan. it was such a brutal time getting
this company going. Like,

anything you would've advised him differently? Knowing all that you know
now?
 I'm not sure I would [00:19:00] because the world is a very different place
today, you know? And at the time,

it really did feel like there was no one they could trust.

is it not impossible not to be holed up in front of Congress. If you reach a
certain scale,

totally.

are Google, or whether you are Facebook, or whether you are anthropic fighting
against the Pentagon,

Oh, it's,

a scale where it is impossible not to have that conflict.

 No, what are you talking about? look, I started AMP as a public benefit
corporation.

'cause I, I think it's actually a very aligned model. Have you heard of REI?
Right. REI is a public benefit corporation. They make billions of dollars in
revenue and profit. Have they ever been hauled up in front of Congress? No.
Like Ben and Jerry's Public Benefit Corporation, have they been, hauled up in
front of Congress?

No. It's because they self moderated right at a time and they said, here's our
mission. we have to build a business. those things are not in conflict long term.
If your goal in life is long term to push humanity forward in some stable,
reliable way, there are always tensions where you have your mission and then
you have your profit motive and you've gotta be able to, to like [00:20:00]
moderate between those two.

I think public benefit governance allows you to do that. And I think we need
more public benefit charters in Silicon Valley and, and technology and I think
we will get there if you look at the arc of infrastructure businesses, for example.
Right.

I, I, I actually, I actually had a chat with a mutual friend of ours who asked not
to be revealed.
Okay.

and they said, for fuck's sake, all these pbcs public benefit corporations, will
these startup founders not just fucking win their market first?

I mean, how are they feeling? Are they investors in anthropic?

No.

Okay, so tell 'em to gimme a call when they'd like to be investors in the world's
fastest growing business of all time. And then they can lecture me about public
gov benefit governance and market share adoption.

Public benefit governance gives the leadership the ability to make decisions that
sometimes are not legible to shareholders as best for them

what decision can you foresee with AMP

is aligned to your mission does not put the profit motive slash incentive first?

There are [00:21:00] many up and down the stack. 'cause we see ourselves as a
full stack scaling partner to the best frontier technology teams. And we also
kind of see ourselves a little bit as how our job is to propose independent
standards for AI as an institution try to, evangelize the adoption of those
standards through profit generating businesses.

We have a venture capital business, we also have an infrastructure business.

the FA good example of this for now is we're actually giving away most of our
compute at cost. Now if you're a shareholder, you'd go. Wait on, do you have
billions of dollars of compute infrastructure you're giving away at cost?

Yes. Because we think that's the right thing for humanity, and we think that's
the right way long term to have a healthy, independent ecosystem, which is
what our mission is. Our mission says AMP is a public benefit holdings
company. our vision is, is to ensure there's a healthy, independent frontier
technology ecosystem.

Our mission is to maximize the world's frontier output. To do that long term, the
teams that are truly doing innovation, pushing the frontier of science and
engineering need ac compute access. And many of those teams today can't
afford to in extraordinary prices for [00:22:00] compute infrastructure today.

And so, you know what, yeah. We're happy to provide them access of that in a
way that's mission aligned.

Ange, how do you secure the compute supply? Maybe I should know this, but
it's the most starved resource today. How

Right.

a resource that no one else can seemingly secure?

Well, step one is you get there first before people realize how, how valuable it
is. I've been, beating the, the drumbeat on this for four years now. when I got to
a 16 Z as a general partner, the first thing I did is I sat down with Mark and Ben
and said, we need more compute.

We need compute access for these incubations I'm gonna do. And they said, no
problem, Anj. Let's set up a program. What do you need? So we used, our
balance sheet to start procuring compute through the oxygen program. That
gave me the ability to build pretty deep relationships with the industry and build
trust with compute partners who now we have lots and lots of relationships with
that we're scaling, in ways that would be very hard if I didn't have that time.

And the. flexibility to understand that what is required to really get that
infrastructure right. You know, we've talked a [00:23:00] little bit publicly
about what we're building, which is the amp grid, which is essentially a, what
the electricity grid did for electricity. We're trying to do for compute
infrastructure.

We see ourselves as an independent system operator of the grid. We, we're not a
cloud provider. We don't own our own data centers. we're not a traditional
venture capital firm either. We see ourselves as an independent system operator,
which means our job is to coordinate capacity across the ecosystem in a way
that allows the best teams, the in best independent teams to provision for their
base load, not their peak.

So they don't have to over provision, but when they want to be able to spike up
and down for training runs for inference needs, they feel secure that the capacity
exists. We are roughly in 1885 industrial, revolution England right now, where
you have all, you know, these, these Frontier labs are like factories that the
STEAM engine has been discovered.

You can use STEAM to produce all kinds of new products. And many of them
are running their own generators in their backyards at half capacity. this makes
no sense. Let's all pool our generators so that a shoe factory can spike up during
the day. A steel factory can spike up during the night and then you maximize
utilization, and ultimately [00:24:00] output.

Yeah.

think about allocating it, are you not using compute and the cost of compute as a
loss leader for your venture fund business, which then comes in and says, okay,
you name any of your incredible businesses that your own, whether it's your
Philanthropics or your Misal or your but for slabs, and say, okay, you'll get the
compute at cost, but for that we need $300 million invested, and that's your way

that's, that's, that's not at all how we make the that's not the deal. the deal is I
incubate new companies like Periodic Labs one at a time. I can only do this one
at a time. 'cause I, I, I like to team up with scientists or engineers who are at the
forefront of their field.

It takes a lot of work to create these new companies from scratch. in many ways
I had the privilege to, to realize that we are entering a back to the future era of
venture capital. If, if you think about. The birth of modern industries. let's talk
about semiconductors. gene editing, you know, the biotech industry or uh, self-
driving cars, Silicon Valley, in the early days [00:25:00] of the founding of
what I call these frontier industries, the way you start the most iconic companies
is very different from how fund companies were funded for the last 10 years in
the Zer era.

Intel, for example, right, was a very close partnership between a couple of
scientists and a investor called Arthur Rock, who was a founding investor and
was at the office every day. Arthur literally used to, Arthur wrote this stock
incentive plan. He used to run all hands at the company every week. If you look
at Genentech, which was incubated in the basement of Kleiner, it was co-
founders were Herb Boyer, professor at UCSF and Bob Swanson, who was an
associate at Kleiner.

And I, I got apprentice in that mode of venture capital. 'cause when I got to
Kleiner, you know, I was 20. wrapping up grad school at, at Stanford Med
School, but I was working nights and weekends, at Kleiner on the investing
team. And Brooke Byers, who was the KPCB, and B had an office next to me
and he had some free time.

So I would go to him and be like, Brooke, you know, teach me your ways. And
he regaled me with all the stories of how Genentech was being founded. And I
was like, wait, so you're saying basically Bob, like co-founded Genentech here
in the basement at Kleiner? And he was like, yeah, that's what it meant to be a
[00:26:00] partner.

And I said, we, well, that's not what happens here anymore. Like we write a
bunch of checks to SaaS companies and then they go off and do stuff. And he
was like, different times.

are they mutually exclusive? can you have a venture ecosystem where you have
a bunch of people writing a bunch of checks as we have done for the last 10
years, and a next generation, or to your point, are back to the future era of
venture capital where you co-found the business side by side.

right,

yeah.

or are we actually entering an era where we are back to the future era, as you
say, where value accrual is in the co-founding and incubation side,

I think it's very hard for them to coexist inside of one person, and it's very hard
to coexist sometimes inside of even one firm, because

you know, there's the reason I'm sitting here at Periodic Labs. I work here three
days a week, every day from 8:00 AM to 8:30 AM for the last year. Liam Doge
and I have had a standup every morning where we go through the priorities of
the company we make them, we prioritize, we go and execute.

I mean, the compute team at of AMP is sitting upstairs, procuring, compute for,
for the periodic guys.

my role models have always been the Arthur [00:27:00] Rocks and the Bob
Swansons, and the Mike Marla, personal computing

Actually, effectively the first CEO for the first year of Apple was Mike Markle.
He was an angel investor and he was the one doing all the CapEx, you know,
supply chain and capital and all of that stuff that allowed Steve and and Wa jobs
and was to focus on the product and the engineering and that kind of deep
partnership is what I get really excited about.

Can I get back to something you said before, which is like, we're at the
Industrial Revolution stage, and I was like, okay, help me understand that. If
we're at the Industrial Revolution stage, what does that mean for where we're
going and how I should be acting as an investor today?

you have to hold two things in conflict that can seem paradoxical. this is the
most important thing I learned from Mark and Ben, future is not, is not
determined.

And so anyone who tells you that they can predict the future with certainty
should be taken with a healthy dose of, suspicion. and instead, I, I try to
approach things like a scientist and go, what are the biggest bottlenecks? Let's
come up with a hypothesis on how these bottlenecks will be solved.

And let, let's. Run multiple experiments in parallel and then whichever one
emerges. You just have to be very [00:28:00] truth seeking and, and be willing
to claim like, say you're wrong. I would say as an investor, your job is to come
up with a hypothesis for where the future is going. And be willing to, to make
multiple different experiments that are aligned with your mission in parallel and
be willing to be wrong and be honest with your LPs that some of them may be
wrong, honest with your teammates.

to a Brian Singerman of the world who always said that? I'm not smart enough
to predict the future, but I, my job is to pick founders that are able to do so.

I think that the most, the safest way to predict the future is to invent it, So do the
hard work. Come up with your point of view on if we're an industrial revolution,
England, what happened next? And what were the emerging properties of the
businesses that became valuable in institutions over the next 50 years, after
1885?

And then figure out which figure from history of that era. do you look up to the
most you know, go read about their lives and the businesses they ran and the,
and the tensions that emerged in the practice of their business later in life. 'cause
then they made mistakes when they were young and try to learn from their
mistakes and then go and execute,

What's a [00:29:00] parallel property direction from 1885 onwards style,
timeframe that you think will play out in the next era?
well obviously in the world of infrastructure, I think we need something like the
grid for, in the compute infrastructure. So that's what I've spent most of my days
on, which is a coordinating mechanism that allowed not the commoditization
necessarily, but the transition of, coal and electricity from being these resources
that were being hoarded to being stable, reliable, uh, commodities that, the best
engineering teams, the best factories had access to.

that's what I think about a lot. since, since you are so talented at media and
you're so talented at storytelling, I think I would, and, and your mission is to
push the European continent. I think one of the things if I was you, is I would be
talk, trying to figure out how do we educate the leading capital allocators and
infrastructure allocators in Europe about the coming era, and get them to
understand their role in unblocking the bottlenecks for the best scientists and
engineers in Europe.

it's, uh, largely a lack of pension fund [00:30:00] reform in a lot of cases, to be

Okay, so spend your time on pension fund reform.

How much more cash do we need in Europe for Frontier AI to be what we think
it can be? Is it like two x? Is it 10 x?

That's a good question. I, I would try to go about it from a top downs approach
and bottoms up sizing approach. you know, for us at amp, when I look at the
grid, we are building out, which is sort of a reasoning by analogy. we have
started securing about 1.3 gigawatts of compute infrastructure. That's roughly
$40 billion of cloud spend over the next four years.

And that is financed roughly, with about 20% of equity. The remaining is debt,
20%, that's about $10 billion of equity capital. The remaining is all debt capital.
We have a bunch of partners that help us put together these equity and debt
packages to secure compute infrastructure for our companies.

I would say in Europe. if you're doing sort of your atomic unit of math in
gigawatts, I would, from a top down perspective, you know, I think Google is
roughly at [00:31:00] 12 to 15 gigawatts of, that I'm aware, aware of, of, of
infrastructure for internal and external deployed needs.

Now they have a huge land power shell pipeline coming, but if Europe does not
have access to Google level infrastructure, then what are you guys even doing,
Like that's roughly what the continent needs for full sovereignty, right? To have
as at least as much infrastructure locally as there is within the alphabet holdings
pool over the next four years.

Is the, what's easier, the equity raise or the debt raise?

I would say the biggest challenge has been figuring out the right aligned
financial structure across both in a way that's legible to capital. Allocators at
scale. Took me about a year to really cut all the pieces, right? But there are very
large equity pools. lemme put it this way. There are a lot of balance sheets,
long-term mission line balance sheets in the world who are mission aligned at
wanting to help frontier scientists reach researchers.

University labs get access to the compute they want, but they don't have oper,
they don't have opex, they don't have cash to spend on the compute. So if you
can find a way to align [00:32:00] equity. debt balance sheets in a way that's de-
risked. The fundraising is not a problem. It's, it's actually a systems design
problem, which it took me again a year, it probably took me four years to get
right.

But now that we've figured it out, it's, it's not been a problem.

Do you think we are under invested still today in data centers?

We are deeply under invested in security. In secure compute. okay, lemme put
this, we are not in an AI crisis. We're not in an AI bubble for sure. I'll tell you
that. We are definitely in a GPU wastage bubble where there are stranded
pockets of compute, like billions of dollars of compute that are sitting
unutilized.

And if we could pull them together on a grid across the independent ecosystem.

are they unutilized? Sorry.

For a couple of different reasons. one is their compute is not fungible. So unlike
electricity, which had to go through a process of standardization, you know, AC
CDC where megawatts or megawatts or megawatts, computer is not fungible
today.

So for, forget fungibility of compute across different manufacturers like Nvidia
and a MD [00:33:00] within a manufacturer. Nvidia chips, for example, H one
hundreds, the GB two hundreds, the GB three hundreds, these are all completely
different chip types. So if you have one cluster where you're doing a training
run on H one hundreds, and then you wanna do continued post training of that
do a distributed training run of that, training, workload on GB two hundreds
doesn't work.

So they, they're just like stranded pools of compute. 'cause the atomic unit of
computation is flops. I wish flops were fungible, but not all flops are born equal
today. If you provisioned a cluster two, three years ago with H one hundreds,
and now you actually wanna run some of those workloads for, for the newer
generation models, you're memory bound by H 100 chips.

You can't unlock, the benefits of the Blackwell chip without basically just like
buying a new cluster. And so now suddenly you have this H 100 cluster that you
don't wanna do training on anymore because it's old school. It doesn't like the
chip doesn't have the right memory properties to train your frontier models.

and it's very hard for any individual company to ha like, see all of this stuff. But
when you're on seven or eight boards like I am, and you've been doing this, you
know, [00:34:00] 15 years and you start to see patterns emerge, you're going,
wait a minute, why is there all this unutilized compute sitting here and there?

This is ose for everybody.

frontier models moving faster than the pace of, chips, as you said there with H
one hundreds, where you, you have newer, newer models and then you're
training them on older and older chips 'cause that's what's free it's not moving in
lockstep. is that the problem that we're articulating?

No, no, no. The problem we're articulating is that compute is not fungible.
There are no standards for fungibility, and there are no institutions enforcing
standardization of compute enough. So we are in the pre standardization era of
compute today, which was the pre standardization era of electricity in 1885.

I hope we can self-regulate, self standardize, and self, enforce standardization so
that we can skip the boom and bust cycles that happened with electricity over
the next 50 years. And this happens with every infrastructure cycle in the pre
standardization era. It happened with electricity in 1885.

It happened with steel, it happened with railroads. And every time you have this
boom and bust cycle, what happens [00:35:00] is wars are fought. Companies
back stab each other. It's super painful, it's annoying.
We are in that era And my view is that compute not being fungible is what's
resulting in the all this talk about ai. The AI bubble. But what people forget is
that we, we don't have a AI capabilities bubble.

The, the capabilities are extraordinary in every domain. We have an infra
infrastructure wastage crisis right now, and it's because there are no open
standards, there's no open protocol for how flops from one, data center can flow
to somebody else who needs it across chip types, across secure boundaries.

And, uh, it's resulting in a lot of pain for the ecosystem. People are just,

If we have compute

stupid.

in the way that you said, will we

Yeah.

the boom and bust cycle or is that just one part of it?

I think that will go a long way in preventing this and instead just allowing this,
Yeah.

sorry for asking. So you are like cheeses. Christ, Harry. I'm a professor at
Stanford and you bo waste my time with this, which is a fair statement. what is
the biggest bottleneck or barrier to compute standardization [00:36:00] that you
want to achieve?

it all goes back to alignment, man, misaligned incentives up and down the stack.

How is Silicon Valley and DC not on the same alignment?

for one, I don't think we have standardized on whether AI should be regulated,
treated, procured as just as good old fashioned software or like a new kind of
system.

You know, like I, again, I went to grad school for machine learning, and what
you learn in machine learning 1 0 1 is models are statistical. They're not
deterministic, right? So when you have a statistical system, there are some
properties of a statistical system that are different from a spreadsheet.
A spreadsheet is deterministic software and a statistical model today is not.

And so should the procurement of a spreadsheet be the same from an IT
perspective as a statistical model, open debate, that is the core debate.

That's the problem. AI alignment, don't get me wrong, is hard, but not the
hardest problem. Human misalignment. Human alignment is real, is really the
problem right now we have in in the world.

we need technologists who [00:37:00] understand the difference between
deterministic software and statistical systems to propose a set of standards for
how procurement for this should work. And then we need standards.

People in DC we have this thing called nist. We have various bodies in the
government that should get together and say, thank you guys for proposing this
standard. This is where it makes sense. This is where it doesn't, this is called an
RFC process and we're gonna standardize on this definition of procurement.

This is what happened with T-C-P-I-P, with the internet. It happened with A
CDC and electricity. We have not done that yet for the model era. these are
called open standards. The standardization process is being confused with
marketing Now. President Trump is actually, I think, trying to do his best, from
what I can tell in at least giving America enough freedom to innovate that these
standards can even be discovered in our labs here.

' cause first you need somebody to actually pioneer and figure out what the
standards even should look like. I think that there's just a lot of noise.

Do you worry that basically the CCP is subsidizing a generation of Chinese
models that are now being used by [00:38:00] American companies whereby
they have frontier models to essentially set where model capabilities can be and
then have a real effort to make the open source Chinese models as close to those
benchmarks as possible?

Yeah.

cheaper.

I mean, the engineering execution right now up and down the stack in China is
extra. Here's what's happening, right? What they realized is that the AI scaling
race is not a chip race. It's a full stack systems co-design race. Where if you
can't compete head to head on chips for now, what do you do?
You compete on systems design. You say, okay, we don't have leading edge
chips here right yet, so let's try to compete on systems, you co-design. The chip
that you have might be Huawei with the compute infrastructure, with the
training run. And then you design that to have a bunch of performance
improvements at every layer of the stack.

And then what you do is you do adversarial distillation at scale, where you take
western models and then you, from various different endpoints, you distill the
state of the art, and then you try to get as many [00:39:00] performance gains as
possible on that data. And then you release that back out to the world as open
models, and then you see what people react to, and then you get feedback, and
then you do the next run and the next run.

And then you catch up. And at the point you catch up, you say, wait a minute,
we're starting to be at the frontier. Why do we need to open source anymore?
This is good enough for our local domestic needs. It's beautiful. It's actually,
and, and, and that has actually, by the way, resulted in innovation. They're,
they're innovating in every step part of the cycle.

And that's why Huawei chips are able to produce capabilities improvements
today in China. That rival some of the best chips here when, when integrated up
and down the stack. In a sense, it's the Google strategy, right? Google is
integrated land power. Shell, TPUs, Borg X Borg, GQM, Gemini. Then the
deployment, I mean the systems co-design there up and down results in
efficiency, that gives you huge performance gains.

At the end of the day, China has replicated that strategy using open source as
sort of a bootstrapping mechanism to catch up. It's, it's extraordinary.

does that concern you?

[00:40:00] Uh, are are you kidding? Absolutely. That's why I think what we
need is a Western grid. where all inference, frontier Inference is served through
an Iron Dome, where if there's any adversarial distillation attacks on any one of
our teams, we coordinate together. So, because I'm on seven boards, I'm in
group chats where I get texted by one founder saying, and is anyone else
noticing today that there's a huge spike in distillation on. From this region, and
then I put them in a group chat.

We coordinate, it's very informal right now, yeah, go ahead.
that state sponsored attacks on Frontier AI labs are getting worse. What do we
not know that we should know?

we should know that there are insider threats. We should know that there's
distillation happening across the US and Europe that is taking advantage of our
of us all not being united. that distillation is, is taking advantage of our political
systems that, our mission critical infrastructure is, is quite vulnerable, especially
data centers that are serving, workloads that are being used by enterprises.

from a business standpoint, if we don't secure [00:41:00] frontier model
inference. Or what I would call state-of-the-art inference behind a coordinated
iron dome. We, I don't think we have a sustainable shot at, staying at the frontier
over the next decade.

I am sorry. What does that mean? An iron dome for inference in terms of
sustaining it,

It means that all inference is served, no matter which company is serving, it is
served through a shared proxy that can I tell each other when there's an attack
happening on one part of the frontier, think of it as an iron dome across the
entire Western front, And just 'cause you're here, you're in one company, you
can't see that your model being served through this other company is being
distilled.

So it's a, it's a deployment coordination protocol. it's basically my group chat
that I've got with like, you know, a bunch of different founders but scales where
people go, we are seeing this attack today, and others go, we are too. Let's
coordinate on defensive response.

I am sorry for my lack of cohesion on question. Really. I feel guilty and I don't
blame you for leaving this interview thinking, God, he's got worse over the
eight years. Not better. But I was watching this interview speaking of inference
[00:42:00] with someone I think from Base 10, and he was saying that the
demand for inference has grown, not linearly, but combinatorially, that is how
we would see it progress over the next three to five years. Do you agree with
that?

If we keep scaling capabilities, that will definitely happen. The problem is there
are a couple of bottlenecks on scaling capabilities that are quite existential. the
four core bottlenecks on the capabilities progress we've talked about, right? It's
context, compute, capital and culture.
And I think capital allocation, huge problem. We gotta educate people on why
this is, why these capabilities are extraordinary like it. This is, this is like the
biggest financial bonanza of all time. If you know where to allocate, I mean,
there's a reason why. I invest in philanthropic, in the seed round.

And now as you pointed out, like the returns of all the, the body of work I've
done over the last four years are attracting LPs at the highest levels, but we're
just getting started. I, I think some of these projections you see are correct if we
unblock the bottlenecks along the way.

The compute and in compute infrastructure, secure compute infrastructure,
that's fungible, that's standardized. [00:43:00] That's the biggest bottleneck. I
think if there's any reason why OpenAI, Andro, Gemini, and so on don't hit their
revenue targets over the next few years, it's because they won't have access to
enough compute.

there's like a related bottleneck, which is that, just think there's,

when I was at Stanford many years ago as a kid, I, I took this class that Peter
taught called, uh. turned into this book called Zero to One. This is Peter Thiel. I
used to be, I was an editor for the Stanford Review and he had this, quote, right,
which is competition is for losers.

you know, having done this now for 15 years, I've kind of updated my theory of
business and I think he was, he was not wrong, but he was insufficiently
precise, which is that I think perfect competition is for losers. I also think
monopolistic compete.

what does that mean? Perfect competitions for

It means that if you have 10 different, like 50 companies all doing LLM training
or doing coding models, that's, that's a losing proposition.

It's, it is like, you know, perfect competition is like restaurants.

There's no defensibility. That's why restaurants go outta business all the time.
It's very hard for them to differentiate. On the other hand, monopolies are
mafias if once you have a monopoly at one part of the [00:44:00] stack, they
stop innovating and instead they try to go or down by using their balance sheet
to acquire.
They start hoarding resources, they start saying, you give me this and I will
force you to basically subsume yourself to me. And I'm seeing that kind of
behavior up and down the stack. And mafias are not good for innovation. I, I
think we're in an era of op. What we need is optimal competition. The optimal
competition set up is you have three or four teams in every frontier that are
making extraordinary progress.

And so if you invest in them, you get extraordinary returns. But they're not so
comfortable to be a monopoly such that they can stop innovating. And that's
important. 'cause when they stop innovating as humanity, we're fucked. And so
we, we need to transition to the era optimal competition in frontier technology.

And I think we need leaders, stewards, venture capitalists, politicians,
educators, to remind the world that we have already lived through this era of
boom and bust and so on. And so these companies, like what's gonna happen,
right? Like you said, orange base stand and inference, all these companies,
inference is an extraordinary growth curve [00:45:00] ahead, but it's not gonna
be an extraordinary growth curve if there are 50 inference companies all
competing with each other on a race to the bottom, which is kind of what's
happening right now.

Like it is not clear to me that we need 50 inference companies. And it's not clear
to me that VCs are smart enough to realize that they're just lighting hundreds of
millions of dollars on fire. In a category where having four or five really good
inference trusted providers is net good.

Will the VC subsidization of 50, 20, 50, 60, 70, whatever companies it is, not
make it impossible for the good companies, the four five, to progress through
that cycle.

it's a bit of a self-destructive mechanism because if you have 50 different
companies all competing for scarce compute resources, then the, the folks who
are actually innovating don't have, can't get it. And so they can't do their next
round of product innovation and so on. And that's the problem.

When you have that like this, this,

where we are now though?

that's where we are right now is the best inference. Teams are calling me up.
Actually all inference teams are calling me up and saying, Ange, do you have
compute for us? 'cause that's, their product is reselling compute. But it's been
[00:46:00] hoarded. It's been hoarded by the hyperscalers.

It's been hoarded by people who are not innovating but are sitting on compute.
And it's so obvious to me now that I've left a 16 z I'm an independent
ecosystem, public benefit corporation, That the existential threat to innovation
in this category is lack of compute now. That's why AMP started procuring
compute for the independent ecosystem a while ago.

And so we are trying to find a way to get these teams enough compute that they
need to keep innovating. But I wish this was

four or five inference companies that win versus the others that don't?

supply access to supply.

It is that simple.

Yep. Compute supply. If you don't have compute, how do you do inference,
man? What are you selling? You need a product to sell. if you're making a
steam engine, you need coal,

one of your former partners, uh, tweeted last night that we're gonna enter a time
where, only model creators access the most powerful models, that will power,
obviously, the services and the application layer or the apps that they provide.
Do you believe that will be a world in which we exist, where model providers
inherently kind of [00:47:00] safeguard the best models for their provisioning of
apps? All Claude, or not?

Martinez is suggesting is that in competing cases, they will offer a worse model.
Which gives them an advantage. A as an example, 11 labs, which serves a huge
amount of application layer. Companies will reserve their latest models so they
can offer the best customer support and then sell their older models to Sierra
and Deagon, so they have a worse quality model, retaining the best for
themselves.

The embedded assumption there, right? What we have learned over the year,
like empirically over the history of technology is that if you have a general
purpose product like the iPhone, That works for everybody. Then the natural
incentive is to amortize the cost of product development of this over the largest
number of users.
So if you have a general model that's good for everybody, it will be available to
everyone. If you have specialized models that are good for some people, there
will be price, there will be product segmentation. And I think what this is telling
us. Is [00:48:00] that if there are many custom models, they will, some of them
will be accessible, others will not be.

And so if anything, I, I think we should see the fact that like there are frontier
model labs saying, Hey, here's a new model we have. It only makes sense for
some large enterprises to access this as vindication of the like ecosystem truth
that they're gonna, there's gonna be an ecosystem of different models, of
different types.

There's no one large God model. cause if there was, I think there would be the,
the market desire to have, you know, prime ministers, presidents and I and
students all use the same iPhone ' cause inherently you can raise the most
money and invest the most product budget dollars to, for a general product and
amortize the cost of that across everybody.

But if you have specialized models, yeah, I don't think they're gonna be
accessible to everybody and they don't need to be. I, I think there's an open and
closed. Access thing is somewhat overblown. I think it just empirically from a
systems perspective, if you look at the history of technology, if you have
general products, they're distributed to the masses.

If you have custom products, they have enterprise segmentation. Some are
accessible to the enterprise, others are not.

Are there foundation model [00:49:00] layer companies that are yet to be built
that will be worth over a hundred billion dollars?

Oh, so many. But they're not foundation model companies. I would call them
frontier systems companies. This is the problem. Every time I kept calling,
trying to educate people, you know, four years ago where they'd be like, Anj.
But you know, Andro is a foundation model company and RA's, a foundation
model company say, no guys, that's just one part of what they do.

Maybe they're starting there because that's a very part that's a core competence.
But there's a reason why, you know, anthropic also has a thing called cloud
code. there's a reason why Mistral has something called Mistral compute, there's
a reason why, Microsoft who's a cloud also has a copilot business.
You know, these labels and categories of foundation model when need to be
viewed, I think with more suspicion they are. Like

 What matters is the full, the systems co-design the systems, the full stack like,
like frontier research loop that you need to run with customers.

And then later when that happens, when you say, oh my God, Anj Anthropic is
now they, they were a model company and now they're launching a product
called Cloud Code. And I was like, do you mean If that was, [00:50:00] that's
part of the plan all along. Of course you need to have a, a pair programmer
interface for a model.

Like what? Why would you assume otherwise? Oh, 'cause you just weren't
paying attention and you had your neat market maps that your associates were
giving you, and you thought that was, that was truth. the commercial
community has forgotten how to build businesses and they've forgotten the
difference between first principles and marketing.

That's the problem. That's one of the other misalignment problems. The ground
truth of these businesses, machine learning systems, businesses, they've always
been frontier systems businesses. They were never just foundation model
businesses. Now, okay, if you had to package that up and tell your LPs that
because that was legible to them, then I, I can't blame you, I guess, but it, my,
the LPs I work with, I'm very upfront with 'em.

I say, look, these categories are going through huge reinventions. And, and,
when you partner with me, what you get is a full stack partner. And I will tell
you the first principles of what's going on. And these first principles, insights
will change over time, but you gotta be comfortable with huge CapEx outlays in
businesses that end up winning the entire category.

That's what frontier technology is. So, foundation [00:51:00] models have been
a deeply mis, and, and this is part of why I started the class four years ago, I just
thought. Security at scale was going through a bunch of reinvention, and then
we reinvented the class to be infrastructure at scale last year.

And this year it's frontier systems because not enough people realize that to
keep the capabilities frontier moving, you need to think about these projects,
these companies as frontier systems projects, not foundation model projects.
Does that make sense?
It does, but when I hear about the CapEx required, I, I respectfully ask, do you
have enough money? I think the $1.3

No, no,

was report.

not today.

yeah. How much money do you need? Ange?

Well, for the gigawatt 1.3 gigawatt, which was kind of our, our proof of concept
that that capital is not a problem. I think the question is if we wanna scale
beyond that,

yeah. We need way more capital to be deployed in across the western front in
the United States and US allied countries.

do you think you need?

 as long as the capabilities frontier keep moving and we want a healthy,
independent ecosystem, we'll just keep raising more [00:52:00] capital. There's
no end to that. I don't, I don't, I don't really, the day machine learning stops
working as a systematic way to give humanity more capabilities.

That's when I'll say we have enough Harry. But that's so far out. I don't even
know how to reason about that.

 I could talk to you all day, but before we do a quick fire, how will van share be
fundamentally different in five years time than it is today?

Well, again, go back to history, right? I think there will be a few people like
Arthur Rock and, you know, Bob Swanson and, and Mike Marla who turned
their, their practice into institutions. Then there'll be others who don't. And I
think if they don't evolve themselves for what entrepreneurs of this era need,
then I think they should get outta the venture capital business because we don't
need more bankers.

We don't need more, like, you know, one of the beautiful things I, I, uh, my
friend Vlad, who runs Robin Hood floated recently this like venture fund thing
on, on Robinhood,
right?

Robinhood Ventures, I think it

Yeah, yeah. But like, when you have software that can play many of the
coordinating roles of venture capital firms, [00:53:00] why do you need
somebody who's just a pure to borrow a Marxism, a wrapper on LPs, The, here's
what I'm most concerned about with the capital ecosystem. Not enough of the
wealth creation opportunity that's happening in Frontier is being shared with the
public. and that's not good for anybody. if you don't share this wealth creation
opportunity with the people who are supposed to be welcoming this technology
into their lives, which is ultimately the public.

What are they gonna do? They're gonna say, I don't want these data standards.

the, with the greatest of respect,

Yeah,

the money in venture capital funds are from endowments, pension funds, funds,
and so that wealth distribution should ultimately trickle down if we

yeah. But how many venture capital firms were in the seed round of anthropic?

Oh, none.

That's the answer for you. And that's happening again and again and again.
There's a huge misallocation of public capital into venture managers who did,
are not capturing enough value in frontier ai. Instead, they're investing in a
bunch of stuff that's not gonna exist, and the public's gonna be mad.

Did you put 300 million bucks into anthropic in one go?

I've had [00:54:00] the privilege to invest many hundreds of millions of dollars
into anthropic across several rounds from the first to the most recent one. So I
consider that, lucky. I I intend to give most away that away to public benefit,
causes public benefit education programs. I think we're at the very beginning
part of Anthropics, uh, journey on commercial progress.

Dude, I'm gonna do a quick fire round with you 'cause otherwise I'm gonna take
all day.
You can advise an LP investing in venture funds. One thing.

Hmm.

do you advise them

educate yourself. Take the class. Do all the readings. Do the readings. Don't,
don't skip the hard work. too many LPs are outsourcing their hard work, the, the
work they're supposed to be doing as capital allocators, which is like
understanding what's actually going on. And then decide which venture
managers and allocators you think have a unique defensible advantage of the
bottlenecks.

I, I would be investing the bottlenecks,

too many gps are not doing the work. The amount of gps who've never built
anything with AI is astonishing.

I agree. Completely agreed.

you'll laugh at me like I've built with every different like vibe code provider. I'm
[00:55:00] trying to turn my media company into an AI first media company.
pathetic compared to the shit that you do. But at least I'm trying, I'm seeing the
bottlenecks of super base integrations and everything that comes with it.

And you learn by building.

Learn by building.

not doing that in the Beginning, you shouldn't be investing. Period.

I completely agree. I mean, I, I was there, there's a sovereign country that came
to me at the end of last year and said, Andrew, we wanna bring 26 of our
ministers to your house and do a one year program where we educate. It's a
frontier program where we learn what's going on in AI from lectures and so on.

and then we wanna do a deployment project where each of our ministers
actually built AI agents. And I said, you know what? that like, if you take C,
take Stanford CS 1 53, that it's a microcosm of this course I'm doing with this
country, this sovereign fund that we've partnered with. and you, you have to do
the work to read the literature, understand what's going on in research, and then
deploy yourself, like build tools.

Uh, you know, the class project, the Stanford CS 1 53 class project is the
[00:56:00] one person Frontier Lab, because I do believe that what would have
taken 50 people to do four years ago now with the right AI tools you can do
with one person and as a leader, if you haven't played with these tools and
deployed yourself and built your own agent, I don't think you understand what's
going on.

I'm not letting the, the ministers who are taking this class with me, I'm not
letting them graduate until they build and deploy agents. I've told 'em that
they're not getting, they're not getting their graduate certification.

Have you told your wife that you've got 26 ministers come into your house?

She let me co-host them. She let me co-host them at our house in sf, you know,
a few, few weeks ago. And I'm very lucky to Viv, I don't deserve Viv, I'll tell
you that, but she's very, very, she, she's mission aligned and we both believe
that the best thing we could be doing with our time is, is educating at scale.

what makes Dario so good that other people don't see from the outside?

a couple of things. One, sheer scientific brilliance. Truly like world-class
technical ability in his domain, an obsessive, desire for truth seeking. [00:57:00]
to keep reasoning, reasoning, reasoning, doing, to, to keep doing experiments
he's a physicist at heart, right? Like I, I think DIO is a physicist at the end of the
day.

He is not actually a computer scientist. and so a physicist, a world-class
physicist tries to derive derive laws, general laws of reality by looking at data
and running empirical experiments. He's, he's an empiricist and he has an
obsessive desire to be a good empiricist.

And the third is mission alignment culture. He says, this is our focus. This is our
mission. No drift. We won't take shortcuts. We, we are willing to make huge
trade offs to hit this mission, and that attracts the best talent, incredible talent in
the face of criticism of people saying, you are a mercenary, you're blah, blah,
blah.

You're just doing this for profit. No, actually, it turns out there's a ruthless desire
to, to stay focused on the mission and that results in hard trade-offs and
priorities. And if you don't, if you're not aligned on that mission, then you'll just
think he's crazy or you know, he's evil or whatever. It's crazy how much ad ho
attacks people I've seen against [00:58:00] him, but he's, that caught that clarity
of mission.

what have you changed your mind on in the last 12 months?

You know, the biggest one is, health. I've had some health experiences between
both the family members and myself, have had health experiences that made me
realize we all just don't know how much time we have on earth, and that makes
you stop taking for granted how much time we have. And so I start taking time
much more seriously.

But I would say, and this was my, my kind of on, you know, every lecture I do
at Stanford, we talk a lot about scaling laws and technical stuff, but I also give
the kids like an an's life scaling laws lesson. Uh, you know, the, at every, I'm
very inspired by Richard Feynman, Feynman's lectures, you know, always kind
of combine technical education with a little bit of life coaching for them.

my like, number one scaling law for them, for the students was take life
seriously, but don't take it so seriously that you forget what makes it worth
living, which is have fun with friends, work on interesting projects with people
you love. Don't take relationships for granted. It's humans that make the world
go around.

And if you're so focused on your next fund or your next [00:59:00] raise or
whatever, you just take for granted. The one thing, we all don't know how much
we have, which is time with each other. I just start valuing my time more, my
relationships with people. I, you know, there's

so many people. I mean, my parents, you know, I left my parents behind in
India to move to college, at Stanford, and I have gone weeks of my life not
calling them or texting them. And now they're, you know, in their sixties and
I've,

sorry.

I would give you a hug if we were in person.

Fuck. I'm so sorry, man. I,

Don't worry. It's okay.
Jesus.

You know, in the first money we ever made from the show, we made it 'cause
my mom has Ms. And we couldn't afford treatment for her. And the only way
that I could pay for it was by putting adverts in the show

Wow.

that that was how we did it and they still pay for it. Thank you to banter for
paying for mom's Ms.

Thank you, Christina. Yeah. Thank you for the corporate [01:00:00] sponsors.
Um, yeah, man. The trade offs. You know, the sacrifices are,

Parents are amazing.

parents are insane.

how do you escape the money treadmill. I didn't have money when I grew up
and I was like, I'll be happy when I get like, X amount of money. Any advice on
escaping that money treadmill?

Look, um,

I was very lucky you know, I went to Singapore on a government scholarship
and, qua Yu, who is the, you know, was the founding father of Singapore, I'm a
big qua uist, realized that, they, they didn't have many resources. They had, they
didn't have money as a founding nation.

They didn't have. They had nothing basically other than themselves and their
location, their strategic location. And he realized we need to build a talent
program. We need to run this country like a company. we would recruit, the
best talent from across Asia. And because I, I think I was the top 10 or
something in some public exam when in the 10th grade in India, I was tapped to
be a scholar in Singapore and I took, I was a government scholar.

Now, I didn't have to actually, I was lucky enough that my parents could have
paid for it. We had a family business in telecom, but it was very [01:01:00]
important to me to be independent from my parents because in Indian culture
and a lot of cultures where if you don't have financial independence, you are
always kind of beholden to somebody else.
And in, in the case of community cultures like India, like there's a lot of
pressure to adhere to their values and so on. I, I think I did. 'cause
subconsciously I'm very lucky. I have a sister actually who lives in London,
who fought my battles for me. She was, she's seven years older and I got to see
that she was a rebel and she wanted to do all kinds of, things and including, she
wanted to go to fashion school and they didn't want her.

So she, but she had to go to law school because they were paying for it. she
actually, I think, fought some of my battles and made me realize like, the more
independent I was, the more I had more freedom I had. And freedom matters to
me a lot. And so I, I, I just define my goal, my financial goals by, through
independence is what ma has always mattered to me.

And so I'm willing to make big trade-offs in, money to retain my independence.
And anytime I find my independence feeling threatened, I go, you know what? I
need a change. So I, I, [01:02:00] that, that's what matters to me. I, I, anything
you need to figure out what is your mission? What, what matters to you more
than anything else.

So you're willing to just turn down all kinds of money and job opportunities and
so on. 'cause that clarifies a lot where you spend your time, basically. Does that
make sense?

Yeah, my mission is really to enrich the already very rich family offices of
Europe. That's it. Yeah.

Okay. Well then you've got a waste to go on the treadmill, brother.

Was, was that not a bug? I didn't read the memo. Fuck. Um, you know, I also
think that people are just not very funny anymore. Like we lack a little bit of
humor in a

I know,

It's

he's crazy.

Yeah. I, I was with my partner the other day. I'm like, you speak like ai? And
he's like, I know. And you know what? I talk to my wife, like, I talk to Claude
and she fucking kills me.
I'm like, yeah, that's not a good thing, dude. Final one. it is a bit morbid, what
do you want to be remembered for?

Oh,

Angie's legacy to be?

Viv asks me, asked me this like, Three years ago at a party. We were like, I
think it was at, [01:03:00] at our like anniversary or something. We were with
like 10 of our friends, our closest friends, including some of the co-founders of
philanthropic. it was one of these classic San Francisco kind of like dinner
parties.

And she puts me on the spot and I just blurted out, I want, she, I think what
she'd asked was like, what do you want it to say on your tombstone? and I, and I
blurted out he was right.

 and the room just went dead quiet. And they were like, yep. And it's because I
have this obsessive desire and need to try to learn where the future is going and
then tell everybody about it. And then everybody thinks I'm like, some snake oil
salesman or whatever. And then like, now that's changed because now it turns
out I was so right.

I made LPs so much money that they're now asking me on, can you, you know,
people like I was invited back to teach this class at Stanford. Right. People are,
are fine, I guess, have realized, okay, Ange might know a thing or two about the
future. Let's go get his take.

I went to this boarding school in, in India called Rishi Valley, and it was
founded by

of no tech,

no tech.

seven [01:04:00] years,

Yeah. Rural India bird.

No wonder, no wonder you are a happy and adjusted person.
It's taken me a while to get here, but yeah.

your children have social media?

Yes. I, I, I, I, I think it'd be crazy to not let them have it. So have access to social
media, but I, I think it has to be done in moderation. And most parents have a
really hard time moderating it with their kids. 'And then it's really hard to
moderate. You know, I, with Rishi Valley, I had access to a computer once a
week. And so you need to enforce something like that where you, you don't take
it for granted. It's within a structured sort of environment. And then you develop
good habits and protocols and practices to not be dependent on it, but you, like,
I would plan my Wikipedia sessions, like I had to plan my, like, you got one
hour a week in the computer room in Rishi Valley.

So you really gotta plan like the highest use of that time. And so you're not
dependent on it, but you just use it as a high leverage strategic asset. I, that's
how I think technology should be viewed. You shouldn't take it for granted.
Like the problem is. You know, people keep saying we're, we're, we're gonna
have the singularity.

So I'm like, have you realized we're, [01:05:00] we've been at this for like 10
years, half of you outsourced your brain and thinking to this device. Anyway,

Oh, dude. Uh, I, I so enjoyed doing this. Thank you so much for putting up with
me. You've been utterly fantastic.

no problem, man. Thank you for doing the, the consistency with which you've
kept up this. I mean, you're an institution now, right? Like the hard thing is,
you've been at this, we've gotten old together, right? When you were doing this,
like you said, you were a kid.

I was much younger.

Me and Pat Grady. Pat Grady was one of the first people I met in Venture and
he was an associate and I was like a 17-year-old and like laugh with Pat. I said
to him the other day, dude, you've gone from associate to like head of Sequoia
and I've gone from podcaster podcaster.

But before we leave you today, you have the idea, but often with AI tools, you
hit a wall. Well, base 44 is where that friction disappears. Turning how you talk
into how you build full stack web and mobile apps, sites, autonomous super
[01:06:00] agents, all built in minutes, not. Weekend spent on damn
configuration base 44 ships it all out of the box, the backend, the database, the
authentication, and the hosting.

It handles the heavy lifting so you can just stay in the flow. It doesn't just
replace the busy work it multiplies you. It makes you so much more capable and
effective version of yourself. In this market, being fast is the baseline, but to
win you gotta be first and base. 44 is that edge. It's the move that lets you skip
the troubleshooting and get straight to the breakthrough.

Launch your next. Big thing@basefortyfour.com. That's base four four.com
after base 44 helps you launch Corgi, helps you cover what comes next. My
word, what? An arresting first line. Get your ass covered with Corgi Insurance
and I'll tell you why. If you are running a business right now, you already know
this.

Pain all too well getting insurance. It's really slow. It's confusing. And my word,
it's full of paperwork. Well, that's exactly why Corgi is here to change the game.
Corgi is the first and [01:07:00] only insurance carrier designed specifically for
tech companies, allowing you to get covered in minutes instead of days.

Corgi provides essential coverages for all growth stages such as d and o, e, and
O, liability, cyber, commercial, general liability, and more. Get your ass
covered. I love the way we say asks. With Corgi Insurance alongside thousands
of other startups@corgi.com slash two zero VC today. That's corgi.com/two
zero vc.

You won't regret it. While Corgi handles the coverage, Turing handles the
talent. Frontier Labs keep facing the same limitation. Models perform well on
benchmarks, but they fall short once they enter real coding tasks, real tools and
real workflows that disconnect between synthetic evaluation and. Actual system
behavior is now a core blocker for Argentic models.

That's why Nvidia Anthropic, Salesforce, Gemini, and other leading lab partners
partner with Turing. Turing is the research accelerator focused on post-training
reliability. They build [01:08:00] realistic RL environments, next generation
data quality systems built from real world operational traces and coding data
sets.

That stress models under conditions where failures matter state changes,
workflow branching, brittle tool calls, and the coding errors that break RL
agents, but never appear in benchmark reports. In reality, a model may
demonstrate correct reasoning in your evaluation setup, yet still select the wrong
parameter or mishandle a code update in a realistic interface.

Turing makes that failure visible and gives teams the signal they need. To fix it.
For labs advancing AG agentic systems, Turing provides the structure required
to understand why these failures occur. To find out how, visit turing.com/two
zero vc. That's T-U-R-I-N g.com/two zero vc.

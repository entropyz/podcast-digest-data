---
type: 20vc-episode
guest: "Joelle Pineau"
company: "Cohere"
role: "Chief AI Officer"
episode_type: interview
date: 2025-11-08
youtube: "https://www.youtube.com/watch?v=51y4KatMBFI"
transcript: "https://20vc.substack.com/api/v1/file/6fa955bb-39c3-43dc-a7fb-95b7c2ce02e0.pdf"
newsletter: "https://20vc.substack.com/p/20vc-newsletter-9th-november-2025"
tags:
  - 20vc
  - ai
---

# Joelle Pineau — Cohere

> Chief AI Officer @ Cohere | 20VC Interview | 2025-11-08

## Key Takeaways

### 1. What Is the Right Barometer for if AI Is Successful?
Can most of your employees do 10x their work with AI vs. on their own? Humans and AI have complimentary abilities. To flat out replace a portion of your workforce is unrealistic.

### 2. The Importance of Open Source AI
Close-sourcing everything has been a deep mistake. We need ideas to circulate to advance the research of AI.

### 3. AI Superstars Does Not Work to Build a Team
Having a bunch of AI superstars in a room does not make them more productive. They need an execution machine, they need the social glue. I’m a big believer in building diverse teams with complimentary talents.

### 4. What Is the Future of the Data Supply Market for the Likes of Mercor and Surge?
The human-AI partnership is not a phase. The balance of outputs will shift; humans will provide complementary direction. Some firms may not exist in 5 years but human-guided training is here to stay.

### 5. WTF Happens When We Have a World With So Much AI Generated Code
With so much AI generated code, the bottleneck isn’t creation: it is selection. We’ll need editorial mechanisms to choose valuable, safe, purposeful code.

---

## Links
- 🎬 [Watch on YouTube](https://www.youtube.com/watch?v=51y4KatMBFI)
- 📄 [Full Transcript (PDF)](https://20vc.substack.com/api/v1/file/6fa955bb-39c3-43dc-a7fb-95b7c2ce02e0.pdf)
- 📰 [Newsletter](https://20vc.substack.com/p/20vc-newsletter-9th-november-2025)

---

## Full Transcript

Joelle: [00:00:00] The scaling laws have been remarkably robust

there's a lot we don't know yet in terms of the vulnerability of these systems

Harry: if you don't need to buy the galactico, why do

you have like an Andrew

Tak, a Daniel Gross and Alex Wang

and the Galactico assembling

If I gave you $10 billion, what would you spend it on first?

Knowing what, you know, what do you not let your children do?




Harry: This is 20 VC with me, Harry Stebbings, and today we have one of the
leading minds in ai, Joelle Pineau. On the show. Joelle is the chief scientist at
Cohere, where she leads research on advancing large language models and
practical AI systems. Before joining Cohere, she was VP of AI research at
Meta, where she founded Anne LED Meta's ai Montreal Lab.

Joelle is also a professor at McGill University and renowned for her pioneering
work in reinforcement learning robotics and responsible AI development.

But before we dive into the show today, are you drowning in AI tools
[00:01:00] Chat, GPT for writing, notion for docs, Gmail for email, slack for
comms, and you are constantly copy pasting between them all losing context
and losing time. This is the AI productivity tax and it's killing your out. Put at
20 vc, we're all about speed of execution, and superhuman is the AI productivity
suite that gives you superpowers everywhere you work.

With the intelligence of Grammarly Mail and coder built in, you can get things
done faster and collaborate seamlessly. Finally. AI that works where you work
however you work. Superhuman gets you from day one with zero learning
curve, and it's personalized to sound like you at your best, not like everyone else
using generic ai.
Get AI that works where you work. Unlock your superhuman potential. Learn
more at superhuman.com/podcast. That's superhuman.com/podcast. And once
you are moving faster with superhuman, make sure you are [00:02:00] moving
safely with Vanta. Customer trust can make or break your business. And the
more your business grows, the more complex your security and compliance
tools get.

It can turn into chaos. And chaos isn't a security strategy. That's where Vanta
comes in. Think of Vanta as you are always on AI powered security. X. But
who scales with you? Vanta automates compliance, continuously monitors your
controls and gives you a single source of truth for compliance and risk. So
whether you are a fast growing startup like Cursor or an enterprise like
Snowflake, Vanta fits easily into your existing workflows so you can keep
growing a company your customers can trust.

My listeners can get $1,000 off Vanta by going to vanta.com/two zero vc. That's
VANT a.com/twenty. EC2 zero VC for $1,000 off. Vanta. You have now
arrived at your destination.

Joelle, it is so great to have you in the studio. I've heard many great things
[00:03:00] from Nick Aiden Repp, so thank you so much for joining me.

Joelle: Thank you. Happy to be here.

Harry: Now, you spent over six years at Meta, and I want to start there because
it's a very transformative time and place. What are the biggest takeaways for
you from that time, and how did that shape your mindset to how you think
today?

Mm,

Joelle: Hmm. Well

I was there from 2017.

to 2025, and you have to see just how much AI changed

Over that period of time,

what we were
really

focused on is fundamental,

AI research. one thing that I've learned.

is just sometimes how long it takes to prove out a hypothesis. We feel like AI is
moving at the speed of lightning, but in fact, there's some things that it just takes
a few years to mature to get the right optimizer, the right compute, the right data
for that to really make a difference.

Harry: I look at where we are today and everyone kind of goes, it's here, it's
here, it's here. And then you actually look at what a lot of the leaders have been
saying recently where it's like, actually, Andre was saying it's not the year of the
agents, it's the decade of agents.

Sam's kind of pulling back. [00:04:00] Two

have we got over our skis and we're actually kind of all pulling back, realizing
that time is the factor we need to rely on.

Joelle: Well, I'll give you an example. of, You know, I've been in research for,
for

a couple decades now. I've been working.

on reinforcement learning for over 20 years. Suddenly

everyone's talking about reinforcement learning, you know, since the advent of
reasoning models, agents and so on. So, you know, sometimes you have to be a
little patient with these ideas and

the right

algorithmic tweak,

the right context. The right.

problem. Domains just opens up the magic.
Harry: I, I was listening to Andre yesterday and he said in this show that
reinforcement learning is terrible, uh,

Joelle: less

terrible than 20 years ago.

Harry: Have we overinvested in RL based methods at the expense of maybe
like more scalable alternatives?

Joelle: I'm still super bullish on RL in that like

the concept itself is so fundamental. You know, this idea of training through a
system of rewards, of indicating what's

[00:05:00] valuable and what's not valuable through numerical.

values. Like

That is so fundamental. It's not going away.

Now,

you know, where we're maybe getting a little bit ahead is thinking that just

RL out of the box is gonna give

us a GI

that part a lot less. So, you know, if you look at

the curve of progress, RL is terribly inefficient. And so the amount of signal you
need to get in order to really shape the behavior of a model is

far from where we are today,

And so we'll need to figure out how to, to really deal with this,

with this learning efficiency, problem.
Harry: you are probably thinking, what did I get myself in for? Um, and I don't
blame you. I ask questions that I think everyone else thinks, but I'm not afraid to
say, I don't know. Why is RL so

Joelle: inefficient?

there's a few reasons

you're gonna

get me on, like a,

a

Harry: this is great.

I'm, I really love to learn. There's

Joelle: there's a few reasons. One is the fact that RL is about sequential decision
making.

So, you know, think about you're starting at a point you need to

figure out what you're gonna do next, and you might pick the right side of the
branch or the wrong [00:06:00] side of the branch, and then like the

road keeps on splitting.

So

every time you make a mistake

it sort of compounds

through the length of the series of actions you're making, so

that

means like the amount of error you can make

can
be very, very large. And to get it right

is quite difficult. Sometimes people compare it to like a needle in a haystack is

like finding the right solution. in rl. so there's that part. The other part that's hard
is the fact

that to train the system, to train the models,

you have to essentially take

actions.

To learn. You can't learn from static data. You can learn something from static
data, but actually

to get the right policy, you need to test it out.

And so that means you need a simulator.

you need to Get the synthetic data. All of that

can be really expensive also. And so we have an difficulty getting like just a
variety of environments and simulation to

test

Harry: When we look at the cost curve for RL, you said you've been working
on it for 20 years. Have we seen that dramatically come down? Will we see it
continue to dramatically come [00:07:00] down or is it a case of it is just a
fundamentally expensive method of training?

Joelle: It's come down, especially

in domains where we have good

reward functions. So the place where most people started

hearing

about RL is around the
alpha go. Time, you know, the

game of Go, which was sort of one

of the goals for ai. Many people thought we were

at that time we were still a decade away

from being able to have machines play go at the level of humans.

and, and out comes a team from Deep Mind, you know,

goes off plays against uh, the world champion and shows that that RL can
basically

do it. and so I would say, in cases where we clearly know what's the goal, we
can write down.

precisely the reward function. We're good, we can make a ton of progress. So
that's why you're seeing progress in mathematics. Very well-defined reasoning
tasks, games, these kinds of things,

Rl

to shape the behavior of models, to get them to be social creatures that we have
no [00:08:00] idea how to do. I mean, I don't know if you have children, but

like shaping their behaviors. You know, the number of times.

you can repeat the same thing and still they do something else. And so there's
something there. You don't know how to write that out mathematically, and
that's where I think we're still in for, for some hard work.

Harry: so when we look at the training versus the inference market today.
We've had so much weight on training so far, and it's been incredibly costly and
expansive. And then I hear everyone say, well actually inference is 95% of the
market, and that's where it's all going, and that's where NVIDIA will make most
of their money.

How do we think about the cost curve applied to training versus inference and
where it sits today?
Joelle: Hmm. I think

There's a lot of different

variants

and

you know, if

you'll allow, maybe I'll pivot to like

you

Harry: Pivot anywhere

Joelle: where

I'm, where I'm going with Cohere

now. Just,

you know, I joined Cohere Less a month ago. Super exciting company.

I think one of the things that Cohere is doing

is actually to develop AI models that

run on premise,

So that means enterprise bring it [00:09:00] in, they run it locally. So

the company has to worry about

the training

of the models. Obviously we want

world class models, for the needs of enterprise,
Doesn't have to worry about the inference, doesn't have to worry about the
inference cost,

the, you know,

the, the clients' customers have to figure out

what's the right

way

for them to digest.

the ai.

That means like there's a lot of motivation to have very efficient models so that
they can run really efficiently on premise.

So, you know, we get caught up into one

one

paradigm, but there are other paradigms as well.

Harry: they're the ones paying for the inference, is there not less incentive to
make them efficient? Because sold you are not the one paying for it. If you are
the one paying for the inference costs. God, I want it to be as efficient as
possible 'cause it's my dollar going to that.

But if it's IBM's dollar, yeah, I would love it to be efficient, but we're not paying
for it.

Joelle: We're still in the early days of AI adoption and enterprise. So it's good
for the client is good for us.

Harry: Totally,

totally
get you. Um, what's the biggest challenge about [00:10:00] capital efficient AI
today? I know that sounds strange when you look at the e economics, so to
speak.

What's the biggest challenge?

Joelle: there's a lot of challenge today.

I think

I, in terms of the economics of ai.

I think one

Of the biggest challenge, the fact that it's,

very hard to have predictability,

right? everyone wants to know when are we going to

hit the breakthrough? Everyone wants to know how many GPUs do I actually
need everyone

wants to know like,

what's the return? I can expect

There's just a lot of uncertainty built into the system.

A lot of that is because

there's a lot we don't know about this

technology

and so that means we have to take in quite a bit of risk

when you're building out, whether you're building out,

your data center,
whether you're building out your workforce, whether you're trying

to figure out, you know, how much data to to curate. And so that makes it
difficult for a lot of people. People want answers and this is a world where we
don't have that level of predictability compared to other industries.

Harry: Does progression happen in kind of a linear [00:11:00] fashion or does
it happen in step functions like alpha go like a deep seek, which depending on
kind of what you believe suggests a lot of efficiency in terms of model
improvement. Does, is it step function or is it linear?

Joelle: I tend to

decompose different

ingredients

that lead to progress? You know, people often talk about the, the algorithms, the
data, the compute

I think in general, compute and

data have a more linear effect on

progress. You build more compute, you run bigger models, you can typically
get better performance.

You feed in more data. It's not just quantity you need

to worry about quality and diversity as

well. but roughly it's more

linear ish with respect to the data.

The algorithms are the ones that have the.

non-linear effect, and so you can explore

Lots of ideas,
and then something like the transformer comes along and just changes the
paradigm

and it's not just a transformer.

you know, on the optimization side, suddenly we hit upon Adam, which is a
technique to, to do the optimization of your model changes in the paradigm
reasoning. [00:12:00] Suddenly we start thinking about

How to put that in.

the loop reasoning and it changes the paradigm. So

Those ideas tend to have a non-linear effect.

The

Challenge with these

algorithmic ideas though,

is that

actually

it

may take a long time to prove themselves out,

so

like the paper can be sitting.

out there, there's thousands of papers coming out, the idea sitting out there, and
we may not think to try it with the right data at the right scale, with the right
combination of hyper parameters. And so you don't notice that effect for a
while. So it's

Hard to predict and it's not linear more on the algorithmic side than I think on
whether
it's data compute, even talent or other things.

Harry: with respect to Google, I mean, transformers obviously birthed in
Google and started as papers for many, well, a couple of years. Um, when we
look, you mentioned that you compute algorithms data. If we just kind of go
through them to understand, everyone suggests that it's weird.

There's two different ones. It's like scaling laws exist, just throw more compute
[00:13:00] at it. When you look at data center investment, when you look at all
desirability of compute, and then again you have GPT five seemingly focusing
on efficiency and other signals. Do scaling laws play out from here?

And if so, for how long?

Joelle: The scaling laws have been remarkably robust.

they don't play Exactly. has, we expect

but still they've been remarkably robust. Lots of people have

bet against scaling laws.

in the past, and I would say overall, you know, we've seen a pretty robust effect.

they

don't work alone. We also

need these algorithmic innovations. but most of the time, you know, I, I
wouldn't be against it

Harry: on the algorithm side, is that the hardest to innovate on? You could
think about, but you can buy more compute might be hard, but you can buy
more compute and data there at different ways, whether it's synthetic or human.
Is algorithms the hardest to innovate on?

Joelle: It's certainly the most creative work to be done and

you know, the

space of ideas is
so

[00:14:00] wide.

um,

that I would say

Hardest in the sense that like you can

move in, you know, I'm a researcher.

hard, you can move in so many different directions and picking the right one,
you don't know until you get there whether it was the right one or not

It's a little bit like reinforcement

learning.

So

in that sense, I think it's

it's

the most interesting,

one is the most

frustrating one and it's the most difficult one Certainly from investors' point of
view to know where to put your chips

Harry: is speaking of kind of knowing where to put your chips and moving
from purely a research lens with, with Matter

to now also building product.

Is there ever this like inherent conflict between intellectually interesting
research with the need to productize and monetize? And how do you think
about that there?
Joelle: I mean,

One of the reasons I am really excited to be joining Cohere actually is because

like we're at a

stage where AI is really starting to be useful,

Maybe not as useful as people.

think it is, but we are there. and by working on AI that's going into enterprise, I
feel we're gonna get [00:15:00] such an interesting signal of what works and
what doesn't work. You know, we keep on talking about, you know, a GI

and AI for the masses and so on.

but.

Actually, like when

you need to sell AI to a business, you get a real signal of what works, what
doesn't work.

and That's what I'm most curious to

see. and you know, we've been using these academic benchmarks for many
years. You get some signal, but

It's not the same as,

as getting this to do productive work.

I'm curious to, I'm curious to learn out of that, you know, we're gonna get new
types of

data,

we're gonna get

I think a lot of insights that are
then going to drive

the research ideas. Um, I think that's, that's

the other thing to think through when you have a large space of ideas to

explore.

Getting that feedback signal from.

the real world is super useful to guide you through that search of ideas.

Harry: I just had a great chat to David Khan at Sequoia who said that he thinks
a good barometer for utility value within enterprises. He's like, does it have the
ability to replace the work of your bottom [00:16:00] 5% in any category? He
says, like, we overestimate a lot. Yeah. Can it replace the bottom

Joelle: mm-hmm.

Harry: In any function?

And if it can, that's a very meaningful improvement. Do you think that's a good
barometer? And how would you advise an enterprise on whether something's
useful or not? As a yardstick?

Joelle: know, I, I, I prefer in terms of a barometer of, productivity, something a
little bit different, which is to say

can

most of your employees do 10 x the amount of work with AI versus on their
own?

that to me is actually,

a better barometer. I think human.

and AI have very complimentary abilities, so to just like

flat out, replace
a portion of your workforce is actually pretty unrealistic. some May, some may
try and some may be slowing down their

hiring, but I

Harry: respectfully. I think 10 xing, your work feels more unreal. Is that, is that
not a bigger ask? I'm almost more intimidated by 10 Xing

my work.

Joelle: Oh. I don't think that's,

unrealistic at all.

Harry: wow.

Joelle: Yeah.

Harry: In a timeline that is the next [00:17:00] couple of years. Yes.

Joelle: Yes.

Harry: I'm sorry. How? How does that actually shape out then?

Joelle: I think

you have to Identify very concretely.

the types of work that you are delivering, but I think we're starting to see like,
you know, Hollywood quality productions being made in a matter of hours. We
are seeing, you know, to take a super concrete case like machine translation. If
humans are doing the machine translation compared to machines doing it, you
go from hours to seconds on

Long form text, multi-page documents

And so for a lot of work, it's not like AI can do all of the work. Humans

still need.

to ask the right question.
They

need to

verify the information they need to shape the tasks. But once the task is well
defined, the product are clear. Like

all the design considerations

are fed into the prompt. You press the button and you've got an answer

in seconds for something.

that used to take sometimes weeks and months

Harry: I'm just kind of

trying to reevaluate a belief that I had for the last few months, which is like foot,
I'm a venture [00:18:00] ambassador for a sin for all of us to make money. We
need to see the transition from kind of human labor budgets

to

AI spend. And it's with that transition where we obviously see the TAM
massively increase

and we make a lot of money.

But when I hear you say that, I suddenly question that assumption. It's like the
barometer for whether we make money. Because you're suggesting that actually
we don't replace the human labor budget, it just makes us 10 x more efficient. Is
that correct? Yes.

Joelle: Yes.

you

know, there's a lot of nuance to all of that, and some work will be harder to get
that same level of efficiency gain.

Whereas other work you'll see a hundred x.
in terms of efficiency gain.

But

I I do think that for a lot.

of the work that's happening right now, that's absolutely feasible.

Harry: Where do you think, I'm sorry. Where is the efficiency gains most
tangible?

Joelle: it goes back a little bit to this notion of what are the tasks that we can
specify?

Well.

in any case where

we can be very precise

about what

a great result looks like, we'll be able to make that task automatic much
[00:19:00] more easily than tasks that are much more nuanced and,

and have a lot of complexity.

Harry: it's ambiguity.

Joelle: Ambiguity.

in the specification of the task is what's hard for our

Harry: Mm. How have you seen enterprise reaction to this? There's fear from
workers sometimes there's excitement from leaders. There's apathy sometimes.

How have

you seen an measured enterprise response?

Joelle: a
lot of the, the workforce,

can be reasonably fearful about job displacement. there's a lot of also

individuals who have,

you know, a bit of an instinctive reaction to, to change. and and change can be
hard for a lot of people. And we're seeing a lot of change in a very short. Time
span.

And so I think

there's also a generational effect. I think for some generations there's that
change is, is more, more

jarring, I think for the.

younger generations. I have teenagers, young adults at home for them. Yeah. It's
just native. [00:20:00] They just, you know, kind of, you know, gonna

grow

up with that technology.

in a different way than, than some of the older generations.

Harry: It's interesting, Sam, speaking of kind of children there at home and
how they engage with it. You know, Sam Ortman said that kind of young
people engage with it as like an OS to the world and AI is that companion for
them and then older people kind of use it as a next gen Google.

mm-hmm.

Do you agree with that and do you see that in your work?

Joelle: I

see a lot of people using it as a tool more than as a, as a companion. people have
this, you know,

Swiss knife in their
in their

work life all of a sudden.

That can be super helpful, but that's really most of what I see.

Harry: What are enterprise's biggest challenges with AI adoption at scale

Joelle: You know, one of the challenges.

is to make sure that the AI comes in and can be integrated in their workflows,
their processes, their information. And so

the challenge is

to deploy in a way that allows them to exploit

all of,

the [00:21:00] information systems that they already have.

And some of them have accumulated these over decades. that's, you know,
some of the work that, that remains to be

Harry: so it's integration with existing systems and data flows. I, and,

Joelle: I, and that's, you know, of course that's something we see a lot of cohere
'cause we do on-premise deployment

You know, one of the things we focused

on the most is

data confidentiality

and security. so that,

So

that enterprise can,
exploit all of that information. So that's top of mind for us. but it's also a huge
opportunity,

I would say. There's a, there's

a big interest

in that, but making sure to, to get that, that compatibility, I think is a, is a
challenge. in many cases for people.

change is hardest for people. And so you have to get them curious.

about using the technology. Many people feel

They have to get it right

the first time, and, and I really think like a spirit of exploration and curiosity is,
is much better suited to,

to the face of maturity of the technology that we have today.

We don't Have all the answers of how

it [00:22:00] should be used, that's gonna come from, from people on the field.

Harry: security is a topic that we quite often glaze over, especially when in, uh,
investing in kind of application layer AI tools.

What

does no one know about AI security that people should know?

Joelle: with respect to ai.

security, I think there's a new front that's opening up with, the development of
agents. And frankly, there's a lot we don't know yet in terms of the vulnerability
of these systems. With LLMs,

We're starting to get a better understanding We've had, you know, quite a bit of
red teaming exercise and jailbreaking and so on, and so people have identified
different
risk vectors.

prompt injections, things like that, which are

Vectors for malicious

actors to interfere with a system

with AI agents

we haven't seen that. And one of the features of computer security in general is.
Often, you know, it, it, it's a bit of a cat and mouse game, quite frankly. Like
there's a lot of ingenuity [00:23:00] in terms of breaking into systems. And then
you need a lot of ingenuity in terms of

building defenses.

And so we just have to stay very active in that sense.

Harry: What are the potential vulnerabilities though in an agent world?

Joelle: in terms of agents, you know, we, we worry a lot about, um,

hallucinations

in LLMs

The

parallel in agents is impersonation, so agents that come along and are essentially
impersonating. Entities, which they don't legitimately represent. And in doing
so, taking actions on the behalf of these entities where they don't legitimately
represent whether it's, uh, infiltrating, you know, banking systems and, and so
on.

And so I, I do think we have to be quite lucid about this, develop standards
towards that. Develop ways to, to test for that in a very rigorous way. There's

ways to reduce that risk drastically,
You run your agent, you know, completely cut off from the web, you're
reducing your risk exposure significantly.

but

then you lose access to some.

information. [00:24:00] So depending on, depending on your use case,
depending on what you actually need, there's different solutions that may be
appropriate.

Harry: That's a really hard one. 'cause like then verification becomes the most
important thing, but then it's like, who's the arbiter of verification? Is it
governments, is it, is it companies? how does one think about that? Who says
you are a valid agent versus an invalid agent? Um,

Joelle: governments can be good.

for defining standards on which we all agree.

Companies are

much better at building

the solutions.

at scale and deploying them.

Harry: Do you think governments are good at setting the standards when you
look at AI and where we are at? And then when you look at the sophistication
levels of government, programs or decision makers with respect, they're just a
little bit behind. Do you think they are actually equipped.

Joelle: I don't think you should

Look at where government are in terms of

necessarily AI regulation, That ai.

as a field is so incredibly young and fast moving and, and by nature and
[00:25:00] there's some good in this,
Governments are moving a little bit more cautiously and, and, and

usually need to

benefit from our knowledge to make good policies. and so

I do think you, you can,

look at other fields in terms of, of regulation. You know, you look at, aviation.
The security record for aviation today compared to where we were 50 years ago
is just incredible. And

governments have played a role

in defining that in terms of standards and in terms of what are the, the norms
and so on.

So I'm quite hopeful, I'm an

optimist about this. Maybe it's my Canadian side, that governments can play a
useful role. in many cases, you know, clear standards actually means reducing
uncertainty for a lot of companies in this space.

But we shouldn't expect that

to be ahead of the technology. I think that would be the wrong order of things.

In some sense, we need to develop that technology with enough of a creative
space, and we need to learn fast and then develop the right, the right guardrails
for that technology

[00:26:00] from, from

from the real learning. We have,

Harry: we, we mentioned that kind of, uh, governments and their role.

Uh, when I had Nick on the show, he was saying actually the benefits of not
being an American company, given some geopolitical challenges sometimes.
Um, just intrigued. Do you think we will have these govern sovereign models
for each geo?
You know, we have Mr. Island in France, you know,

COHEs obviously in Canada or founded in Canada by, and you've got global
kind, HQs.

Do you think we all have these sovereign models and regionalized winners?

Joelle: I

Do think it's healthy that there are models.

that are getting built in different places around the world, not just in, in the US
and, and China right now.

I think this is healthy in terms of diversity, of of thoughts.

I think it's healthy in terms

of having a greater

amount of

people with access

to technology. I do think for cohere, you know,

the vision isn't to be a Canadian company,

like the vision is to be a global AI company and I,

think yes. You know, we have a headquarter in, in Toronto.

We have teams that are distributed around the world. We have a [00:27:00]
great team here in London

as well as in the US

and, and France and other places.

And so,
having that ability to deploy models that operate across the world, I think is
gonna be absolutely an important part of the, the strategy for cohere.

I think there's a great opportunity,

what it gives us to be headquartered in Canada.

is like a sensitivity to the fact that it's not always a one size fits all solution. You
know, I go back to the research we've done, we've done leading work in terms
of multilingual

model, and it

turns out it matters.

You

go to Japan, you go to Korea,

and they do want models that work well in their

language. people in the workforce are still operating in, in the language of the
country.

So having a company that, that

is attuned to that, that values, that, that internationalization of model is actually
important on the global market.

Harry: on the team building side. Obviously Canada has great talent. You
mentioned obviously some in London as well. What have been your biggest
lessons, observations on [00:28:00] team building, building in this like talent
frenzy that we're in Also, how, how do you analyze that?

Joelle: one

of the things that's.

that's

important when you're, you're building a, a team
for ai, I do think you need

people who have,

vision, who

have like a sense

of like, what can we create

just because we're in a space where there's so

much innovation that is still needed.

So

you need an ingredient of,

vision that can be 1, 2, 3 people who bring that, that ingredient of, of vision.

You

need people who have amazing,

execution muscle,

they don't care that it's their idea. They care that if the team agrees on an idea,

they are just gonna push this and get it done. They're gonna

build a system, they're gonna run the

experiments. They just have that. technical rigor to execute. And then

you need people who kind of like keep the team together.

who have like this sense of like, who needs what to operate well and who are
that social glue. humans are still social beings and that social glue in a
[00:29:00] team matters a lot. Where

I've seen it fail is to have just sort of one type of person,
inside the

team

Um, So I'm,

I'm a big believer in building teams with

with diverse

complimentary, talents.

Harry: so you can't just buy the Galactica.

Joelle: I don't think you need to. I think you, you really have to be thoughtful
about putting people in a group.

The other thing that helps a lot is

for the team to have focus. You know, if it

goes in all sorts of different.

direction, you'll lose the, that, that power that you get from, from people
working together.

So having a lot of clarity, what's the North star? What's the goal?

Where are we going?

Even if over time, that needs to change, but that level of clarity is required for
everyone to be

working in the same direction.

Harry: if you don't need to buy the galactico, why do

you have like an Andrew

Tak, a Daniel Gross and Alex Wang
and the Galactico assembling it is, is

Joelle: you do, You

do need a few

of these

like Uber [00:30:00] talents in the team. There's

a relatively, you know, short,

number of people who just understand this technology very deeply. You do
need some of this talent, and if you can afford it,

you should, you should,

get some of that talent. But you don't need all of your team. You

need, you, need like a, a, a team.

with complimentary skill as well.

Harry: Does that create a good team? Like if I gave you, you know, $10 billion
to go build a team and you could buy a couple of these luxury star players, I feel
like his top Trump's cards for like sports teams, but you can buy a couple. Does
that create a good team when one is a $3 billion person and then the rest just
average $50 million people?

Joelle: Yeah. I,

wouldn't say no. If someone offers me the, the opportunity to, to hire, there's
definitely some really talented people.

in the field

and They deserve to be fairly compensated

This technology.

is going to have pro,
make a lot

of people very

rich and have major effects in terms of society. And so, you know,

we should be rewarding [00:31:00] the, the talent. But I'd be very thoughtful
about what are the teams that I

put together and how do they work together rather than just like, hire roster of
superstars without being thoughtful, how they're gonna work together.

Harry: So you, it's so funny. So because of the impact that you can have in
these teams, actually the multi-billion dollar price tax that you see can even be
justified.

Joelle: time will

tell, I don't think it's necessarily

needed

to go at that scale, but time will tell.

Harry: If I gave you $10 billion, what would you spend it on first?

Joelle: one of the things you need is

a

balance between talent and compute.

if you have too much talent and not enough compute, you're wasting your time.

usually like in.

equ between those, those two pieces,

I think we often underestimate the importance.
of data and, data is getting more and more expensive. And so I would certainly
spend a, a good chunk of it on, uh, on data as well.

Harry: So many things to unpack there. do you [00:32:00] feel you have
sufficient compute today?

Joelle: I think we are reasonably well resourced in terms of

compute, uh, and, and, and

building the models that we want to build. Yeah.

Harry: So access is not a massive problem? Why is data becoming more
expansive?

Joelle: data comes in in different forms.

on the

One hand, the days of like having

data

labelers who can say this

is a cat and this is a dog,

or somewhat over like the easy task the AI.

can do. So we're getting in a space where we need more specialized tasks. So,
you know, imagine you're building AI for enterprise. There's a particular
business logic. You need to make sure that you're catching the errors. You're
gonna need someone with like deeper understanding of the tools. So that's more
expensive talent to come in and actually prepare the data. There's also a lot of
data that's synthetic.

data.

when you're building agents, you

need to build environments
and to build environments. You need some pretty creative folks who are going
to build you like synthetic simulators, we've seen this on the robot side for many
years,

People [00:33:00] building robot simulators.

Now you're building AI for enterprise so

you need to think of like, how are you gonna simulate these work processes in a
reasonably realistic way that the AI can train

on that

And so

that generation of environments and benchmarks and dynamic

domains, can be pretty expensive too

Harry: When you look at, the expansive data and then you said, oh, you cat dog
lamppost got these cap caps, you know, the, you click. The ones which have,
like, as a, I get them wrong, I legitimately get them wrong. I'm like,

Joelle: They're getting harder.

Harry: getting so hard.

Joelle: are, they are. It's not just

Harry: the other day I called up my CO I'm like, I've failed the Revolut. Uh,
I'm so sorry that I'll try again in half an hour.

Joelle: Please

let my

a agent answer that one for

Harry: Honestly, it was embarrassing. Um, but, um, the question that I have is
you, when you look at
Mac Core, when you look at Surge, when you look at Turing, how do you
evaluate that market, which is providing a lot of that talent?

Is that an [00:34:00] ongoing enduring market or is that just a hey, for the next
three to five years, we'll need it in the training phase of these models? But I
don't know what it looks like beyond that

Joelle: I don't think it's a phase

in the sense that

I do think this.

partnership

we'll call it, between humans and machines where human provide guidance to
machine. we're in this for a long time. What will change is the nature of

the information that the AI provides versus the information,

that the humans must provide as a compliment. some of these firms may not.

be around in five years, but this notion of having humans guide the behavior
guide and train the behavior of AI system

Harry: It, it's super interesting. I, I kind of, as an investor and, and,

one of them,

see all of them converge around like needing to do three things now. They used
to just kind of be talent acquisition. Oh, we'll get you these people. And now
they're like, we'll get you these people and we'll get you high quality data that
you can really use.

And now it's like, oh shit, we need this third pillar, which is we'll also help you
[00:35:00] implement that data into your models, do training and help you with
benchmarking and proving that it's actually viable and now they need all three.
Are you seeing that third one where it's like implementation of their data as
well?

They don't just hand it over the fence.
Joelle: There's definitely some of that that's happening. I think for me the, the
even bigger trend we're seeing is.

the moving from just labeling data to crafting environments, to produce new,
new tasks.

Harry: you said about synthetic data and that also being a very important
segment to consider. Do you get model degradation when you get this kind of.
Reinforcing loop of models learning on synthetic data, which street creates
more data for synthetic and it actually degrades, or does it improve

Joelle: It really depends how you're generating your synthetic data. So in some
domains, if you think like images, languages, like

LL m's talking to each other at some point?

you definitely

get the

degradation And that degradation is due to essentially,

like a loss of diversity of your data. So, you know, you can make an analogy,

you know,

you, you [00:36:00] take a bunch of people, put them on an island and let them
reproduce.

You know, at some point The genetic diversity is gonna keep shrinking. and so
you get a

reasonably

similar phenomenon with, uh, with models because you're not injecting
diversity

into

the data.
So for there are domains where lack of

diversity

means

you get a collapse of distribution.

there's other domains where

you don't need diversity. If you think of

like, playing chess, Plano, these kinds of games, we know exactly how to
generate board configurations.

And So we can generate

tons of synthetic data, not

endless 'cause it's a closed world, but still tons of synthetic.

data and through that learn for a long time.

Then there's domains that are sort of in between

If I think of

coding.

We can generate synthetic code. You

Take normal code,

and we know how to inject diversity into the code.

Like I can take a couple repositories, mix and match apply, an LLM to
transform it.

And so there's a way to [00:37:00] generate synthetic
data. The language is predictable enough and there's enough structure that I also
know how to inject diversity

so that you don't get that collapse.

So The hope is that, especially in these

domains, we can use a lot more synthetic data and do it

without suffering.

from the degradation of performance.

Do you

Harry: Do you worry that we are creating a world with just much worse code?
A lot of people are concerned by the quality of code that's being outputted and
actually how we're just relying on it pretty haphazardly. Do you worry about
that? Um,

Joelle: let me make an analogy in terms of like the quality

of

generation. you know,

you ask about code generation, but let me take you back to,

2015. Image generation, I dunno if you have

it in your mind, but the quality of the images that were

generated, we had image generation models in 2015. They were really bad. The
resolution was bad, the composition was bad and so on. And from 15 to about
2022 or so, we saw huge [00:38:00] progress in terms of the quality of the
image generation. So you think of

code generation, like right now, we're

in the phase we were for.
image 10 years ago.

Yes, There's a lot of bad code that's getting generated.

there's a lot of code that will get thrown away, but wait another

10 years,

And I think the quality of the code that's produced is gonna be excellent.

Harry: What will the developer world look like in 10 years when that is the
case?

Joelle: if I carry my analogy further,

I

dunno if it's a reassuring scenario. 'cause if we look at where we are today in
terms of

image generation, there's just like, the

volume of image, getting

generated is huge.

what matters now is sort of

you know, picking the,

picking the quality out of the volume.

And so I fast forward 10 years on code generation when the, we have the ability
to generate a ton of code, to do a ton of different things. We're going to need
some selection mechanism to decide what code we actually want when there's
actually value. And so that's gonna come, there's still going to be some sort
[00:39:00] of editorial design choice. Someone needs to decide like,

of All the code we can generate. What's the code?
we want to generate? What do we need to be running in terms of our digital
world?

Harry: So it's like a chief curation artist

Joelle: Yes,

Harry: within each

Joelle: Curation

doesn't go away.

Curation verification. This is work that doesn't go away.

Harry: does the structure of teams fundamentally change then you, you, it's
funny kind of playing that back to you and then also playing back to what you
said earlier about the human and if that is the case. There's not much of a
partnership is there between human and ai.

It's a chief curation person sitting on top of a huge amount of artificially created
code.

Joelle: Well, that's your 10 x productivity improvement there.

It's,

Harry: but it remove you tick in that box, but it removes the human element
there. Um,

Joelle: you still, you still need people with, with intent. That's one thing that,
you know, you need to decide what you want to build and what purpose does it
serve. And so that that intent is still there, that that role of, of critique [00:40:00]
is still there. Um, so

the team. Composition does change significantly.

once you suddenly have, you know,

Designers who
in their hand have amazing tools to go directly from the ideas in their head to
the, to the digital world.

maybe eventually to the physical world. That equation definitely changes,

Harry: Do you think prompts and the way that we interact today with prompts
and with chat largely is like the enduring interface for human engagement with
ai.

Joelle: it's

Awfully limited.

and, prompts can mean in a few different things, but, but the idea of like

typing in a box, that to me is very

limited and we're gonna break out of that box already. We're seeing a lot of,

uh, cases where voice is a lot more natural as an interface. I do expect we'll see,
you know, gesture, eye gaze, these kinds of much more multimodal ways to
interact with the, with the ai, rather than just stick in that, in, in, in that prompt
box.

but language is

incredibly powerful. So if you think of [00:41:00] prompt as being more

language as a way to.

express ideas and communicate with a machine, that's a powerful paradigm. I
mean, as humans, we, so much of our communication is based on language. I
don't think we're gonna move away from that it encodes information.

You know, language words are symbols?

that encode so much information, so efficiently, and so I don't think we're we're
close to getting away from that.

Harry: When you think about what you did believe that you now have changed
your mind on what's most prescient,
Joelle: Oh. I'm a

scientist that is happy to be

proven wrong anytime, as long as there's new evidence. I'm genuinely

curious to know. Other scientists are much more like

holding on to very, very strong.

conviction. I have weak conviction, but

Very strong.

respect for the scientific method and, and, and rigor, experimental rigor, you
know, theoretical rigor as well. I used to be quite skeptical that neural,

networks were necessarily the ultimate solution to machine learning.

I'd seen [00:42:00] enough cycles of neural networks kind of peaking and, and,
and then, um,

being less, less useful. And I used to think every time you change the scale of

the data.

You know, you go from hundreds of examples to thousands, thousands to
hundreds of thousands to millions of examples. Every time you change the size
paradigm that neural networks

were the First thing we tried

' cause they're a universal function, approximator, and then something else
comes out that was better and

that was true for the previous generations. You know, some of you may
remember SVMs

as like being better than.
the neural networks in, in early two thousands. I seem to be quite wrong on this
one, like, neural nets seem to be here to stay.

Um, And the ability to do back propagation and

gradient descent and all that seems to be a really powerful

way to learn.

Harry: What does everyone else believe quite strongly that you think they are
quite wrong on?

Joelle: I don't have a lot of patience as a scientist for people who are predicting
sort of the, the [00:43:00] extremist scenarios, whether it is, The catastrophic
risks of AI

or whether it's the.

you know, winner takes all, you know, AI becomes our overlord kind of
scenario. I don't have a lot of patience for that. I wouldn't say it's necessarily
widespread, but I just, lack scientific rigor to, to analyze these kinds of scenario.

I'm, I'm much more pragmatic, grounded, I'm

pro innovation.

I'm excited to see where, where AI is going and the problems it can solve. but
I'm not

So interested.

in just going around and, you know, making up science fiction scenarios.

Harry: you've been on the most incredible, you said there about kind image
generation 2015 and partly how much it's improved. we are seeing this kind of
unbelievable capital supply go into the space in a way that we haven't seen,
obviously

for many, many years.
Is it a good bubble where we are getting incredible improvements and it's
fundamentally advancing technology? Or is it a bad bubble where costs are
becoming too exorbitant? Teams [00:44:00] are too impossible to build
computers. Too difficult. Is it a good bubble or a bad bubble?

Joelle: I think about it as a bubble with bigger variants. It's like,

You know,

the upswing is gonna be bigger and you know, there's going to be big
downswings as well.

And so there's a lot of variance into the system right now.

as long as

people have a tolerance to risk

then I think AI is a great investment.

And, we should continue to be

supporting, you know, risk,

taking, new enterprise, new ideas. There's a ton of exciting new startups being
created. We should continue to, to support them.

you just have to be tolerant to risk.

I've had some people on the show suggest that, uh, evals are

Harry: to put it delicately bullshit, uh, and that they don't actually mean
anything anymore. And like, you know, humanity's last test, like what does that
really even mean?

Uh, and we have these new tests that come out of it. What is this? And
leaderboards, what is this? Is that fair? Or do you think they actually serve a
very effective [00:45:00] utility to the ecosystem?

Joelle: I do think they, they are, um,
really

good indicators. So I think you do need to take evaluation seriously in terms of
knowledge, but you shouldn't take

them seriously in terms

of the ultimate goals.

So

you know,

valuation and there's lots of different,

benchmarks and so on. You

have to

decide like what type of

models or model are you

building? What's the characteristics of your system?

And then think of Evaluations as like unit test for the

performance of your system. And software engineers will

know what that is, right? Like you run through that evaluation and that gives
you like a signal

of how the system is doing in a particular dimension. But as we're building
systems that are more and more

General do very specific

tasks, you don't optimize for these, we build AI systems that go into enterprise,

None of our clients ask about like, are you able to win the math Olympiad with
this model? That's
not what they care about. They care about bringing value to their business.

Now

We're curious to know how well we do on [00:46:00] math problems because it
can be predictive of behavior on other things, but you don't obsess over a
specific. Benchmarks. You kind of look at the ROI in terms of what you're
trying to build.

Harry: we mentioned there about kind of access for

enterprises. Enterprises have money and that's a great luxury. In a lot of cases,
research institutes, universities often don't. With the kind of bubble like
tendencies, people with money are able to afford to compute the talent. Are we
seeing this kind of lack of access or democratization for great institutions that
are educational maybe who now can't afford to compete in this new world?

Joelle: certainly

A lot of universities have a lot less resources than, than companies today. That's
not completely new. when I joined Meta in 2017, um,

one of the reasons I

did that is because I, I could

already see the.

the disparity in terms of access to compute and I was really curious to see how
you could do research with a lot more, compute.

But you know, there's still amazing research that's being

done in, in universities. You go to the major [00:47:00] international
conferences, neuros, ICML and others, and often the best paper awards are
actually won

by researchers out,

of universities.
there's a lot of good ideas that you need to,

test out at small scale. and in a

university you have a lot more freedom,

to pick

pretty risky

ideas,

at a small scale,

but still, you know,

no one's asking you to,

to justify your, your,

your research in, in ways that that often happens in companies. So I

think they have, they play different roles in the ecosystem.

and what's actually especially good is talent flows between, between them,
university students come in, do internships, take jobs at companies. We've also
seen a movement of people coming out of these large companies, going back to
university, teaching, sharing with the next generation what they've learned,

Harry: How important is it to have seen success and how valuable that makes
you? When you look at people like, uh, Amira raising 2 billion at a 10 billion.
It's like, well, no one's seen the success that she's seen with OpenAI, so it's
valid. Help [00:48:00] me out as an investor, is it that valid to place that much
of a premium on access to seeing it at that level that we are or is that slightly
overpricing it?

Joelle: I think

in many cases, you know, when it comes to

deciding where
to invest, very early on, when you don't have tangible, tangible.

information, I mean, you look at people's track record and

There's a part of

that

that maybe like

you know, what have they learned in terms,

of the, the core recipe.

But

the other thing is also the achievement.

of Having put together amazing,

teams who are building world class models. And

there's a lot of

subtlety

to that.

and

So I think

you, know, both of these ingredients are, are important to consider. I don't,

Harry: If you were investing today and you are joining my team, which
category would you most like to invest in? Be it security, be it, generative ai,
compliance, you, you name it.

Joelle: Yeah.

there's a
lot of verticals, whether healthcare

scientific discovery, that I think have incredible [00:49:00] promise where we're
gonna see real tangible progress within five years that are going to change
completely the face of what we can do. So that's probably where I'd, where I'd

push.

Harry: That's very exciting. On the healthcare front in particular,

when you think about that timeline as well, I'd love to do a quick fire round with
you if that's okay. So say a short statement, what would you most like to do, but
because of technical or financial limitations, you're not able to?

Joelle: I'm super

keen

to figure out

how we build, societies of AI agents.

We're

doing it implicitly, but how do we look at populations of AI agents interacting
together and having like a sandbox for, for doing

that,

maybe something I'll, I'll get to do, is it lack of time, resources, something else?
There's just like a ton of different things.

to do, but keen to, to see what happens there.

Harry: When you think about that ecosystem of agents, you have children.

Yes.

Joelle: And

Harry: And AI changes our relationship with other humans and
friendship and social. How does AI impact social [00:50:00] friendship
connection,

Joelle: It definitely

does. And you know, there, there's a sense that we spend a lot of our time in the
digital world

and for

some folks, you know, I look two of my

children, they spend a lot of time in the digital world playing

online games with their friends. It's still very social.

It's,

There must be some ai, there's the digital platform, but

it's still a very social experience.

others have more individual.

experience. There's

Definitely a shift.

of this time we spent, uh, towards that platform where we

go look for that, for that.

social element,

Harry: Knowing what, you know, what do you not let your children do?

Joelle: ah,

Eat too much sugar

Harry: to Totally. That's so that's their like
physical diet. Completely agree with that. Yeah. Is there a technical diet

Joelle: I spend some time discussing like settings. I mean, like, you get an
Instagram account, great. You can have an Instagram account, but

like what are the settings on that account? Making sure they understand

I mean,

Harry: as a fun conversation with mom, isn't it? We're gonna discuss
[00:51:00] settings. Oh God, that was

Joelle: I know that was

not a popular one,

Harry: did they? Listen?

Joelle: the

thing with

children

is you.

don't know till later.

Harry: Do you limit screen time?

Joelle: I

spent

a

lot of energy, especially in their younger years.

limiting screen time. My kids did not have a cell phone till they were 14, 15.

Harry: Did you see adolescence?
Joelle: have not.

I

Harry: Watch it. Basically, a little boy goes up to his bedroom and, um, gets
lost down kind of rabbit holes of TikTok and Reddit and it does not turn out
well. I have,

Joelle: I have, I've heard about I just haven't had time to, to sit down

Harry: Do you worry about the, the loneliness pandemic and then also just the
mental health crisis that we have,

Joelle: Uh, I do worry a lot in general about

making sure that

that people are

healthy mentally,

we have to be careful about taking shortcuts and saying, you know,

because suddenly

you know, we have certain platforms, we have AI and so on that is causing.

that mental illness.

You know, there are a

Number of people who

are suffering and

[00:52:00] they deserve

to,
to have good answers to the situation. And they deserve to. We deserve to find
real solutions to that. And there's a lot of people looking for shortcuts and short
answers, but I think more research into that is definitely warranted.

Harry: What's your biggest lesson from working with Zuck?

Joelle: he is incredibly deep into understanding the work

like he

does not coast. You know, when he

started getting into ai, just the

the depth of the question that

he'd ask, he just gets really interested in the topic and goes super deep and that

then just informs

everything he does after. So you can have the most amazing team, but like as a
leader, you need to go deep and understand the work.

Harry: did you see him change?

Joelle: as anyone gets more knowledgeable about a topic

you get more decisive. There's a phase where you're really learning and trying
to to understand, and there's a phase where you understand a lot of things and
then you make your decisions

faster, so

certainly that

that shift happened.

Harry: What [00:53:00] one AI buzzword would you ban if you had a magic
wand?

Joelle: existential risk.
Harry: why?

Joelle: Because it just makes people afraid.

and it's not out of fear that we make our best work and we take good decisions.

Harry: Do you find the cost of talent exorbitant?

Joelle: talent is costly.

Talented people deserve

to be to be paid well? And again, you know, someone coming in just

because of money, rarely is going to be

the right person, But you do need to

compensate people fairly,

Harry: final one. What are you most excited for?

We, you don't like the existential risk? I don't like that. The doomsday planning.
When you think about the positivity that can come, what are you most excited
for when you look forward to the next three to five years?

Joelle: I do think some

of the work in terms of.

AI for, A scientific discovery is going to be pretty fascinating to see. just in
terms of the doors, it's gonna open up the ability to explore, combinatorial space
of, of solutions.

So

I'm [00:54:00] curious about that. and then I'm

super curious to see, how can we actually make our models more efficient?
There's larger and larger and larger models. No one wants to run these models.
You know, I spent a lot of my career
building, um, open source models

and I'll give you one example.

You know, we were in, in the frenzy of

large language models

and I pulled the stats on, you know, most downloaded models of last month.

We had a model like.

Roberta from 2019, small language model was getting 20 million downloads a
month. People want efficient models that they can use, that they can run. So I'm
also super keen to see what we're going to be able to do at the scale that runs on
like one or two GPUs.

Harry: Final. Final one you said there about kind of open, um, we seem to like
be reverting to a closed world now. Is that the world with which we should
predict and plan on,

Joelle: That's a deep mistake. I mean, I will continue to believe that

especially

for research the ideas need to circulate,

and this

thought that you [00:55:00] can just

like close

this down is, was absolutely false.

I mean,

people are

Harry: we are, do you not think we are then moving into that world like
everyone seems to be closing systems, closing access
Joelle: there are

definitely a number of places people that are closing down access

I don't think that is going to,

to be effective ideas will circulate.

And I also think it's a mistake from a point of view of fostering innovation.

Harry: This has been such a joy. I've learned so much from this conversation.
Thank you so much for putting up with my very basic questions, but I've loved
having you on the show.

Joelle: My pleasure. Thank you.

Harry: But before we leave you today, are you drowning in AI tools Chat, GPT
for writing, notion for docs, Gmail for email, slack for comms, and you are
constantly copy pasting between them all losing context and losing time. This is
the AI productivity tax and it's killing your. At 20 vc, we're all about speed of
execution, and superhuman is the AI [00:56:00] productivity suite that gives
you superpowers everywhere you work.

With the intelligence of Grammarly Mail and coder built in, you can get things
done faster and collaborate seamlessly. Finally. AI that works where you work.
However you work. Superhuman gets you from day one with zero learning
curve, and it is personalized to sound like you at your best, not like everyone
else using generic ai.

Get AI that works where you work. Unlock your superhuman potential. Learn
more at superhuman.com/podcast. That's superhuman.com/podcast. And once
you are moving faster with superhuman, make sure you are moving safely with
Vanta. Customer trust can make or break your business. And the more your
business grows, the more complex your security and compliance tools get.

It can turn into chaos. And chaos isn't a security strategy. That's where Vanta
comes in. Think of Vanta as you are always on AI powered security. X. But
who scales [00:57:00] with you? Vanta automates compliance, continuously
monitors your controls and gives you a single source of truth for compliance
and risk. So whether you are a fast growing startup like Cursor or an enterprise
like Snowflake, Vanta fits easily into your existing workflows so you can keep
growing a company your customers can trust.
My listeners can get $1,000 off Vanta by going to Vanta. Dot com slash two
zero vc. That's VANT a.com/twenty VC two zero VC for $1,000 off Vanta.

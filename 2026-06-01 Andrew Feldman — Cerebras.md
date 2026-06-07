---
type: 20vc-episode
guest: "Andrew Feldman"
company: "Cerebras"
role: "Founder & CEO"
episode_type: interview
date: 2026-06-01
youtube: "https://www.youtube.com/watch?v=6EOwSXE3Xws"
transcript: "https://20vc.substack.com/api/v1/file/482abb09-5e37-4422-a837-e6ccd0d472d3.pdf"
newsletter: "https://20vc.substack.com/p/20vc-newsletter-1st-june-2026"
tags:
  - 20vc
  - ai
  - china
  - defense
  - infrastructure
  - saas
---

# Andrew Feldman — Cerebras

> Founder & CEO @ Cerebras | 20VC Interview | 2026-06-01

## Key Takeaways

### 1. Why We Are Not in an Infrastructure Bubble and It Is Just the Start
Unlike past tech bubbles that overbuilt ahead of demand, the AI infrastructure rollout is running significantly behind immediate market needs . Major chip makers face massive multi-billion-dollar backlogs because data centers cannot be built fast enough to keep pace with the exploding, real-world user demand happening today.

### 2. Anthropic Did Not Get a Good Deal With Elon. They Got a Deal That Was Available.
Founders are often forced to take action on what is available in the market rather than what is ideal. Anthropic’s deal with Elon Musk required them to buy “down rev gear”, older H100 chips rather than cutting-edge B200s, leaving them a generation and a half to two generations behind the absolute leading edge.

### 3. Why Jensen and NVIDIA Are Wrong to Sell Chips to China
Widespread security consensus confirms that selling leading-edge tech to China means their military and government will inevitably leverage it to compete with Western industry . As an industrial adversary driving down global costs in vital sectors like solar and automotive, American chip companies should be completely comfortable selling fewer chips to protect strategic boundaries.

### 4. What the F**k Is Going on With the Price of Memory and Why Is It a Problem?
Exploding AI demand makes High Bandwidth Memory (HBM) the most critical bottleneck right after fab space. Because only three manufacturers produce this specialized memory and cannot keep up, prices have skyrocketed, allowing suppliers to command software-like 80-85% gross margins on hardware fabrication.

### 5. Are Google Best Positioned to Produce the Lowest Cost Tokens and What Challenges Do They Face?
Owning the full stack from data centers to chips gives hyperscalers an immense cost advantage over standard clouds paying high hardware margins. However, the historical downside is that your market is constrained strictly by your own internal demand, meaning hardware innovators must sell externally to maximize volume and lower unit costs.

### 6. My Biggest Advice to Entrepreneurs Scaling Their Business
Your initial focus must be entirely on winning just one customer. Landing that first anchor client forces your company to build the necessary operational muscle, adjust your supply chain, and learn how to properly service a massive organization so you have the capability to keep the next ones happy.

---

## Links
- 🎬 [Watch on YouTube](https://www.youtube.com/watch?v=6EOwSXE3Xws)
- 📄 [Full Transcript (PDF)](https://20vc.substack.com/api/v1/file/482abb09-5e37-4422-a837-e6ccd0d472d3.pdf)
- 📰 [Newsletter](https://20vc.substack.com/p/20vc-newsletter-1st-june-2026)

---

## Full Transcript

[00:00:00] We can't build data centres fast enough to keep up with demand.

We have a $25 billion backlog.

if demand stays high, we are gonna continue to see memory shortages for at
least the next several years.

I think it has been NVIDIA's strategy to try and create competitors for the
traditional hyperscalers.

I think they have funded and backstopped and over allocated to the neo clouds.
they have created a dependence, which is probably not healthy.

So over time, of our industry is a massive reduction in the cost per unit
compute.

for hard problems, there is no upper bound how much faster you wanna be

This is 20 VC with me, Harry Stebbings, and I'm so excited to welcome a dear
friend Andrew Feldman, found and see at cereus. Now, this show just makes me
incredibly happy and proud to do because this is a true testament of resilience,
of grit, of building really hard things. And last week, cereus went public, the
largest semiconductor IPO ever.

The price went from [00:01:00] $185 to $311. They got over five and a half
billion dollars. It was an incredible day for an incredible team. Today, we deep
dive on the future of chips, the future of US China relations, the future of data
centres and energy. This was an incredibly wide ranging conversation, and I just
wanna say a huge thank you to Andrew for being a great friend to me over the
years and for being a fantastic advisor to 20 vc.

Before we dive into the show today, you have the idea, but often with AI tools,
you hit a wall. Well, base 44 is where that friction disappears. Turning how you
talk into how you build full stack web and mobile apps, sites, autonomous super
agents, all built in minutes, not weekend spent on damn configuration base 44
ships it all out of the box, the backend, the database, the authentication, and the
hosting.

It handles the heavy lifting so you can just stay in the flow. It doesn't just
replace the busy work it multiplies you. It makes you so much more capable and
effective version of yourself. In this [00:02:00] market, being fast is the
baseline, but to win you gotta be first and base. 44 is that edge. It's the move
that lets you skip the troubleshooting and get straight to the breakthrough.

Launch your next big thing@basefortyfour.com. That's base four four.com.
After Base 44 helps you launch Corgi helps you cover what comes next. My
word, what an arresting first line. Get your ass covered with Corgi Insurance
and I'll tell you why. If you are running a business right now, you already know
this pain all too well.

Getting insurance, it's really slow, it's confusing. And my word, it's full of
paperwork. Well, that's exactly why Corgi is here to change the game. Corgi is
the first and only insurance carrier designed specifically for tech companies
allowing you to get covered in minutes instead of days. Corgi provides essential
coverages for all growth stages such as D and o, e, and O, liability, cyber,
commercial, general liability and more.

Get your ass covered. I love the way we say ass with Corgi Insurance alongside
[00:03:00] thousands of other startups@corgi.com slash two zero VC today.
That's corgi.com/two zero vc. You won't regret it. While Corgi handles the
coverage, cheering handles the talent, frontier Labs keep facing the same
limitation.

Models perform well on benchmarks, but they fall short. Once they enter real
coding tasks, real tools and real workflows. That disconnect between synthetic
evaluation and actual system behaviour is now a core block off for Argentic
models. That's why Nvidia and Anthropic, Salesforce, Gemini, and other
leading lab partners partner with Turing.

Turing is the research accelerator focused on post-training reliability. They
build realistic RL environments. Next generation data quality systems built
from real world operational traces and coding data sets that stress models under
conditions where failures matter state changes, workflow branching, brittle tool
calls, and the coding errors that break RL agents but never appear in benchmark
reports.

In reality, a model may [00:04:00] demonstrate correct reasoning in your
evaluation setup, yet still select the wrong parameter or mishandle a code
update in a realistic interface. Turing makes that failure visible and gives teams
the signal they need to fix it. For labs advancing ag agentic systems, Turing
provides the structure required to understand why these failures occur.
To find out how, visit turing.com/two zero vc. That's TURI g.com/two zero vc.
You have now arrived at your destination.

Andrew. Dude, it is so lovely to have you on the show. I have to say I was, I
was quite emotional last week when I saw the IPO 'cause you are one of the
kindest, greatest people. I, I love getting to know you. I so appreciate our
relationship and so to see that culminate last week with the IPO, it was really
special.

So congratulations for last week, dude.

Thank you so much. Those were really kind words, and was a really exciting
day for, for, for the company and the team and, the people who'd, who'd
believed in us and, and who backed us for, for a [00:05:00] decade. it was great.
Thank you for, for, for saying those nice things.

Not at all. And I was, I was thinking like, in terms of this conversation, how I
wanted to structure it. And I, I always get back when I have amazing people like
you on the show, which is Eleanor Roosevelt's kind of statement of, not very
intelligent people. Discuss other people, mediocre people, kind of discuss
current events, and then intelligent people discuss the future and ideas. so I
thought I'll grapple with my own ideas and wrestle with your incredible brain to
help me understand where we're at and where we're going

I wanna start with, on the one hand, we look at the in landscape, then it's like,
oh my gosh, an AI infrastructure bubble. And then on the other hand, we look
at, you know, Janssen Wang last night. He comes out and says, we're gonna be
spending three to 4 trillion on AI infrastructure by 2030. How should I balance
the, oh, there's an AI infrastructure bubble with this appreciation of three to $4
trillion spent by 2030.

I've been thinking a lot about this. I think when you look at other bubbles and
you look at bubbles in the [00:06:00] past, and I, I was in one in, in the late
nineties when we built out a, an enormous amount of fibre optics. And you
sometimes have economists who, who maybe think it's relevant to look at
1880s, the building out of a rail.

I'm not sure that's relevant. But, what I see is that there was a pension to believe
that if we built it, they would come. Right. The infrastructure build out was way
ahead of demand. And that was true in railroads. was true in, fibre optic cabling.
And in a strange way, that is the exact opposite of where we are with ai.
The infrastructure build out is behind demand. We can't build data centres fast
enough to keep up with demand. We have a $25 billion backlog. Nvidia has a
backlog. a MD has a backlog. Others have backlogs. they have backlogs
because we can't get data centres built fast enough. And it's not that we're
building on the come, we're not building a head of demand.

We're building behind demand. [00:07:00] that is a very different observation
than, those who say there's a bubble. I don't think they've really gotten their
head around the fact that we are trying to keep up with demand, not the other
way around. And I, I don't think that's a characteristic of a bubble when you are
trying with your infrastructure to keep up with what people want today, not in
the future today, and their demands are growing over time.

Is it ultimately a good thing that we are meted in our ability to build out data
centres because it almost tempers the demand if we were able, and Gavin Baker
said actually kind of the delays and the permitting and the challenges that are
incurred today actually help. 'cause if you are able to have it all today, all of
demand would be met with all of supply and that would actually be a challenge.

sometimes the world is like, I was in my twenties the first time I went to Vegas
and went to the buffet, right? You, you eat so much, you feel sick for days, all
in front of you and you just gorge yourself. I, I think the market can so
sometimes be [00:08:00] that, I think Gavin is an extraordinarily thoughtful sort
of guy this.

I think we are being metered. We also know that the reason you put metres on a
freeway is because it makes the, the freeway traffic smoother it avoids hiccups.
that's exactly what metering is designed to do. And so I think he used that, that
analogy extremely thoughtfully. one of the advantages that OpenAI has I think
one of Sam's brilliances was that he saw an exponential growth he saw what that
would mean in a year or two to the demand for compute.

And he wasn't afraid by it. He went out and took action and perhaps others
couldn't believe it, or they were looking at the same demand, sort of steep,
exponential growth. And we're like, well, we can't need that much. You can't
need tens of gig. That, my mind hurts if you do that. Whereas what Open Air
did is they went out and they were like, we're gonna contract for it here and
here.

We're gonna get power, we're gonna get data centres. We're gonna sign up for
hardware. And an ability to, to believe your [00:09:00] data in a exponential
growth environment, out a year or two or three I is a superpower.
Do you get rewarded for that insight? If you can just buy it from Elon now on
demand.

I don't think they can buy the same thing from Elon on demand. They bought
down rev gear.

I'm sorry. I've learned from doing this show for a long time. I can ask stupid
questions. They, they brought down rev gear. What is that?

Yeah, they bought h they, they, they got H one hundreds. They didn't get the B
two hundreds. They didn't get the most current. they are a generation and a half,
maybe two generations behind. this was not a great deal. It was a good deal for
Elon. He had them around, but they were forced to take action a deal that, I
think was, was not the ideal deal.

They wanted, it was the deal that was available.

Going back to what we said about kind of the delay in data centres and data
centres being a constraint.

 I just hear everyone say, well, memory, memory is the shortage to Harry, and
that's why we're seeing it increasing cost, you know, for five x in certain

cases

Is that true? How should

we think about memory being the [00:10:00] shortage as well?

Well look, what's happening here is there is such extraordinary growth in
demand that it is putting pressure on all parts of the supply chain memory.
TSMC, is right after Fab Space, memory is number two item that's needed. And
what's happened is there are only three companies that make the memories GPU
use.

We don't use that memory, but that HBM is made by Samsung and Micron and
Hynek they couldn't keep up. And so the prices shut through the roof. I mean,
micron producing numbers where they have 80, 85% gross margins. I mean,
they're getting software gross margins on making memory. yeah, I, I think it's
extraordinary.
that is a limitation for all GPUs, but not us. We don't use it.

 again, going back to my idea of what the future looks like, what should one
expect from that? Does it ease? Does it ease over time? What happens to the
cost?

the challenge here is that, that these are extremely, lumpy items, right? You,
you, you [00:11:00] can't just add a little bit of manufacturing capacity at a fab.
you, you have to build a fab for $40 billion and takes five years to build. if you
see demand explode, you cannot respond quickly.

All you can do is fill your factory. Once your factory's filled, you gotta build
another factory, right? It's a, a, a step function in your ability to meet that
demand. And the step is huge and takes years. so if demand stays high, we are
gonna continue to see memory shortages for at least the next several years.

You think we will see a peaking of demand? You've seen so many different

not if AI continues to improve in usefulness. I mean, what, what's happened
here I and this is something that, that I have, I haven't heard others to sort of talk
about, is that somewhere in 2025, the models got smart enough to be really
useful. Before that area, these were sort of, sort of a novelty.

AI was like, cool, and then nobody used it. Remember, we, we make AI with
training and we use it with inference. And so once the, the ai we [00:12:00]
made 20, 25 ish, got smart, we began using it. And this explosion in demand
that Janssen described and that we very much agree with is happening.

That's because people are using it day and they're using it on more and more
problems. They're using it on harder problems. And it is sweeping through
different demographic groups. It's not just 28 year olds in Silicon Valley. 85-
year-old father. right, my 11-year-old niece.

It is, right. It is sweeping through demographic groups and they're using it all
the time. that is what's driving this demand. if we continue find ways to make
the Ai, the frontier models smarter and more useful, we'll keep using it. The
demand will continue to, con on this sort of exponential curve.

You, you've compared past cycles before. In this conversation, Sarah Fry said
about, cloud providers can be, similar and to some perspective to what we're
seeing today in terms of frontier models. And she said that last night. To what
extent do you think you see the [00:13:00] commoditization there and they
essentially become utilities versus differentiated providers with meaningful
moats.

I think it has been NVIDIA's strategy to try and create competitors for the
traditional hyperscalers. I think that has been a strategy of theirs. I think they
have funded and backstopped and over allocated to the neo clouds. they have
created a dependence, which is probably not healthy.

the truth is, is that what, what AWS and Azure offer extremely useful for most
enterprises. They offer credibility and legitimacy. They offer security. They
offer layers of different software for different parts of your organisation. If
you'd like to enter in the AWS world, you can enter with Bedrock, you can use
tools like SageMaker.

You, you have a collection of different ways to, enter and you can store your
data there. You have your S3 instances. I mean, you can have an entire offering.
I think that is really valuable to a segment of the market. I think there might be
other segments of the [00:14:00] market.

They're like, gimme cheap compute. don't care about anything else. in that case,
your strength as a hyperscaler becomes your weakness. You have the security,
you have the other layers of software, and you have some of the costs that are
associated with that. And if people don't walk that if you don't care about leather
seats, And their leather seats in the truck, there's extra cost in the truck. And
when you buy the truck, find somebody who's got a truck that's got Naga hide
seats, our business just 'cause it's wrapped up in, technology's no different than
any other business.

it's segmented There's value. That value comes at a cost. You have to make that
value. The hyperscalers make the value. They make the value through software,
through security, through having rules about their data centres, about the
security, physical security, the various security checks they put in.

Those are enormously valuable, to most parts of the market. But not all.

You said about the costs there. When we look forward, how do the costs of your
business change significantly over time? We, we spoke about the cost of
memory going up five x. If we look at the [00:15:00] cogs in five years time,
how do you think they will look? Most significantly different?

Well, the, the increase in memory has been very good for us because don't
suffer it. Right? This has given us opportunity, we use sram and there's no
shortage of sram. the cost of SRAM hasn't changed. and, you know, no SRAM
maker 'cause TSMC etches it into your chip while they're making the logic,
there are no extra margins to pay the HBM maker.

And so, we have been advantaged in this environment. We have been
advantaged by the fact that there are constraints on COOs. At TSMC, don't use
COOs. We are advantaged by the fact that we're at five nanometer and the three
nanometer node is the most oversubscribed. our supply chain is advantaged on
these dimensions.

and others are paying the price. The, the price of, of GPUs has gone through the
roof.

And so to my question on cogs, do we see like a plateauing of cogs in terms of
it can't get cheaper and this is the stable state. Do we see a [00:16:00]
meaningful reduction?

I think what what happens over time, Harry, is, all of us, we, improve our
designs. designs deliver more tokens per unit time. They deliver faster tokens.
we are 15 x faster because architectural reasons we will continue to, to improve
over time. Nvidia, they'll continue to improve over time.

I believe the gap will widen between our performance their performance. But all
of us, the whole industry, us Nvidia, a MD Qualcomm arm, everybody's chips
will be better in three or four years than they are today. They will produce more
per unit power and they'll produce more per dollar cost.

So over time, of our industry is a massive reduction in the cost per unit
compute.

Was chatting to a friend who is, is phenomenal mind, and he said that Google
will become the lowest cost producer of tokens because they own the full stack
from TPUs to data centres, networking, power procurement. Do you [00:17:00]
think that's right, that that full stack ownership will lead to their highest margin,
lowest cost stability.

there are, pros and cons of that strategy, the pro is you have everything from the
ground, Land all the way up to tokens, The downside you can only sell your
TPU to yourself. And historically volume mattered a lot. And so your market is
constrained by your own demand. Whereas if you were able to sell to the whole
market, you might have more, more demand and be able to drive down the cost.
It's an open question. Google is threatening that argument. I think your friend's
argument is reasonable. but there has historically been a, a challenge if you only
have one customer yourself for your hardware that has historically limited the
size of the opportunity landscape for you.

You think they should sell to external customers?

I think you are already seeing them step outside of their own data centres for
this exact [00:18:00] reason. What it says in your friends' construction is our
ability to sell hardware is constrained by our ability to build data centres.

one can imagine a world where you don't want that constraint. would like to be
able to sell hardware to anybody's data centre. these arguments are extremely
complicated. rarely unfold in a simple form. but it is true that when Google or
when Cereus puts our equipment in our own data centre, have a, a significant
advantage over Neo Cloud because neo clouds are buying hardware gross
margins of 70, 80% for Nvidia.

To the hardware in those data centres, and then they have to make their margin.
That's not what Google's doing. not what we're doing.

does that mean they're dramatically overvalued when you look at a NES or a
Cool Weave or any of the others like.

Look, I think Core Weave has been an extraordinarily innovative company. I
think they've solved, a, a series of, of financial challenges with really innovative
sort of financial engineering. They were the [00:19:00] first to use debt. I, a
very innovative way. They get enormous credit for that. They have been
extremely good at sort of rapid deployment, which itself is a really important
skill in, in this environment.

I don't know about the others, but all of us have challenges as our business
grows. think they have produced really interesting things through creativity
now. It's, it's different creativity than, than, than, than what I have. but, they've
gotten paid for real innovation in financial, thinking.

Speaking of real innovation, I saw the post about you running Kim EK 2.6, 6.7
x faster than the next fastest GPU Cloud.

We, we posted it while one bozo at an analyst firm was on TV saying we
couldn't do it. I mean, if ever there, there, there was a example of being
empirically proven dead wrong have these numbers posted while you are on TV
saying they can [00:20:00] never do it.

It was perfect. I enjoyed that. a collector of examples of people being dead
wrong. Uh,

my wife has a list of when I'm dead wrong, so I, I've sort of embraced this and
collect it.

You should be a venture investor, my friend. With a portfolio of 30, you'll be
dead wrong a lot.

You have, if you're lucky, 80% of your portfolio where you were dead wrong

You should do if you're doing it right.

Yeah, I agree with that. How important was that for you, and is there a stage
where actually it doesn't matter being that increment more important, like 6.7
times? This is so much more important. It's not

20% more important.

That's right. I think, for hard problems, there is no upper bound how much faster
you wanna be, nor the value of speed. I think that if in three minutes we can
solve problems that take others 20 minutes, then think of all the extra problems
we get solved.

think of if I'm your competitor and I'm solving your hard problems and three
minutes and you're taking 20, imagine over a day or a [00:21:00] week, I mean,
you get smoked, you'll be smoked in this example. that is the way this is going.
speed is of the essence. and it's true in coating.

It's true in e agentic flows. It's true in every part, of the AI landscape. I mean,
lemme just ask you this question. How big is the market for slow search? Really
how? How is zero? How big is the market for dial up for slow internet, right?
How much would I have to pay you? Let's try turn it around and say there's a
negative market here.

If I gave you a thousand dollars a month to have slow internet in your home,
you wouldn't take it a thousand dollars a month, That's how it is to engage with
an important technology. Slowly.
Why do we believe that inference will be any different?

I am kind of pushing them. When you power codex and you are able to be so
much faster if you are claw code, are you not like, ah, bugger.

They are. I think you have to be. We have to be.

Are you able to settle to them also? Again, please tell me, start off.Oh, no, no,
no. Look, right now we are digesting one of the [00:22:00] largest deals in the
history of Silicon Valley, right?

like, for fuck sake, Harry, gimme a break. I've just signed a $20 billion deal.
You want more?

You know, while we were on the road, some investors would ask, they say, oh,
you're heavily concentrated. You have a big portion of your business with
OpenAI. And, and we say, I talked to you a year ago when I had a billion dollar
deal with G 42, and you said, you're heavily concentrated. You have a billion
dollar deal with said, I come back to you in a year with a 20 plus billion dollar
deal, and you tell me the same thing

But with a different customer as well.

with a different customer.

With a different customer. And I, I tell everybody that the, the way you get
good and the way you have succeed with many customers of size is first you
win one. the way to catch big customers is first catch one and learn. Build the
muscle, change your supply chain. Learn how to work with a large customer.

Then you're in a position when the next one comes to have a chance to win, and
what's more chance to keep them happy once you won. And then once you have
[00:23:00] that muscle, you're in a position to go out and win the next.

It is a huge deal.

What are the biggest challenges in fulfilling it with the greatest of respect? You
go to sleep at night going, whoa, that is quite a lot.

Look, I, I think, what has happened, Sam said this, he said, the first time people
used G-G-G-P-T, I think it was what, four something. They said, oh, this is
amazing. And the next day they're like, and come, it's not faster. the rate at
which you get accustomed to something and then want better is amazing in our
industry.

And it used to be the case that 20 megawatts was a lot, then a hundred
megawatts was a lot, then a gigawatt was a lot. And now we're running around
looking for gigawatt facilities. that's, in any other time, 750 megawatts would've
been a mind boggling amount. And now we're like, yeah, we got that right.

I, it it is the, the, change in mentality over the last year or two for everybody in
our industry has been sort of extraordinary. years ago, if you'd have [00:24:00]
said, we're engaged in a multi gigawatt build out, or you think about what Cruso
is doing or think about some of the other cool companies, what, SoftBank
Power is doing, what some of these groups are doing.

And you say, delusional five years ago. And right now it's like, oh, another one.
Yeah, that makes sense. I mean, we should try and get our UAE Stargate at five
gig goes, oh yeah, yeah, no problem. That seems reasonable. That's what's
happened. It's this extraordinary sort of change in thinking.

If we are nonchalant to multi gigawatt build outs

today, what are we in five years time?

It's difficult to imagine. And by the way, that that is exactly where, I think Sam
is the best in the world. Maybe Elon is where everybody else's brain shuts
down, right? When you're trying to think about a hundred gigawatts or 500
gigawatts, guys, they have sort of this ability to not be constrained by the way
the world has always been, and that is [00:25:00] such an extraordinary power.

When you have such scale as the multi gigawatt, you mentioned that the 500
gigawatt, does energy not just become the core crux and bottleneck that enables
winners and losers?

I certainly think that, people like Sam and Elon and others have said that's what
they believe, that at the end we're in the business of turning electricity into
intelligence therefore the limiting factor of electricity. I don't know if I agree
with that, but that is certainly a very reasonable view from, from where we are.

the, bear case against that? What's the alternative argument? It doesn't have to
be yours, but how?
Oh no. That, that you bump into something else. that what happens in fact is our
models can't getting smarter. that you hit something that has an assumption built
in that the models keep getting smarter and you keep feeding them more energy.
And at the end of the day, the models are either smart enough or keep getting
smarter so that it makes sense to keep feeding them energy.

that might be true. I don't know.

Do you think we'll be able to build out data centres in the way that we need to
and build out [00:26:00] capacity in the way that we need to? When we see that
40 out of a hundred data centres are now not being built out, even post-approval
because of local municipalities permitting dis like

disruption I

AI is not popular.

Harry, I think it's hilarious. People say, oh my God, the data centres are late. Oh
my God. There are delays, have you built a kitchen? Your contractor was late,
right? Pick a little tiny project in your home, was it built on time and on budget?
No. Now, imagine building, Something the size of 50 football fields and
requiring interaction with local municipalities and, and power companies and
regulated industries. these things aren't gonna be delivered on time historically,
people's mind explodes and they never think about their own experience in their
own homes.

Does your contractor show up every day? No. Does he do exactly what he says
he is gonna do rarely, Do the materials, the tiles, or whatever you, you selected
for your home, Do they sometimes delayed? Yes. All that same thing happens
when you build a data [00:27:00] centre, generators, sometimes they're late,
sometimes they're fall off a truck.

Literally, they fall off a truck and the damage is done to them. Are the
transformers late? Sometimes the transformers, I mean, everybody suddenly
sort of throws their arms up and says, oh, everything's late, or they have to deal
with localities. Anybody who's built anything big knows this is par for the
course.

This is what building is.

So you are not concerned then about bluntly local neighbourhoods, seeing data
centres as

a symbol

of life.

the following, I think our industry did a shitty job of engaging the community
properly. And, I think Brad Smith put out a post a while ago that should have
been the way we all work from the get-go, And it was, be clean, make jobs, they
can be good for communities.

We can do this thoughtfully, These create thousands of local jobs, and
thousands of local jobs means restaurants and lunches and hotels and The way
they were done, was, I dunno if sneaky is the right word, but sort of shielded
and, [00:28:00] and wasn't open and they weren't good neighbours.

Now there is no reason why we can't be good neighbours. There's no reason
why the, we, we can't add these to, to communities and, have the community
benefit from it, And we have to do some thinking, right? We have all the, the
heavy equipment out there. Build a football field for the, for the local school,
build a school at a church or a synagogue to the community, right?

We can be good neighbours at very, very low cost. We can pay our own way,
Don't try and use sort of, loopholes in the way power companies have
historically amortised the cost of new power lines over 30 years. and push that
on the community. That's bs we ought to pay our own way. We ought to look
after our neighbours.

when we do that, I think that the neighbourhoods that, that embrace this will,
will benefit enormously. But

we didn't do a great job. I mean, we didn't do a great job as an industry at all.

 it feels like kind of the cartels in Columbia though, where it's like, you know,
they built the churches and they built the schools and they had such good
businesses and such high [00:29:00] margins that they could kind of get away
with it because of that and hey, great.

I don't think that's right. I I, I think, These localities have have a resource that,
that isn't being used. They have power. many of these land is cheap because
nobody wants it. you're not going to parts of metro New York. Everybody wants
that chunk of land.
You're going to places where the, the, the, the price of land is depressed. You
are near, power resources. And my position I is that we ought to be good
neighbours and we ought to be transparent. We ought to pay our own way.
Now, thi this seems not to be very controversial in my mind. I think the best and
most concise description is, is what Microsoft has put forward.

And we should have been doing that from the get go. most communities are
comfortable their neighbours pay all their own way. And it's only when groups
tried to, to shift costs or not pay for the full resources they're using. Our data
centres don't need to use a tonne of water.

They can recycle it. You can have a closed loop, we can [00:30:00] pay our own
way. We can upgrade substations, we can upgrade grids, and pay for it in its
entirety. we shouldn't be pawning that off on local communities.

Do you worry about like AI as a brand? You know, you see meta layoff a huge
amount of people today and it is challenging to see, 4:00 AM emails from Zuck
and you know, jobs being lost.

Yeah, I do worry about it. Those are, those are people

they have families and, I think there are sort of two views, Harry, I, I, I think, to
date. Most of the layoffs were AI washed. That they were, because we did
boneheaded hiring during COVID. It is actually because a great deal of
productivity gains has been, have occurred over the years that we're just now
harvesting.

The ability to gather information from across the organisation to synthesise it
and put it in one place is now changing what it means to be middle
management, the role of information gatherers and presenters is being
eliminated. The ability for us to automate [00:31:00] roles, and none of this is
AI yet, is really 90%, 95% of what the, in my view, what the, the terminations,
have been about. it's easy to to, to put them under the umbrella of ai. Now, is
starting just now to have meaningful enterprise impact. but if you are an
engineering organisation that can't see how to take advantage of vastly more
productive engineers, I don't think you're long for this world. the list of things I
want our engineers to do is 50 times as much as we have engineers, right? as we
get more productive, we do more things, we're gonna hire more engineers.
We're not gonna hire less engineers.

can, can I ask you? We, we, we saw Benioff say that he spends 300 million a
year on anthropic, which, equates to about 3.8% of developer salaries on
philanthropic to make it justify the valuations that we're seeing for these
companies. It needs to be 20%. Do you have any concern in that movement
from 3.8% to 20%?

No. I mean, I, I think if you look at, I, I've never done this in [00:32:00] any
detail, but if you look at what we pay hardware engineers and you look at what
the tools we, we, the EDA tools they use, I bet you're much closer to 15 or 20%
than two or 3%.

what's happened is historically software engineers use very low cost tools and
hardware engineers used extremely expensive EDA tools.

And so interesting, isn't it? I mean, I, the cost of bugs in hardware is so high that
we became accustomed to using many expensive tools in software we threw
people at the problem rather than tools. as AI becomes more productive, I
certainly don't see a problem where software engineers are using 50 a hundred
thousand a year each in tokens, there are 47 million software engineers in the
world.

I mean, that's $5 trillion. just in software engineering token use.

we, we mentioned hardware engineers, we mentioned software engineers. What
role does not exist today that you think will be incredibly commonplace in three
to five [00:33:00] years?

I've been a part of over the past 25 or 30 years, several technical transformations
that produced jobs in companies that didn't exist prior to the mid nineties. The
role of CIO didn't exist. CIO arose as a role with Cisco, with their sort of rise to
dominance prior to the mid nineties, the amount of enterprise networking was
de minimus.

There was a role was often VP of Telco infrastructure. That job is gone. We
don't have a phone system. In fact, we don't have phones on people's desk. call
me on my cell phone, That job disappeared. Completely gone. And companies
that built the PBXs, like Rome and all these other, that business has shrunk to
nothing.

Now, later, what happened in the two thousands, With the rise of Palo Alto
Networks and these other security, the role of CSO never existed prior to that,
And what you're gonna see is the rise of roles that reflect the governance of AI
in companies. Now, [00:34:00] some companies have chief AI officers.
I don't know if that's what it is. But as these technologies become important in
companies life, new jobs emerge jobs that never existed before. New
organisations exist, where there were none previous ones disappear. I think role
of HR changes fundamentally. the part of ar, hr that just, that answered
questions, that provided information about benefits that disappears.

AIS can, can answer all your questions. they can provide better answers, faster
answers, more thoughtful answers. it becomes something different. The
management of people becomes something different. I think there are all sorts
of other parts of, of organisations that have fundamental changes,

because AI can answer the questions that they used to answer.

Do you agree? The biggest inhibitor to enterprise adoption of AI is data
structure and data cleanliness, preventing.

No, The biggest are, are lawyers. no, really, I think the security apparatus and
the lawyers who, when they don't understand the technology, [00:35:00] say,
no, we can't do it. they're the saying no business entrepreneurs are in the getting
it done business. there's a reason for this, that your security apparatus and your
lawyers, I mean, everybody, they're, they're in jobs that everybody just blames
them, No credit, no credit failure blame. No credit, no credit, no failure, blame.
I mean, that, that's their life. And it's brutal. it's brutal.

You're selling it so well for

any your aspiring lawyer.

listening go into being a ciso. Oh, it's brutally hard.

We had a year where nothing happened. Well

done.

that is their dream. I mean, every day their phone doesn't ring their, it is like, oh,
made it to another day.

but when confronted with new technology, because their payoff structure is
such that they're in the business of trying to avoid risk. they are a drag on
adoption of new things. And you see this across the board lawyers don't know
how to contract for it. There's no precedent that's in a business of backward
looking precedent.
You wanna make a lawyer uncomfortable. I know your girlfriend's, a lawyer ask
her to work in an area with no [00:36:00] precedent. They don't know what to
do. They, their whole training is about what has everybody else done before?
How do we synthesise this? How do we work within those rules? I think the
wide scale adoption and use of ai, in organisations is today limited by security
and, uh, legal.

once they agree we need to do this, here are the rules we will use, there's a huge
amount of productivity be gained, then you are immediately constrained by the
way you chose to husband and marshal data the way you chose to organise data
over years. And so companies like, or organisations like Mayo Clinic that have
been on a 30 year quest to organise data, they're at a huge advantage.

Same with companies like GlaxoSmithKline and other companies who, who
haven't perhaps been as disciplined, as thoughtful about the organisation of their
data, are at a disadvantage.

On the security and the provisioning side, do you think we will see industries tip
like legal has done where the biggest firms in the world are now going, oh shit,
we need ai. Our clients are saying [00:37:00] we need ai, Harvey or Agora, and
I'm not gonna get into which one, but like there's two options.

Boom. Do you think all industries will follow the tipping or do you think most
will follow the slow agreement that

it's the new normal?

what's happening is the leaders are tipping, right? And, I, I think even Jensen
told a story that, that he was battling with his own internal lawyers around the
use of, I think it was Cursor. And finally he just decreed, we'll get, we're gonna
do it I think at some point, leader's way the productivity gains against the
unseen boogeyman of Brisk. And the problem with unseen boogeyman is
sometimes they're actually real, right? Not often, but sometimes. that's the
problem. What does he call him in, in John Wick Yaga. John Wick is the guy
you send to kill Baba Yaga.

Just, I, you know, I think for me, I'm not that young anymore, but I'm definitely,
uh, capable of ex

exuberance.

I know you're in your sixties, but you look good.
Yeah. And listen, it's the, it's the facial moisturising routine,

 we [00:38:00] mentioned, um, security permissioning, legal, everything in
between. They get even more fricking nervous when it's open source, they shit
the bed. how do you think about that? I see more and more companies,
especially in the Valley, really push the boundaries on with Frontier and then try
and get as close as possible with open source, given the

cost

advantages. Is that the future? And what does that

mean?

look, I, I think we as an ecosystem have made real progress in sort of the, the
legal, gunk around open source. But the result has been a, a complexity that
hurts your head. if you ever want to, to dive down a rat hole that has sort of no
bottom, a discussion with lawyers about open source software.

And th there's no end to the depth and the boredom, which you will suffer a as
you head down this hole. this has made doubly worse by some of the best open
source models were made by Chinese companies. and they're exceptionally
good models. Kimi K two Deep seek, Quentin. GLM. These are extraordinarily
good models.

They're not [00:39:00] quite as good as the closed source models, but they're
exceptionally good models. And I, I think, that is a case of, trying to decide,
whether it makes sense to, to, to, to save money. they have been, easy for us to
adopt to demonstrate extraordinary speed on, it's a hard problem.

I mean, I don't envy the, the legal team and, and the security groups that are
thinking about these things. the truth is the tidal wave is so big and the demand
is so high they often just get, washed over.

Do you think we should be selling chips to China as a result?

No, I, I think, let's remove all of us that are self-interested.

even though I'm arguing against myself interest, right? if you remove me and
you remove Jensen, you remove Lisa and you remove everybody in the chip
industry and, and you say, if we sell to, to somebody in the security business,
and you ask this question, if we sell leading edge technology to China, will
there military use it?

Everybody says yes. That there is no debate on that point. Their military will
use it. ask a second [00:40:00] question, which is, if you sell our leading edge
technology, will their government use it through their industry to compete with
us? in an advantaged way. The answer is also yes that's where I stop. There's
complete agreement that those two things are true by everybody the security
business and outside of the chip business. now you can say that keeping them in
our ecosystem the best way to manage that problem. That's one argument and
there's some merit to that.

There is. Keeping them from building their own, their own ecosystem is
something that's in our interest. There's real merit in that. I don't agree with
either of those arguments, but they're real arguments and they have real merit.
they are, at least our industrial adversary.

as you travel the world and you see the results of some of their industrial policy,
for example, the, driving down the cost of solar, driving down the cost of
lithium batteries the results it's had in their auto industry. And the fact that you,
you travel the world and you see Chinese cars, and fewer and fewer American
[00:41:00] cars, they're an industrial atmosphere.

I don't love that. I, for years did business with entrepreneurs there at Baidu and
at Tencent and Didi and all these companies. And they're every bit as good as
anybody in Silicon. And I would love a, a world in which they weren't an
industrial adversary. And instead we were working together to solve real
problems.

state of the world is the state of the world for me. if it's an industry, as American
industry, we sold fewer chips and we didn't sell 'em to China. I'm just fine with
that.

people would argue back and say exactly as you said there, if, if we don't sell
them, they'll build their own capabilities and they'll get very good at it, and then
we won't control it. Why do you not think that that's a credible argument?

I think the chip industry R requires you to go through TSMC and TSMC
requires you to go through A SML, or, or Samsung. there are choke points to
manage those challenges. I think the strategy in any case is, those I think who,
who disagree with me, would, would [00:42:00] suggest that, you don't wanna
sell them your cutting edge technology.
You wanna keep them down. Rev, I, I'd like to keep, my industrial adversaries
more than down roof.

 with that, how important is it that we onshore TSMC, like capabilities and
companies given Taiwan's vulnerability to China?

we have problems in the US in long range policy,

policy that endures more than a single administration, right? We have problems
building infrastructure that is clearly needed and crosses municipality lines. let's
look at things. China has done extremely well. Their power infrastructure is
extraordinary.

And in the US we are a patchwork of 1950s technology, if we're lucky, that's
really bad. there are things we don't do well. one of them thinking about long-
term consequences of, like not investing in fabs in the us. I mean, we didn't just
lose the fabs, we lost the surrounding ecosystem. We lost the packaging
[00:43:00] expertise. we lost a whole set of, surrounding, strategic jobs and
industry.

it is extraordinarily important we get it back. And I've been saying that for a and
a half, that the CHIPS act not subsidising intel, it's important that, that we have
cutting edge fabs in the US that we, surround them with cutting edge packaging
technologies. these are a strategic asset.

If I said that you have one policy change that you could usher through with no
resistance, what would it be?

I, I would allow, TSMC and, Samsung, a 20 year period free from all local
ordinances, all of them build fabs their desired location in the us. If that's
Arizona, that's great. If that's Texas, that's great. 20 years, no local rules. Allow
them to build fabs and I, I would say that use the same rules you use in Taiwan.

Don't, don't build garbage, use exactly the same construction techniques and
[00:44:00] rules, et cetera, that you, that you've built fabs successfully
elsewhere in the world. But local ordinances are disastrous and not intended to
cover pyramids, right? Fabs are modern pyramids, Harry, they are the greatest
things humans make in manufac in the manufacturing world.

By far, by far, close.
Alexandria, I sit here in London, should I be worried? And you have the best
Frontier Labs in the us. You have amazing open source and amazing
manufacturing capabilities in China. does Europe really have? We, we've kind
of failed on the model front. Ms. Str, it's the leader, but it's sadly no. Nowhere
near others. Should I be worried?

you should be worried at the pattern the, the pattern of, sort of lack of success
across a range of technologies. It, it's not just that, that the leading AI
companies are, are, most of them are in the us but the leading chip companies,
but the leading software companies, right? Of course, there's some examples,
SAP and, and some others.

[00:45:00] But, there has emerged in Europe of afraid of it then regulate it, tax
it, sort of mentality that that works against entrepreneurship. And, and I think
Europe, this isn't true across the board, and clearly there are pockets outside of
Cambridge and, and in London and, and Stockholm the guys at lovable are
doing really interesting stuff.

And there are all sorts of counter examples. on the whole, its population, the
opportunity to do vastly better on the innovation front across industries is sitting
there, unexercised. that I think is, is a worry.

How much of your business do you think will be in Europe in five years time?

think along with this, they have been slow to adopt new technologies. Not only
have they been sort of slower to invent new technologies, but they've been
slower to adopt new technologies. I think the fastest adoption will not be in
Europe. but in the, the, the two and a half to three to five year range, it, it'll be a
meaningful portion.

Is, is that in line with your experience? I mean, my experience from a long way
away. And from visiting [00:46:00] regularly and talking to customers, is that
your experience?

Layer. No, I think we have some of the world's best companies. Whether you
are 11 labs or your Synthesia or your DeepMind. I I think a hundred percent on
the infrastructure, on the chip side, on the model side, unwaveringly. So, so in
large part with a little bit of nuance, which you, to be fair, Adam there with
lovable and so hot hotspots.

So I think we're totally aligned there in, in respect.
Yeah, yeah. I think you've done real work to argue against that and hats off to
you and the others in the venture community. I, I think capital plays an
important role. I think a culture in which it's okay to fail plays a role that, that,
that is, not traditionally in Europe. Careers are at one company and are long,
and that breeds a, a conservatism.

I think one of the most powerful parts about Silicon Valley is the absence of a
stigma. If you try to do something extraordinary, crash and burn, VCs don't hold
it against you. They, they ask you what you learned and often it's great
experience and a credit to you I [00:47:00] think that is something that, that I've
not, don't understand it, its history, is clearly present.

Can I ask you before we do a quick fight, uh, we mentioned the IPO at the start.
You timed the IPO with the greatest of respects in my mind to absolute
perfection before a SpaceX IPO before anthropic or open ai, was that strategic
and deliberate was the greatest of respect, or was it relative luck?

No, let, let, let me share. It was 100% deliberate. tried to go public a year and a
half earlier, and we couldn't get it done because we bumped into CFIs. we're 10
years old. We tried to get public for years It was 100% luck and grit sort of a
relentlessness and an unwillingness to fail.

But did you have in your mind the other IPOs and when liquidity would be
best? Excitement would be highest.

did we know, when we set the date that chips would be on a run and that it was
impossible for, X AI and open AI and et cetera to get [00:48:00] public before
we didn't know any of that when we set the date. but what we did know, was
that, we had a chance to be the first and only AI pure play in the entire market.

There's only one, and that's us. we had a chance to bring an extraordinary
growth story to public market investors who had been shut out, that, we tried
again and again. And that, that's how you get lucky Harry. He, he is, smart,
hardworking people. Relentless work. They get lucky and occasionally they,
they find the perfect timing.

Should you be investing in companies Building on top of you, you said about
trying and trying again. Jensen said before that he wishes there were companies
he had invested in and about bluntly investing in the ecosystem around Nvidia.
Do you think Cerebra should be investing more aggressively in the application
layer built on top of you?
I think that's an opportunity that is newly available to us. probably not with
venture dollars or traditional venture dollars, right? I, I, I think you have to
think very carefully about y your investors. when you're using venture dollars,
the [00:49:00] question is, should we be investing in them or should our venture
partners be in investing in them, With public dollars, the mandate is different
and your investors have different access. And so, the opportunity for, for us to
do really interesting things with our, our customers and our partners grows.
includes acquiring companies, that includes investing in companies that
includes different structures of partnerships.

And we, we have to explore them all.

You mentioned the multiple times trying to go public and the persistence. What
do you know now about going public that you wish you'd known when you
were trying multiple times?

Is it what you thought it would be?

no. Look, I, I think what happened was, we bumped into a, a CFIUS challenge
that was sort of obstructionist there were unnamed concerns that that never got
articulated that, that sort of lived in the ether, about, some of our, our large
customers. and then we got a new government those concerns disappeared we
were able to move through it really [00:50:00] quickly and thoughtfully with a,
a really fair resolution.

And by the way, a resolution that we had proposed a year earlier.

Is it charm administration? Unwaveringly better for business. Again, I

sit here in the uk.

un unwaveringly better for business. there are things I agree with. There are
things I disagree with in this administration, but unwaveringly better for
business. gotta be at bat taking swings and you've gotta be building every day.
when we got public, we were a much stronger company.

had larger sales, we had, we're further down our roadmap. We had better
customers. you, you sort of have separate, you know, we, we, we didn't get
public because of, but we kept building the business and the business got better
and better and better. And that gave us the opportunity to try again.
that's, I think the message to, to your builders, to your audience who, who, who
builds companies is a lot of stuff will happen that is not in your control. Right.
There'll be bad times, there'll be you know, I was raising money in the summer
2008. Yeah, that's right. That look on your face is exactly right.

Summer 2008, bear Stearns Falls apart in March. Lehman Brothers is
[00:51:00] exploding. In September, VCs didn't wanna put money to work. And
you know what? The only thing we could do, we could keep trying and keep
building.

I was 11. I was playing Pokemon dude.

Yeah, that's right. when you were outta nappies, we, we were out raising money.
and what you can do is run with the things you can control you are always
stronger if you keep building always. if you keep adding customers and you
keep moving your technology forward, adding space between you and your
competitors, that's what you can control.

Good times bad. That's what you're in charge of.

I have to move into a quick file ' number one did What have you changed your
mind on most in the last 12 months?

 I think there, there are a lot of things that, that sort of, as you prepare to go
public, the, the number of people who call you and try and sell you stuff is, is
insane. suddenly developing a presentation which should cost $20,000, is a
$200,000 project. you get 20 emails a week about wealth management.

Suddenly you get just the [00:52:00] garbage. it's like when you get married,
Harry, it's the same. want a photographer to do a corporate event, $3,000. You
want a photographer do the exact same thing, only call it a wedding, three times
as much. Same for a caterer, same for everything,

Why? ' cause you can't put a price on love. Like, because they know your why

you.

the same reason no be, be because, they can. And that's something that I didn't
expect, and it's sort of uncomfortable. the number of people trying to take a little
nibble of your IPO, and get paid on it, that was a surprise to me. I, I didn't really
think carefully about that prior to getting out the door.
I mean, listen, you touched on Europe. From an American's perspective, if I
touch on America from a European's perspective, there's always a take. It's like,
it's always about the money in America, the transact, the money, the money, the
the E Oh, it's like oof.

we, we have a problem with that in our society. I think that's right.

it is both the, the source of some of the drive in the entrepreneurship and some
of the source of, of the uncomfortableness.

how did money change you as an [00:53:00] entrepreneur? Like it changed me
as an investor. I go for way bigger upside. I'm not so fearful of losing money.

I grew up on the Stanford campus and the only currency was intellectual
horsepower. my dad's tennis match, he played doubles every Saturday and
Sunday, and they were like six or eight guys in rotation I look back and four
ended up with Nobel prizes and one had a fields medal. Right. You know,
William Shockley lived next door to us.

Dude invented the trans transistor. And what we knew about him growing up
was on Halloween, he gave full-size candy bars. That was what we thought
about as kids. after I sold my last company, nothing changed. nothing's
changing now. I think what's made me proud, what made me proud in my last
company is we, we made a hundred millionaires.

What made me proud in this company so far is we've made 800 millionaires.
800 if you don't like doing that, you have no business being CEO. If you don't
like delivering for your team, you're not a real leader. that feels good every day
here.

Heat a hundred [00:54:00] millionaires.

800 millionaires.

Yeah, that must feel pretty great.

Well

done.

are people who bet many of them bet long periods of their career with us, right?
I mean, and maybe you get 35 years of a career as a top working engineer and,
many of these guys have been with me for three or four companies. Some of
them been here 8, 9, 9 and a half years,

we, we've spoken before on off record about kind of personal lives. I'm
intrigued when you are a public company, CEO, and you are going public. The
world wants a piece of you. You are public now. You're public. Any advice on
how to sustain an amazing marriage and an amazing relationship while also
being a public company, CEO, and going through that process?

pick a wife with patience, pick a partner, a husband or a wife, partner, who,
understands what it is to, to be an entrepreneur. I don't think, and I look at my
co-founders and, and our leaders, every day when you are a leader of a, of a
startup, a pressure test on your soul every single day.

if you're a real leader, when you are 30 people, a little, a [00:55:00] little
company picnic, look out what you see are mortgage payments and braces that
need to be done, that you're responsible for. And that doesn't change. if you
really believe that and you, you hold that in your heart every day, you carry real
weight with you.

you have to share that with your partner so they understand. it's really hard if
they don't. I think almost everybody and, and maybe your, your, partner has felt
this, and every CEOI know has told the story of their partner telling them that
they're more lonely when you're sitting next to them thinking about work, your
mind is just ripping on work than they were when you weren't in the house.

think that what we do is a family thing. There's a price to be paid and often you
see your wife. I mean, I'm on the road three weeks a month. put it this way,
Emirates Airline sends me a Christmas basket. This is an Arab airline sending a
Jewish guy a Christmas basket.

You know how frequently you have to fly for that to happen? it takes a toll. And
I, I think you have to think really hard about, How to put some credits back.
[00:56:00] 'cause otherwise they're just a scream of debits against your
relationship.

Final one for you, dude. What's the kindest thing anyone's done for you? You
know, we see a lot of, uh, whether it's your investors publishing on, your IPO
Day and, oh, I met Andrew once at a coffee shop, you know, oh, I opened the
door for him once I was part of cereus. what's the kindest thing?
I think, and this is for you, Harry, and, and the VCs is, to have empathy for how
hard our job is. I think one of the, the things that I was really lucky with was we
had a board that, understood, they didn't need to put more pressure on us, that if
the pressure doesn't come from within, all right, they bet on the wrong people.

you know, you know, hardware is, is extraordinarily difficult. And we had, and,
and we attacked a problem that had never been solved. And we had an 18 month
period where we were spending 8 million a month and we couldn't build it.
Yeah, 8 million a month. We were burning for 18 months and we couldn't solve
the technical problems.

You know what it's like to have a board meeting every six or eight weeks and
come back and say, nah, I [00:57:00] can't do it. can't do it.

You did you doubt yourself at that point? 18 months.

Course. think there's this myth that CEOs don't doubt theirselves. It's not driven
by relentless fear of failure. Of course, of course you do. but I believed in the
methodology we were using. I believed that, each time we failed, we learned a
little bit and we didn't fail the same way again.

where it started, we failed in the first two seconds, and then, then a year later we
were failing at, at an hour. each time we, we did a full failure analysis each
time, and every single one we failed at for 18 months. that's some of the
proudest work in my career, was that problem.

nobody else to this day has solved it. Nobody else knows how. I think you can
imagine getting back to your previous question, that I wasn't a peach at home.

 Right. I, I wasn't chipper, I wasn't light, I wasn't happy. I was failing every day
at work, single day for a long time. And I, I think, if you wanna attack hard
problems, you have [00:58:00] to come to grips with that. You have to learn to
manage it. You have to surround yourself by people who, who you believe in,
who you want in the boat, when the hardest problems are, are present.

And I had all of those things. and my wife was an extraordinary partner.

Dude, listen, I so appreciate you. I so appreciate you putting up with my
incredibly wayward questions from

partnership.
they're interesting. I, I think, Harry, you're, you're an extraordinarily good
interviewer. you can cut that part if you want.

No, I loved it. That's fantastic. trust me. We're gonna start the teaser is Harry,
you gonna show? Thank you,

Harry, you're an extraordinarily good interview.

But before we leave you today, you have the idea, but often with AI tools, you
hit a wall. Well, base 44 is where that friction disappears. Turning how you talk
into how you build full stack web and mobile apps, sites, autonomous super
agents, all built in minutes, not weekend spent on damn configuration base 44
ships it all out of the box, the back end, the database, the authentication and the
hosting.

It handles the heavy [00:59:00] lifting so you can just stay in the flow. It doesn't
just replace the busy work, it multiplies you. It makes you so much more
capable, an effective version of yourself in this market, being fast is the
baseline, but to win, you gotta be first and base. 44 is that edge. It's the move
that lets you skip the troubleshooting and get straight to the breakthrough.

Launch your next big thing@basefortyfour.com. That's base four four.com.
After Base 44 helps you launch Corgi helps you cover what comes next. My
word, what an arresting first line. Get your ass covered with Corgi Insurance
and I'll tell you why. If you are running a business right now, you already know
this pain all too well.

Getting insurance. It's really slow, it's confusing, and my word, it's full of
paperwork. Well, that's exactly why Corgi is here to change the game. Corgi is
the first and only insurance carrier designed specifically for tech companies
allowing you to get covered in minutes instead of days. Corgi provides essential
coverages for all growth stages such as D and o, e, [01:00:00] and O, liability,
cyber, commercial, general liability and more.

Get your ass covered. I love the way we say ass with Corgi Insurance alongside
thousands of other startups@corgi.com slash two zero VC today. That's
corgi.com/two zero vc. You won't regret it. While Corgi handles the coverage,
Turing handles the talent. Frontier Labs keep facing the same limitation.

Models perform well on benchmarks, but they fall short. Once they enter real
coding tasks, real tools and real workflows. That disconnect between synthetic
evaluation and actual system behaviour is now a core block off for a agentic
models. That's why Nvidia and Thro, Salesforce, Gemini, and other leading lab
partners partner with Turing.

Turing is the research accelerator focused on post-training reliability. They
build realistic RL environments. Next generation data quality systems built
from real world operational traces and coding data sets that stress models under
conditions where failures matter state [01:01:00] changes, workflow branching,
brittle tool calls, and the coding errors that break RL agents but never appear in
benchmark reports.

In reality, a model may demonstrate correct reasoning in your evaluation setup,
yet still select the wrong parameter or mishandle a code update in a realistic
interface. Turing makes that failure visible and gives teams the signal they need
to fix it. For labs advancing ag agentic systems, Turing provides the structure
required to understand why these failures occur.

To find out how, visit turing.com/two zero vc. That's TURI g.com/two zero vc.

---
type: 20vc-episode
guest: "Andrew Feldman"
company: "Cerebras"
role: "Founder & CEO"
episode_type: interview
date: 2025-10-12
youtube: "https://www.youtube.com/watch?v=FdhAxqR1wVs"
transcript: "https://20vc.substack.com/api/v1/file/da2337e2-e85f-426a-b783-2088bab24f5f.pdf"
newsletter: "https://20vc.substack.com/p/20vc-newsletter-12th-october-2025"
tags:
  - 20vc
  - ai
  - founder-advice
  - hiring
  - infrastructure
---

# Andrew Feldman — Cerebras

> Founder & CEO @ Cerebras | 20VC Interview | 2025-10-12

## Key Takeaways

### 1. WTF Is Going on in the World of Chips Right Now
There is unbelievable demand & nobody knows where it’ll go in the future. We have customers asking us for 5M to 40M queries per second. Companies are reserving capacity as future options.

### 2. Nvidia Is Showing Signs That It Is Running Out of Innovation and Needs to Use Bully Tactics to Win
When big incumbents are running out of growth, they use their balance sheet more & their technology less. They buy business and pre-announce products to freeze competitors and customers. Nvidia fits this pattern.

### 3. The Real Question to Ask When Analysing the Rate of Chip Depreciation.
How much faster are future generations than the current generation? At some point it is more cost efficient to buy a new chip than one that’s fully paid off. If the chip industry does not continue to build extraordinarily better parts people will not move on.

### 4. It Is BS to Suggest That the US Does Not Have Power to Supply AI.
People often say the US does not have enough power & that is wrong. They have plenty of power: natural gas in West Texas, hydro in upstate New York… The problem is location: they are nowhere near people or data centers.

### 5. The US Has Fundamental Limits in AI Expertise, and the Government Is Making It Worse.
The US is not producing enough AI practitioners. Historically, the US was able to attract talent through universities and the H-1B visa. If they want to build homegrown talent, they need drastically better university programs.

### 6. How Regulation and Permitting Is Massively Holding the US Back in AI.
Samsung had to redesign a fab they built in Texas because of a local fire ordinance. The US government worked for years to deploy billions of dollars & a local fire ordinance set the project back 10 months. That is a problem we need to work through.

---

## Links
- [Watch on YouTube](https://www.youtube.com/watch?v=FdhAxqR1wVs)
- [Full Transcript (PDF)](https://20vc.substack.com/api/v1/file/da2337e2-e85f-426a-b783-2088bab24f5f.pdf)
- [Newsletter](https://20vc.substack.com/p/20vc-newsletter-12th-october-2025)
---

## Full Transcript

Andrew: [00:00:00] things are moving at a rate that, 6, 8, 12 months out,
everybody's unsure. It's so fast.

It's so big.

there is unbelievable demand and nobody knows where it will go in the future.

the question of depreciation is how much faster are future generations than the
current generation? that's the actual question on depreciation.

people often say we, we don't have enough power in the US and this is strictly
wrong. We have plenty of power. It's in the wrong places.

Risk comes, in financial markets where people fundamentally underestimate
risk

no company ever went bankrupt by paying extraordinary people too much

Harry: This is 20 VC with me, Harry Stebbings, and I'm so excited for the
show. Stay following our blockbuster episode with Jonathan Ross at Groq last
week. I'm so excited to welcome another leader in the space today in the form of
Andrew Feldman, co-founder and CEO of Cereus, building the world's fastest
AI inference and training.

Now, cereus recently closed a $1.1 billion series G round. $8.1 [00:01:00]
billion valuation with names like Fidelity, tiger Valor, and others. Included in
the round, They've leapfrog GPU limits, operate at trillions of tokens per month
and are filing to go public very soon.

This was an incredible discussion. I'm so grateful to Andrew for his friendship
and I hope you enjoy the show.

but before we dive into the show, stay, I love seeing the team come together to
make this show happen. What I don't love is trying to keep track of all the
information, the data, and the projects that we're working on across dozens of
platforms, products and tools. That's why we use Coder, the all in one
collaborative workspace that's helped 50,000 teams all over the world get on the
same page, offering the flexibility of docs with the structure of spreadsheets,
Coda facilitates.

Deeper teamwork and quicker creativity and their turnkey AI solution. The
intelligence of Coda Brain is a game changer, powered by Grammarly. Coda is
entering a new phase of innovation and expansion, aiming to redefine
productivity for the AI era. [00:02:00] Whether you're a startup looking to
organize the chaos while staying nimble or an enterprise organization looking
for better alignment, coder matches your working style.

It's seamless work space connects to hundreds of your favorite tools, including
Salesforce, JIRA, Asana, and. Figma helping your teams transform their rituals
and do more faster. Head over to coda.io/twenty VC right now and get six
months off the team plan for startups for free. That's Coda, CODA. IO slash two
zero VC and get six months off the team plan for free Coda io slash two zero
VC and talking about precision, that's exactly what Brex brings to your
finances.

So when Brex was founded, it wasn't just about creating another financial
product, it was about solving the really gritty challenges that founders faced.
Daily. Let's be honest. Building something from the ground up is hard enough
without dealing with clunky, outdated banks that pile on fees and [00:03:00]
leave your cash idle.

B Brax is different. It's the financial stack that scales with you no matter where
you are in your journey. From corporate cards to maximizing your runway to
earning yield on your cash. Brax was designed with founders in mind to make
every dollar go further so you can focus on building. And here's what really
stands out to me.

Brex combines the best of checking treasury and f. The IC insurance in one
powerhouse account, you can send and receive money globally at lightning
speed, earn yield from day one, and still access your funds whenever you need.
Plus, with 20 x the standard protection through program banks, your cash is not
just working harder, it's working safer.

Two, it's no surprise that one in three venture-backed startups in the US with
companies like Anthropic, Coinbase, and Robinhood. God, these companies are
incredible. Trust Brex to help them grow. If you wanna join the smartest
startups on the planet, head over to brex.com/startups and see what they can do
for you.

And talking about trust today, customers expect it faster than ever, and that's
why [00:04:00] over 10,000 global companies trust Vanta. Vanta automates up
to 90% of the work for in demand compliance standards like soc. Two ISO
27,001 and more using smart AI to centralize workflows, manage risk, and get
you audit ready in weeks, not months.
So you can stop chasing paperwork and start closing deals. And a new IDC
report found that Vanta customers achieve 535. Thousand dollars per year in
benefits. That's insane. And the platform pays for itself in three months. I had
no idea about these. Whether you are growing fast or just getting started, Vanta
connects you with trusted auditors and experts support.

To help you build trust with customers, get a thousand dollars off your first year
at vanta.com/two zero vc. That's vanta.com/two zero vc. You have now arrived
at your destination.

Andrew. Dude, it is so lovely to have you back on. I so enjoyed our first show.
You put [00:05:00] up with my naive questions. Enough to agree to do a round
two, man. I must be charming.

Andrew: Harry, I'm, uh, okay with any questions, naive or otherwise, happy to
do it. Anytime I, I read your, your LinkedIn posts, your Twitter posts. I'm
rooting for your mom.

Harry: dude, you are too kind. listen, I want to start with the billion dollar raise
that you just announced yesterday. can you just talk to me why it's important,
why now, and what it means for the company?

Andrew: Look, it was the largest raise ever done our category. it was done at
the highest valuation and with premier investors. at late stage investing, you're
looking for, the likes of Fidelity. They are the. what would the English call it?
The sort of Oxford or Cambridge of investing?

Right. I mean, they, they are the, premier, public market investors and when
they choose to lead around, it brings Wall Street a great deal of confidence. we
were really happy to partner with them and with the treaties to lead the round.
And then we, were able to get enormous participation from Tiger Global, from
valor from [00:06:00] 17, 89.

So that's 0.1. I think 0.2 is that, we now have sort of the dry powder to really
push Take the opportunities in front of us, to build out our manufacturing to the
scale and scope. We want to add new data centers.

We added five this here in the US to add more data centers. And we have more
big ideas. I think incremental improvements, make believe gains achieved by
dropping from, you know, eight bit to four bit, those aren't gonna get us to the
promised land in ai.
 we've got real work to do as a community, I think this funding puts us in the
catbird seat for that.

Harry: On the Fidelity side, it's actually interesting. I have Brian Halligan, the
CEO of HubSpot on the show. Recently and he actually taught me the
importance of specifically getting fidelity in both pre IPO and when you IPO,
just because of the signal that it sends and I didn't actually realize as a venture
guy the weight that's

Andrew: As an early stage venture guy, you're like, who are the public guys?

Harry: I Okay, fidelity Like what? [00:07:00] Whatever T Row. Sure. They're
all the same, right? And I was

Andrew: No,

Harry: Like Fidelity are the monster in the

Andrew: they're the monster.

Harry: of getting them is is very high. Can I ask you, dude, like why not go
public? cause it was rumored that you guys were gonna go public.

Andrew: Oh,

Harry: this pre-public

Andrew: we, we, we still have every intention of going public. I think it's very
common, in, in, late stage to do a pre IPO round. I, you can get it done very
quickly, if it doesn't distract you and keep moving. I think there were so many
opportunities in front of that, gathering the capital.

So that we could continue to prosecute these opportunities was a no-brainer.

 you said about the real work to be done. I think it's quite difficult for everyone
who's not really in the market to understand what the hell's going on, given all
the news that we see. Can you help us just with the lay of the land in the last
three months of, where are we at now? What's changed? the first thing, Harry, is
we are in a, stage of the market where the [00:08:00] claims are enormous,
Where, tens of billions of dollars are being done here and there and nobody's
reading the fine print that it's over five years. And it's up to, this is the great sort
of CYA word in, in marketing history is it will be up to a hundred billion over
five years.

Right. Well, up to means. It could be 30, it could be 12, could be 40. Right. You
could pick a lot of big numbers and it won't be bigger than, and so as you read
these deals, I think, you have to really think about the timeframe over which
they're being done.

You have to think about whether, anybody is actually counting, Lots of people
are saying they're going to, gonna bring hundreds of billions of dollars of jobs to
the US and this and that. in eight months, has anybody got little, little
spreadsheet, like nine jobs plus one factory? I mean, who, who, who holds
anybody to account?

And the the answer is nobody. I think that's number one. I think number two,
what this signals more than anything is that there is unbelievable demand and
nobody knows where it will go [00:09:00] in the future. That it's so big and
happening so quickly that they don't know. we have customers coming to us and
saying, we would like between five and 40 queries per second.

Well, how do you not know by a factor of 35 million queries per second where
your demand's gonna be? How how are you unsure by an order of magnitude of
what your queries are gonna be? the answer is, things are moving at a rate that,
6, 8, 12 months out, everybody's unsure. It's so fast.

It's so big. And so you should think about sort of these announcements as sort of
options on the future, right? That that's really the, the way to think about it is, in
an unknown environment, how can I take an option on the future? I don't know
if I'll use it all, but I'll pay something the future, rights to have some capacity.

So that, that's a, a way to think about it.

Harry: given that it's so fast, it's so big, how do you think about planning for
that uncertain future?

Andrew: It's brutal. there's a very interesting question about, in extraordinarily,
[00:10:00] rapidly moving environments, what the right planning cadence is.
what you really need is good planning, changing rules rather than good
planning. Right. I mean, we have to make big bets.

We're making five and seven year investments in, data center capacity. we are,
making, hundreds of millions now on term of billions of dollars of bets in
supply chain. and those are not three month bets, I think what you need to do is
use different rules that have historically been used.

You, plan more frequently. You have a shorter, view. You take options on the
future. and if the future moves against you, you, you, you lose the premium on
the option, you pay a little price to secure some capacity. And if you don't use it,
you just, you go, all right. that was sort of a way to manage uncertainty about
the future.

what do you think the chances are that you are still underestimating even your
wildest of demand expectations?

hundred percent. I've been wrong. if you would've [00:11:00] said, a year ago,
two years ago, pick, pick a time at which it would've been conceivable that,
open AI would get the valuations are getting right? Wouldn't have been
conceivable. Three months ago, six months ago, nine months ago.

when was it like the day before? Right. I think that's true with the demand we're
seeing. It's true with the valuations on companies we're seeing it's true with, the
rate of ideas entering the community.

Harry: How much of this do you think is sustainable? Everyone lobbies that,
oh, it's not sustainable. A lot's experimental, it's not enduring. How much do
you think is sustainable?

Andrew: I would say that they're always grumpy people who, who like, it'll
never work. And you'll never beat Goliath. and truth is most things don't work.

And most of the time Goliath wins, But there's no alpha in that. There's no
money made for you or me be betting on the biggest of the big dogs to continue
not to lose. Mean, how, how uninteresting is that? of course, if Nvidia keeps
growing [00:12:00] at the rate they're currently growing 11 years from now,
everybody on Earth works for them.

Right. Guess do the math right? I mean, however, is it possible that our
economy looks very different in five years? Is it possible that, the things we
value, are very different? that we have reorganized around ai? We've seen a
major bump in labor productivity. We have, benefited dramatically, and the
economic pie is much larger.

I think that's not only, likely, it's almost certain. And I think,
Harry: that if Nvidia continues to grow the way that they do, everyone will
work for

Andrew: you keep doubling at that rate you multiply you can't keep doing that.

Harry: to what extent is it just completely unshakable at this point for them?
Like where the scale and the size of money is. Like, you know, Jonathan Ross
from Groq said on the show, they will unwaveringly get $10 trillion within a
five-year timeline.

Andrew: I hope he's long on them. Then. I don't pick public market stocks. I
don't like picking public market stocks. in the public market, you can lose
money on good companies. You can make [00:13:00] money on shitty
companies, and that, for me, doesn't sit well, right? an entrepreneur, as a David
in the battle with Goliath, I wanna make money when, when we build a great
company, period.

But, can they continue to grow?

I think we are seeing some things that big companies do as they begin to worry
about growth. I think, your balance sheet more and your technology less, This is
something that historically, large companies have done as they feared for their,
technical prowess.

Harry: And when you say that you kind of referring to investments in your
open

Andrew: Yes,

Harry: dollars and 11 labs and

Andrew: yes. you start buying business as opposed to winning business. we
saw that with Cisco, who emerged it as a dominant position, you know, 99,
2000, 2001, that that has been, uh. one of the strategies, another strategy you,
you see is this predatory pre-announce where you announce B three hundreds
before anybody can get B two hundreds.

You start talking about Ruben before B two hundreds are, technically, finished.
you [00:14:00] don't talk about, the field failure rate of your products, which are
massive. rather, you, sort of keep talking about the future in an effort to
convince people to wait to make a good decision, rather than go with
technology that's, better and present.
I think these are the strategies of, of very large companies using their strengths.
and I, I think that's what you're beginning to see unfold with Nvidia.

Harry: speaking of a hundred billion into opening it, how did you analyze that?
For, for me, reading that, I didn't really know how to analyze it. It's so
unprecedented.

Andrew: it was designed for nobody to understand it. if one wants to make
something very clear in an investment we've invested this amount of this
valuation, the deal's done. Now if you wanna make something more difficult,
it's up to this amount over an unbound specified amount of time at no valuation
given or a valuation specified.

But it can change, it wasn't designed for you or, other analysts to anchor on
different things. And, and that's a, a very reasonable thing for both of them. But
it's [00:15:00] just. It's not an analyzable thing. beyond the fact that, Nvidia has
chosen to try and lock up a portion of, open AI's demand, by investing in them,
that's about as much as you can say

Harry: I totally get you. And I'm glad that it's meant to be confusing. 'cause I
was confused looking at it, going, what price was this? How

Andrew: I, I,

Harry: buying?

Andrew: I, I don't know if it was meant to be confusing. I think it was meant to
be, uh.

Harry: you know, my mother goes shopping and I ask her, it is a lovely dress,
Jules. How much is it? Well, it doesn't matter. It doesn't matter.

Andrew: You call your mom by her first name. Hold on, wait a sec. Let's go
back to the important thing you call your mom by her first name,

Harry: Oh yeah, Jules.

Andrew: okay? You don't call her mom. I've never called my mom Shirley. I
mean, I, I, well, I could never call her. I mean, that was just mom or something
else, but not,
Harry: no, but when I, when I get the like, price on application, I'm like, oh,
Andrew, oh dear. Oh, that, that's what this felt like. That's what I was like,
really? No,

Andrew: I, I, [00:16:00] I, the truth is, is there may be, and there are likely a
huge number of moving parts that make it impossible to clearly, describe
without giving out more than they wanted to give out,

Harry: You mentioned pre announcements that like B three hundreds, B two
hundreds, timings of such. we thinking about chip depreciation in the right way?
again, I just did a show with Jonathan. He's like, Hey, we are actually thinking
about them on like an 18 month time cycle to maybe two years.

And I was like, wow, that's, it's quite quick. Are we thinking about it the right
way and how should we be thinking about the amortization of chips?

Andrew: we are in unprecedented waters. people are clearly still getting value
from H one hundreds, and that's more than two years, right? So, if you say it's a
two year depreciation, you're empirically wrong, and I think people are still
getting value from a one hundreds though, not on the cutting edge.

And so that's closer to three or four years. and could be as long as five or six.
the question of depreciation is how much faster are future generations than the
current generation? that's the actual question on depreciation. Because
[00:17:00] with depreciation, you're saying at some point it's no longer worth
using a part that's fully paid off because there is a new part that so much faster
uses, so much less power that it's better for me to retire it.

That's the actual the underpinning to the depreciation question. If I have a data
center and it's 50 megawatts and I have this much capacity in it at some point,
even though my chips in it Have been depreciated and I'm running them at at
zero cost, right? Power plus zero depreciated cost.

It makes sense to move them out because new chips are so much faster, so much
better use, so much less power. I get so much more dollars per and so that's the
question. if we don't as an industry, continue to build extraordinarily sort of
better parts generation after generation, then people don't move from one
generation to the next.

Harry: They last longer, you depreciate them longer, where are we, and I feel
very naive for asking this. Where are we in the performance improvement
pathway for chips? Are we like in there, we've [00:18:00] got 90% and we're
incremental gains? Or are we at the, we are still at the super early stage and we
have 90% of the gains to be made.

Andrew: the question is, in that case, whether you read people's marketing
material or the actual performance results, certainly people's marketing material
would lead you to believe, that generation, over generation, there are huge
gains. a little bit of engineering digging, probably leads you to the conclusion
that you're getting two, two and a half x, per meaningful generation move.

not more, If you compare apples to apples eight bit to eight bit four bit to four
bit, if you compare actual performance. you know, you might have more flops
on the chip, but your memory bandwidth didn't improve more than two x, so
you can't get to them, these chips are a solution, and if you make one part fast,
it's a system, you make one path fast and the other part, doesn't move as far
forward, it becomes the new bottleneck it doesn't matter how, how many flops
your chip has.

If you can't get data onto and off of the chip, those are wasted. the question isn't
how much, how much faster is the chip? [00:19:00] It's how much faster is the
solution? that includes memory, which has, for inference is the fundamental
limiter for the GP architecture. And so, uh, it doesn't matter how much faster the
chip goes, it how much faster the memory bandwidth is.

Harry: On this, I, I was shouting to a founder in the space and he said that what
everyone fails to understand is that like, although SRAM sounds great in terms
of having memory on SRAM is obviously you'll describe it much better than me
and hate me for this, but SRAM is obviously memory, like on ship versus off
chip.

Andrew: Yep.

Harry: great, but he said it's completely unable to handle scale. And so,
although it may be quicker. anyone who wants to do large scale, it is incapable
at present of doing that, and that's a fundamental need and requirement of any of
the large providers.

Andrew: Right.

Harry: that's fair and how do you think about that?

Andrew: not only is it fair, it's the reason we went to wafer scale. what your
friend said is strictly true in that SRAM is blazing fast and low capacity. HBM
is a flavor of dram. It has high [00:20:00] capacity and it's very slow now,
Nvidia and all GPUs, including, AMDs chose a big capacity memory that is
slow because it was perfect for graphics.

You don't have to go to memory very often. You can hold a lot. You don't go
very often. SRAM is blazing fast, but it can't hold very much. So the problem
on traditional chips is if you put memory on the chip, you are using space that
could be otherwise used for compute. You have a fixed amount of real estate,
and so if you put half memory, half your real estate's available for compute.

our idea was that if we, we sort of, if we built a chip that was the size of a
dinner plate. We could stuff it to the gills with fast sram, overcoming the
limitation of sram, which is it doesn't store very much by putting a huge amount
down, by using more silicon area. Now, if you're an SRAM solution today in a
sized chip and you're trying to do a trillion parameter model, use four or
[00:21:00] 5,000 chips.

What a mess. You know how many cables that is? Do you know the, impact to
the ai, it's a horrible mess. And it limits you from doing things you wanna do
with the ai. like speculative decode. It has all sorts of painful challenges. The
other hand use one of these, or two or four, And it's simple.

It's easy. And this is what your friends had Exactly. Right? And the reason we
went to build a bigger chip. It so we could fill it with this fast sram so we could
get over the traditional limitations of SRAM that killed in the store very much
by using a lot of space, by using a huge amount of, of silicon area.

So your friend is exactly right. You might listen to 'em again in the future.
Yeah,

Harry: Question to you, no offense. That seems a little bit obvious, like, okay,
increase the real estate, shove more

Andrew: yeah,

Harry: on,

Andrew: it does, doesn't it? Yeah.

Harry: it, is it as obvious as it seems? Am

Andrew: No.
Harry: something here?

Andrew: Well, what we were missing is that for 75 years, nobody could do it.
building a bigger chip had proven impossible before we did it. Nobody in the
history of the compute industry had been able to build [00:22:00] a chip bigger
than about 840 square millimeters.

In the 75 year history, the compute industry, and many people had tried and
failed, after we did it, Elon tried Dojo and they failed. it's really, really hard. our
strategy, had never been done before, never been successfully, yielded. And so,
while it was obvious, it was hard.

Harry: So when we think about like where the market is today in terms of.
Training inference. Do we agree then that actually NVIDIA's chips are much
better for training than yours are, but yours are much better for inference than
theirs are, and the market splits in that respect.

Andrew: No, we're faster on both. But the, software challenges. In training are
real.

Harry: What does that mean?

Andrew: it means that when a new model is built, and everybody reads about it
a publication, it was done on A GPU for, everybody to, to train it. they take the
recipe that was originally done for the GPU and they have to move it to the
recipe for their hardware.

Whether that's A TPU, whether that's an [00:23:00] A-M-D-G-P-U, whether
that's another, dedicated chip like ours. have to move it. And that's, a harder
software lift in inference. The truth is nobody cares about cuda. Nobody even
cares about PyTorch. what they want is an API. it's literally 10 keystrokes to
move from, A GPU based solution on, open A-I-O-S-S one 20 B to our
solution.

It's 10 keystrokes. That's it. it's nothing. the answer is, is that, while we are
faster at training and we are faster at inference, it's easier to demonstrate
inference, right? You just put up a side by side to show that you're faster than a
thousand B two hundreds. you gotta get a thousand B two hundreds.

you need to Train the model for four weeks or six weeks. You gotta stand up a
cluster of arm machines. You gotta, it's a bigger lift. I think, the market right
now is easier. To move people off GPUs in inference and the, number of people
doing inference is vastly [00:24:00] higher than the number of people doing
training.

Harry: when you look at the inference market today, how has it developed in a
way that you did not expect?

Andrew: I think it's really hard for the mind to wrap itself around geometric
growth or exponential growth. Right? I think there is nothing confusing about
the greater growth of inference. The greater growth of inference is the number
of people who use it times the frequency of use, times the amount of compute
needed per use, it is three. Different variables multiplied by each other. The
problem is they're all growing fast and that produces some mind numbing
effects. More people are using ai once they start using ai, they use it more
frequently, and what they want to do with it is bigger and more complicated, so
it uses more compute.

And so you have three variables. The size of the markets a product of the three
all growing fast. we knew that going in, we see that and it still takes your breath
away. that, that is really, [00:25:00] really interesting.

Harry: I don't think we've seen anything yet.

Andrew: I agree. I, I think, the reason I'm a hundred percent sure that, that we
are underestimating the market is because of that premise.

Harry: I think Sam Altman said it very well in terms of how people use chat
GPT, but he said, you know, essentially the majority of people use it like
Google,

Andrew: Right.

Harry: replacement. And actually the younger people use it as an operating
system for the future, which is the right way to do it in his

Andrew: As an Absolutely right. I, I think, in 1988, Robert Sallow, who won
Nobel Prize in economics, he asked this question. He said, we see computers on
every desktop and everywhere we look except in the productivity statistics.

And you say, well, that's a really interesting thing to say. And there was another
economic historian who jumped into the fray and he did this huge study. name
was Paul David and he wrote a, a very famous paper called The Computer and
The Dynamo. And what he studied was the adoption of electricity in the
manufacturing sector between about 1880 and 1955.

And what he showed was at the beginning, electricity [00:26:00] produced very
little productivity gains. It was basically used as a backup for belt-driven
systems. And it wasn't until they reorganized the shop floor to take advantage of
electricity that you got this huge jump in productivity. And if you roll that
forward to the computer, what he was saying is, look, we used computers to do
things.

We were already pretty good at that. We replaced a typewriter, we replaced
general ledger accounting with spreadsheets. We were good at those things.
You didn't get a big jump. And what he predicted and then happened
immediately thereafter, by the mid nineties, you had a huge jump in
productivity. We had begun tying them together.

We'd built the internet. We had the, the first parts of a cloud. and all these things
used compute differently in ways that had never been consumed before. And
you got this massive jump in productivity. If you use open AI and a various of
their competitors, the way you use Google, you'll see a very modest jump in
productivity if you use them in a fundamentally different way.

That was Sam's [00:27:00] point. You'll see a huge jump. And if we reorganize
ourselves around ai, you're gonna see massive productivity gains. If we use AI
to replace things, we're already doing Google or something else, you're not
gonna see very big jumps at all. And so that transition takes time.

And what he pointed to is a demographic. Younger users are using it in a
different way than older users. Older users are replacing something they already
had. Younger users are using it in a way that never existed before an operating
system for life.

Harry: If we are gonna see that transition, that you mentioned there, the, the
energy requirements are just. Insane. I mean, Sam said a trillion dollar spend.
He needs the energy of Japan.

Andrew: Yeah.

Harry: feasible, Andrew?
Andrew: yeah, it's feasible. is it desirable or good for society is a different
question. It it's feasible. people often say we, we don't have enough power in the
US and this is strictly wrong. We have plenty of power. It's in the wrong places.

Right. It's, it's not where we have people or where we have fiber optic cable. We
have a [00:28:00] ton of power in West Texas, in natural gas. We have a ton of
power in, upstate New York in hydro. We have a ton of power in lots of places.
We don't have people there. the problem is, is one of a mismatch between where
all the power is and where the people are, or where the buildings are, or where
the telco fiber is that we need to get data to.

And from the data center. The second observation is one of a community, and
that's that to the extent we consume this extraordinary amount of power, we
have an obligation to deliver amazing things. And that's not all of us, think we
have an obligation to deliver drugs that, that are more efficacious, to deliver
better healthcare, to, to make, aging less painful, make the looking after of aged
parents or sick parents.

you go through societies, ills, and woes. if we are gonna consume this amount
of power, the burden is on us to deliver value for it. if we use it and don't do
that, then it's not a gain for society. But if we,

Harry: controllable? you know, creating Ghibli or Ghibli images, I get it
wrong, isn't particularly [00:29:00] value inducing, but it churns a huge amount
of, compute and energy. Can we control that? That's like,

Andrew: It's a very hard question, and I, I, you know, I'm one voice in this, the
problem with markets. Is that they do a lot of things that aren't productive in
order to get one that is very productive, Ghibli may or may not have been net
societally gain, but maybe the technology that is, used in Ghibli is used for x-
ray crystallography and later is fundamental to finding major scientific
breakthroughs.

I mean, that's the messiness, at any given point in time, right? You can point to
in a thousand poppy strategy, which is what a market is, right? A market has a
lot of bad ideas to get a few good ones, that's your business. Your business is
investing behind a lot of big ideas, most of which fail.

and the market is that writ large. So in that environment you can always point
to, oh, that was a dip shit investment. Harry, why'd you invest with them? I
mean, they, they blew up. you can always say that after the [00:30:00] fact, look
at that. They're using a ton of energy for that. That's not useful.
Let's see. and so I, I think the answer is we need to be sure that at a societal
level where we use government dollars, where we use tax breaks, where we use,
permitting, breaks, we are sure that we are giving these to disproportionately to
projects that, that matter to society.

Harry: Do you think Trump's done more to help or to hurt the US AI effort?

Andrew: I think it's confusing. on net it's probably more to help. the Biden
administration was misguided and afraid. the Trump administration, I think to
his credit, they, he surrounded himself with, some smart people, in the AI space.
on net it's been positive.

Harry: When you look at what is required in terms of energy, is nuclear
unavoidable or the sole solution to be the providing force of energy for this next
generation of ai?

Andrew: No, it's not unavoidable. it's a very reasonable decision for countries
that don't have lots of alternatives. you know, [00:31:00] Canada has more
falling water than anywhere else on the earth. the opportunity for Canada to
develop, the cheapest power on earth is mind boggling. there is cheap power in
lots of places.

but in order for, countries that, that, wish to and don't have the natural resources
of Finland that has geothermal or Iceland, that has geothermal or Canada that
has falling water, nuclear is a very reasonable and cost-effective strategy,
especially over, a several decade view.

Harry: What worries you most today, Andrew?

I do think of, this idea that, to consume the resources we're consuming, we have
to be sure that, we produce some extraordinary outcomes.

Andrew: I worry, that, the opportunity is so big that as a community we're
running sort of helter skelter at it.

that actually sometimes, instead of running where you trip and fall and graze
your knee and chip a tooth, if you stopped and thought and marched, you, you
might get further over a 30 or 60 or 90 day period. [00:32:00] Um,

Harry: about the concentration of value in Mag seven? They now make up
more of the s and p than they pretty much ever have done in history, and that
concentration of value is very real. If AI hits a speed bump in any way, could
derail significantly, and the multiplier effect of that is felt by everyone.

Andrew: right. I, I think the, the risk there is not that they consume that much,
that they are that much value, that's not the risk. I think they're that much value
because we believe the future economy, will reward that. I think the issue is, is
that people then think the s and p is a safe investment or a safer investment than
it might be.

risk is the mismatch, in the mental model, people have Risk comes, in financial
markets where people fundamentally underestimate risk when risk is priced
properly. then what happens is, your outcomes are not surprising. if people
continue to think the s and p is sort of an index of the [00:33:00] global
economy, or, and it's not, it's 30% or 50%, seven companies, then they're
exposed to sector risk that they weren't signing up for.

They thought they were diversified. In fact, they're heavily dependent on a very
narrow sector, and that's a risk. that seems to me to be a, challenge in the new
world order and all the advice that sort of the pundits give, you know, a
diversified portfolio when the world changes and that portfolio is not you keep
holding it and it's not diversified anymore 'cause of consolidation.

then there's real risk.

Harry: Do you think the risk is priced properly when you look at Nvidia at four
and a half trillion?

Andrew: I think they've proven themselves to be the, the greatest company of
the first quarter of the 21st century. Right. they've proven themselves to be,
extraordinary company. In the first quarter of the century, and I, I, I don't know
if four trillion's right. But I think, a very big number, maybe it's too low, is right,
because of what they've achieved.

Harry: When we look at, we, [00:34:00] we said before about the insatiable
demand, that we cannot predict or anticipate. What are the bottlenecks today in
your mind? again, we had Jonathan at GR on and he was like, actually, you
know, I had someone come and demand five times the supply that I have in
total. that was from one customer, suppliers, mine. How do you think about the
bottlenecks that we have to reach the insatiable demand that you might.
Mentioned.
Andrew: I think if you go back to planning, if you've got customers demanding
five x that your capacity, I mean, you probably didn't get your planning right.
Right. You probably should have, should have planned better. I think there are
bottlenecks, at every level that are real and meaningful.

I, I think, the first one is expertise. we have, fundamental limitations in AI
expertise. We're not making enough AI practitioners. We're not making enough
data scientists who understand, data pipelines. our universities aren't minting
enough.

our challenges in the US with immigration, don't help that. we, have historically
sucked the best and the brightest first on J ones to [00:35:00] come to our
schools and h ones to stay. if that is not our policy, we need to make them. if the
government decides that, that that is not the way they wanna build a workforce.

Instead they wanna build it, outta people who live here. we need to do a better
job of training those people. We need to do a better job of teaching them in K
through 12. We need to do a better job of educating them in our universities in
order to, to make the number of, of engineers we need to meet this demand.

That's a bottleneck. And it's why the best and the brightest are, are getting such
extraordinary compensation.

Harry: Is the war for talent completely outta control? You're seeing your zucks
of the world spend hundreds of millions on one person. think that's a blown up
anomaly? Or do you see the Wolf of Talent being unprecedented?

Andrew: there are engineers, Who have skills that no number of other
engineers working together can achieve. There are scientists who do, who have
ideas and who have brains that are, can't be replicated by lots of other talented
people working together. ought they to be paid more than class soccer players?

I have no idea. maybe, maybe not.

Harry: mean, [00:36:00] inherently,

Andrew: yeah, maybe,

Harry: rationale standpoint, yes. The

Andrew: they should be. That's right.
Harry: a chief scientist at OpenAI, if they add $50 billion of enterprise value to
pay them a billion dollars is worth it.

Andrew: It may well be, and that, that's what we have to think about. I mean,
we've, paid, Charlie Sheen two and a half million dollars in episode for two and
a half men, I'm pretty sure that, there are lots of people who are, whose net
productivity to society is above that. Um, we're playing,

Harry: spent it all.

Andrew: I saw the, I just saw the show on, was it Netflix or Prime? what a sad
story, of somebody who was so self-destructive and so talented. but, you know,
should we be playing soccer players or basketball players? I have no idea.

And I, I don't spend a minute worrying about whether we're paying
extraordinary people too much. no company ever went bankrupt by paying
extraordinary people too much. if you wanna go bankrupt, pay mediocre people
too much, that's how you, mess up. nobody's ever struggled by paying truly
extraordinary people too much.

Harry: What's the other bottleneck? You said expertise is one.

Andrew: TSMC [00:37:00] can't build fabs fast enough. the truth is, is that
these are both for, for TSMC and, and Samsung. These fabs are the most
amazing manufacturing plants on the planet. you know, these are 30 billion, $50
billion factories. their ability to build them quickly enough is very much limited.

that in turn limits and keeps the supply, below where it would like to be of
chips, not just our chips or Nvidia soup. Everybody's chips below where it
might otherwise be. Keeps the cost up. right now there's a shortage of, of data
center capacity. there's a huge amount of investment that has gone into that.

there's a lot of words, but where are these gigawatt facilities that everybody's
been talking about, everybody's committing to, and where are they? Well,
they're not up yet.

Harry: How long does that take?

Andrew: Right. You know, somebody, like, for Elon, who's the fastest in the
world and maybe the best at building plants and large construction projects, it
takes six months, eight months, and for the rest of the world, it takes a year and
a half, maybe [00:38:00] longer, and
Harry: Are we investing enough in data center builder? I mean, it is one of the
most insanely, hot categories now in terms of investment properties. I, I'm
coming from like a pure Wall Street mindset.

Andrew: Oh, yeah.

Harry: Wall Street guy wants to be in data centers.

Andrew: it has a structure that they really understand. Right. It looks like a
bond to them. it looks like a piece of real estate. You, you, you get a tenant, they
pay rent every month. you, you can loan against that. You, you get an
investment grade tenant that's basically a bond. it has the advantage of, of
falling into a category or a pattern that is really well understood in the debt
market and in the capital markets.

and that's an advantage. core weave and some of their sort of financial
engineering and innovations there help the world to see that. you know, like
many things, lots of people will enter, the smart will make money. the less
sophisticated will will lose money.

building data centers is not for everyone.

Harry: How will you lose money? Building data centers?

Andrew: I think if the best can [00:39:00] build them for 8 million a megawatt,
and you're spending 12 or 14, that's how you lose money. You lose money
because it, it begins as, can you get access to low cost power? It then continues
to, once you have access, can you get permitting? Does that take long or do you
have real access?

It gets you fast permitting once it becomes a construction project. Can you keep
control of your costs? once it's finished, can you keep good tenants in it? the
ways to lose money and property are large in many there's no free lunch there
either. when you are trying to go unbelievably quickly, it's harder and harder to
be disciplined and not make mistakes.

Harry: To what extent is it important to be fully horizontal? You know, we
hear about Zuck wanting the data center build out to be just immense. In terms
of size and scale, to what extent does it need to be horizontal versus vertical?

Andrew: it is completely unclear, the most successful two companies to date,
OpenAI and Anthropic, neither are vertical, OpenAI used, Azure, a hundred
percent infrastructure for years, and Anthropic has [00:40:00] used a
combination of AWS and, and Google, and so neither are vertically integrated
to date.

now whether that's the right strategy going forward, whether they'd make those
decisions again, It's clear that it's not the only strategy, that there are plenty of
working models where you are not fully integrated from, chip through system,
through data center, through software all the way to the top

Harry: Again, sorry to cite it, but it's, it's kind of handy having just done it.
Jonathan said that you would definitely have open AI and Anthropic build out
their own chips. Because then they would have control of their own

Andrew: uhhuh.

Harry: Do you think?

Open Air and Anthropic build their own ships so they don't have self-reliance
on Nvidia in the way that they do today?

Andrew: I think that there is, a long history of software companies failing to
build chips the list is, is very large. whether, OpenAI can do it. whether they can
do it through partnership with, other vendors with Broadcom, with smaller,
more innovative companies is an open question.

companies at the size of Microsoft have been unable [00:41:00] to deliver, uh,
chips, there, there are plenty of examples as you look across the fang, group
where chips were tried. I mean, probably the most successful is Google and
they're 10 years in, modern software does not fit well in a chip making
framework. weekly sprints don't work well on two year long projects. move fast
break things often. Is not the way you think in the chip world. The way you
think in the chip world is measured twice before you cut once because your
bugs cost you six months and tens of millions of dollars.

it's a very different mentality. And where there's been success, it has frequently
been acquired. Apple got into the chip business through buying pem. Amazon
got into the chip business through acquiring Anna Perna. Google acquired the
talent from a collection of companies, and then set it a bu that was aside and
under somebody who, who had enormous respect in the organization and os
and, had a 10 or 15 year view.

these are things that, have been challenging in in many companies.
 ship building [00:42:00] is an MBA nightmare, your analysis that says, Intel
had you know, between 2000 and 2010, some of the world's leading architects,
the world's leading fabs, and proved completely unable to build a working cell
phone part.

And you asked, so why they had everything they needed. And, you know, you
do an MBA chart and it's like, it's impenetrable. And the answer is, this is really
hard. very small sort of mental model differences produce tremendously
different results. How did every leader miss the largest compute market?

in the first part of the, 21st century, how did a MD miss it? How did go, how
did How did Arm win it? all the leaders missed it. And then you say, all right,
maybe there's something in the guts here that I don't understand. Right? You
gotta really get in there. And it's not on a PowerPoint.

It's not in a two by two, it's not at some sort of consultant level. It is deep in the
DNA of the small number of people who can build these things. you know,
[00:43:00] we are lucky at cereus. We've got one of, the top six or eight teams
in the world other startups don't.

Harry: does that market look like, do you think in 10 years time? I know 10
years is a huge amount of time given where we're at, but in 10 years time, is it a
monopoly market with one taking 90%? Is it

Andrew: which market?

Which part of the chip market? We're talking about AI silicon, or we're talking
about silicon in general, or we're talking about

Harry: would say silicon in general.

Andrew: Yeah, absolutely not. One takes 90%. you know, even at the, at Intel
strength, they had dominance in X 86 and zero market share on the cell phone.

And almost no share in the switching market. Broadcom had dominance in the
switching silicon market, which is a form of processor in silicon, and no share
in X 86 or, uh, other forms of compute. Yeah, it will not all accrue to, one or
two companies.

Harry: how do you think about the importance of margin today as a business,
as Cereus,
Andrew: Well,

Harry: given that.

Andrew: I think the [00:44:00] reason we were able to raise at a higher
valuation and from better investors and, and more money is 'cause we had them.
And others who were out looking for Mark looking for, money had negative
margins. as you prepare for being a, a credible public company, people do look
at your margins.

that's a really important part of, of moving from being an idea to being, a real
company.

Harry: What are NVIDIA's margins today?

Andrew: Extraordinary. Some of the, the highest in history for a hardware
company.

Harry: How do you think about that? Is that just pricing power, which

Andrew: Yes,

Harry: advantage

Andrew: absolutely. I mean, the, the, the short answer is why does it make
sense for, AWS to, build a training part? Well, 'cause they want to get rid of the
78% gross margin that NVIDIA's charging them. it might be on the high end
chips, 85%.

people don't like that historically. Historically, people sort of put that in the
back of the mind and they remember it. when Intel stumbled the number of
people who came out of the, the woodwork to kick them when they were down,
it was extraordinary. And it was sort of [00:45:00] years of pent up frustration.

when the giant stumbles we've seen that again and again.

Harry: Speaking of that giant stumbling and being built, do you think
sovereignty will be a big enough reason why are built? You know, we have like
Misra, a model provider in in Europe, and kinda sovereignty is that core play.
Do you believe that is a sufficient enough core play to be giant.
Andrew: Well, I think right now, sovereignty plus the fact that we deliver their
inference through, the fastest. hardware on Earth makes their, product, the
Lechat product really compelling. they're using their, their advantages, to
compete, there were in Europe too few, if AI labs that are, uh, doing interesting
work.

they sort of looked around and, and sort of used strategic advantage, you know,
we wanna be the Europe's leader, you know, played that card really well. hats
off to them and then they raised at a huge valuation,

Harry: A final one, just in terms of geography, deep seek obviously had that
moment and it kind of solidified the concerns around China. How do you feel
about [00:46:00] China today as a pressing concern towards the US in terms of
the race towards a GI between the two?

Do you hate the way that it's posited as like China versus the us the AI race?
How do you feel about that?

Andrew: think it benefits neither the position we're in, the arms race certainly
didn't, help either the US or Russia. in, in the, the eighties and nineties, we, we
both spent money we wish on weapons we wish would've been spent on
infrastructure people or, or other things. we will be much stronger if we can find
ways, to peacefully, engage, before these issues.

We, we knew the guys at, at didi and bike dance and, and, Ali and Baidu
extremely well. They were talented engineers trying to build cool stuff. I think
our governments at loggerheads and, that's a problem. we had a huge
opportunity in, 2019 to do a deal in China I decided to pass because I, I didn't
think it was, the right thing to do, long before, the Department of Commerce
Limited exports to China. I, I didn't think it was right, and [00:47:00] I was
concerned about how the technology would be used. the real politic right now is
that they're better at making drones. They're better at making robots. their
government has an extraordinarily aggressive policy in AI for years.

They, they backstop their venture groups, right? So if you lost money in an AI
company, the government would make you whole. imagine that, Harry. Imagine
how much money you could make if the government of the UK Offset some of
your losses from AI companies that didn't work out. you know, we have real
work to do in the US decades.

Harry: do you have to do that you haven't done? What would you like
Andrew: Oh, I think, uh, China thought long and hard about, their power
infrastructure their form of government allowed them to, to plan strategically.
Our decentralized form of government has left us with sort of a patchwork of
power infrastructures. even if the federal government wants to support you,
their local regulations like at the, at the city and county level of towns, that can
interfere with a project and, and set, a project back, billions of [00:48:00]
dollars.

I mean, Samsung built a fab in Texas and they had to change the design of a fab
because a local fire ordinance and the US government worked for years to get
deployment of billions of dollars in Texas and a local fire ordinance set them
back eight months, 10 months and caused them to redesign the fab.

I that's a problem. that we have to sort of collectively work through. we have the
premier universities, historically drawn talent from around the world. if you
look at, the great CEOs in our industry, Johnson Hawk 10, Lisa, I mean, you go
down the list Sundar, at at Microsoft they came and their parents came.

We gotta take that really seriously.

Harry: You don't buy the whole, well, actually, a, a load of people actually just
abused H ones and we'll just move to O ones, which people were using anyway.
And the average salary for an H one was $120,000. it's a good thing and people
will just use O ones.

Andrew: I am sure that in every government program there's abuse, was there
more abuse in the H one than in, [00:49:00] in other areas? I don't think so.
having the best and the brightest come to your universities and once they benefit
from.

Sort of our great institutions to want to stay and contribute, first with a J one,
which is the student visa, and then enter the H one B lottery through the,
through the, approved process, To get a green card and become citizens. And
this is how my parents did it, right? I think it's one way to bring an
extraordinary amount of talented people to the US

Harry: Is there anything else you'd change? You said the power infrastructure
and the permitting

Andrew: power infrastructure ends up at, at the local level, which is not
necessarily where big ideas, and sort of strategy is well knitted together. we
have starved our universities of compute. if you wanna do interesting training
work at a university, very hard to get enough compute to do that. We're just not
set up for that. those are two dimensions. I think the Trump administration's
done a good job in, generally relaxing some of the regulations that were
[00:50:00] painful.

Harry: Andrew, I wanna do a quick fire with you. So I'm going pummel you
with quick questions and you gotta gimme your

Andrew: You, you know, that's hard because I only have long answers, Harry.
So,

Harry: what do you believe that most around you disbelieve?

Andrew: we will have peace in the Middle East in our lifetimes

Harry: Why do you believe that?

Andrew: having visited spent time now and in the UAE in Saudi and Qatar, I
think the returns to moderation the economic gains. Someone said, we're, we're
too busy to hate right now. We're too busy building. those have been writ large,
so clearly in the UAE with the rise of Dubai and the UAE in return for making
peace with Israel in return for, a more moderate, position.

Uh, I, I really believe that that is the path to the future.

Harry: How much of your revenues are from the UAE.

Andrew: I think in the S one it says, uh, maybe the first half of 24. We haven't
published others, but a lot, 75, 80%.

Harry: [00:51:00] I mean this in the nicest way. Do you not have to say nice
things about it then if

Andrew: That's a, that's a very fair question. No, I, I went there to do business
as a Jewish guy, before we had any business done. Right. I, I, what I found
surprised me, and we, we don't do much in Saudi, and I think they're making
great strides, and we don't do anything in Qatar right now. I think they're
making great strides.
it may well sort of be colored by the fact that I, I spend time in, in Abu Dhabi
and I spend time in Dubai and I spend time in Riyadh and I spend time in Doha.
sure it's colored by, by those things, but I, I think, I think.

Harry: Why are your revenues concentrated there? Is it just 'cause they're like
more willing to embrace innovation, new relationships, new vendors?

Andrew: they, they bought so much they consumed and you know, the, the data
I gave you was through the first half of 24. placed such big orders. They
consumed all our manufacturing capacity. they are, building at such an
extraordinary rates that through the first half of 24, they consumed an enormous
amount of, of our manufacturing capacity.



Harry: Did [00:52:00] their orders exceed your expectations of their orders?

Andrew: I think their orders exceeded everybody's expectations. you can be a
professional salesperson in Silicon Valley for 20 or 30 years and, and not see a
$500 million order.

you can go around the valley right now and talk to VPs of sales or VPs of sales
at, dozens of public companies who've never seen an order of that size. they
were bold and they were early. And, you know, when we, we started doing
business with G 42, nobody heard of them.

Everybody in the world heard of them mistakes.

Harry: was a resource planning mistake from you? I mean that nicely,

they're all mistakes in retrospect, we hadn't won them and we had the resources
for it, that would've been a resource planning mistake. I mean, I'm, I'm in the
business of, of making big bets and, making lots of mistakes, Harry.

What's the biggest

bet you've made with cereus? Work out.

Andrew: my bets here have, have been pretty good. to go to way for scale to
solve a problem that, nobody had previously solved. Gene Amal, one of the
fathers of our field failed. IBM failed. Ti [00:53:00] failed. everybody's failed at
this. We had a period of about 15 months between about 2017 and, early 2019,
where we couldn't make one.

We were running a burn of about 6 million a month, 7 million a month.

And we stayed with it, and our board stayed with it. the result was,

Harry: signs that it would work?

Andrew: yeah, we did, and we weren't running around like chickens without
our heads. We were going through engineering process. Each failure was, you
know, we did a full fa a failure analysis each time we fixed the cause.

We did another one, didn't work, did another one, didn't work. And each time
we got a little better and we got better and better and better, Then we solved it.
the first one that worked, the founders were in a tiny little lab that was a
converted conference room that for cooling, we had the windows open and we'd
blown a hole in the wall so we could get external, a chiller outside and poured
in.

And when we had it running, the founders stood there together and stared at the
box running, which is about as interesting [00:54:00] as watching paint dry.
And we stood there and we couldn't believe it. It was like we have just solved a
problem that for 75 years, the smartest people in our industry have been unable
to solve.

And we stood there for like half an hour and it was, it was one of the highlights
of, of my career.

Harry: Pretty cool. Alright, I'll give it to you.

Andrew: Yeah. So, so that, that, that was a, a big, big bet that that was, uh.

Harry: fair enough. I the six, 7 million a month burn. I'm like, all right, fair.
That's, uh, I'm almost picturing like angels singing and this like tears coming
down your face.

Andrew: You know what it, it felt like that and it was, you know, the brainchild
of my co-founders, it was their invention it was, a physical manifestation of
their ideas.
Harry: where are people investing today? Where they will completely lose
their shirt?

Andrew: the silicon industry is not place for 25-year-old CEOs, no matter how
smart you are. the returns to having built parts before in what we do are
enormous the number of different relationships that are necessary.

you need a relationship with the [00:55:00] fab. You need a relationship with
the EDA toolmaker. You need backend design engineers. You need logic design
engineers. You need IP relationships with IP providers. it has been an
extremely, difficult road for, young CEOs. On the other hand, young CEOs in
many of the markets you invest in have done extraordinarily well, particularly
where, They look like their customer. the reason that, the entire social
networking world was built by young founders is it they were building a
product for their friends. And that is an advantage, The reason that AI startups
who are doing, tools for other students, for coders are, are young, is because,
they understand the needs and demands of their target customer base
extraordinarily well.

that's an area where people are gonna get, clobbered is to take a mentality that
said, it's enough to be smart in this field, to build a good chip. That, that has
historically not been the case. that there are real returns to [00:56:00] having
done 15 or 20 of these in the past.

Harry: Where are people not investing enough, where they should be investing
more?

Andrew: there are this collection of extremely unsexy things that are, causing
tremendous pain across the industry. Data cleaning, your data pipeline. these
things are, you know, nobody, puts on their, their LinkedIn data pipeline expert.
And yet these are some extraordinarily valuable cats. nobody leads with, a
leader in the, the cleaning and tokenization of data.

and these are extraordinarily important, roles. many AI projects fail on those
fronts have nothing to do with the ai. they fail 'cause the data was a disaster.
they fail because everything except the AI was a failure. that's an area that, that's
profoundly underinvested in.

Harry: What do you think the data provision market looks like? We see surge,
McCaw, invisible, Turing, handshake, moving into it more and more. What
does that market look like five years? All of [00:57:00] them are above a
hundred million a RR. What the fuck happens there,
Andrew: I don't know. I, is a very curious market. know, scale,

Harry: it curious?

Andrew: well, scale sort of pioneered it. touring was in a different market
completely and pivoted to it and found great success in it.

there are these collections of others. I think clearly, the provisioning of value
added, tagged, or, evaluated data is really important. whether it's durable,
whether we get machines that do it, every bit as well as people. It is a question
that that's really hard to answer right now.

That's why it's curious is that clearly it's important now, and the question is, will
it clearly be important in three years? that's a, question I don't know the answer
to. Maybe I'm, you know, it could go either way.

Harry: What's your craziest prediction in terms of how AI reshapes the future
in five years? For example, Jonathan said, Hey, I think AI will create massive
labor shortages. create so many jobs for so many people that we will have
massive labor shortages.

Andrew: In five years, [00:58:00] absolutely wrong, I think, economic
dislocation, isn't resolved in very short periods of time. That might be true in 15
years, but, in the three to five year timeframe, I certainly don't believe that will
be the case. Mm-hmm. the adoption of AI or the diffusion of AI into the
economy, it will nibble its way in.

let's ask this question. alpha fold, sold, solved one of the hardest problems in
chemistry. A problem that had been open for years. Name a drug that's resulted
from it. Not one now, I believe there will be, but alpha folds four years old now.
this was a massive breakthrough for which the inventors were given Nobel
prizes.

Where's the drug? Show me the, the medical benefits. It will get there. It will be
important. Continuations of the model will have fundamental impact, but where
are the x-ray crystallographers who are displaced because of it? That was what
X-ray crystallographers were doing, only physically.

they're not outta work. in fact, there's more demand for them. think it will have
really [00:59:00] interesting, effects on the way we educate children. And that's
an interest of mine. you know, we, we've sort of been educating children the
same way since Alexander the Great was tutored by Aristotle, right.
And, and it was sort of like, get a smart person. They're older, they stand behind
you, they tell you what to do, read, you read it, you talk to them about it, they
correct your paper. this form of instruction has been sort of unchanged. Maybe
YouTube changed it a little bit in that you had different instructors.

But imagine a system where, for example, you made a set of mistakes in your
math work the result wasn't read on a paper. Oh, look, you got it wrong here,
but they compared the type of mistakes you made to the type of mistakes
thousands of other students made and said that for this group of mistakes, we
have found that the following workbook is extremely effective at remedying
this whole in their thinking, Imagine that, nobody does it. Nobody differentiates
and modifies the training [01:00:00] based on the type of error the students are
making, and that's exactly what you ought to do. so I, I think the way we teach
will change a great deal. what it means to be entry level in, uh, a company will
change a great deal because what entry level has generally meant in consulting
firms at investment banks has been doing shit work.

in particular, being really good at spreadsheets and writing summaries of other
people's research. AI will be better at that.

that will change a great deal. I mean, I always thought that was a terrible way to
spend an extraordinary, your, your 22 through 24 years, you are, coming outta
top schools. There's so much to be learned. There's so much, you can contribute.

but to do huge hours doing spreadsheets, I think there's vastly more productive
thinking that those students, that those young people are capable of and more
learning that they can do and therefore be vastly more productive in the
following years. And I think AI will, change that.

Harry: Final one for you, Andrew. What would you [01:01:00] do if you
knew? Knew you wouldn't fail or couldn't fail?

Andrew: I guess I don't, I've never thought of that. I, I look at it the other way
is that, every day I go to battle with Goliath every day. Every dollar we sell is a
dollar that if we didn't work at it, if we didn't think, if we didn't invent, if we
weren't 10 times better, would default to Nvidia.

And before I, competed with Nvidia, I competed with Cisco 15 years in every
dollar that we sold there. If we didn't build better product, if we weren't more
aggressive, if we weren't more creative, would've defaulted to the market share
leader. And I, I think for me, in my career, I take great pride in facing every
day.
The most wicked curve, the curve ball pitcher for your cricket example, you
know, the, the, the scariest spin bowler, the scariest speed bowler. I enjoy that,
that that is something that, in a quiet moment you sit back and say that, that, I'm
competing with every disadvantage against the absolute best in the world
[01:02:00] every, every single day at work.

And I love that. and what's more, everybody's betting against me except a very
small group of people who you named, who stood up early on and said, you
know, maybe he can beat them. that's the life I've, I've chosen and the, the
career I love.

Harry: that is such a good end as well. You know, I do obviously many shows
there are some ends where like, oh, we can't end like that. That is like a
depressing, that's a fantastic end. I so appreciate that. I so appreciate you. You
know, you're my go-to when I'm trying to understand what the fuck's going on.
and so thank you so much for explaining this to me today, dude.

Andrew: Well, I'm happy to, to jump on, my view, of your, LinkedIn post, by
the way, is there, there are two, exactly two things I've read in my life that, feel
like they understand what entrepreneurship is. And the first is Ben Horowitz's
book. The Hard Thing About Hard Things, and the other is your tweets and
your, your, your LinkedIn post.

They have the feel of, what my life is. This notion that, that somehow you can
achieve [01:03:00] greatness. You can build something extraordinary by, by
working 38 hours a week and, and having work life balance. that is mind
boggling to me. It's not true in any, any part of life and your willingness to jump
in and say, no, that's not how it's done, guys.

you can have a great life. You can do many really good things, and there are lots
of paths to happiness. But the path to build something new out of nothing and
make it great isn't part-time work. It isn't 30, 40, 50 hours a week. It's, it's every
waking minute. And of course their costs. you know, it's probably true for world
class athletes too.

If you listen to, What Ronaldo talks about. I mean, he worries about everything
he puts in his body. He trains every single day. They work on rest, right? Rest
isn't rest. Rest is something you work on. So your body rejuvenates faster. this
isn't 30 hours a week or 40 hours. These guys are the best in the world at
everything.
Harry: But before we leave you today,

I love seeing the team come together to make this show happen. What I don't
love is trying to keep track of all the [01:04:00] information, the data, and the
projects that we're working on across dozens of platforms, products and tools.
That's why we use Coder, the all in one collaborative workspace that's helped
50,000 teams all over the world get on the same page, offering the flexibility of
docs with the structure of spreadsheets, Coda facilitates.

Deeper teamwork and quicker creativity and their turnkey AI solution. The
intelligence of Coda Brain is a game changer, powered by Grammarly. Coda is
entering a new phase of innovation and expansion, aiming to redefine
productivity for the AI era. Whether you're a startup looking to organize the
chaos while staying nimble or an enterprise organization looking for better
alignment, coder matches your working style.

It's seamless work space connects to hundreds of your favorite tools, including
Salesforce, JIRA, Asana, and. Figma helping your teams transform their rituals
and do more faster. Head over to coda.io/twenty VC right now and get six
months off the team plan for [01:05:00] startups for free. That's Coda, CODA.
IO slash two zero VC and get six months off the team plan for free Coda io
slash two zero VC and talking about precision, that's exactly what Brex brings
to your finances.

So when Brex was founded, it wasn't just about creating another financial
product, it was about solving the really gritty challenges that founders faced.
Daily. Let's be honest. Building something from the ground up is hard enough
without dealing with clunky, outdated banks that pile on fees and leave your
cash idle.

B Brax is different. It's the financial stack that scales with you no matter where
you are in your journey. From corporate cards to maximizing your runway to
earning yield on your cash. Brax was designed with founders in mind to make
every dollar go further so you can focus on building. And here's what really
stands out to me.

Brex combines the best of checking treasury and f. The IC insurance in one
powerhouse account, you can send and receive money globally at lightning
speed, [01:06:00] earn yield from day one, and still access your funds whenever
you need. Plus, with 20 x the standard protection through program banks, your
cash is not just working harder, it's working safer.
Two, it's no surprise that one in three venture-backed startups in the US with
companies like Anthropic, Coinbase, and Robinhood. God, these companies are
incredible. Trust Brex to help them grow. If you wanna join the smartest
startups on the planet, head over to brex.com/startups and see what they can do
for you.

And talking about trust today, customers expect it faster than ever, and that's
why over 10,000 global companies trust Vanta. Vanta automates up to 90% of
the work for in demand compliance standards like soc. Two ISO 27,001 and
more using smart AI to centralize workflows, manage risk, and get you audit
ready in weeks, not months.

So you can stop chasing paperwork and start closing deals. And a new IDC
report found that Vanta customers achieve 535. [01:07:00] Thousand dollars per
year in benefits. That's insane. And the platform pays for itself in three months.
I had no idea about these. Whether you are growing fast or just getting started,
Vanta connects you with trusted auditors and experts support.

To help you build trust with customers, get a thousand dollars off your first year
at vanta.com/two zero vc. That's vanta.com/two zero vc. You have now arrived
at your destination.


---
type: 20vc-episode
guest: "Zach Lloyd"
company: "Warp"
role: "Founder & CEO"
episode_type: interview
date: 2025-10-19
youtube: "None"
transcript: "https://20vc.substack.com/api/v1/file/0b025357-c916-4407-a249-6cd44c8afb90.pdf"
newsletter: "https://20vc.substack.com/p/20vc-newsletter-19th-october-2025"
tags:
  - 20vc
---

# Zach Lloyd — Warp

> Founder & CEO @ Warp | 20VC Interview | 2025-10-19

## Key Takeaways

---

## Links
- [Watch on YouTube](None)
- [Full Transcript (PDF)](https://20vc.substack.com/api/v1/file/0b025357-c916-4407-a249-6cd44c8afb90.pdf)
- [Newsletter](https://20vc.substack.com/p/20vc-newsletter-19th-october-2025)
---

## Full Transcript

[00:00:00]

Harry: This is 20 VC with me, Harry Stebbings. Now I am so excited for the
show today. Today was probably one of the most, I don't know how to say it.
Maybe loose discussions that we've ever had. There was no structure to this one
for sure, and it was one of the most fun shows, by the way I've ever done. Zach,
the guest was.

Incredible. So time for the guest intro, Zach Lloyd, founder and CEO of Warp.
They are adding a million of net new a RR every single week. They are the next
generation developer terminal reinventing how engineers build and collaborate.
They've raised over $70 million from the like of Sequoia, gv, Dylan Field, Eli
Gill, and even the legend.

That is Mark Benioff. Now, before founding Warp, Zach was a principal
engineer at Google where he led development of. Google Docs. I mean Google
Docs. What a hero. As I said, Zach was one of the most fun guests I've ever had
on the show, and he really put up with a lot of shit from me in this episode,
[00:01:00] and so I cannot wait to hear your thoughts.

Let me know your feedback, Harry, at 20 vc.com.

Harry (Adverts): But before we dive into the show today on this show, we care
about velocity. Most teams lose it in code review, not in writing code. Now,
code Rabbit fixes that the second a PR opens, it leaves clear line by line
comments, calls out what the change might touch, and offers one click fixes.
You can teach your organizational standards using your own custom
instructions, such as Cursor or Claude Rules, and enforce them on.

Every PR Code Rabbit has so far reviewed more than 13 million PRS and
installed on 2 million repositories used by over a hundred thousand OSS
projects. If you want to cut code, review time and bugs in half, try a free
month@coderabbit.ai with the Code two zero vc. And while Code Rabbit keeps
your code clean, Tessie makes sure AI handles the rest hiring shouldn't take
[00:02:00] months.

Tessie's AI agents work 24 7 to keep your recruiting pipeline full, instantly.
Reviewing inbound applications, sourcing top talent, rediscovering those hidden
gems in your a TS, detecting fakes and pre-qualifying candidates before your
team. Even starts interviewing. What makes Tazzie so different? Well, it's all in
one AI agents across the workflow from open to offer a built-in a TS plus a 750
million candidate database.
That means added recruiting capacity when you don't have enough hours in the
day. And that's why companies like Mutiny Pocus and Orum and even public
companies like Real already trust Tazzie with features in VentureBeat.
TechCrunch, fortune and Axios, you have to check them out. Tazzie AI slash
two zero VC for 10% off your first year and start making hires in days after
Tazzie streamlines your operations.

Warp Dev helps your team ship faster. AI coding [00:03:00] is everywhere, but
most of it, honestly, it's pretty chaotic. Code that is almost right, but you don't
really understand Well. That's why Warp exists with Warp. The old lines
between terminal and IDE disappear, it's a seamless environment for coding
with agents where you can prompt, plan, review, and ship.

Production Ready code, edit files in app. Review diffs as you go and deploy
straight to production without switching tools. Warp tops the benchmarks.
Literally number one on terminal bench. Top five on software engineering
bench. Verified and is trusted by over 600,000 developers and used by 56% of
the Fortune 500 engineering teams making it one of the fastest growing AI
companies with revenue.

Growing 30 x this year with warp, you don't just get speed, you get code you
can trust. The average developer saves five hours a week with Warp. It's almost
half a day. Try Warp for free at Warp Dev [00:04:00] slash two zero VC and to
get Pro. For only $5 for your first month, use the Code two zero vc. That's two
zero vc.

You have now arrived at your destination.

Harry: Zach, dude, I'm excited for this. it's been a long time coming, so thank
you so much for joining me today.

Zach: Yeah, I'm psyched to be here.

Harry: Dude, I would love to start Google Sheets. You led engineering there.
Rewrote it from the ground up, is what I was told in my extensive referencing,
which is a venture investor is almost fuck all, because we don't do diligence
these days, but sorry, I'm just going for it today.

 it's gonna be a great show, dude. Uh, so product and design lessons from
rewriting Google Sheets.
Zach: First thing from rewriting Google Sheets I would say don't, don't rewrite
things. we rewrote Google Sheets because. It's a crazy scale. And so, you know,
if you have something that has million plus users, which is what it had at the
time, I think it's now like a billion users. It really matters that the thing is
[00:05:00] awesome. and so it's worth the effort of like 30 to 40 engineers for a
couple years to like get it right. Right. But I would say for the audience, for this
show, which assume is more founders like rewriting is like a horrible idea. it's
like pausing time.

Harry: If you don't rewrite, you not just do sticky tapes with technical debt
though, like I'd say rewrite and rewrite early, like make a decision, make it fast
and go.

Zach: so for the startup people out there, I think try to pick the right thing to
start is like a little bit better advice. So one lesson I did take for this is for Warp,
for instance, we built it the hard way to start, meaning like. you know, I could
kind of see around the corner, like if we built it on sort of web tech or whatever,
we're gonna run into a bunch of performance problems, which is a lot of what
we were trying to fix with the, sheet rewrite. like good engineering matters, but
I think it's highly dependent on like where you're at in the stage of building a
thing. And so, yeah, rewrite, if you have like crazy product market fit and you
know, a hundred million plus users, it needs to be perfect. If you're really early.
I [00:06:00] think rewrite is a little scary.

Harry: But if you rewrite with a shit ton of users, surely you're just gonna have
a massive time lag for a load of people waiting, like rewriting when no one
gives a shit. I'm sorry. You are, you are the builder and I'm the venture
capitalist.

But it just doesn't make sense to me like why rewriting, pausing.

Growth. Like pausing progress with millions waiting versus when no one gives
a shit.

Zach: I guess if you literally have no one, fine. But my take is like in startup
land speeds everything and the antipater that I'm looking out for is like, okay, I
was a Google engineer, building for tons of scale and then go to a, found a
company. And like, it's very easy to get like anchored on sort of the beauty of
the engineering and trying to get the engineering perfect.

And if you don't have a product that anyone cares about, I think like that's a
crazy place to be spending your time at the beginning of a company. It should
all be around. Like, can I build something that people want to use? And there's a
engineering mindset mistake I think that [00:07:00] people will make where it's
like, well, they don't want to use it 'cause the performance isn't like 30% better.

That's, that's not a good place to spend time.

Harry: internally at Google.

I walked with one of the biggest execs in the world the other day and they said
that Sundar is a terrible leader, but the, well, we said we'd be spicy today, so
fuck it. You, you, but he has brilliant managers beneath him and they are very
decentralized in their decision making, and so it actually works very well.

Would you agree with that? And when you assess the state of talent within
Google, having been there for, you know, several years would you agree with
that? Are

Zach: I think Google's a risk, like I would never have said that, five, 10 years
ago. I find myself using chat GPT more and more and so I think they have
innovators dilemma problem. this isn't directly answering your talent question,
but I

Harry: no.

Zach: it's more of like incentives, where it seems like they're really slow on AI
is like my take

Harry: you are not impressed by Gemini.

Zach: I am definitely not impressed by how Gemini is like integrated into their
consumer [00:08:00] products. I think Gemini, as a model is, good. It's in like,
like the three models that we care about at Warp or Gemini, uh, GPT five, and
Claude. So it's, it's like there, I don't know. They had a lead, they wrote the
paper on Transformers. It's not an awesome outcome from my standpoint. And
then from like a talent perspective, there's still a ton of very, very smart people
at Google. It just seems like a super risk averse place to me right now. like the
people I know who I respect a lot to be clear, are by and large staying at Google
because they are, they're super well compensated and it's like a very, very like,
cushy thing, but they, it tends to like keep around the sort of like people who
want to take fewer risks.
So, I don't know. I'm not, I'm not loving what I'm seeing from the outside. but I,
I, I had an awesome experience working there back when I was an engineer.

Harry: Sell all of my position in Google. Sell, sell it. Uh, I, I, I, I'm a big buyer
of Google,

Zach: Yeah.

So here's the bull case on Google is they have the, they have crazy [00:09:00]
distribution. They have a crazy brand. They have amazing infrastructure. Uh, so
it's like, I don't think Google's like beyond hope, but like,

Harry: crazy distribution, crazy brand. Gemini could be integrated much better
in time. They have, they have YouTube,

they have Waymo. They have 10% of stock.

Yeah.

Zach: been in a Waymo? Waymo is crazy.

Harry: No, no. I've never been, but I think it could get,

Zach: is a, Waymo is the, is the coolest product I've been in in a long time.

Harry: I agree. Okay. And that could be a mega part of it. They, they have also
10% of SpaceX. I'm like, there's a lot to like here.

Zach: Yeah. But they have like a, I think the culture's super slow. And so I
don't think a super duper slow culture. they're going against very, very
aggressive fast moving companies. Like I think open AI's execution on chat
GPT is really good, but maybe the inertia of just being so big and having such
distribution is enough.

I don't know.

Harry: When you compare Gemini, clawed and GPT, how do they compare for
you internally today?

Zach: the [00:10:00] two leaders are GPT five and the cloud models. And so
we measure them, like, first of all, it's like, it's not so much gut. It's like we
literally, we, we have a whole bunch of benchmarks. We run SW bench, we run
terminal bench, and GPT five are the two best Claude, They have like different
personalities, which is kind of interesting.

Like when you're using them for coding, like Claude's a little friendlier. GPT
five is like a little bit more like, me do a whole bunch of thinking. Take it takes
a long time, is my, my biggest issue with it. But then it tends to come back with
something that's really good. and at the moment, Gemini, which is on two five,
and I, I'm sure they're working on Gemini three is not as good.

Harry: Would you be as direct or blunt as saying that GPT wins consumer and
anthropic wins Enterprise?

Zach: would say that GPT wins consumer, I don't know who wins Enterprise.

Harry: Yeah. 'cause they have so much of an emphasis today on Codex that I'm
just like, I think they could win enterprise and developers too.

Zach: I, I think developers [00:11:00] is open I'm biased here 'cause the, the
situation that I want actually is competitive dynamic with the, at the model layer
for. the coding models. I don't know that anyone has like a super strong moat at
the API layer, just to be

Harry: If, if you play out the next five years. You said that I really appreciate
you being open about the bias nature of your opinion. Most people, especially
people like me, VCs, aren't, we just state these views. They're hoping no one
knows that we have massive positions in these companies. Um, but when we
actually think about what that market looks like in five years time from the
enterprise developer market, can you help me understand what you think it will
look like?

Maybe putting biases aside.

Zach: yeah. So just in the development space,

Harry: Yeah.

Zach: the market is gonna be, there's gonna be two pieces to it. So there's gonna
be like, a set of interactive productivity tools. think of like things that
developers literally are using. you're sitting there, you're telling an agent what to
do, you're like, Hey, write this code for me.
Help me understand this production problem. And then there's [00:12:00] gonna
be a set of automation tools, that's gonna be more like, okay, crash came in.
what was the root cause of it? Is there a PR that can fix it? And it's gonna do it
automatically, and you'll have some developer who's reviewing it. Those are
gonna be the two, the two classes of things. I think over time the automation is
clearly like a better market, the more valuable thing. companies are gonna
wanna like just pay for stuff that automatically creates software. It's a huge
market. It goes into the labor spend a little bit. But I think the productivity piece
is also, I don't see it being, I'm just guessing at timeframes here, five years is a
long time with these AI models, just to be clear.

But in the next few years is what I see happening. So those are the two big, the
two big buckets. And I think more and more we'll go into automation.

Harry: When you look at your dabs today, internally, what are they using? Are
they using claw code? Are they using casa? Are they using cognition?

Zach: They use Warp. we're now fully into like the coding agent space, like
history of the company. Obviously we started as a, as a terminal, but the,
terminal form [00:13:00] factor is the preferred form factor for doing agentic
work at this point. Whether you're using like a terminal app, like Cloud Code,
uh, in Warp, you just literally use the Gooey app to do it. And so every single
coding task we do starts with a prompt, which is the big shift in productivity
that's happening right now. We don't necessarily finish every task with a
prompt. there's certain things that are too hard, it doesn't matter which, which
tool you're using, but everything starts with a prompt.

Then we try to get all the way to completion if we can with the prompt.

Harry: do you think Prompt is a sustaining input to get desired output? Like in
three years time, will we still as users be prompting.

Zach: It's funny, it sounds kind of stupid. It's like, oh, start with a prompt. Um,
the general thing is like, are you starting with some expression of human intent?
And like, I, I'm using prompt for shorthand of that and like, it's more than just
you're writing some paragraph or something.

It's like what's gonna matter more and more is the total context that the model
has available to it. And that context is gonna come from more and more places.
It's not [00:14:00] just gonna come from like a person saying to do something.
but yeah, I think like generally, if you're doing something creative and it's not
totally deterministic what needs to be done, there needs to be some expression
to the computer from. a builder to do the thing. it's not gonna read your mind.
So, yeah, I think it's like, even that sounds kind of stupid. I think that is the
thing.

Harry: When we look at like available budgets, you know.

Do you think that CEOs, CTOs, CPOs are willing to spend multiples of what
they already do on these tools to get developer productivity increased?

Zach: If you're comparing it to developer productivity tools, like, a million
percent. Yes. the budget for like developer productivity tools is not that big. It's
like

Harry: It's shit.

Zach: Postman or what, like, I don't know what your, like your old school
developer tool is. it's like a small dollar amount per seat per month. And you're
using it to increase the productivity of someone who you're paying like
$200,000 a year.

Harry: my friends is Jason Lakin from Sasa, and he says that we'll get to a
stage where it could be up to [00:15:00] like $10,000 per month per developer.

Zach: Maybe, I mean, again, I think like thinking of it per developer, thinking
of it through the productivity lens, like you're thinking of it in terms of like, how
do I multiply developer's output? I think it's some point you just get into the lens
of like, what's this software worth to my business? Which is, a lot like every
company at this point, to a greater lesser extent is like a software company.

It's the biggest lever that they have. And so, it's gonna be orders of magnitude
more that companies are willing to pay, for these types of tools. 'cause they're
just, it's not, it's not a productivity tool.

Harry: Okay. It is not a productivity tool, but we do look at productivity gains
as a measure of effectiveness. we are X more percent productive. We create X
percent more code in less time, whatever, whatever. Are we actually seeing
productivity increases in terms of output that are meaningful and measurable, do
you think?

Zach: In terms of whether we're seeing productivity gains, I think no one
[00:16:00] knows. Like there's a bunch of studies that show not really. like I,
again, I would, I would be like a little more nuanced. So if you are using
lovable, yeah, of course. Like you're going from like, I can't do anything to, I've
built an app that's like insane. and so the cases where it's like zero to one. Yes. I
think when you go into the professional development environment, which is like
where Warp is focused, there's a bunch of studies that show not really it's sort of
like the noise that's created by, who are attempting to use like a vibe coding
technique on a production code base, kind of outweighs or can slow you down.

And so I think that's the big problem with it right now. And this is what we see
when we talk to companies. It's like they all kind of rush to deploy some sort of
agen coding solution. No one really knows if it's working and whether it's
working or not. Depends a ton on like how you use it. and so, you can't just vibe
code with it.

I'm not a huge vibe coding person to begin with. And so there's like a way you
have to use it in order to get productivity gains and then it [00:17:00] needs to
be figured out how you're gonna measure those.

Harry: Would you say Ag agentic coding tools have product market fit? I know
that sounds utterly ridiculous when you look at cognition's, $10 billion price and
cursors, $28 billion price, you'd say, of course they do, you moron. But if you
have customers that are genuinely questioning productivity gains and kind of
going, nah, do they?

Zach: so great question. in like the prosumer market, there's like strong product
market fit, but it's not, I would say it's not a great market. meaning like they're
very high churn, price sensitive customers who are building things that don't
have a ton of economic value in the enterprise market, I actually think the thing
that has most product market fit is like auto complete, which is not the sexiest
type of ai.

So it's not agentic ai, it's like cursors original product or even copilot, if you're
doing like hand editing of code, it's like clearly helpful. To have the thing like
show you the gray text and kind of read your mind when you get into like Warp
or [00:18:00] Claude Code or Cursors agent. or yeah, even I think cognition's its
own beast, honestly.

It's like a, it's more of like an automation thing. I think it's like really early in
that market and people, there's like a lot of like intuitive signal that it's helpful,
and there's a ton of willingness to pay. But in terms of like, will companies get
measurable impact from it, it's gonna happen.
Like, It's gonna be transformational and it sometimes is transformational now,
but not with every coding test and maybe not in the aggregate.

Harry: Does it make one X devs or engineers 10 x or does it make 10 XA
hundred x? Like who does it favor the lower quality or the higher quality?

Zach: Favors the higher quality. And this is counterintuitive, like causes a lot of
problems with people who don't know what they're doing in a professional
environment. so if you are a newer engineer, or more junior engineer or maybe
just like not that sophisticated of an engineer, it's a problem to me because want
to use these tools the most [00:19:00] but they end up producing code that you
don't understand or that can't be shipped or they won't get through code review
or that contains security bugs. Whereas to successfully use these tools, you need
to be like more sophisticated, smarter, more experienced. And if you can do
that, you can get a crazy productivity gain ' but you already kind of need to
know what you're doing. So I think it's a little bit counterintuitive. Like would
much rather have senior developers using these tools. There's a little bit of a
paradox in that they don't necessarily want to use these tools, like they feel like
they can do the thing themselves. But if you get a senior developer who's really
good at, at wielding these tools, it's very powerful.

Harry: Would you say in five years time, we will have more or less engineers
in dev teams?

Zach: I think we're gonna have less, I think we're gonna have fewer, more
senior engineers who are managing the work of a lot of agents.

Harry: do we see the collapsing of roles when we look across the dev spectrum
now, you know, you've got products, you've got eng, you've got design. Do we
see the [00:20:00] collapsing into these like superhuman product builders, or do
functions remain intact?

Zach: In terms of collapsing of all the roles, if I had to like design a role for the,
Uber person who builds with ai, it would be like a product oriented senior
engineer. we see a lot of like managers and designers who will use the tools to
make prototypes, and that's actually very cool. But to get stuff to production, I
think what you want is like someone who like I said, more sophisticated than
the agent. and I think there's a real cap on what a product manager or designer is
able to build with this stuff right now. So I guess short answer is I don't really
think so.
And if there was like a role I would design, it would be a product minded
engineer.

Harry: How do you think about the shittiness of prosumer, but then also the
challenge of needing to go in top down from enterprise and get adoption, which
is much harder.

Zach: Yeah. So our motion is PLG. so I think I've like overstated, like how,
these tools [00:21:00] aren't working that well for real devs, they are working
well for real devs in real, you just, you need to learn how to use them. Right.

Harry: what does that mean? Learn how to use them. Right.

Zach: Yeah. So if you're like, um. Someone building in a sort of naive way, and
I kind of blame vibe coding for this. Like what you'll do is, uh, be like, build me
this thing that looks like X, And the build me this thing that looks like x doesn't
tell the agent how the thing should work, at least from like the engineering side.
and so if you do this on like a big complicated code base, it fails or like it
produces something that just like wastes a bunch of your time. It might like
iterate and go in circles for hours and finally get you something that like seems
to work from a user perspective, but it won't be something that you'll actually
want to. release. so to make it work in a production setting, it's like you need to
tell it how to build it, and that means you need to understand the code. And so
it's just, it's very liable to like kind of lazy usage, which doesn't work [00:22:00]
well.

Harry: Do you worry about the security of a lot of these builders? When you
look at a lovable or a rats, you know, security is often questioned. Is that a fair
concern?

Zach: I think it's a totally fair concern if you're doing it the same way on like a
code base that matters. Yes.

Harry: Dude, do your margins matter? I know that seems strange, but like, you
know, I get, I'm in a lot of companies and, uh, I get top line revenue. You know
what? I never fucking get, never get margin.

Zach: tell you.

Harry: No. How does it matter? No margin. It is like, Harry, why are you being
so negative? I'm like, oh, I'm sorry. I'm, I'm so anti founder friendly does
margin matter in this cycle?
Zach: Do margins matter? I think like, yes, definitely. If only because let's say
your users cost you money, it just gets super duper expensive, the faster you
grow. And that's like, so you

Harry: Are you, are you positive margins?

Zach: not right now, but not like we're, we're working on it. it's, it's really,
really costly.

I mean, so [00:23:00] to talk about like the pricing stuff,

 here's the fundamental problem with pricing these AI products is like.
consumers expect, like if you're going for the pro members, let's say for a
second, not the enterprise, because enterprise we're, we're margin positive. but
on the consumer segments it's like, it's very, very hard. They expect something
that looks like SaaS pricing.

Harry: Yeah.

Zach: they expect like, you know, 20 bucks a month, 50 bucks a month, 50
bucks a month is a lot. you get more than that starts to get into like their
comparing to like their gym membership or something.

Right. the more they use it, more it costs you, so the better your product market
fit in a sense of like, the product is getting better. where's your businesses from
like that perspective. and to some extent I think it's actually fine to subsidize,
like if you're subsidizing users who are going to turn into enterprise leads, think
it's like super smart to subsidize people who are building. know, personal
websites where there's no strong economic incentive,

Harry: doesn't n just go in the marketing budget. Like, you know, when you
look at the, uh, I [00:24:00] completely agree with you.

The

economics are shared when you have the massive funnel and you are doing
PLG and converting a very small number. But do you not put that in the
marketing budget and just subsidize

Zach: Yeah, I think to an extent you do that at some point though. It's like if
you're growing so fast Warp is not growing really fast, right? Like, you know,
million dollars in ARR every week,
Harry: You are doing a million a week?

Zach: Adding of net new a RR. Yeah.

Harry: can you just say that again?

Zach: we're now adding a million net new a RR every week, or even less,
honestly, recently.

It's accelerating people love the thing, however, it's like, yeah, you can count
you, sorry, do the accounting for it however you want. you know, from our
perspective, we want to be growing that in a sustainable way. So I, I think it's
crazy to just be like, no, margins don't matter.

It's some point you're gonna run outta money if you're growing really fast. And
though we could probably go raise more money, like

Harry: You,

Zach: But

can I ask you, like, how would, how are you thinking about that as an investor
when [00:25:00] you're seeing a company like Warp that's growing, we're
growing extremely quickly? I think we're still like, I think that's outlier growth.
How do you think about, how sustainable that growth should be?

Harry: my honest, again, my, this is a very, I'm loving this show 'cause it's so
natural, but I'm also, I'm candid here.

I, my worry or the risks that I'm underwriting here is you really have to believe
that the standalone businesses that will be built outside of the core model
providers, and I think Codex and C Core code are gonna be incredibly difficult
competition with immense, immense budgets.

That would worry me. And so my question to you, it's not like the, oh, is it like
super shitty quality customers? I think if you're using Warp, you're probably a
pretty high quality dev.

I'm more worried that you are switchable and I think the switching costs are
pretty low. And so I think actually the ability for people to switch to an
anthropic or a open AI is pretty high.
I would share the same, by the way, for cursor even.

Zach: [00:26:00] I know I'm not supposed to be interviewing you here, but like,
do you think that, um, there's some inherent lock in that they have that, the other
companies don't have?

Harry: No, no. I, I don't at all. I just think they have a shit load of cash. I think
they will be hoovering up talent. and I think they can outspend everyone.

Zach: Yeah, I think the competition from the model providers is a big, is an
issue, but it's like why

Harry: do you, how do,

well, well, I, I get you. I get you. And I don't, it is a really shitty VC thing of
like, well, Google could just do that. And that was always the case that, well,
Amazon could just do that, but here they could and they are.

Zach: So I guess I, I'm not gonna speak for like the whole app industry, but for
Warp, it's like a different product. So every other single product out there either
a clone of VS code, which again is Codex or Cursor or Windsurf or whatever.
They're all the same product or they are terminal apps. I do think, [00:27:00]
like even if you believe that it's like really cheap now to clone software, it's
really not cheap to clone, warp. we were building this thing for five years and
it's a very, very differentiated product experience. I don't think that's enough.
Maybe I feel like there's like a VC trope right now around like, well, product's
not a mote.

I think that that's like kind of bullshit, especially when everyone else in the
market has the same product. So I, I'll speaking for Warp, I actually think we
can differentiate on the product quite a bit. if you believe though that it's all just
like, they're all the same thing and it's like has the most money wins, I guess.

I see what you're saying, but I don't agree with that

Harry: When you say product is emote in a way that people don't believe, what
you are essentially saying there is that switching costs are high because of
product quality. How is that?

Zach: With some amount of, like, again, I don't wanna like say like lock in it,
but there's stickiness in the product. There's stickiness in features
Harry: I'm so sorry. In in what way?

Zach: So there's stickiness just in like the product experience itself. It's like,
okay, I've become accustomed to this thing.

there's stickiness a little bit in the fact that, you know, we have a ton of users,
we have way, way more users [00:28:00] than, than Cloud Code, for instance,
or Codex. We have 700,000 users because we've been doing this for years.
That's not stickiness, but that's like, there's a great funnel.

Harry: do you have more users than code?

Zach: I'm like 98% sure of that. Yeah.

 so I can tell you part of the reason I believe that is because of where we sit in
the stack, I can actually see how many people are using cloud code in Warp.
And I can see the trends of all these other products, which is is an interesting
thing about where we are. and it's not super high volume

Harry: What trends are you seeing?

Zach: So every time one of these model providers puts out a thing, whether it's
Cloud Code or Codex or Gemini, you see like a temporary spike in their thing.
people using it within Warp. And I think the nature of the developer market,
which is kind of over, I don't know, underappreciated, overlooked, whatever, is
like just wanna try the newest thing always.

it's a fragmented market. They wanna try the newest thing. Again, this can work
against Warp as well,

Harry: Okay.

Zach: these other things are basically equivalent. Like they're all the same
[00:29:00] product, whereas Warp is not. and I can see I, you can see the spike,
you can see it settle down. I don't think like the model providers based on the
data I'm seeing are winning here. I think honestly, if I look at the space, the one
that comes up the most is Cursor. I think execution is really good,

Harry: what Cara doing Well.
Zach: I, I think they're their fundamental product of like auto complete is really,
really good. they're like a better version of copilot and copilot. It's actually, it's
ama again, I think it's a testament to what startups can do. Like copilot had their
product and you might be like, why did Cursor win?

Cursor won? Because their thing was like, better. It worked better, it provided
like more accurate suggestions and developers care about that. So that, that
wedge was really good. The switching costs into it was really low. And then
Cursor I think has been really fast. with Enterprise. I don't think cursor's like
agent product is that awesome. they've done a really good job. Everyone knows
Cursor.

Harry: Well, Microsoft just to sleep at the wheel there, like they had co-pilot.
What the fuck?

Zach: like the repeated [00:30:00] story with bigger companies who, don't have
the same pressure to innovate. yeah. They were asleep at the wheel. They had
copilot. It's not as good. it's literally, it's like a bunch of, like, I, I know the, the
guise at curse. There's like some smart people from MIT who are like, they were
actually working on something else.

and then they just kind of out executed on the auto complete part, which again, I
don't think auto complete is the future. So I don't feel like I'm like seeding
competitive ground here to cursor. The future is more like developed by prompt,
but really, really good execution on their part.

Harry: Our curse of paying massively for talent. I've, I've spoken to so many
people and like,

Zach: As far as I know, like they are, they're paying massively for talent.

Harry: do you feel the pressure to pay massively for talent?

Zach: Yeah. I do. It's like a super competitive space, like I think we can offer,
because we're like

Harry: I.

Zach: like we can offer more equity. they can probably offer more cash, but
yeah, it's like a crazy, crazy space that we're in right now. Very competitive,
which again, I think, think [00:31:00] reinforces the, like, of senior engineers is
not going down. it's never been more competitive for us to hire someone. Good.
Harry: as a vc, part of my core morning activity is tweeting shit that will
probably be regretted later in the day. but I tweeted that I've been investing for
10 years and I've never seen such frothy environments. 200 X revenues, insane
packages, like insane packages for engineers. just nuts, dude.

Zach: Do you, you mean in terms of like the VC valuation or what people are
getting paid or just the whole,

Harry: I, I mean, the environment itself is just fucking nuts. Nvidia investing a
hundred billion dollars into open AI is fucking nuts.

Zach: Yeah.

Harry: For them to then go and spend on Nvidia chips like,

Zach: do you, I think it's like, do you fundamentally believe that this is
transformational technology? If you do, I think, I mean, it's crazy, but it's like
not crazy. I think it's I'm a skeptical person by nature, I am a full [00:32:00]
believer that, AI is going to change every single business. So

Harry: think you can.

Zach: losses.

I put it that way, but there's also gonna be some big winners.

Harry: Well, I think, you know, bubbles are often associated with bad, and I
think you can have good bubbles, which is like, this is a bubble, which will lead
to a huge amount of money lost, but with a huge amount of technological
development made.

Do you think it will have the short term impact that people think it will?

Zach: I think it's gonna depend a bunch on what industry you're in, what the
short term impact is. I think for highly competitive, unregulated things like if
for startups, for SaaS businesses, I think it's gonna change everything for
knowledge workers. If you're not in a regulated industry, I think it's a big deal.

Harry: for SA businesses, it changes everything.

What do you mean by that?
Zach: I think what I mean is like if you're working at, there's a few different
angles. There's the business angle and there's the worker angle. I think the cost
to start a sort of. Software driven business is gonna go way, way, way down.
[00:33:00] That's one thing. I think from a worker perspective, if you are
working at a place like I'm gonna pick a random company, Salesforce, and
there's no real regulatory blocker for the deployment of ai and you're in like a
competitive market, AI is gonna be deployed really, really rapidly and change
what daily work looks like. I think if you're in like the healthcare industry the
government, and it's like I'm still filling out paper forms when I go see my
doctor right now, it's less a question of like, is the technology, transformational
than like, are the incentives there to deploy the technology and like I worry that
it's just gonna take a long time.

Harry: Do you think this is a three year thing or a 10 year thing? I'm
constantly, uh. Thinking about No, no. But like, you know, we often
overestimate what we can do in a year and underestimate what we can do in 10.
And it takes longer than we actually think.

Zach: I think it's more like a 10 I think like, again, the technology's gonna run
way ahead of the deployment of it, just 'cause the deployment of it takes a long
time. You'll see the [00:34:00] deployment go fast in industries where there's
not a lot of barriers. This isn't like the most profound point in the world.

But if you go to the DMV, you're still gonna be dealing with like some
annoying old school stuff because it's just hard to deploy technology in certain
areas.

Harry: So adding a million a week, at what point do you go? Shit, we need to
really focus on margin and actually making this a really efficient business.

Zach: We are doing it now maybe you could tell me as a VC is stupid, but like
you know, we send a big check to Anthropic. We send a big check to, open ai.

Harry: If I pay you a dollar, how much goes to anthropic?

Zach: I don't know if I wanna like explicitly like say that right now, but like,
they get a lot of, like,

Harry: I
Zach: say they get, they get a dollar. Let's just, let's just say, let's say that for a
second. and so I dunno if I'm gonna get in trouble with, uh, investors or
whatever for

Harry: Are you kidding me? Compliance is gonna kill me for this episode.

Zach: No, but let's, let's, let's not put a, let's say it's, it's taking a lot of it,
[00:35:00] um. And so what, what we're doing, again, because it's growing so
fast, which I think

Harry: Hmm.

Zach: good, I think it makes sense to be like, do we make the, the usage of
these models more efficient? How do we change our pricing so that it's like
more aligned with customer value?

So we make more money as users use war more, not less money as users use
war more. it's a big focus for us right now. the trick is like, can we do it without
harming growth?

you know, that's like where this question of like, the smarter thing for us to do
is, is to like, just take it to a certain point.

Keep

Harry: What is,

Zach: more capital.

Harry: what does a, what does Andrew say?

Zach: Andrew says, we are in an awesome spot and should like get the margins
a little bit better and then raise more capital. Basically.

Harry: That's such a VC thing. It's like, hey, keep growth high, but get better
margins and then go.

Zach: ba basically he Andrew's not in there being like, well what we could
change the number of requests we offer on this plan [00:36:00] by why? So he
is like, you know, he's like, we're doing awesome. We have a thing people love.
Don't fuck that up. First of all, like, don't fuck that up. make the product even
more compelling. cause I will say even we're not competing on price. Like, so
here, here's where I would be worried about margins If I were like, in this space,
if we were like, we're reselling Claude for, you know, 75 cents on the dollar or
whatever, it's like, what's the point of being in that business? we're not
perceived as inexpensive. We're like, like a premium product for people who are
doing serious coding. And it's still very expensive because we're somewhat
inefficient in terms of how we do it. if we were competing on price, I would say
like, let's just find a different business.

Or you have to, you have gotta be really strategic and find the right cohorts that
are paying that are like super profitable. and so Andrew's like just try to make
the product is awesome, and different as possible. Try to get the enterprise
motion going much as we can because those are better customer segments. don't
mess up the growth sensible with the margin so [00:37:00] that we're not just
like incinerating VC, capital, willy-nilly, but like, we're in a very cool spot.

Harry: I mean, that's pretty tough.

Zach: is, your face is so funny. Right now

Harry: I was just,

Zach: like a crazy

Harry: it is just shit advice, don't mess up. Growth, improve margins, focus and
like lean into enterprise. It's like, we will add it

Zach: Tell me why that's shitty advice. Like what would you be

Harry: because it is like, it's like of course, But there is a world of trade-offs,
which is like, I cannot sustain growth, focus on margins and improve them,
move into enterprise or sustain it and make it super happy.

Oh. And continue to focus on beautiful product quality all at once. Yeah, sure.
Fantastic.

Zach: that's like what doing a startup is. It's like I,

Harry: No, no. Doing, doing a startup is a game of, and, and this is from, from
me. You, you startup founder should listen to me vc, who's not building a
startup.
Zach: me how to do it. Yeah,

Harry: Uh, this is, this is how fucked up the world is [00:38:00] today.

Zach: how to do it.

Harry: No, but I just think it's a constant game of trade-offs and understanding
what you are willing to give up for a certain gain.

And so it's a case of I'm willing to give up a little bit of growth in return for a
focus on margins and that will mean X, Y, and z. I think to just say we want it
all is idyllic.

Zach: So I Okay. To boy, give Andrew more credit. Now I, I feel like I'm
gonna piss Andrew off in this interview. Andrew's very, very smart. He is an
awesome

Harry: Brilliant. Brilliant. It's way smarter than me, by the way.

Zach: I think if we had to prioritize, we would say don't, screw up the revenue
growth. But there's nuance and like, I think it's very easy to go on a podcast and
be like, revenue growth, revenue growth, whatever. It's like, no, we have to like
also make some progress on the margins. like,

if you're a smart investor, you're gonna wanna leak. and like, the way, the way
to think about the margins at least is like there's an immediate concern with
burn, which probably we can get more money. I think the bigger long term
concern is [00:39:00] like, are you a below market reseller of intelligent tokens?
that's not a good business to be in. And so we don't want to be in that business.
but I don't believe that. And so it's like, do what you need to do right now to
like, get the thing to a, you know, good enough spot without screwing up.
Growth is kind of the, the main point.

Harry: And can I ask you end state, what are the margin profiles of these
businesses look like? are these like 15 to 20% margin businesses and the state?
Are they like 60, 65?

Zach: End state's not obvious because it totally depends what happens in the
model market. somewhere there's gonna be a margin, right? Like Anthropic has
a big margin on their API business right now, what I've heard is 60% margin on
Anthropics API, I've heard 50% on an open eyes. I, again, I've heard this, I don't
know if it's exactly right or not, but if there were no margin anywhere in this
stack, I think it's really bad, but there's margin. the question then is like, well,
who's going to, who's capturing that? and I think it depends if the model
providers are really competitive. even better would [00:40:00] be like some
open source model that's like, good enough.

I think the app layer is gonna get a lot of value. If you think that it's gonna be
like one model provider runs away with it, then that's like horrible for us. don't
think that's gonna happen. I think that's, there's too many smart people who are
working on building these models. so our bet is like, there's competition.

It might look like GCloud AWS Azure level competition, or it might look like
actually like open source like database competition and then we're gonna have
an awesome business. But I don't know,

Harry: Do you think it's open? Really? I can see the AWS, Azure, Google
Cloud Trio. I can see three or four players going and taking dominant share.
How do think opens it?

Zach: don't think open either, if I'm being honest. The reason I

Harry: I.

Zach: open, like, that it's just so damn expensive to build these things. And so
what's the economic incentive? It's not like open source software. People like
make the analogy like, oh, open, I'll take the word open and apply it to open
models. Open source software works because it's a bunch of like hobbyist
developers who are giving their time to build something [00:41:00] really hard
models. Somebody's gotta spend all the money to like make the thing
competitive. but here, here's the flip side, here's the way it could work is like it
could get to a point where just like for coding, let's say our domain, basically
solved.

Meaning like models that are good enough and you don't need the frontier
model.

Harry: Hmm,

Zach: actually starts to matter is like how good are you getting context in from
a company? How good's your interface, how good's your automation, like in
orchestration stuff? And that's not crazy to me.
Like, it's crazy to me that the frontier model would be open, but it's not crazy to
me that there's like a good enough model that is open.

Harry: well that, that's a story that your lovable and your rat will say, which is
that you can increase margin over time by having model selection, which will
improve obviously your margin by being able to choose older, like worse
models for more simplistic requests and demands.

Zach: Yeah, I mean I, it's not how I frame it. I would frame it as like coding
may literally be [00:42:00] solved, which is a crazy thing to say, but like at the
model layer, it might just be the level of intelligent token is like good enough
that if you feed it a code base and a prompt and a bunch of contexts, it can make
the right coding change and you don't need this year's. This year's model to use
a Elvis Costello reference to, to actually get the good, to get the good result. So,
I, I would look at it more like that, and then, yeah, if there's competition or you
could do model routing, like, if you're like squeezing margins like that, I think
it's a more precarious place to be.

But I think that you know, the price per intelligence for any fixed level of
intelligence is definitely falling.

Harry: I love Elvis Costello. Great, great. I've never had an integration into a
show of Elvis Costello, but like Elvis Costello is like, I mean, that'll get me
weeping If anyone watches like nodding hill, it's just like Puff. Fantastic. Yeah.

Zach: this is a fun recording.

Harry: Oh yeah, yeah. No, trust me, this is.

Zach: a little scared of my level of transparency in this, but whatever.

Harry: Oh, don't worry. It's fine. You should, you should see [00:43:00] my
team. And they're just like, oh no. What did he say? What did he say? dude,

Zach: I, we, we mentioned OpenAI several times. Let's play a game over,
under, on a five year period. Over under $3 trillion market cap.

that's a lot of market cap, but I think over.

Harry: Wow.
Zach: Yeah,

Harry: Yeah. I advised some of my mates to sell at 500 billion, and now I'm
being like, ah, that was really bad.

Zach: I'm very bullish on open AI

Harry: I'm like, yes, no, I, I,

Zach: good reason. Like other than like, I think that they have the, the, I think
they have the magic consumer product, the next generation of it. And it's worth
so much.

Harry: it is, but also if you're an investor, it's not a great business to be invested
in. I mean, like the, early investors in OpenAI have got like $5 billion of
enterprise value right now, which is like a 25 x for them, which don't get me
wrong, is amazing, but it's actually not like great SaaS businesses will give you
25 x super bases early investors will have a 25 x.

Zach: That's interesting.

Harry: And it's [00:44:00] because of the dilutive nature of the business being,
it's actually not been such a great venture investment. This is the greatest
transfer of wealth from VCs to team members and founders.

Zach: I'm glad I'm a founder. I mean, I mean, has I, I haven't gotten the VC
transfer of wealth to me yet. it's not exactly why I'm in it, but yeah. Let's see.

Harry: Can I, on the VC side, you've never run a formal fundraising process. I
heard. how did you think about the fundraising processes with Warp? Was it
always just preempted how do you reflect on them?

Zach: So I have done, I have done the, um, the formal process thing before. I
didn't do it with Warp, I did it with the company before Warp, where when we
went out to raise a Series A, we like, you know, flew out to Silicon Valley and
pitched like 20 firms in like a week or whatever. of took the best term sheet and
then like got in bed with. Investor and I did not think that process led to an
amazing result. and so with Warp, I really tried not [00:45:00] to replicate that.
Like the way I did it with Warp was as I was developing the idea, I was talking
to a few investors I knew who I'd known for a really long time, who just, when I
was like, I'm ready to do this idea, were like, we love the idea.
We wanna invest. So not every founder is gonna have that opportunity, but if
you have that opportunity, I think that's preferable. And then for the subsequent
rounds of Warp, which were Dylan Field led, the A in Sequoia led the B that
was all preempted. And so those were

Harry: How does Dylan come to lead the A? Like I love Dylan. He's great.
Does he just like reach out and be like, I love the product. Hey, let me lead the
a.

Zach: so Dylan was a small angel investor at the seed. And then from the get
go, he was like, just super excited by what we were doing. I think some extent
of like pattern matching with like, thesis was like reinvent, like a horrible tool
that developers spent all their day. And so I think that that like resonated with
him.

And then we were doing [00:46:00] well, but still very early and he came and
was like, I'd like to, lead your a and I was like, okay. And then Andrew wasn't
that different. We were still really early.

Harry: Can I? How big, how big was the a?

Zach: we raised, like, this was in 2021. It was like a $17 million a

Harry: Wow.

Zach: things have changed by the way we're, you know, we started back in like
the dinosaur era.

We're like a 5-year-old company.

Harry: No, I, I love that Individuals. I love that individuals lead $17 million
Series A. It's like, go, go Dylan. Like fucking legend.

Zach: Dylan's a Dylan's awesome.

Harry: Dylan Dylan's awesome. And so then, and so Andrew then comes in
and goes, yo,

I wanna,
Zach: introduced me to Andrew, 'cause you know, Andrew's on, Figma board,
and Andrew and I really hit it off. and again, it wasn't, we didn't need the money
at, at that time. were, it was just a totally different time in the company. We
were like, know, it was a free product at that point with good user growth, but
not really like a good business model or not a bus.

Like, we weren't even [00:47:00] monetizing,

Harry: you weren't monetizing at the bee.

Zach: we were not monetizing at the beat. This is, this was, so this was another
frothy crazy period. Right. So this was like pre ai. and I, I don't know if I speak
for Andrew, but I think an Andrew again was like, there's some amount of
pattern matching. Like and then I think he liked me. And I think he liked that
we were building a really hard app a big market. and so they invested very
early.

Harry: How much did he invest? How much was around?

Zach: That was a 50 million round, which I think, by the way, is gonna, he's
gonna look very smart.

Harry: no. He's gonna look fantastic, but I'm just like, what a fantastic investor.
Like what a prescient pick to, because that's not obvious. Respectfully. Like $50
million that I didn't want to guess your,

Zach: it for a long time. Like, again, I'm like, again, I'm probably unusually
transparent for founder here, but like we were terminal company, which is not a
real market,

Harry: yeah.

Zach: to be clear. And so it was very much like we're [00:48:00] displacing a
free product. The thesis of Warp was like, Hey, there's this, there's this tool you
know, every developer uses every single day.

That kind of sucks. And like, I still believe this, there's a much better version of
this that could exist. It's actually very hard to build. It's gonna take a bunch of
capital to build, to get like people to work on it. There's a non-obvious business
model, like the business model that we started with was like collaboration,
which makes
Harry: Huh.

Zach: my background on Google Docs and Figma. to some extent we got lucky
that AI came along because that's like a way it like took us from being like a
really, really nice user interface product to something that's truly transformative
for people's work. but like the general initial thesis was kind of right in that like.
This product sucks and it's used by everyone and something better should exist.
And so I think that was like the bet. and then we'll figure out like how to, how to
like build a great business around that. And it's turned out, you know, I don't
know if AI is gonna be like, I think Verdict is out on app layer companies and
AI like you're talking about, but from a like, does this [00:49:00] thing really
help people do their job better at standpoint?

It's like it proved to be right.

Harry: but I mean, it's just incredible when you look at that 50 million check
with no monetization pre ai.

Zach: No monetization And not even a huge user base either. Just to be clear.
Like when they did that round, we were in the thousands of Wow. Right? And
now we're like, know, I think we'll hit a million of active users, active
developers this year. We're now, obviously we're growing our revenue super
duper fast, but it was like really, really risky.

and I, I mean, I wonder if Andrew thought it was reflected on, it was like, what
am I doing? But like, I don't know. I think it's actually

Harry: Well, I, I think this is where actually more successful investors make
better investors because you are able to take risks like that when you are not a
very successful investor. You can't do a chat like that. You, you just can't.

Zach: no. I think like, like incredibly risky investment, but because

Harry: He's fucking Andrew Reed and he's at Sequoia, but, and like he's, yeah,
he do whatever he wanted,

Zach: And that's by the way, like again, if from a [00:50:00] founder
perspective, getting to work with someone who's super secure and confident is a
huge, huge advantage compared to working with someone who is like, you
know, like the more junior person who. have a win. I like, I feel like investors
insecurity will bleed into the relationship
Harry: Oh so much. absolutely. And they, you know what's also hard is when
they have a lot of pressure put on them by their partnership and they then bring
that pressure to you. I always say you wanna work with a partner who's got a lot
of wins under their belt. Andrew's a great example. Andrews Robin Hoods is
Klans, his vans.

I mean, it goes on and on with Andrew. No one is fucking questioning Andrew
inside Sequoia ever.

Zach: Right. That's what you want. Like,

Harry: That's what that's what you want. That's great.

That's great.

Zach: not necessarily easy to get and like, but like if you have someone who's
really confident, it's just, it's like he's in a role of like supporting me, not
pressuring me.

and I think

Harry: Does it change your business? Having Sequoia and I, I didn't mean that.
Like, oh, I want VCs to just like, [00:51:00] you know, jerk each other off. Um,
but like, but like when you have Sequoia money, does life get easier?

Zach: A little, here, here's what, here's what Sequoia, like I'm, I'm a used
Sequoia fan. Here's what Sequoia has done well for us. So there's like a halo
around the brand, right? So like, from a recruiting perspective, it's good. From a
like, customer conversation perspective, it's sometimes good. I'll give you like a
really tangible example.

we were getting user reports that were being blocked by CrowdStrike.

Harry: Hmm.

Zach: like this security software, right? Which kind of makes sense. Like we're
at that layer of the stack. Like we do all this crazy stuff to make warp work on
people's computers. So we're like, oh fuck, we're getting by CrowdStrike. That's
like really, really bad. And it's like we're, we saw all of our usage start to go
down at certain companies. And so I reached out to Andrew, I was like, can you
help me here? And then that day I was on the phone with the president of
CrowdStrike. he is like, I'm looking into it. I don't think that we've actually done
anything.

I think this is a [00:52:00] configuration issue. 'cause we, we ended up being
blocked at Salesforce of all places. Uh, you know that, I don't think you get that
if you, if you have like your kind of random VC firm, but the connections there
are real, it's fricking cool. Right.

Harry: Yeah, if

Zach: that's a Chico.

And I, I was, I was telling my, my, I told my wife that and she was like, oh, that,
that is like pretty cool.

so that's an amazing story in my take of like why Sequoia is awesome.

Harry: I absolutely love that. Is there anything you would've done differently
about the fundraisers?

Zach: honestly, no, but I think, again, I think I'm like a little lucky here in that
like a second time founder, I had like, some access to people I knew.

think we're gonna have to do one of these like competitive ones at some point. if
I,

Harry: Yeah, but dude, you, but you, you, you must be getting inundated now.

Zach: I am inundated.

Um.

Harry: you about any funding. No.

Zach: you seem uninterested. yeah, uh, [00:53:00] yeah, it's like,

Harry: I, I, I have a very simple perspective to this. If Andrew's Keen. I'm
keen.

Zach: uh, no, we we're getting, we're getting a ton of, of interest and we, you
know,
Harry: Do you like it? Like, help me understand. 'cause Norm, I'm on the other
end of this. Okay. do you like it or are you like, oh, fucking another vc? Yeah.
Yeah. You've got a thesis on the space. Sure. You do.

Zach: So I think it would be like kind of arrogant to be like, oh, I hate this.
Like, it's like, no, it's, it's cool people. You're running a business and people are
interested in giving you money. I think that is not the default case for most
people in the world. And so, like for me to be like, oh, I don't, that's so
annoying. No, it's great. It's, it's awesome to have the interest from a, like how
to manage it as a founder. I just basically don't take the calls right now. I'll do
them once in a while to just like like and like where we're at, have a strong
feeling that like when we do it, I'm not gonna do it based on an [00:54:00]
inbound email.

I'm gonna do it based on like either existing investors or they're gonna introduce
me to someone who I, like I'm optimizing for the relationship. Right. And so it's
hard to get that from just like a sales pitch over an email.

Harry: I thought we bonded so well here. This was like a, this was like a meet.
Cute, you know the romantic meet. Cute. Have you ever seen the holiday? You
ever seen the holiday?

Zach: I haven't seen the holiday. What's

Harry: Jesus Christ. This is not a fit. But that's that. That's it. That's it. Term
sheet gone. I mean, if young, not, dude, this is like the greatest romcom ever.

Kate Winslow, Jude Law. Come on, Jack Black and basically.

Zach: I'll ask my wife.

Harry: she's, she's seen it and she's upset with you for not seeing it. And the
meet cute is, when a couple meet and it's like, you know, a man meets a woman
in the coffee shop.

Zach: I knew we were gonna get along.

my, I'm concerned that I've been like too open, but I think it's gonna be
interesting for people listening. Like I'm

Harry: Uh,
Zach: unfiltered. So anyhow,

Harry: I do. [00:55:00] Dude, I think the most important thing is like a natural
conversation. you have Benny off in, in the company. No.

Zach: Mark Benoff iss my cousin, so Yes. So take that for what it's, uh, what
it's worth, but yeah, he is, he is a significant investor.

Harry: No way. Benny off's your cousin.

Zach: Benoff was my second cousin. Yeah.

I was, you know, I have pictures of me and him. Hanging out as a kid when,
when I was a kid and he was at, he was at USC, so I grew up in LA and I have
very distinct memory.

Like he was always like, like precocious as a business person, I have very
distinct memories of him picking me up from my house as a kid. And he had
this white BMW convertible my parents being like, that's your cousin Mark.
He's gonna be really successful. Or maybe he was already like at Oracle being
kind of successful and I remember riding around with him. but yeah, he's my
cousin.

Harry: Wow, do you know this? So I emailed Mark 53.

Zach: podcast, by the

Harry: Yeah. So I emailed him 53 times and then like after the 53rd time, he
responded and agreed to come on. [00:56:00] And since then he's like turned
into a friend and he's a wonderful, awesome dude. that is so funny that he's your
second cousin. So was he in the first round?

Do it. Why did he not just fund it all?

Zach: Well, he was, he is been in all the funding rounds.

Harry: Ah.

Zach: I don't know. I wanted, like, I wanted some variety and plus like, Mark's.
Mark's awesome, but Mark's not like sitting down with me being like, here's,
here's how to think about like, your customer base mark's not like closing
candidates for me. I just wanna be, clear.

Whereas like, you know, Andrew or even Dylan sometimes will help, do that
kind of thing. So Mark's awesome.

Harry: Andrew and Dylan will close, will close candidates and customers for
you.

Zach: well Candidates yes. Customers not so, like, I haven't been asking them
to do that, but like, yeah, if I'm like, we have this incredible engineer who I
wanna join the team, can you explain to them why they should join Warp a
million percent? Do you not do that for your portfolio companies?

Harry: Do I? Yes. But do most other VCs? Hmm.

Zach: That's like one of the things that I'm actually wanting.

I.

 the other VCs I have are like, I have Greg from Box Group and [00:57:00] Eric
from gv, and I trust them all to be like pretty cool,

Harry: box and Greg are great. Fuck they, they're really good. I'm, yeah, man.
Yeah, good. So that, and then who from gv?

Zach: Eric Norlander. Do you know him?

Harry: I, I, I dunno him. Well, but GV is a team I know very well, and they're
very good. So I'm not surprised.

Zach: he is good. I mean, I worked with him at Google, so it's like there's,
there's just very, very long relationships here that I have with these people in
terms of trust

Harry: Well, I mean, you burn that relationship now you were like, yeah.
Wouldn't, wouldn't be long on Google or so.

Zach: like that. That's not a thing I'm afraid of saying. Like they, they need to
like get their. Like I'm saying it all the time. Like you know, I have a 18 month
old son, right? and he's, um, his new favorite thing is to talk to our, we have
Google Home like, we'll be like, Hey, you know, hey Google, what's a, uh,
what's like a horse sound like?

And it'll be like me. And so he walks around and he is like, go, go, go, go,
whatever. And like, the thing is like broken half the time and I'm like, I don't get
it. It's like, I know the technology to do this well exists. [00:58:00] I get better
results from like, speaking to warp and like, it's just such a thing with the
company's so fucking slow that I can just see myself in the meetings where the
various product managers are like, how do we get Gemini into this thing?

And then it's like some gemini org is like, some PM is coming in and well, like,
we can't put it in because it's like not translated into 70 languages or what. I can
just imagine the conversations there, which is like, why, again, why I like
starting a company. It's like way faster.

Harry: Do you want pisses me off more than anything? I love whisper flow.
You know, whisper flow.

Zach: whisper Flow is integrated in Warp.

That's how you talk to Warp. Yes.

Harry: Okay.

On Apple, on the keyboard integration. It is terrible. You have to, and it's not w
uh, Whisper's fault. To be clear, it's Apple's fault. They don't let it be one of the
default keyboards. You have to then go back, enable it in whisper, and then it
will work. It's just like Apple, just fucking buy whisper and just like make my
day.

Zach: No, it's, it's it's cra it's a crazy, like, not, not invented [00:59:00] here or
like whatever, like I don't, I don't know what's going on at these huge
companies and

Harry: Which incumbent are you most impressed by? And then we'll do a
quick fire out.

Zach: oh God. I, I'm not like in my space, not really any of them. not to be a

Harry: No,
Zach: it's like they all,

Harry: Microsoft

Zach: I guess, but they, like, I think that they kind of screwed up copilot, I don't
really know what Amazon is doing. Like, they, they put out a, coding thing,
which people seem to like, okay, is not great at developer stuff.

Just period from my time there. And Apple is always just like super duper slow.
So, I don't know. I, I guess Microsoft, if you're putting a gun to my head of like,
who's I'm just talking about my space, who's doing the best? I don't think any of
those companies are doing a great job

Harry: massive punch.

Zach: insult all of our potential acquirers.

But like, I, it's just like, I, I just don't, like, I, I think that it's like there's a big
company thing that's a real

Harry: Otherwise it is like playing hard to get, it's like, you know, it's dating,
don't worry, you're fine. Yeah, yeah, yeah, That's fascinating. [01:00:00] and
then my favorite is that you have like an Atlassian who's like, buy it, buy it, buy
it. I mean, Atlassian and buying everything. The m and a team there are having
a blast.

Zach: they're going shopping. again, I don't totally get, the strategy, I'm not, I'm
not plugged in on, but it's interesting,

 my theory there is that the founder just loves certain products, like, loves like
the browser company's product. And they're like, okay, this is available. I will
buy it.

Harry: for 610 million. I would love to be in on the board of the browser
company. It's like in cash. Yes. The yes. It's like, have you seen.

Zach: super cool product. but yeah, no, it's, I don't,

Harry: There's a

Zach: investor in the browser company and I know Josh actually,
but it's a, yeah, crazy market.

Harry: that that deal was like an Eddie Izod video. Do you know Eddie Izod,
the comedian? Uh, yeah. And he is called Cake or Death, and it's like you get
offered cake or death, uh, cake, please. Uh,

Zach: that's hilarious.

Harry: 600 million ago, like we had fucking nothing. Josh is amazing
[01:01:00] and I we've got him coming on the show. Great dude. But like,

Zach: he is, he is incredible. But

Harry: that must have taken about three and a half milliseconds to jump on.
Like, yes.

dude, this has been one of my favorite shows all year. Um, I've loved it. Uh, my
favorite is you also listen to the show and so you are like, you, you know that
they are not normally this fun.

Zach: no, I mean, well, I, I would listen to this episode. I would be like, oh, that
this guy is interesting.

Harry: Oh yeah. No, no. So am I, um, listen, we're gonna do a quick fire. So
I'm gonna say a short statement. You give me your immediate thoughts. Who's
your favorite founder Building an AI today?

Zach: do you know granola? Do you know

Harry: Yeah.

Zach: you heard of that product? So he's a friend of mine. I'm a small investor
in that company. I the way he thinks about it. I knew he, I knew him at his last
company too. Uh, he's building really cool AI native stuff, so I think he's doing
a great job. It's like get, get rid of the black box in Zoom is like a very
interesting, it just makes the product experience so much better. So I like it.

Harry: Do I hear a funny [01:02:00] story about Chris? my, my partner Kieran
was the first investor that he met for granola. And he's a Harry, you've gotta
meet him Sunday night, go for drinks. And so we went for drinks on a Sunday
night and I met him and he was doing something he wasn't sure. Something
with AI and something with notes.

But not sure that was it. no idea beyond that. And I, as an investor in mem and
Rome research and like six other note-taking companies, I was like, Kieran,
dude, someone needs to set up a GoFundMe page for this guy. 'cause that's the
only way he's gonna get money. And I told Chris this, by the way, like, this is
not me being a dick.

Like Chris is a friend now, and I love him. And I, and I told him this, actually
we were like, fuck no. Uh,

Zach: You didn't invest.

Harry: no.

Zach: Oh, that was a mistake. He's great.

Harry: Yeah, no shit is a mistake. Thanks. Yeah. I obviously as a terrible
mistake. We, we, not only did we not invests, we said you should set up a
GoFundMe page.

Zach: So you just like insulted him. That's [01:03:00] awesome. I love it.

Harry: Oh, no, no, no. He was like, this is hilarious. Like, maybe it'll be tough
to raise. And I'm like, fuck, That was a mistake. Oh. It goes to actually the
importance of relationships. 'cause had I known him for a while, that would've
been the easiest check ever to write. But meeting him for the first time, you are
like, notes ai.

Hmm

Zach: I can see if that's the pitch. I you're not making it the most compelling so
I could see why maybe you passed. Yeah.

Harry: okay. What do you continue to do, but wish that you didn't?

Zach: I probably, I've like historically waited a little too long to hire to like be
leaders on the team. So my, my default, like for instance, I like someone else on
the team, basically like ran our growth function at Warp for years. And I think
value to that. Like it's better to like try and do saying yourself as a founder first
before hiring someone for it. But there's also lots of people who know how to do
stuff way better than I know how to do it. And so I, I may probably waited a
little too long on. On that. We hired a great growth person who's [01:04:00]
like, been awesome.

Harry: What happens to X ai?

Zach: I would integrate x They, they approach us all the time to put out their
coding models, but I need, I need some reason that it's like measurably better

Harry: Hmm.

Zach: wanna add one of these, I hope that they have a competitive thing in my
space. I don't really know. I think it's great though.

I want, I, I want more models out there and so I'm the existence of X, although
we don't use it anymore.

Harry: Open AI at 500 billion or atropic at 180 3, which to invest in.

Zach: I've said it before in this interview. I'll say it again. I'm very, very bullish
on OpenAI because I think they have a winning consumer product. anthropic is.
Maybe the best AI lab, like from a research perspective and from like the mo,
like their models are incredible. I think it's a big problem not to have the
consumer product there.

And so I don't know, an API business gigantic business? So they're gonna have
to really win on these like enterprise vertical businesses, and maybe they will, I
hope not. Like [01:05:00] we're competing with them as a frustrating thing as
someone in the coding space and or a customer of them. but I, I think OpenAI
with chat GPT is gonna be gigantic.

Harry: Rat clip versus lovable versus bolt. What happens there?

Zach: I know you're a lovable investor. I don't have I, this one I truly don't have
a strong take on. will say from, again, from a selfish perspective, I think it's
much better to be in the market for professional developers in the enterprise
market for cogen than I do think it's. be in a, like, like essentially the no code,
code market.

I don't know which of those products is the best. I don't really use them.
Harry: Is like a web flow, totally dead.

Zach: Yeah. Uh, I think here, here, the argument for web webflow, it's like
Webflow in particular. I don't, we used to use it, we moved off it. Like they
need to leverage the fact that they have this great hand interface for building
websites, but like, I don't think you really need that.

So I think Webflow is really, really in a ton of trouble. [01:06:00] Yeah.

Harry: well, I mean, Excel and lovable too. So you got, but you just gotta
transition of,

Zach: I mean, like, I,

Harry: love about this market is like, yeah, our s killing web flow, let's being
lovable.

Zach: so like the bull case on these is like, oh, well wow. Anyone can build
something that's cool. And then I think you naturally have to ask the question of
like, okay, cool. What are they building? and I worry that what they're building
is like the next gen of WordPress or Squarespace or Webflow.

And like the business case for those types of apps is not that awesome to me.
and so that's why it's like, I think you want to be, if you're in, you know, the, the
coding market, I think it's way cooler to be in the market for like building the
really hard to build apps that have billions of users.

Then they'll like, the, you know, some someone's like Shopify store. And by the
way, I think Shopify could also, you know, be big in this space eventually.

Harry: What would you do if you weren't scared? [01:07:00] An example for
me would be, I would be in Silicon Valley. Like candidly, we've had a
wonderful conversation. Shows like this make me realize how much I love what
I do truly. But I'd be in Silicon Valley, I'd be in the Colosseum of, of investors.
I'd be before Andrew Reed in the funnel.



Zach: this is gonna sound crazy and this is not a thing I've thought through, but
like point, like I would like to have like some kind of like impact outside of
technology maybe in politics. I think I would like, I don't think the world wants
me in politics. I think that like the way that I like, think of things is probably.
Not very appealing to most people, but I, I like hate what's going on politically
I'll just say in the us and if I could have like some bigger positive impact, it's not
just like starting a business, I would do it, but I don't, I don't really think most
Americans probably want me in politics, but that's like, I would love to have
some big positive impact on our country, to be honest.

Harry: I respectfully, I think when you compare yourself to the other
candidates, said, welcome you with open arms. Like,

you know, [01:08:00]

Zach: Yeah. May maybe at some point.

Harry: it's a relatively low bar, I find. who do you not have on your cap table
that you would most like to have?

Zach: So we have a cool cap table with a combination of like, operator,
investors.

 I think having, having someone, like you, if I say you probably you, like,
you're, you're, you seem to have like the big, you who, who can think through,
like the, one of the challenges we have is like breaking through the noise. And

Harry: Hmm.

Zach: think someone who has that superpower would be a great person to, to
add. my best answer, but

Harry: Oh, I thought it was a pheno. That was my favorite of all the answers of
all the show. Of all the show. That was the one. final one, what are you most
excited for? So, like, when I think about my mother's got multiple cirrhosis, I
think that we will have incredible cures to some of the world's most challenging
diseases in 10 or 15 years, which it excites me immensely.

What do you find most exciting?

Zach: Yeah, it's, it's that type of thing, just to be honest, like I'm getting older.
[01:09:00] think we are at this really interesting spot where we're on the
precipice of like amazing, crazy technology that truly could like help a ton with
healthcare or help a ton with people's prosperity or learning or whatever.
And on the flip side, I think we're at this very precarious, like. Political spot.
and I feel like those two things are like racing each other it's super unstable.
We're not like a spot of equilibrium. my hope is that the technology, like the
advances in technology can really, really have big impact.

I think if I had to pick one area where I'm most interested, most, hopeful as well
is like in health, like that would truly be transformative for like, you know, me
and my family and just like having some sort of real medical progress. but I'm
also scared 'cause it's like, it's like a very like situation right now in the world, in
my opinion.

Harry: Oh, thanks for the fucking tone of positivity. At the end. Bring up
geopolitics to finish the show. I'm.

Zach: Oh, yeah, I, I don't know. I was being very, very honest. It's like, it's
really [01:10:00] incredible technology and it's like, it's like never been a worst
time to deploy it, in my opinion. So I hope that the, that the sensible people,
kind of can, get the technology deployed. So that really is helpful to people.

Harry: I, I, I hope the same. And, you know, thank the Lord. Every day I see
Palmer Lucky's colorful shirts that, you know, here's our hope for geopolitical
stability. but, but yeah, I agree with you. Thank you Joe's aside, you, you have
been a fantastic guest.

I had no idea, like, coming into this, like obviously I spoke to Andrew, but you
have been so much fun, insightful, entertaining, honest. Seriously, thank you for
being such a great guest.

Zach: Thanks for having me. I, I knew this was gonna be really fun and it didn't
disappoint. It was awesome. Thanks for having me.



Harry (Adverts): But before we leave you today on this show, we care about
velocity. Most teams lose it in code review, not in writing code. Now, code
Rabbit fixes that the second a PR opens, it leaves clear line by line [01:11:00]
comments, calls out what the change might touch, and offers one click fixes.
You can teach your organizational standards using your own custom
instructions, such as Cursor or Claude rules, and enforce them on.

Every PR Code Rabbit has so far reviewed more than 13 million PRS and
installed on 2 million repositories used by over a hundred thousand OSS
projects. If you want to cut code, review time and bugs in half, try a free
month@coderabbit.ai with the Code two zero vc. And while Code Rabbit keeps
your code clean, Tessie makes sure AI handles the rest hiring shouldn't take
months.

Tessie's AI agents work 24 7 to keep your recruiting pipeline full, instantly.
Reviewing inbound applications, sourcing top talent, rediscovering those hidden
gems in your a TS, detecting fakes and pre-qualifying candidates before your
team. Even starts interviewing. What makes Tazzie so different? Well, it's all in
one [01:12:00] AI agents across the workflow from open to offer a built-in a TS
plus a 750 million candidate database.

That means added recruiting capacity when you don't have enough hours in the
day. And that's why companies like Mutiny. Pocus and Orum and even public
companies like Real already trust Tazzie with features in VentureBeat,
TechCrunch, fortune, and Axios. You have to check them out. Tazzie do AI
slash two zero VC for 10% off your first year and start making hires in days.

After Tazzie streamlines your operations, warp Dev helps your team ship faster.
AI coding is everywhere, but most of it, honestly, it's pretty chaotic code that is
almost right, but you don't really understand Well. That's why WARP exists
with Warp. The old lines between Terminal and IDE disappear, it's a seamless
environment for coding with agents where you can prompt, plan, review, and
ship.

Production Ready code, [01:13:00] edit files in app. Review diffs as you go and
deploy straight to production without switching tools. Warp tops the
benchmarks. Literally number one on terminal bench. Top five on software
engineering bench. Verified and is trusted by over 600,000 developers and used
by 56% of the Fortune 500 engineering teams making it one of the fastest
growing AI companies with revenue.

Growing 30 x this year with warp, you don't just get speed, you get code you
can trust. The average developer saves five hours a week with Warp. That's
almost half a day. Try Warp for free at Warp Dev slash two zero VC and to get
Pro For only $5 for your first month, use the Code two zero vc. That's two zero
vc.


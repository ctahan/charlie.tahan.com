---
title: "Does Quantum Matter in the Age of AI?"
date: 2026-11-16T09:30:00-06:00
tags:
  - blog
description: "My UW–Madison keynote of November 16, 2026, slide by slide, with my words edited to read and the points I prepared but skipped brought back in."
cssclasses:
  - keynote-slides
---


> [!note] Notes on this talk
> I kind of went hog wild on this talk for UW-Madison. Everything was made from scratch. And I mean everything. The talk itself is a web app server designed to be interactive: it listens to what I’m saying, allows audience input at forks to choose directions, is simulating a quantum wave in the background. I worked with the automatons on the structure of the talk, what I wanted to say. I wanted to demonstrate how AI is changing science and what it means to be a scientist and highlight the big question our field faces - what is the delta between quantum and AI. I gave the automatons all the policy documents I was associated with, all my essays and writing, my scientific papers, all the course materials from my Nanotechnology and Society course I taught in 2005 as a graduate student at Wisconsin. I pointed them to our recent public talks from Microsoft Quantum. I asked them to research the state of quantum and society and do their own research. It was truly a collaborative effort. And they surprised me at times, and certainly found stuff I would have forgotten. The talk app itself generated a draft voice track which we iterated on - I wrote it to allow me to give feedback in real time. I included the present state of model video creation from a technical paper and highlighted science discovery loop examples. I even vibe-coded a game for the audience to play after the talk inspired by SimEarth!
>
> We live in this unique moment in time where it feels like you can make whatever you can imagine, and still have it be novel. I feel like this will be a good marker of the state of AI technology. I have no idea what I would do in a year to top this. But I’m sure it will be out of date. 
>
> > Summarize the main points I made in this talk, just a few bullet points <10
>
> - Nano is the precedent. It didn't vanish; it dissolved into semiconductors and materials, and AI will absorb technology the same way.
> - Quantum policy stayed narrow on purpose. The law focused on what's fundamentally different (security, economy, workforce) so it wouldn't become a grab-all. You stand by that.
> - Being a scientist is changing this year. AI speeds up every step, but it's still slop; the game is verifying it, and the slop gets harder to catch.
> - Small teams with AI move very fast if they know what they're doing, so the bottleneck moves to hardware and hands-on training.
> - Quantum is "AI minus the rest of the universe." Big and strange aren't enough; it has to be useful, and only a few algorithms are (cryptography, simulating nature).
> - Your bet: quantum computers as telescopes that feed AI quantum data, as code made LLMs better at everything. It loses if classical methods can supply that data.
> - When AI makes everything, nobody knows how things are made. Most people won't care; the open question is the model directing it.
> - The charge to the room: find where quantum really differs from AI and bring the public in, because the public will conflate the two.
> - Don't scare-monger: AI is the real story, so watch for quantum's step changes. We don't know what happens when you include the rest of the universe.

*The transcript of my opening keynote at the Quantum–ISSH Symposium, University of Wisconsin–Madison, November 16, 2026, slide by slide. [Watch the video on YouTube](https://www.youtube.com/watch?v=jH9mP4x4xgg).*

*==Shaded== passages are the points I prepared but skipped in the room. Words in \[brackets\] correct a slip I made; the footnote says what I said.*

![[blog/assets/madison-keynote-2026-11-16/slides/000-title.jpg|Title slide, with a photo of Charles Tahan: Does Quantum Matter in the Age of AI? Charles Tahan and the Automatons. UW–Madison, November 16, 2026.]]

![[blog/assets/madison-keynote-2026-11-16/slides/005-000-3.jpg|the question, 3 · "Just shout out a number of years…"]]

==Before I tell you who I am, I’m going to read you a question, exactly as a congressman asked it.==

“Since I am out of time, I am going to ask each panelist how many years they think it will take … to give us an intelligence that surpasses any known human intelligence. Just shout out a number of years, and make sure it is longer than anyone will hold you to account for, because we will forget your answer in less than a decade.”

==I won’t forget.==

![[blog/assets/madison-keynote-2026-11-16/slides/007-000-5.jpg|for the record: question 1 · a show of hands, counts typed in · question 2: the quantum computer · a show of hands, counts typed in]]

For the record, a show of hands: how many years until an intelligence that surpasses any known human intelligence?

Five of you said it has already happened. Ten said within three years, I think. I’m not very good at math. Eight said within ten years. Never? Holy mackerel. It took a recount, but three of you said never. To those of you who said you have no idea: I appreciate you.

One more question, ==one that panel wasn’t asked==: how many years until a quantum computer does something someone needs that no ordinary computer can do?

Twenty of you said within five years. That’s a lot of people, and I’ve got some education for you. Six said within ten years, and two within twenty. Nobody was bold enough to say never. I’d have expected a lot of “no idea.”

==I’ve been told that I’m a good guesser. You’ll see my guesses before we’re done.==

How many of you are physicists or engineering experts? Roughly a third. Social sciences and humanities? About 60–40, I’d say. That’s good to remember; we’ll come back to it.

![[blog/assets/madison-keynote-2026-11-16/slides/011-145-3.jpg|"Since I was here…" · the technical side: Cambridge, DARPA, fifteen years at LPS · the policy side: OSTP, the White House · Microsoft Quantum]]

I was here twenty years ago. I had the great fortune of doing my physics PhD here, in quantum computing, with the Marks (who were in the room) and others. In my last year, I got the opportunity to co-teach a course on Nanotechnology and Society. I’ll come back to that in a moment.

First, a little background. After my PhD, I spent many years doing technical work.

\[I was a postdoc at Cambridge\][^c1], then went to DARPA for two years as a consultant and helped start their quantum programs. Then I went to NSA’s Laboratory for Physical Sciences==, for fifteen years==. LPS is like the physics department of NSA’s research directorate, located at the University of Maryland. I ran quantum computing programs, had a research group at the university, and eventually became technical director and then chief scientist, working on high-performance computing, quantum computing, sensing, packaging, all kinds of things.

From there I got a little bit into policy, because when you reach a high enough level in government, they start sending you downtown to represent the agency, whether you like it or not.

I became the executive secretary of the quantum subcommittee of the National Science and Technology Council, in OSTP, the Office of Science and Technology Policy. That was just as the National Quantum Initiative was being written and passed, so my job was to hold the pen on the national quantum strategy. I did that for a couple of years, in my day job. Then I became ==Assistant Director for Quantum Information Science and== the first director of the National Quantum Coordination Office. You heard about the NNCO. That was quite an experience. I was still on loan, still running the lab at LPS.

In 2018, during the first Trump administration, we had five PhD quantum physicists in the White House, on premises, in the National Quantum Coordination Office, one of the biggest offices in OSTP. It was an extraordinary time. I was there for about four years.

After I left government, I spent four months at the University of Maryland helping write its quantum strategy for the state. Then I went to Microsoft Quantum, where I do mostly technical work. I lead the Hardware and System Architecture team ==and the DC quantum office==.

![[blog/assets/madison-keynote-2026-11-16/slides/012-act-1-0.jpg|Act I · The same room]] ^act-1

![[blog/assets/madison-keynote-2026-11-16/slides/016-215-3.jpg|the 2005 course banner · "Nanotechnology is cool. … consequences" · day-one answers · two questions that ran through the course]] ^nanotechnology-and-society

Twenty years ago, in the last year of my PhD, two professors got some NSF money to have graduate students teach a course in science and technology studies: Nanotechnology and Society. They were Wendy Crone, in the \[Engineering Physics department\][^c2], and Clark Miller, who went on to ASU. I was one of the two people picked to teach it. I wasn’t their first choice, but I was picked.

It was a tremendous experience. We put together the course materials ourselves, and they let us teach it on our own, with no help in the classroom. Afterward we wrote a paper on what we learned.

The first and last sentences of its first paragraph: “Nanotechnology is cool. … What are the consequences for our society?”

On the first day, I asked the students for three examples of nanotechnology. (I didn’t remember any of this; I had to go back and look.) The first answer was advanced computing: really fast computers. The third was stain-free pants. They were pretty on top of things, actually.

Two questions ran through that course. Is nanotechnology real, or is it just hype? And how do you include the public: who decides how we implement nanotechnology, and the policies that go with it? ==They matter today.==

![[blog/assets/madison-keynote-2026-11-16/slides/018-315-1.jpg|the page · "size of the Pentagon" + 1T card · "quantized spins" · (10¹⁵), small]] ^feynman-1959

The second reading we gave them was the famous paper on nanotechnology from a physicist’s perspective: Richard Feynman’s “There’s Plenty of Room at the Bottom,” from 1959. If you read it again today, it hits different.

==Feynman imagined a computer that could make judgments.== One line surprised me: “we would have to make it, perhaps, the size of the Pentagon … TVA would be needed to run the computer.”

That’s an AI data center. We’re now spending \$1 trillion a year in capital expenditures on data centers. Microsoft alone is approaching \$200 billion a year.

Another: “We can use, not just circuits, but some system involving the quantized energy levels, or the interactions of \[quantized spins\][^c3], etc.”

This paper was about data centers for AI, and about qubits, sixty-six years early.

He also estimated how many bits of information there are in all the books in the world: about 10¹⁵. Remember that number.

Back to that hearing: it was about the nanotechnology initiative.

![[blog/assets/madison-keynote-2026-11-16/slides/025-415-4.jpg|Kurzweil · Peterson · Winner]] ^the-2003-hearing

The question was Congressman Sherman’s==, in April 2003==. It was interesting to read, because they were talking about artificial superintelligence in the context of nanotechnology, two things I wouldn’t associate much today.

There were four or five panelists. Ray Kurzweil, the futurist and brilliant inventor, said 26 years. That would be 2029, \[three years from now\][^c4]. He’s pretty good.

Vicki Colvin, who led the nanotechnology center at Rice, said 45. ==Christine== Peterson, from the Foresight Institute, said 25 to 30 years.

Langdon Winner, the only social scientist on the panel, said: “Actually, I hope never.”

What did you say?

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/027-415-6.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/027-415-6.mp4" aria-label="collapse 1 · &quot;wider public debate&quot;" style="width:100%;border-radius:6px;background:#000"></video>

Most of you said \[within ten years\][^c5], and the other 40% said never or had no idea.

Winner went on: “Perhaps this needs wider public debate.” And Congressman Sherman answered: “That is pretty much how we spent the last five minutes.”

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/028-500-0.jpg" src="blog/assets/madison-keynote-2026-11-16/condensed/500-0-1.mp4" aria-label="the 2003 advisory sentence · it morphs into 2018&#x27;s" style="width:100%;border-radius:6px;background:#000"></video> ^two-laws

The Nanotechnology R&D Act explicitly included societal and ethical concerns. ==It wrote society into the sentence about who advises the program: experts in “… commercial application, or societal and ethical concerns.”== That changed a bit with the National Quantum Initiative.

==Then I went to Washington and helped build the quantum version, with the same architecture: a coordination office, a subcommittee, an advisory committee. And almost the same sentence.==

![[blog/assets/madison-keynote-2026-11-16/slides/030-500-2.jpg|2003: the law lists AI "which exceeds human capacity"]]

But there, “societal and ethical concerns” got replaced by “national security and economic concerns.” I’ll try to explain why.

As I mentioned, a particular concern of the nanotechnology initiative was “artificial intelligence which exceeds human capacity.” ==The nano law listed it as a societal concern. In 2003.== It wasn’t mentioned at all in \[the quantum initiative\][^c6]. We never even thought about AI in the context of the NQI at the time.

![[blog/assets/madison-keynote-2026-11-16/slides/031-500-3.jpg|the strategy: three doors, one test]]

Society came into the NQI through three doors. The first was economic security, the predominant one. The second was national security, mainly because quantum computers, if you can make a large one, are very good at breaking our public-key encryption. The third was the workforce.

My summary: the real focus of the National Quantum Initiative and the national quantum strategy was to identify what was fundamentally different about quantum’s societal implications versus those of other technologies. We very consciously tried to keep quantum from becoming a grab-all for science and technology. When that happens, the funding gets spread across everything, and nothing really happens in the thing you’re trying to fund. The subcommittee thought very deliberately about how quantum differs from nanotech, AI and other technologies, and how to separate and protect it so that you focus on the things that matter. ==Breaking the world’s encryption is quantum’s alone; it got a presidential memorandum and a deadline. A small field that takes ten years to train someone needed its own talent plan. Jobs, privacy and misuse are real, but we judged them covered elsewhere.==

This debate is still going on today. The National Quantum Initiative has yet to be renewed. We are eight years in, and it was supposed to be renewed at five.

![[blog/assets/madison-keynote-2026-11-16/slides/032-500-4.jpg|2026: the bills disagree]]

For the third time, there are versions in the Senate and the House, and they differ on the societal elements. \[The House one has them. The Senate one, as introduced, would strike the word “societal”\][^c7] ==and end the National Nanotechnology Program==. It’s interesting to see Congress still debating how to incorporate society into the renewal.

![[blog/assets/madison-keynote-2026-11-16/slides/033-715-0.jpg|the Automatons ask: the report I co-chaired (June 2023)]] ^the-automatons

![[blog/assets/madison-keynote-2026-11-16/slides/034-715-1.jpg|what they counted: society, once]]

In my time at the NQCO, we also had a presidential committee of external experts who, as part of the law, had to deliver a report to Congress. It brought together the leaders in the field, and it was chaired by me, from OSTP, and Kam Moler, from Stanford.

I should say now what will become obvious: this talk was greatly enabled by AI. I call them the Automatons. I do mostly technical work these days, so I had the AI go back and read all the documents from my Nanotechnology and Society days and all my policy documents. It found things I had forgotten. ==I also asked it to push back on me. When you see a violet card, that’s the Automatons talking.==

For example, it counted how many times “society” or “societal” appears in this report==: six times in 19 pages. The report made four recommendations, and society appears in one of them, as the reason to go faster: “To realize the potential of QIST for society, the NQI must accelerate the development of valuable technologies.”==

![[blog/assets/madison-keynote-2026-11-16/slides/035-715-2.jpg|the clock, while I answer aloud (nothing of mine on the card)]]

“Ethics” and “ethical” are never mentioned in this report. That’s what they highlighted. Why?

From our perspective, it didn’t come up that much. Assuming funds would be limited, we were very focused on directing them where they would really make a difference. This report was for the second half of the quantum initiative. The first half was about workforce and fundamental R&D. The second half had to be about translating that into applications, and getting the balance of economic and national security right, so that we don’t choke our potential by being too restrictive.

We decided to focus on those aspects of the NQI renewal, and to convince Congress to actually fund the renewal ==before the program expired==. When you’re translating a technology from science into application, the funding has to go up by a factor of 10 at basically every technology readiness level. We had to make the case that industry needed to get involved in a more serious way. ==The societal stakes that were quantum’s own, security and talent, are both in the report.==

I stand by the decisions we made, and I think they still hold up pretty well today, despite what the Automatons thought.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/036-915-0.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/036-915-0.mp4" aria-label="found by the Automatons: the map the AI brought back" style="width:100%;border-radius:6px;background:#000"></video>

I also asked them to find out where the funding for science and society went. As mentioned earlier, the National Nanotechnology Initiative had a big chunk of funding explicitly for nanotech and society.

Other national quantum initiatives around the world, mostly modeled on ours, did cut off a piece. The Netherlands cut off 3% of its budget, and that 3% went explicitly to a Centre for Quantum and Society. The budget, \[€615 million over seven years\][^c8], is a lot for the Netherlands. ==The UK asked its public. In the United States, the AI found no national public dialogue on quantum.==

It’s not quite true that the US had nothing. All of NSF’s Quantum Leap Challenge Institutes had societal components, but there was no particular center where it was all focused, and no explicit mandate.

Then there’s QUASAR, a recent global initiative ==for quantum and society== that I didn’t know about. It has only one US member, the Wisconsin Quantum Institute, which I thought was pretty cool.

After teaching that course in Nanotechnology and Society, I \[went on to a postdoc\][^c9] and came back to technical work.

![[blog/assets/madison-keynote-2026-11-16/slides/039-1015-2.jpg|the article, 2007 · his definition · the national strategy, 2018: the same line · the press: Wired, New Scientist]] ^spookytechnology

==In 2007== I wrote an article called “Spookytechnology and Society.” ==Spookytechnology was my name for technology built on the strangest parts of quantum physics.== My motivation was to prevent the mistake that happened with nanotechnology. ==Nano was named outside science, and it came to mean everything, from new materials to tiny robots.== We needed a real definition of what quantum information science is; otherwise it just becomes everything. Spookytechnology was not a great word. I’m glad it didn’t catch on.

It did get some press, though. Wired and others picked up on “spookyweapons,” with pictures of Star Trek ships firing quantum torpedoes.

But I think the message still holds.

In the national strategy we wrote \[eleven years later, in 2018\][^c10], the definition is basically the same. ==I was executive secretary of the subcommittee that wrote it.==

A lot of effort went into constraining what quantum information science and technology is, so that it doesn’t become everything. What’s different about it? Unless you know what’s unique about it, you can’t make the right policy.

![[blog/assets/madison-keynote-2026-11-16/slides/040-1015-3.jpg|card 1 of 3 · a reader: "when it works, not how it works"]]

The other thing the Automatons found really surprised me. Back in those days of the internet, you could leave comments on articles. You can’t do that on New Scientist anymore; today you go to Reddit or wherever. Under the New Scientist article on Spookytechnology, one reader commented: “People will want the technology when it works, not how it works.” I think that was a very interesting find, and we’ll talk about it more.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/041-1030-0.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/041-1030-0.mp4" aria-label="So what happened to nano? The buckyball falls into a chip" style="width:100%;border-radius:6px;background:#000"></video> ^technology-recedes

What happened to nano? Nano didn’t go away. It was absorbed. It became fundamental to our semiconductors and our materials. ==It worked, so we stopped asking how, and stopped calling it nano.==

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/042-1030-1.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/042-1030-1.mp4" aria-label="a census of 2005 gadgets collapses · &quot;Most things will become intelligence&quot;" style="width:100%;border-radius:6px;background:#000"></video>

I would argue that with AI, all our technology is going to do the same thing, and we’re seeing evidence of that. Technology will move away from physical things like laptops and phones and become embodied in intelligence.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/043-1030-2.jpg" src="blog/assets/madison-keynote-2026-11-16/condensed/1030-2-3-4.mp4" aria-label="Star Trek: gadgets, and a ship&#x27;s computer (line drawing) · Star Wars: the droids are the computers (line drawing) · &quot;Messier&quot;: the relative value of human intelligence" style="width:100%;border-radius:6px;background:#000"></video>

I became a physicist because of Star Trek: The Next Generation. But that world doesn’t look like it’s going to play out. Star Trek was very human-centric. The technology empowered humans: you had tricorders, and the ship’s computer. ==The computer answered questions, but it was clearly limited.== It was very human-led.

As I’ve said in another context, I think the future is much more Star Wars-like: you have droids that embody intelligence, and you just ask them for stuff. ==Nobody there relies on a laptop or a phone. They rely on R2-D2 and C-3PO. The intelligence is out in the world, and nobody asks how it works.== That has a lot of implications. It’s messier, and it lowers the value of human intelligence in comparison, which we’re starting to see. ==But in a sense it’s also more human. Laptops and phones are a blip in our existence. Would we deal with them if we didn’t have to?==

![[blog/assets/madison-keynote-2026-11-16/slides/046-act-2-0.jpg|Act II · Back to today]] ^act-2

Back to today. Laurie, Mark and I discussed this when we were working out what I should talk about. I don’t think we can talk about quantum without talking about AI, because AI is dramatically changing what it means to be a scientist and to do science. I want to talk about that a little.

![[blog/assets/madison-keynote-2026-11-16/slides/048-1115-1.jpg|"Everything will change about being a scientist." · "Now. This year."]]

In a talk at NYU a couple of weeks ago, I asserted that everything will change about being a scientist, this year.

For me, everything has already changed. It’s happening now.

Let me explain why I think that.

![[blog/assets/madison-keynote-2026-11-16/slides/049-1130-0.jpg|Microsoft Discovery + Quantum: what my division does]] ^ai-for-science

I’m very fortunate: I work in a division of Microsoft called Discovery + Quantum, which reports to Satya Nadella. ==I see this up close. Microsoft is my employer; weigh what follows with that in mind.==

We do only two things. First, we build quantum computers, and that means everything across the stack: the applications, the software development tools, the quantum operating system, the firmware and all the hardware to run it. We build qubits, and we work with other companies who build them, so that we can have the best quantum computer at any given time. We’re also learning how to pair that with high-performance computing and AI in Azure.

The second is Discovery, which is focused on AI for science: building tools to accelerate science.

![[blog/assets/madison-keynote-2026-11-16/slides/050-1130-1.jpg|the discovery loop]]

The picture on the right is the new model for science, combining AI, HPC and quantum. The scientific method still works: reasoning, hypothesis, experiment and analysis, in a loop. What we foresee, and it’s happening in real time, is a loop fed all the time by high-performance computing, AI, quantum and robotics. Our division does all four.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/051-1130-2.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/051-1130-2.mp4" aria-label="how Discovery works: design, predict, test, remember (the agent working, behind)" style="width:100%;border-radius:6px;background:#000"></video>

One example comes from the people who sit next to me; it isn’t my work. They have been applying the Discovery tools to accelerate science, and this work, done with Yale, looks for a new material for batteries.

The loop looks like this. You start with the problem, and the agents help you design what to do: for example, find a new molecule to replace vanadium, which is a scarce resource. Can we find an organic version? The system predicts variants, then gives the chemists what to make, or synthesize, and test.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/052-1130-3.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/052-1130-3.mp4" aria-label="Discovery: the app, CLIO, Bookshelf with GraphRAG, tools" style="width:100%;border-radius:6px;background:#000"></video>

Then it takes those results, analyzes them and makes new predictions. It’s still very much a human-in-the-loop system, but greatly accelerated by AI.

At the core of the Discovery Engine is something called the \[Cognitive Loop via In-Situ Optimization\][^c11]==, CLIO, from Will Chappell and colleagues==. It’s an embodiment of the scientific method that tries to keep the agents under control, with checks and balances. ==The agent works out its own approach, shows how sure it is, and lets the scientist see how it reached a belief, and correct it.== It also uses other Microsoft tools, like GraphRAG, which lets you ingest thousands and thousands of data sources and turn them into a knowledge graph you can search quickly. It can call custom tools, too, like LLMs built specifically for chemistry or other sciences.

You can download it to your computer now. It’s in alpha or beta, whatever they call it: a skin for VS Code that helps a scientist do science with a bunch of AI models. It tries to slow you down, so you do it the right way.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/053-1130-4.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/053-1130-4.mp4" aria-label="the Yale campaign · what the agent did differently" style="width:100%;border-radius:6px;background:#000"></video>

Discovering a molecule for an organic battery is not easy. People spend years and decades trying. ==These are flow batteries, the big tanks of liquid that store energy for the grid. Chemists at CanAm Bioresearch made the molecules, and Yale tested them. The agent organized the work into three rounds and picked its own tools.== The system came up with many candidates that were synthesized and turned out not to work. Those negative results were fed back in. ==When the lab disagreed, it learned to doubt its own model.==

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/054-1130-5.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/054-1130-5.mp4" aria-label="the failure none of the models predicted · the redesign, made and measured" style="width:100%;border-radius:6px;background:#000"></video>

==One promising candidate failed in the lab in a way none of the models had predicted. The machine didn’t catch its own mistake. The wet lab did.== Then the system came up with new designs and a proposal for why the old ones weren’t working, and its research partners made them in a wet lab. It worked==: the redesign was much more reversible, though not yet as good as the molecule they started from==. Something that would have taken years took months. You can read about it in the paper cited here.

![[blog/assets/madison-keynote-2026-11-16/slides/056-1245-1.jpg|how I made it: what the agents read, what came out]] ^how-this-talk-was-made

I want to tell you a little about how this talk was made. I tried to do something special for you, to push the limits of AI technology. I’m not sure everybody understands where we are.

First, I gave the Automatons, the AI, everything. I said: go read every paper I’ve ever written, every policy document I’ve had my name on, all the coursework I gave my students in 2005, and search what’s happening in science and society, because I’m out of the loop. What’s going on in quantum and society? Then I iterated with it. I learned a lot, things I’d forgotten and things it found, and we developed this talk together.

![[blog/assets/madison-keynote-2026-11-16/slides/057-1245-2.jpg|the Automatons: the band, what I threw out · the marks, at the bottom]]

I use many different agents; the best ones right now are Astra and Opus 5.5. That gives me many advisers, with different perspectives==: one AI builds, one audits, and five advise==. I also have my own OpenClaw bot, called Scibok. But LLMs create a lot of garbage, so getting to what I want to say is an iterative process. ==About one of their ideas, six rules for this university, I wrote: “none of this makes sense to me. what is our goal here”.==

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/058-1245-3.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/058-1245-3.mp4" aria-label="this app: custom, interactive, listening (live: what it heard)" style="width:100%;border-radius:6px;background:#000"></video>

This app you’re seeing isn’t PowerPoint. It’s custom, made from scratch for you, and completely interactive. It’s listening to me now, and it shows and highlights what it hears. In the background, a quantum wave function is evolving in real time.

It also let me work on the talk interactively. I’ve probably worked on this talk more than on any other I’ve ever given.

![[blog/assets/madison-keynote-2026-11-16/slides/059-1245-4.jpg|and a system to rehearse it (one of my notes)]]

It creates a synthetic voice of me ==giving the talk to a simulated room==, and I can listen to it. If a slide isn’t right, I hit N and leave a note: “No, I don’t want to include that. I don’t even understand what you’re talking about. That sounds ridiculous.” Then it goes back and fixes it. ==One run-through gave 27 notes. The one on the slide is why there’s no battery number in this talk: I didn’t know what it meant either.== It’s quite a remarkable thing.

This is just a data point in time. I have no idea what this will be in a year, but it will be radically different.

![[blog/assets/madison-keynote-2026-11-16/slides/060-1245-5.jpg|managing the slop: how the AI work is kept checkable]] ^managing-the-slop

One thing I want to get across, if you don’t work with AI all the time like I do: it’s all still slop. Managing the slop is very hard, because AIs generate it exponentially; they’ll create as much as you want. That is the name of the game, for scientists especially but for anything: how do you verify each step? This talk tries to verify every claim and trace it back to real sources, and external validators check those sources. ==Every calculation is recomputed by code, a second AI reviews the first, and every decision is written down. On the slides, each claim is marked with what supports it and whether an AI drafted the wording.== It still won’t be 100% right, but it has gotten very, very good. It’s the same way I do science now.

![[blog/assets/madison-keynote-2026-11-16/slides/061-1345-0.jpg|"You may be AI-pilled if…"]] ^ai-pilled

This is what my desk looks like at home. I’m truly the AI-pilled of the AI-pilled: many, many agents running all the time on different computers. It is not a joke that I’ve written 200 papers since Christmas.

I wouldn’t publish those papers. They’re not correct, or I can’t prove they’re correct. If they were, I would publish them. That’s where we are: you can generate much more than you can verify. As a science community, we’re trying to get to where you can believe it’s correct.

I work on the future roadmaps for Microsoft’s topological program, and I can’t tell you what those are yet. ==I’ve also been designing a ten-thousand-qubit machine, and not alone: my small team drafts the designs, and very busy experts, people building today’s systems, give us feedback. The real design rests on twenty years of intuition and knowledge, and on many people’s expertise.== But I can give you a taste of what this means==, from a paper anyone can read==, because I think it’s remarkable.

<video controls preload="none" playsinline poster="../blog/assets/madison-keynote-2026-11-16/slides/062-1345-1.jpg" src="blog/assets/madison-keynote-2026-11-16/feature/paper-to-10000-qubits-with-voice.mp4" style="width:100%;border-radius:6px;background:#000"></video> ^paper-to-10000-qubits

*From the paper to a 10,000-qubit design: the paper, the one prompt, and the movie the AI made, as I presented them (with sound, 58 s).*

This is a paper I wrote with MIT Lincoln Laboratory in \[2023\][^c12], when I was still in government. It’s a proposal for a specific type of qubit that, if you could make it, would be smaller and easier to control. ==The qubits are tuned by a voltage, with their capacitors built down through the silicon, and the couplers can be tuned without magnetic fields.== You can give this paper to an AI and ask it to make you a video of how it’s made, scaling it up from a two-qubit proposal to ten thousand qubits. This is the prompt. That’s it. ==It’s condensed from the ones I actually typed; then the agents go around the loop: design, compute, check, review, fix.== This is what you get.

It’s a 3D visualization of a 10,000-qubit quantum computer being built: all the qubits on one chip, the readout resonators on top, all the wiring, the 3D packaging, the fridges, the 4 K electronics. It’s not right. ==The first drafts shorted every qubit to its coupler, and the couplers barely coupled.== But how would you tell? If I were a VC, could I tell that it wasn’t real, that it wasn’t correct?

There are two messages here. One: if you know what you’re doing, you can move radically faster than ever before.

![[blog/assets/madison-keynote-2026-11-16/slides/065-1345-4.jpg|experts faster · anyone can learn to build]]

The second: it’s also incredible for teaching. You can now let people see what a quantum computer at that scale looks like==, and anyone can learn how to build one==.

A couple of other examples.

![[blog/assets/madison-keynote-2026-11-16/slides/066-1345-5.jpg|the Qubit Zoo, kept by Scibok]]

I have an OpenClaw agent that I set up at Christmas (I haven’t really done anything with it since). It reads the arXiv every day for the latest physics papers, collects every new qubit that’s proposed and goes back in time to collect the earlier ones. I created the Qubit Zoo, I don’t know, ten years ago. It was a side project, and like many things I do, I created it once and never went back to it.

Now Scibok, my Vulcan AI, maintains it for me. I named him after Sybok. He’s kind of grumpy, but he’s passionate about science. ==Every morning he checks his work against a second model before he updates the atlas. His motto: “The pipeline handles volume. Curation handles truth.”== The experiment here was whether it would turn to slop over time. So far, I don’t think it has. It has gotten better, although I don’t check it that much.

![[blog/assets/madison-keynote-2026-11-16/slides/067-1345-6.jpg|Meqanic: 2016 and 2025]]

He’s kind of annoying, too: he texts me every day, and I can’t keep up.

Another example is Meqanic. I wrote it right before my first child was born, and it took me thousands of hours to make. It’s a game designed to teach you quantum intuition without your knowing it. Could you make a version of Sudoku for quantum? Just make a game. This past Christmas, I recreated it in just over a week==: twelve days, with an AI agent==. The pace of change is remarkable.

![[blog/assets/madison-keynote-2026-11-16/slides/068-1345-7.jpg|"Small teams with AI…": the Maryland lab and its team]]

My thesis is that small teams who know what they’re doing can now move incredibly fast through design, code, theory, even engineering analysis. The bottleneck is moving to hardware.

That’s one of the motivations for the new research center we created in the Discovery District in Maryland. We announced it a year ago and launched it in September. The governor visited; it was a big, cool thing. This is my team, still in hard hats. The center is designed to be a mashup of quantum hardware: we have space for ten fridges and multiple types of qubit technologies, and a maker space.

There are three special zones. One is for Microsoft’s proprietary research. One is for working with our partners: several labs that work on different qubit technologies==, companies making quantum computers that want to interface with our quantum OS stack, and eventually Azure, and middleware companies working on key components for scale==. ==We also work there with DARPA to evaluate our topological qubit systems.==

![[blog/assets/madison-keynote-2026-11-16/slides/069-1345-8.jpg|next door: a quantum maker space for hardware, and its partners]]

The third is a community zone, next to the university, where we can do informal training for industry.

We have a lab with contributions from other hardware providers: RFSoCs from AMD, cabling and a fridge from Bluefors, qubit chips from Intel, IQM and Quantum Motion. ==Our partners, Fermilab and Riverlane among them, donate hardware and mentorship.== People can put together small quantum computers and get real hands-on experience with hardware. I believe it’s what we need to be doing. That’s the future. ==It’s an example of the leverage that’s coming for people who know what they want to do, are motivated and have some experience. At least for a little while.==

Then came the first decision from the audience.

![[blog/assets/madison-keynote-2026-11-16/slides/070-1515-0.jpg|two forks today; this one: the scientist or the science?]] ^scientist-or-science

We could talk first about how AI will affect the scientists, or the science. ==The scientist: what happens to a person’s judgment and training when AI does the struggling. The science: what happens to the field, what gets studied, published and cited.==

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/071-1515-1.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/071-1515-1.mp4" aria-label="THE ROOM CHOOSES · a show of hands; I call it (click a cluster, or press 1 or 2)" style="width:100%;border-radius:6px;background:#000"></video>

The room decided by a show of hands.

![[blog/assets/madison-keynote-2026-11-16/slides/072-1515-2.jpg|the room’s door first]]

It came out about 50-50, which surprised me, and I went with the scientist first.

After what I’ve just described, and for anyone who reads the news, this is probably not news: the effect on scientists is dramatic. Take me, a theoretical physicist. I don’t know how many years I have left of being valuable. I certainly don’t need grad students anymore. They slow me down.

The field has different perspectives on this. ==Google DeepMind’s policy team wrote in July that AI agents are conjecture machines: hypotheses are cheap now, and validation is the bottleneck. They add that leaning on them could de-skill junior scientists. Risa Wechsler at Stanford: “AI changes what problems are tractable, but it doesn’t tell us what problems matter.” In September, Fields medalists, twenty-eight of them now, signed a declaration: “The goals of the AI companies and the goals of the mathematical community are severely misaligned.” Terence Tao says current models are “ready for primetime” in math and theoretical physics, with one warning: they can produce “arguments that look polished while hiding the weak step.”==

My own position is that it’s still slop, but it takes longer and longer to prove that it is. I quantify it like this: if I have AI write a paper I want and give it to my smartest guy, how long does it take him to find a problem? At Christmas, it took about an hour: “Charlie, you’re crazy. What the hell is this?” Now it takes a month, or I need a team of people to validate it. ==It greatly accelerates people who know what to do, or who can find the mistakes. I worry about how junior people will be onboarded.==

At some point, I think, the slop will be so good that it is correct. Partly that’s because the AIs aren’t just getting better; they’ve also learned to use tools, and we’ve learned how to validate them externally.

![[blog/assets/madison-keynote-2026-11-16/slides/073-1515-3.jpg|then the other door, in full]]

The other door: the science. In the last month, the Aaronson–Ambainis conjecture, a problem in quantum information, was proved by AI==, in a machine-checked proof: there is no exponential quantum speedup on random inputs. Human review is under way. The model is Anthropic’s, and Anthropic’s models also built this talk==. I’ve heard about the Navier–Stokes controversy==, a claimed proof that the community hasn’t accepted. On one day, 722 AI manuscripts were released; three were retracted within three days==.

Open problems are starting to fall, especially ones that can be checked: mathematics, anything with a formal proof, some problems in theoretical physics. But in physics, at least, ideas still matter, and a lot of physics is still driven by experiment. The acceleration is very real, and it’s happening fast.

==The cost: a study of 41 million papers, in Nature this year, found that scientists who use AI publish three times as many papers and collect almost five times the citations, while science covers fewer topics. For quantum, a field built by a few people on unfashionable ideas, that pull toward data-rich topics is the risk.==

![[blog/assets/madison-keynote-2026-11-16/slides/074-1720-0.jpg|ACT III · Is quantum different?]] ^act-3

Now we’re getting to the quantum part. I think the central question for us all is: how is quantum different?

First, a little primer on AI and quantum. All of classical computing will be absorbed by AI. AI is the notion that I can train a deep-learning network: feed it a lot of information and lock in the weights between its artificial neurons. But everything about AI is still zeros and ones, governed by our classical understanding of computer science. It does a lot. The question is, what’s left for quantum?

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/075-1720-1.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/075-1720-1.mp4" aria-label="AI: billions of numbers, learned from data, on ordinary bits" style="width:100%;border-radius:6px;background:#000"></video>

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/076-1720-2.jpg" src="blog/assets/madison-keynote-2026-11-16/condensed/1720-2-3-4.mp4" aria-label="a qubit: an arrow on a sphere, 0⟩ rotated to +⟩; two complex numbers · the phase: φ sweeps the equator; the odds stay · measure it: one bit" style="width:100%;border-radius:6px;background:#000"></video> ^what-is-a-qubit

Quantum is different. Its fundamental unit is something called a qubit, a quantum bit. A qubit can have two states, zero or one; those are its classical instantiations. But it can also be in a superposition: it can be zero and one. It can have a phase, too. You need two complex numbers to describe any one quantum bit.

==Picture an arrow on a sphere. Pointing straight up, it’s zero. Rotate it halfway down, and it’s as much zero as one.==

==Spin it around the equator, and that’s the phase. The odds of zero and one stay the same.==

==Measure it, and you get just one bit: zero or one, with odds set by those two numbers. The phase is gone.==

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/079-1720-5.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/079-1720-5.mp4" aria-label="every qubit doubles it: 2, 4, 8, 16… complex numbers" style="width:100%;border-radius:6px;background:#000"></video>

That becomes powerful when you add more qubits and let them interact, because as you go from two to three to four qubits, the amount of numbers you need to describe the state grows exponentially. Six qubits require 64 complex numbers, and it scales: ==every qubit doubles it==.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/080-1720-6.jpg" src="blog/assets/madison-keynote-2026-11-16/condensed/1720-6-7.mp4" aria-label="entangle two: each alone a coin flip; together they always agree · measure both (click): they agree, and the link is gone" style="width:100%;border-radius:6px;background:#000"></video> ^entanglement

The core unique thing is that superposition creates a correlation that’s solely due to quantum mechanics, called entanglement. If I take two qubits and let them interact, I can no longer describe them separately, as two vectors, for example. I describe them as a whole, no matter how far apart they are.

These are two qubits interacting; the purple line is entanglement. ==Neither has an arrow of its own any more: each one alone is a fair coin.==

When I measure those qubits, the entanglement goes away, and you get one outcome with some probability, here one-one. ==The two always agree.==

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/082-1720-8.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/082-1720-8.mp4" aria-label="a quantum computer: set, entangle, interfere, measure" style="width:100%;border-radius:6px;background:#000"></video>

That correlation is intrinsic to quantum mechanics, and it’s the power quantum computers will use.

Say you have five entangled qubits. Quantum computation is taking qubits, entangling them, and measuring them. Dealing with the analog nature of the qubits, and working out how to take advantage of that state space, is the whole game of making quantum computers useful.

==Today’s machines are small and noisy, and they have started to correct their own errors, spreading one good qubit, a logical qubit, across many noisy ones. Google, Quantinuum, Microsoft with its partners, Atom Computing and IBM now run logical qubits on about twenty to a hundred qubits, and in the best experiments the errors shrink as the code gets bigger.==

To me, the foundational question, the equation that represents what we need to know in our field, is what is left when you take AI and subtract the rest of the universe. That’s where quantum is.

![[blog/assets/madison-keynote-2026-11-16/slides/083-1730-0.jpg|"Quantum = AI − ●": the ● is the universe]] ^ai-minus-the-universe

AI fundamentally represents only zeros and ones, but we know the universe operates by the laws of quantum mechanics. That’s the operating system of the universe. Quantum information science and technology is trying to devise computing and information technologies based on these fundamental rules, not on zeros and ones.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/084-1730-1.jpg" src="blog/assets/madison-keynote-2026-11-16/condensed/1730-1-2-3-4-5.mp4" aria-label="the universe gets very small; AI is a galaxy of stars · n = 50: Feynman&#x27;s library, 18 PB · a Universe of stars · n = 266: more numbers than atoms (our count) · collapse: one measurement, 266 bits" style="width:100%;border-radius:6px;background:#000"></video>

Our galaxy has hundreds of billions of stars, up to about 400 billion. That’s about the number of weights in a very advanced large language model==: Meta’s largest open model has 405 billion==.

==Fifty qubits need about 10¹⁵ numbers, 18 petabytes just to write down.== That’s about Feynman’s \[10¹⁵ bits, all the books in the world\][^c13].

But look at the Hilbert space of even a small number of qubits: this is the number of complex numbers you need to describe that space. ==On this scale, the AI galaxy is one dot.==

You can think of it as a universe, because even \[266 qubits give you about 10⁸⁰ numbers\][^c14]. It’s insane. That’s more than the number of atoms in the universe itself.

There’s a catch, though. When you read out those 266 qubits, you only get 266 numbers==, each a zero or a one==. The state might encode an insane amount of information, but you can only ever extract a very small amount of it. That’s why making quantum algorithms is hard.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/089-1730-6.jpg" src="blog/assets/madison-keynote-2026-11-16/condensed/1730-6-7.mp4" aria-label="the ideal: the P matrix from Meqanic (2016) · let the environment in: it drains to the diagonal" style="width:100%;border-radius:6px;background:#000"></video>

Another way to look at it is how I visualize it in the game Meqanic. ==Every square is one correlation among six qubits.==

On the left are all the quantum coherences, all the numbers I just told you about, for a fairly small quantum computer. But when you add noise, what we call decoherence, all those quantum parts go to zero, and you’re left with only the classical parts. ==The environment measures the qubits for us.==

![[blog/assets/madison-keynote-2026-11-16/slides/091-1730-8.jpg|the real machine, and its competition]]

==Error correction buys back good qubits at a steep price: in the design I showed you earlier, ten thousand physical qubits make about fourteen logical ones. The race is an imperfect machine against a century of chemistry and computing, and now AI.==

![[blog/assets/madison-keynote-2026-11-16/slides/092-1730-9.jpg|how quantum is the universe, really?]]

That’s the fundamental difference between quantum and classical. Classical, what we see in the world around us, is the diagonal. Quantum is what we’re trying to preserve in a quantum computer. The question is: how quantum is the universe, really? What are the problems we care about? ==To me, the seminal question in our field is how big the delta is: what quantum computers can do that AI and classical computers can’t.==

There are many ways to think about this.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/093-1845-0.jpg" src="blog/assets/madison-keynote-2026-11-16/condensed/1845-0-1-2-3.mp4" aria-label="the players: a wall, a referee, a coin each, an answer each · the rule: match, unless both heads · the best plan: both always answer 0 (75%) · an entangled pair: a dial set by each coin (85%)" style="width:100%;border-radius:6px;background:#000"></video> ^a-game-for-two

This is a game that tries to tease out the strangeness of quantum mechanics==: a game for two players who can’t talk. Each gets a coin flip, and answers zero or one==.

==They win if their answers match, unless both coins are heads. Then they have to differ.==

==No plan agreed in advance wins more than three in four. That’s a theorem: for you, for me, for any AI.==

The fundamental thing about the game is that there’s a difference between the classical outcome and the quantum outcome. If you give the two players an entangled pair of qubits, ==with no message in it,== they can do better==: they win 85 percent of the time==.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/097-1845-4.jpg" src="blog/assets/madison-keynote-2026-11-16/condensed/1845-4-6.mp4" aria-label="an AI agent calls the quantum computer (terminal replay) · two entangled qubits · simulated here; the real tests were in 2015" style="width:100%;border-radius:6px;background:#000"></video> ^agent-calls-a-quantum-computer

For decades, many different groups played this game experimentally to prove Bell’s theorem. But now, if you have a quantum computer on your network, you can tell GitHub Copilot about it and ask it to write an algorithm that plays this game and proves out this quantum experiment for you. It’ll do it, and you get the results. That’s just one example of what’s going on in AI.

==I gave an AI coding agent one paragraph like that. Nobody gave it a tool for this: it read the manual, wrote its own program, and counted the wins. Around last Christmas, this started to work.==

A quantum computer lets you test the fundamentals of quantum mechanics. ==The entangled pair won 83 percent of four thousand rounds.==

==I should tell you: that quantum computer is a simulator on my laptop, with error rates like today’s machines.==

==The real tests were done in 2015, in Delft, Vienna and Boulder, on entangled pairs kept apart, and the quantum prediction held.==

![[blog/assets/madison-keynote-2026-11-16/slides/100-1945-0.jpg|you have seen two of three: big · strange · useful]] ^big-strange-useful

The takeaway is that quantum is cool, but there are three different ways to think about it. Quantum information can represent very big numbers. It can appear very strange to us. But at the end of the day, it needs to be useful.

==The Automatons pushed back here: “Exponential state space is not an advantage proof.” They’re right.==

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/102-1945-2.jpg" src="blog/assets/madison-keynote-2026-11-16/condensed/1945-2-3-4.mp4" aria-label="the room shrinks: every possible book · measure it: one book, at random · an algorithm: the art of finding the book" style="width:100%;border-radius:6px;background:#000"></video> ^library-of-babel

Think of the Library of Babel. ==In 1941, Borges imagined a library that holds every possible book. Every truth is on a shelf somewhere, every falsehood, and mostly noise.== You can have a library with \[all those books\][^c15], but if you can’t find the one you’re looking for, it’s useless to you.

==A quantum computer’s state has a number for every book in a library like that. But measure it, and you get one book, at random.== Quantum algorithms try to come up with very clever ways to encode the right answer into the thing you can measure.

That’s the ==art== of a quantum algorithm. ==It makes those numbers interfere, so the book you want is the one you’re likely to pull. Without one, big is just big.==

![[blog/assets/madison-keynote-2026-11-16/slides/105-1945-5.jpg|STRANGE: real physics, no speedup]]

The strangeness, the difference between 75 and 85 percent in the game, is bizarre. It happens only because of quantum mechanics, and yet I can simulate it on my computer perfectly. It’s nothing different, and it’s not useful for anything.

![[blog/assets/madison-keynote-2026-11-16/slides/106-1945-6.jpg|USEFUL: the test (big and strange fail it)]]

==Useful takes three things: someone needs it, it beats the best classical method, and you can pay for it.== There are other examples in the literature. Google had amazing results on quantum sampling ==in 2019==: very hard to simulate classically, but not useful at all. ==The classical estimate of ten thousand years has since become fifteen hours.==

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/107-1945-7.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/107-1945-7.mp4" aria-label="what passes, and what it costs: real problems mapped to physical qubits" style="width:100%;border-radius:6px;background:#000"></video> ^how-many-qubits

It comes down to finding algorithms that matter, and there are very few algorithms a quantum computer can run that are valuable. They’re predominantly around cryptography and simulating nature: chemistry, molecules==, like FeMoco, the catalyst that fixes nitrogen==. Fortunately, that’s pretty important to society. But it’s still a pretty small number of algorithms where a big quantum computer will be useful. ==Most need millions of physical qubits, and the estimates keep falling.==

![[blog/assets/madison-keynote-2026-11-16/slides/108-1945-8.jpg|World View: "A customer pays for what works"]]

Even that is hard, because quantum computers are competing with 40 years of Moore’s law and really good classical algorithms and approximations. ==As I wrote this summer, quantum machines “don’t yet beat supercomputers. A customer pays for what works, not what is promised.”==

Very briefly, about cryptography.

![[blog/assets/madison-keynote-2026-11-16/slides/109-3000-0.jpg|how RSA works: easy to multiply, hard to factor]] ^breaking-encryption

Our cryptography is based on a hard math problem: factoring a large number into two numbers. It’s hard to do, but the answer is easy to check. That asymmetry is what makes public-key cryptography work. ==That’s RSA, the lock on your browser.==

![[blog/assets/madison-keynote-2026-11-16/slides/110-3000-1.jpg|why a quantum computer is good at it: hidden structure, easy to check]]

Quantum computers happen to be very good at it, because there’s some hidden structure in the mathematics==, a repeating pattern,== and because the answers are easy to check. ==Peter Shor showed how, in 1994.== But even then, you need a lot of qubits to do it.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/111-3000-2.jpg" src="blog/assets/madison-keynote-2026-11-16/condensed/3000-2-3.mp4" aria-label="2012: about a billion qubits (qubits shrink to pixels, then the wall of screens) · 2026: 94,000" style="width:100%;border-radius:6px;background:#000"></video>

In 2012, the estimate was about a billion qubits, running for about a day, under wildly optimistic assumptions, to break our encryption==: RSA-2048, a standard public-key code==.

That has improved. This year’s estimate is about 100,000==, running for up to a month==, again with optimistic assumptions, and still a long way from where we are technologically. We’re at about 100 qubits now.

![[blog/assets/madison-keynote-2026-11-16/slides/113-3000-4.jpg|meanwhile, the classical side]]

Even classically, the AIs have gotten very good at some of this. ==This September, teams using AI coding agents set two classical factoring records, with no new algorithm and no threat to today’s keys.== But intrinsically, these are hard mathematical problems we don’t think classical computers can ever solve. That’s what’s unique about quantum.

==The government’s high-value systems must move to post-quantum key exchange by 2030, and once the keys move, breaking today’s encryption matters less.==

![[blog/assets/madison-keynote-2026-11-16/slides/114-3000-5.jpg|sensing: clocks · entangled sensors · small and light · new modalities, and AI reading all of it]] ^sensing

I’ll also mention quantum sensing, briefly. Quantum effects have made very good sensors==: clocks that agree at the nineteenth digit, telescopes linked by entanglement, an atomic clock that weighs thirty-five grams==. But from a policy perspective, at least five or ten years ago, they weren’t that different from the sensors we already think about. They’re just better, so our export-control policy and the rest don’t change much.

That may be changing as AI comes into the picture. AI is so ubiquitous now that different modalities and faster sensors might make a huge difference over their classical counterparts. ==Quantum could also push sensing into new kinds of measurement nobody can predict yet. The people who invented atomic clocks never pictured ride-hailing apps.==

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/115-2200-0.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/115-2200-0.mp4" aria-label="MY AGENTS CHOOSE · the fleet’s tally (1/2 forces)" style="width:100%;border-radius:6px;background:#000"></video> ^small-or-big-delta

This is what I call the fundamental question: is the delta, quantum minus AI, big or small? I asked the agents. Of course, I ask the agents everything. I asked \[24 of them\][^c16] through Copilot==, and had one agent pull their answers together. Eighteen said small and six said big. The synthesis came down on small, at 60 percent: “useful but limited additional quantum value … the credible BIG window is 2036-2041.”==

They predicted it’s small. For the next 15 years, we’re not going to see huge quantum advances over AI. But after 2040, which is kind of far away if you’re an industry guy, we will. ==Most of the six who said big bet on quantum data feeding AI. The synthesis warned me itself that these models share training, so eighteen to six is not eighteen independent votes.==

![[blog/assets/madison-keynote-2026-11-16/slides/116-2200-1.jpg|the chosen branch, deep (50 s)]]

There’s reason to believe that most physical systems aren’t that quantum. A lot of the things we calculate for chemistry, like the ground-state energy, are very well approximated by classical computers. ==Garnet Chan at Caltech and co-authors from Google put it this way for chemistry: evidence for an exponential quantum advantage “across chemical space has yet to be found.”==

==Nano dissolved into chips. Maybe quantum dissolves into the AI stack.==

![[blog/assets/madison-keynote-2026-11-16/slides/117-2200-2.jpg|the other branch (15–25 s)]]

But on the flip side, we just don’t know. Quantum is so different. ==For much of nature, the data AI needs doesn’t exist. Factoring at scale resists every known efficient classical method. And for some tasks, a quantum computer can learn from nature with exponentially fewer experiments. The delta could be big.==

That brings me to intuition==, where I think a big delta could come from==.

![[blog/assets/madison-keynote-2026-11-16/slides/118-act-4-0.jpg|Act IV · Building quantum intuition, for people and for machines]] ^act-4

Act Four is about how you build quantum intuition. We grow up learning about gravity because we fall down. We don’t learn about quantum physics, because we don’t experience it in our daily lives. I’ve spent a lot of my career thinking about how to let people experience it.

![[blog/assets/madison-keynote-2026-11-16/slides/119-2415-0.jpg|the 2022 wish: “What does that girl see?”]] ^quantum-intuition

I wrote an essay ==in 2022, “A Quantum Wish,”== about what it would be like to step inside a quantum computer. ==It imagined a museum where every visitor is a qubit: walk close to someone and you entangle; press a button and you’re measured. My question was, “What does that girl see?”==

I was working with media professors at the University of Maryland on this. How do you visualize entanglement, and get a physical sense of what’s going on?

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/120-2415-1.jpg" src="blog/assets/madison-keynote-2026-11-16/condensed/2415-1-2.mp4" aria-label="scene · two visitors meet, part, and a third passes (0–17.6 s, played at 1.3×) · scene · the girl presses her button (measured at 18.2 s)" style="width:100%;border-radius:6px;background:#000"></video>

==This is one answer, reimagined with AI and computed live.== These are people, each holding their own qubit. As they get closer to each other, the entanglement grows. ==They walk apart, and the correlation stays.==

You can see it in these purple strings. Then you bring in measurement==: the girl presses her button==, and the entanglement goes away.

![[blog/assets/madison-keynote-2026-11-16/slides/122-2415-3.jpg|the real thing: Quantum Intuition XR (IEEE TVCG 2026)]]

It’s a visceral way to experience quantum mechanics.

This has turned into a VR app you can download. ==Myungin Lee’s group at Maryland built it to help build intuition. I’m co-PI on the project, and it’s in IEEE’s visualization journal this year.== I made a 2D version online, if you want to play it.

This also translates to my central thesis about AI.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/124-2415-5.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/124-2415-5.mp4" aria-label="we grow up without it; a model trained on quantum data might not · World View: &quot;customer and accelerant&quot;" style="width:100%;border-radius:6px;background:#000"></video>

If you could give AI quantum data in a very deterministic way, say from a very large quantum computer, it might grow up with quantum intuition, and get there far faster than we can. ==I learned mine over 25 years; a game or a headset can give someone a little of it sooner. That’s the bet in the equation: quantum equals AI minus the universe.==

==As I wrote in Nature this summer, “AI is both a customer and accelerant: quantum machines will produce data about molecules and materials that nothing else can, and could be used to train better classical models.”== Then the question is: how powerful is that?

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/125-1830-0.jpg" src="blog/assets/madison-keynote-2026-11-16/condensed/1830-0-1.mp4" aria-label="a telescope collects: the universe, a few photons at a time · a quantum computer reaches in: probe, manipulate, measure" style="width:100%;border-radius:6px;background:#000"></video> ^telescope

==Quantum is the description at a more foundational layer. We have very limited access to it, with few instruments around the world.==

Quantum computers are, in many ways, like telescopes for the universe. They let you not only see what’s going on, but actively manipulate it. You create very artificial quantum states by hand, and you can run whatever experiments you wish, as we’ve seen.

If \[an AI\][^c17] had that, the way it has access to a game (that’s how they do reinforcement learning now), how good could it be, even if it’s still classical? My thesis is that quantum computers will give that to AI.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/127-1830-2.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/127-1830-2.mp4" aria-label="its data, into AI: step functions we cannot predict" style="width:100%;border-radius:6px;background:#000"></video> ^my-bet

You’ll use that quantum data to train artificial intelligence, even classical artificial intelligence.

![[blog/assets/madison-keynote-2026-11-16/slides/128-2900-0.jpg|the 2040 paper, Future Charlie, and card 2 of 3: the models got better at all science]] ^simplest-quantum-computer

I wrote a paper about this ==in 2024==, “The Simplest Quantum Computer,” and last year I talked about it dressed as Doc Brown. The paper is written from the year 2040. It’s completely speculative ==(it’s dated April 1)==, but if you’re interested in my guess at the future, you can read it. The guess is that models will get better just from quantum data. ==As the paper puts it, looking back from 2040: “the models got better at all science, and we didn’t know why.”==

![[blog/assets/madison-keynote-2026-11-16/slides/129-2900-1.jpg|only trained on it]]

==The models weren’t doing quantum processing. They were only trained on it.==

![[blog/assets/madison-keynote-2026-11-16/slides/130-2500-0.jpg|trained on code: better at code, and at more than code]] ^trained-on-code

There’s some reason to believe it. Look back at the last five years of training LLMs. When LLMs were given code from public repositories on GitHub, they got remarkably better at code.

But they didn’t just get better at code; they got better at everything. They got better at reasoning, simply because they had access to all this structured data: things you can run and check. ==In 2022, the model trained on code beat the text model at commonsense reasoning, on tasks with no code in them. A controlled test in 2024, on small models, found that adding code to the training data improved reasoning and world knowledge too.==

![[blog/assets/madison-keynote-2026-11-16/slides/131-2500-1.jpg|then a checker · DeepSeek-R1: "a reliable verifier"]]

==Then came a second jump, from a checker: training on problems whose answers can be checked.== The papers from DeepSeek and OpenAI speculate about giving these models biological and chemical reagents. You need things that are verifiable, and those could increase the general capabilities of LLMs.

![[blog/assets/madison-keynote-2026-11-16/slides/132-2500-2.jpg|"For chemistry, the checker is nature."]]

For code, the checker is a test suite: I can run the code and see if it works. But for chemistry, you need nature, and nature is embodied, fundamentally, by a quantum computer.

![[blog/assets/madison-keynote-2026-11-16/slides/133-2600-0.jpg|the Automatons object, aloud: benchmark jumps are not a mechanism]] ^the-bet-and-how-it-loses

![[blog/assets/madison-keynote-2026-11-16/feature/automaton-benchmark-jumps.m4a]]

*The Automaton’s objection, as it played in the room (a synthetic voice).*

The Automaton objected, in a synthetic voice: “Benchmark jumps do not establish your proposed mechanism or transfer to science.”

So the Automatons are British. They’re saying this is complete speculation: you can’t automatically translate it to science. That’s true.

![[blog/assets/madison-keynote-2026-11-16/slides/134-2600-1.jpg|the bet: the missing data]]

But there is evidence for the idea. Microsoft has been developing deep learning models for chemistry, and you can start to simulate that quantum data classically. ==Skala, one of these models, was trained on about 395,000 high-accuracy classical labels. On the 17 hard molecules in its test, its error is five times what it is on ordinary ones; its authors call them “the multi-reference cases for which we lack training data.” My bet is that a quantum computer supplies those labels.==

![[blog/assets/madison-keynote-2026-11-16/slides/135-2600-2.jpg|the cost, and the catch]]

You don’t have a quantum computer big enough yet, but you can use a huge computer to calculate the answers exactly up to some size, give the model that data, and see if it improves. You do start to see some improvement, at least for chemistry problems.

==The full calculations need millions of physical qubits. Training data for AI may need fewer: only the hard labels where the models fail. Matthias Troyer and Chi Chen put that at about a million physical qubits.==

==There’s a catch, which Garnet Chan and colleagues pointed out: whatever makes the quantum algorithm’s starting state easy to prepare may also make the problem easy for classical methods.==

![[blog/assets/madison-keynote-2026-11-16/slides/136-2600-3.jpg|Jacob’s Ladder: quantum bends the curve, AI flattens it · early evidence]] ^jacobs-ladder

The figure is from Matthias Troyer and Chi Chen at Microsoft, who argue that combining AI and quantum data directly will overturn the exponential cost of classical simulation. ==On their ladder, the more accurate the chemistry, the more it costs. Nobody has yet trained AI on chemistry data from a quantum computer.==

![[blog/assets/madison-keynote-2026-11-16/slides/137-2600-4.jpg|how it loses · what I am betting]]

The flip side is that if a classical method can provide this data ==just as well, for less money==, then quantum computers are not useful. That’s the fundamental question, for scientists and for industry.

==We don’t know the step function quantum data will give to AI’s ability to make things and understand things better. But it could very well be dramatic.==

![[blog/assets/madison-keynote-2026-11-16/slides/138-3415-0.jpg|card 3 of 3]] ^magic

The Automatons found another comment, ==from a second reader of the same 2007 article,== and it flips the usual saying: “Any technology which is distingishable \[sic\] from magic is insufficiently advanced.” If it doesn’t seem like magic, it’s not good enough. I thought that was very relevant. ==The first reader said people will want the technology “when it works, not how it works.” In 2007 that was a shrug. Now it worries me.==

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/139-3415-1.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/139-3415-1.mp4" aria-label="the phone comes apart: &quot;somebody knows&quot;" style="width:100%;border-radius:6px;background:#000"></video>

Look at the phone. It comes back to the whole thesis of AI. What happens in a world where everything in our phone is developed by AI and not by a human being? Right now, somebody knows how to make the glass. Somebody knows how to make the battery. Somebody knows how to make the processor. At some point, the AIs will be making it. That’s already happening. Then nobody will know.

I’d argue it doesn’t matter to most people. Most of you don’t know how the processor is made; you just want a better iPhone every year. But the model directing all this is the great unknown. When you have a model that’s better than human, maybe even incorporating an understanding of the universe we have no hope of perceiving, you can be manipulated by it.

==I’m a parent. I’ve watched my own son in the infinite doom scroll. The research on what it does to teenagers is contested, but the feed was built to win, and it usually does.==

![[blog/assets/madison-keynote-2026-11-16/slides/140-coda-0.jpg|Coda · Your turn]] ^coda

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/143-3930-2.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/143-3930-2.mp4" aria-label="your triangle: building a quantum ecosystem · huge for AI · for quantum, we don&#x27;t know yet · one thing to most people · the fourth vertex: the public" style="width:100%;border-radius:6px;background:#000"></video> ^the-fourth-vertex

To end today: this part is about you, and how you can contribute to this question of quantum in society.

This is a figure I’ve been showing. I care about building quantum ecosystems, in Maryland and across the country. How do you get a crucible of innovation? You need people, you need talent, you need infrastructure, and you need government, industry and academia to come together to enable that.

But the real question, I would argue, is what’s different about quantum and AI. For AI, clearly, the implications are huge.

For quantum, I argued in government that they’re fairly narrow, but we don’t know yet. ==That’s the point of AI minus the universe.== Finding these differences is key.

==Twenty years ago, my course here asked: who decides?== For you, the question is how to add the public as an element of this. In the quantum community, we haven’t done that explicitly yet, because of that decision: we tried to keep quantum very narrow, focused on what’s different about it.

In the quantum office, I didn’t want to worry about AIs taking over the world. That was not my job. I didn’t want to worry about synthetic biology. That was not my job either. I wanted to worry about quantum information. What’s different about that? I did have to worry about encryption, obviously, and about the fact that it’s an emerging technology I can’t predict. But those other problems are other people’s problems: the NNI office’s, or the climate change office’s.

![[blog/assets/madison-keynote-2026-11-16/slides/144-3930-3.jpg|the charge to this group]]

But I don’t think we can say that anymore, because of AI. In the public’s mind, AI and quantum will become the same thing. ==In the UK’s 2024 public dialogue on quantum computing, people worried quantum would bring what they saw as the harms of AI.== That’s why education will matter.

==That’s my charge to the working groups this afternoon: how should the public be included in the evolution and deployment of these technologies? In AI, in quantum, and where people can’t tell them apart.==

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/145-4030-0.jpg" src="blog/assets/madison-keynote-2026-11-16/loops/145-4030-0.mp4" aria-label="&quot;Five things to take into this afternoon&quot;: each lights in turn, on its own" style="width:100%;border-radius:6px;background:#000"></video> ^five-takeaways

I have five things for you to think about.

One: ask yourself what is fundamentally different about quantum.

Two: quantum information is an emerging technology. We don’t know its ramifications yet. In many forms, it doesn’t exist yet.

Three: don’t cause more trouble than is really there. It’s important. Don’t fear-monger if you don’t have to.

Four: my argument is that AI is a real story, but we don’t know the step function quantum will bring to it. The two will be conflated in the public’s mind anyway.

Five: at the end of the day, we don’t know what will happen when you include the rest of the universe.

<video data-loop muted loop playsinline preload="none" data-poster="../blog/assets/madison-keynote-2026-11-16/slides/146-4400-0.jpg" src="blog/assets/madison-keynote-2026-11-16/condensed/4400-0-1.mp4" aria-label="through the eyepiece: how big is the delta? photons, one at a time, then they stop · the disc fills with the wave and stays" style="width:100%;border-radius:6px;background:#000"></video> ^ending

To sum up: how big is the delta between AI and quantum? I don’t know. I’ve argued that it’s small, and I’ve argued that it’s big.

This is the telescope looking into the universe. ==Through the eyepiece today, the photons come one at a time.== My bet in the Nature World View I wrote over the summer was that in five years we’ll see a quantum computer do something that really surprises us: something we can’t simulate classically, or that we weren’t expecting. ==The sentence I wrote down: “In five years or less, a quantum computer will do something that someone needs and no ordinary computer can do, with a solution that changes how we look at the world.”==

Building a quantum computer is hard. I’ve been working on it for 25 years. We think we need hundreds of thousands to millions of qubits, or hundreds of millions, to beat our best classical computer. I’m competing with Azure, the biggest computer in the world, so my quantum computer has to be better than that. Five years is, I think, still ambitious. But the bet combines the rapid change in science due to AI with all our progress in quantum over the last 20 years.

==At the start, you raised your hands.== You overwhelmingly agreed with me: twenty of you think it will happen within five years==, six within ten, two within twenty, and none of you said never==. ==As I also wrote in July: “A good guesser is just someone who has been surprised enough times that they stay humble.” AI is the story. Quantum is how the rest of the universe gets into it.==

In the background, there’s been a wave function==: a simulation running behind every slide, in which every idea I raised is the source of a quantum wave, and the waves interfere==. We’ve been measuring it at our decisions==, and at each fork it collapsed into clicks==. This one we’ll leave unmeasured, because we don’t know.

![[blog/assets/madison-keynote-2026-11-16/slides/148-4400-2.jpg|Gonzaga, sophomore year: Earth Systems Science, a first Mac, SimEarth]]

One more story. My first foray into science and society was as a sophomore in \[high school\][^c18]==, at Gonzaga==. The NSF comes back into it: two \[teachers\][^c19] at my school got an NSF grant to teach a new after-school class on Earth system science. This was 1993, when the internet was just coming out, and the whole premise was to learn it from NOAA and NASA data on the internet. ==It was the first time I used a Mac, and it changed my life forever.==

The first week, ==before we learned HTML, FTP and Gopher, and data sets on climate change,== they had us play a game called SimEarth. Does anybody remember SimEarth? Anybody old like me? In that game, you create a society from scratch, and you learn how the Earth pushes back as you cause damage, by making volcanoes and so on.

![[blog/assets/madison-keynote-2026-11-16/slides/149-4400-3.jpg|EPOQ: early access, this afternoon · play the Madisonia world]] ^epoq

I got nostalgic making this talk, and I decided to give you a gift: I wrote you a game called EPOQ, a reimagining of SimEarth from scratch. ==I gave the AI this talk, and all my papers, and worked with it on a first version you can play today.== The game is focused on societies. You guide your society and your planet, called Madisonia, through policy decisions. Should we plow the fields? Should we invest in a national farm initiative? Should we let AI take over? Then you see what happens.

I’m not claiming it’s good; it’s slop. It’s a really beautiful slop, I have to say. Take a picture and try it. That’s my gift to you, because Madison has been very good to me over the years.

![[blog/assets/madison-keynote-2026-11-16/slides/150-4400-4.jpg|Thank you · charlie at tahan.com]]

I don’t know if it’s good or not, but thank you.

## Questions and answers

*Seven of the questions from the fifteen minutes after the talk, transcribed as asked, without names. \[…\] marks a detail left out, and a bracketed word with a question mark one the recording didn’t catch clearly, since most questions were asked away from the microphone. The answers are mine, edited to read.*

> **Question 1.** You started us with a question of when AI or when quantum computing will surpass our current expectations of human intelligence. I guess I want to ask you, what do you think has to change in human intelligence to handle all these changes in things like AI?

We’re already reaching the limits of what we can process. I have hundreds of agents working all the time, and I can’t keep track of what’s going on. Either we become cyborgs, or we let them do their thing and go back to living like humans. There’s the Star Wars future, where we’re all still humans in a great sea of intelligences, and the question is how we coexist. Or we merge with them. That’s my opinion: one of two choices.

> **Question 2.** Two questions. The first one is super quick. One time I heard you speak, maybe a year or two ago \[inaudible\], you were talking about quantum as a new paradigm of compute. I’ve always loved that. I’ve actually kind of sold that since you said it, and I’ve used it over and over again. And now today it’s like the delta between AI and quantum is small. I get what you mean by that, but I’m wondering if you could comment on that with the paradigm of compute.
>
> And then on AI, an interesting comment: a professor friend of mine made the exact same comment, because he loves AI too. He has a team of agents, and he said, I think, the exact same sentence, which was something like, I don’t need grad students anymore because I get so much done. You talk about the 200 papers and stuff. So I’d be a little bit critical of that: is it also maybe an evolution of that manager person themselves? Maybe going from manager to an all-star engineer, or maybe someone else does the teaching and the mentoring, and it’s like, hey, I just want to work, this is so cool, I just want to be with the AI and get stuff done.

That’s extremely insightful, and I’ve thought about it myself. As your career progresses, you become the boss: you make decisions, send people off to work on things, and review what comes back. AI brings you back; I’ve heard the same from colleagues. You don’t have to spend a whole day figuring out how to put Python on your computer before you can do the science. You say, put Python on my computer, let’s get going. It lowers the barrier to doing the work, and that lets the bosses get back in the game.

As for grad students: I say I don’t need them, but I still want them, and we need some of them. The question is how many. That’s a fundamental question, and it will be hard to deal with. Will AI accelerate everybody, or a few people a lot more? It’s like the trombone players in a symphony: we only need two, and they need to be really good. Versus a whole symphony of violin players. We’re all going to have to tackle that question, and I don’t have an answer for it.

> **Question 3.** \[…\] My question is maybe slightly rude, in that I’m going to turn one of your questions back on you, because the first question in your charge to us today was exactly the one I was thinking about all during your talk: whether quantum is an enabling technology or a paradigm shift. You’ve presented it largely as an enabling technology, by presenting it within the frame of AI: what it does is it sort of gets us to places faster and better. But my understanding is that within theoretical physics, it really is a paradigm shift. It is a fundamentally different way of thinking and being, as you’re trying to get across with some of these quantum intuition games.
>
> So I guess the question that I have for you is: is it right now an enabling technology because people are not thinking of ways to use it within a new paradigm? What would it do differently if we were thinking in a paradigm, and not just applying it as an enabling technology? And what are some of the ramifications that we could consider if it was actually more of a paradigm shift?

These are good questions. Let me level-set first. Forget about quantum sensing: quantum clocks exist, and they’re very useful. We’re talking about quantum computing.

First, quantum computers are not useful right now. They’re not big enough to beat what I can do on my laptop, so it’s very hard to tell. For certain applications, like cryptography and chemistry, we can cost it out: I need 100,000 qubits, they have to be this good, and they’ll do this. They could factor a number in a month that would take me 10 billion years. That’s transformational. Those are exponential speed-ups, and we don’t have them yet. That’s one statement.

The second: from the perspective of computer science and physics, quantum information science and technology is a foundational shift in computing. Our whole basis of computing, everything in this laptop, rests on our abstractions: I call them the zeros and ones, the Turing machines. That is not how the universe works. It’s a subset. It turns out to be extremely powerful: you can do everything AI can do, everything a computer can do. But it’s not complete. It’s wrong, in some sense. Quantum information science fills that gap. This is how the universe actually runs: not on zeros and ones, but on quantum mechanics, the laws that govern the universe. And we have shown how to get exponential improvements on certain problems: some math problems, and simulating nature.

But we are bad at predicting what a foundational shift will do. That’s why I call it an emerging science and technology: we don’t know what will happen. And this is the fundamental question: is it big or small? My bet, after 30 years of my life, is obviously that it’s huge. On the other hand, over the next five years, AI is pretty damn big. Everything in the world is mostly classical, and AI’s ability to approximate the stuff that matters to us might be very, very large. It’s hard to know how much the exponential matters. Cryptography will matter until it doesn’t, and then it’s really just simulation. How big a leap will it be, and what else could come of it? It’s very hard to predict. That’s why it’s the problem.

> **Question 4.** Thank you for that really interesting talk. I learned a ton. You started out with a prevailing metaphor. You said it’s going to be either Star Trek or Star Wars, which I appreciate as a fellow TNG head. And I really like that, but I wonder if there is a third option. And the third option is what keeps me up at night, which is more of a Blade Runner universe, where technology is introduced everywhere, but we have massive income and wealth inequality, where most people live in misery at the bottom, and then there are a few people in the big pyramid that have all the money and technology. So I wonder if you could comment on that likelihood, as a third possible option that’s not Star Trek \[word?\].

I think that is Star Wars, actually. In Star Wars, most people are not doing that great. But it’s hard to predict. My wife accuses my family of being natural doomers, and I don’t like to be that doomerish. What you certainly see is that AI tools can make some people exponentially more valuable. They make other people more valuable too, but not exponentially. Your 10-times programmer could become a thousand times, and your one-times programmer two times. What happens in that world?

I think we basically have to become Europe, where we say everybody’s got to be doing well. We all need jobs. Otherwise, it won’t be fulfilling. We’re facing a scenario where we have to ask: what is our meaning? As a mathematician or a physicist, I’m not going to be that great at it compared to AI. We’re all trying to figure that out, and it depends on how it plateaus.

At the Global Physics Summit in April this year, we have a workshop called the Quantum Vibe Shop: how do AI tools affect scientists? My talk is called Cope, because we’re seeing a lot of coping. Why am I doing all this creative stuff? Because: what’s my value? That’s going to change dramatically over the next few years. But Mark’s still got his experimentalist, so he’ll be fine for five to 10 years at least. We’re working on robots, though, man.

> **Question 5.** \[partly inaudible\] I wanted to just ask a maybe technical question, maybe not. You pointed out that the whole universe is quantum \[word?\], and yet most things are not quantum \[word?\]. I just wanted to ask you an opinion on what the biggest chunk of the universe is that’s actually important \[word?\], right? \[partly inaudible\]

Watching our applications team: it’s chemistry simulations of very complicated molecules with a lot of strong correlations. Those are extremely hard to simulate classically. And to be clear, you see a lot in the news about quantum data accelerating AI. Our predictions are that you need a quantum computer with error rates of 10 to the minus 15, which means millions of qubits to generate that data. You need an extremely good quantum computer. Once you had that, and it was free, I think you’d see dramatically easier ways to make pharmaceuticals, drugs, custom everything. But that’s a ways away. AI could bring in the timeline a little.

The other part is that I don’t know. The analogy is deep learning: in the ’80s, you couldn’t have written down an algorithm that would predict where we are today. Heuristics got us here: data plus compute plus deep learning. If you had a quantum computer, plus all this other stuff, we don’t know what will come out the other end. It could be far better than our primitive minds can predict.

> **Question 6.** I really appreciate your comments about putting some boundaries around what is quantum. I mean, I think those of us who were studying nanotechnology a while ago saw the rush in, and so then suddenly everything was nano, and people who were not doing nano now buy \[word?\] the nanotechnologies. And there are really impacts in terms of how funding happens, how attention is focused. So your description of what happened with the quantum initiative is really interesting to me, because there was a real paring down, which maybe not only made the field smaller, but also excluded some of these social and ethical perspectives. And yet, paired with that, we see AI as this crazy expansive term that nobody’s trying to control. Now everybody is doing AI, and everything counts as AI, and there’s so much attention from scientists, technologists, social scientists and humanists on AI, and thinking about it compared to quantum.
>
> So what does it mean? As we think about intersections with quantum, are we simply misfiring? Is this the wrong space? Is the real work to be done in AI, where there is a more expansive terrain? Or is there a possibility of focusing more narrowly on quantum, and bringing these kinds of perspectives into a conversation that hasn’t yet happened in that space?

This is what I wanted to convey. There’s a real danger in saying “we’re going to do quantum and society,” and then it’s: what the hell is it? You need to think about what is different, and what you want to add. I’ve argued that you can’t talk about quantum without AI, because it’s so integrated in the science now. It’s going to be tied up in data centers anyway. We’re talking about putting quantum computers in data centers, and everybody’s worried: is that more data power? All the societal issues come to the fore.

I don’t have an answer. I think that’s the question. You need to figure out this afternoon what to focus on that would make a difference: what you can add to the conversation. It’s not enough to say “I’m doing quantum and society.” What are we really worried about? Is it encryption? How does quantum affect data centers and AI? How does it get merged in the public’s consciousness, and is that dangerous? Because it could end up killing quantum. If the public turns against AI and data centers, suddenly quantum has a target on its back for no reason. That’s a dangerous outcome, and public engagement and science-and-society studies should tackle it. That should be your job: to teach, and to figure out what matters. I don’t have the answer yet.

> **Question 7.** \[…\] So the question is: I’ve had Claude \[word?\] relate briefly the standards \[word?\] of nano, AI and Quasar \[word?\]. I just didn’t know \[partly inaudible\]. They’re the same: \[inaudible\] development, ethics, which is not a surprise, I suppose. In your experience, what is the… I was taking \[word?\] the fact that you went to a Jesuit high school. Men for others. So, hey, my friend, the Jesuits \[word?\] are smart people. What, in your experience over these decades, is making sense to you, from my perspective as a humanist social scientist? What are the engaging questions for you?

For me, and I’m AI-pilled, it always comes down to human beings, which is what it has to do for us. Why am I a scientist? Because of two teachers at Gonzaga. I happened to win the science fair that year, so they let me take their course, and it changed my life. I had a couple of summer research experiences in high school, and they let me keep going through the hard parts.

In the White House, and in what we’re doing with the quantum maker space, it’s those experiences that matter for people: doing things, showing your value, beyond your grades and everything else. Grades don’t keep you going through the hard days. I worry that will get harder and harder as everything gets easier with AI.

Our job is to do two things. One is to keep it hard. You don’t get better unless you do it the hard way, in many respects. The people who will succeed in this world are the curious ones who ask: why does this work? Why is that the answer you’re giving me? I want to understand it. I want to try something different. I want to make a game myself. I want to do it myself. How do we instill that, force that, in kids and people who are growing up? That’s one.

Then we need to figure out our place in this world. It’s hard for me to accept the Elon Musk vision, where we’re all gardening while the AIs do all the hard, good stuff. Screw that, man. That’s not why I’m here. How to be impactful in this world is an existential question for humanity. I think it’s more about humans now than at any other time in our lives. That’s my answer.

---

> [!info] The opening keynote, Quantum–ISSH Symposium, University of Wisconsin–Madison
> November 16, 2026 · Memorial Union · [Watch the video on YouTube](https://www.youtube.com/watch?v=jH9mP4x4xgg)
>
> My words from the room, edited to read. ==Shaded== passages are from the talk track I prepared but didn’t say in the room. Words in \[brackets\] correct a slip I made; the footnote says what I said.
>
> How this was made: the recording was transcribed by Whisper and cleaned by Claude agents. Claude then rewrote my delivery as prose, slide by slide, brought in points from the talk track I had prepared and rehearsed but skipped in the room (shaded), corrected a few things I misspoke (in brackets), and edited it all to read without changing what I said. Nothing was added from anywhere else.

[^c1]: Said in the room: “I got a PhD at Cambridge.”
[^c2]: Said in the room: “ECE department.”
[^c3]: Said in the room: “quantum spins.”
[^c4]: Said in the room: “two years from now.”
[^c5]: Said in the room: “5 to 10 years.”
[^c6]: Said in the room: “the quantum institute.”
[^c7]: Said in the room: “The Senate one does. The House one doesn’t.”
[^c8]: Said in the room: “something like 600 million a year.”
[^c9]: Said in the room: “went to do my PhD.”
[^c10]: Said in the room: “20 years later.”
[^c11]: Said in the room: “Cognitive Loop for In-Situ Optimization.”
[^c12]: Said in the room: “2003.”
[^c13]: Said in the room: “10 to the 15 books.”
[^c14]: Said in the room: “200 qubits gives you 10 to the 60 numbers.”
[^c15]: Said in the room: “those 10 to the 15 books.”
[^c16]: Said in the room: “like 30 of them.”
[^c17]: Said in the room: “a quantum computer.”
[^c18]: Said in the room: “grad school.”
[^c19]: Said in the room: “professors.”

<script>
(() => {
  const id = decodeURIComponent(location.hash.slice(1))
  const el = id ? document.getElementById(id) : null
  if (!el) return
  let moved = false, loaded = false
  for (const e of ['wheel', 'touchstart', 'keydown', 'mousedown']) addEventListener(e, () => { moved = true }, { passive: true })
  addEventListener('load', () => { loaded = true }, { once: true })
  const t0 = Date.now()
  const check = () => {
    if (moved) return
    if (Math.abs(el.getBoundingClientRect().top) > 2) el.scrollIntoView({ behavior: 'instant' })
    if (loaded ? true : Date.now() - t0 > 20000) return
    setTimeout(check, 250)
  }
  check()
  addEventListener('load', () => setTimeout(check, 300), { once: true })
})()
</script>

<script id='keynote-loops'>
(() => {
  const a = document.querySelector('article.keynote-slides')
  if (a ? a.dataset.loops : true) return
  a.dataset.loops = 'on'
  const loops = a.querySelectorAll('video[data-loop]')
  const dress = (v) => { if (v.dataset.poster) { v.poster = v.dataset.poster; delete v.dataset.poster } }
  const play = (v) => { dress(v); const p = v.play(); if (p) p.catch(() => {}) }
  if (!('IntersectionObserver' in window)) return loops.forEach(play)
  const ahead = new IntersectionObserver((seen) => {
    for (const e of seen) if (e.isIntersecting) { dress(e.target); ahead.unobserve(e.target) }
  }, { rootMargin: '200% 0px' })
  const io = new IntersectionObserver((seen) => {
    for (const e of seen) e.isIntersecting ? play(e.target) : e.target.pause()
  }, { rootMargin: '50% 0px' })
  loops.forEach((v) => { ahead.observe(v); io.observe(v) })
})()
</script>

<img alt="" aria-hidden="true" style="display:none" srcset="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///ywAAAAAAQABAAACAUwAOw==" onload="const a = this.closest('article'); if (a ? a.dataset.loops : true) return; const s = document.createElement('script'); s.textContent = document.getElementById('keynote-loops').textContent; a.append(s)">

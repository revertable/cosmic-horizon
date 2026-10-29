---
description: >-
  A personal reflection on traditional and AI-assisted development, the choices
  shaped by experience, and the shifting boundaries of developer competence.
---

# Try It.

> “I've played this game before.”
>
> — Seong Gi-hun, _Squid Game_

## The Horizon I Knew

For nearly ten years, I developed software primarily with Java and Spring.

I read code, wrote code, traced failures, fixed bugs, and deployed systems. Sometimes the server refused to start. Sometimes a feature that worked yesterday broke after an unrelated change. Sometimes an integration test revealed a remarkable number of things we had confidently declared finished.

We investigated, corrected the problems, and tried again.

That was software development as I knew it.

Over those years, I developed a firm belief about what it meant to be a competent developer.

If you built a system, you should understand how it works. You should be able to explain its structure, read its code, and modify it yourself.

I believed this so strongly that I would have questioned anyone who claimed to have developed software without those abilities.

I can still hear the question I might have asked.

> “How can you call yourself a developer if you don't even understand the system you built?”

It sounded perfectly reasonable.

For a long time, I never thought to question it.

## Shifting Horizon

I used to have a fairly narrow understanding of my professional territory.

Java. JSP. JavaScript. Spring. Enterprise systems. Public-sector projects built with South Korea's e-Government Standard Framework (eGovFrame). Systems integration projects.

Those were familiar.

Perhaps React, if I wanted to venture a little further.

Beyond that were job postings filled with unfamiliar technologies and terminology. Rust, Kotlin, RAG, LLMs, and countless other names seemed to belong to different kinds of developers.

I would read those postings and quietly close the tab.

Then I began developing software with AI.

I built a desktop application using Kotlin and Swing. Later, I built another using Rust, Svelte, and Tauri. I also developed Synethos, a RAG-based service that answers questions about my career and development work using approved records.

My knowledge of those technologies varies considerably.

If you put me in front of an empty Rust project and asked me to write Hello World without looking anything up, I might need to check the syntax first.

Yet I have developed, improved, tested, and released a Rust-based application.

At first, even I found that contradiction amusing.

But something else was happening.

The technologies I once considered outside my reach were becoming practical options.

When I encountered a job posting mentioning RAG or LLMs, I began having a different thought.

_Wait. I could probably do that._

My professional world had grown.

I carried nearly ten years of experience into that wider world.

## Rust? Trust.

When I work with AI, I bring my existing experience into the conversation.

I know how requirements become systems. I have seen what happens when a seemingly minor condition is overlooked. I have spent enough time maintaining software to recognize that a quick implementation can become a long-term problem.

Those experiences influence the questions I ask.

I discuss problems and possible approaches with ChatGPT. Sometimes I arrive with a clear decision. Sometimes ChatGPT offers an alternative I had not considered. We examine the options, and I choose a direction.

Codex then handles much of the implementation and technical verification.

I examine the results, operate the application, investigate problems, and decide what happens next.

AI contributes ideas, implementation details, and sometimes designs I would never have arrived at independently. I openly acknowledge those contributions.

The decisions I make are informed by years of development experience, even when the code is written in a language I can barely use fluently.

Sometimes an AI explanation immediately connects to something I already know.

Sometimes I ask for clarification.

Sometimes I find myself saying, _Wouldn't this other approach make more sense?_

The same tool can explain the same technology to two people, yet their conversations may go in very different directions.

Experience changes what we recognize, what we question, and what we decide to do with an answer.

And every new project adds to that experience.

Eventually, I realized something.

> “I didn't know Rust. I knew how to develop software.”

That distinction opened doors I had kept locked from the inside for years.

## Two Voices

Not long ago, I needed to explain how a particular technology had been integrated into a project I had developed.

I knew why we had considered it.

I remembered discussing the approach.

But I could not immediately explain the details of the current implementation.

So I opened my development records.

With AI, I traced the earlier discussions, examined the relevant code, and followed the changes that had been made since the original decision.

The answer emerged.

I understood where the technology was used, how it had been integrated, and how the implementation had evolved.

The question was resolved.

Yet something continued to bother me.

_How could I have built something without already knowing that?_

It was an old, familiar voice.

The voice of the developer I used to be.

Then another thought appeared.

I had encountered a question, located the relevant information, examined the evidence, and established an answer.

Wasn't that also an exercise of development competence?

I remembered how often I had done essentially the same thing before AI.

Opening code I'd written months earlier and staring at it like a stranger.

Searching old documents.

Tracing a call through several layers.

Wondering what past-me was thinking.

Sometimes asking a colleague who remembered the original problem.

Now AI was helping me do those things.

The experience left me with a question I still haven't completely resolved.

> “Must a developer already know the answer, or must a developer be able to find and establish the answer when it matters?”

I suspect the answer depends on the situation.

During a critical incident, the time required to recover understanding can become a serious risk. Some decisions demand deep knowledge before implementation begins.

Those conditions affect how I prepare, document, verify, and operate a system.

They also make me question the expectation that one person should carry an entire system in their head.

## Whose Code Do You Trust?

There is a question that often appears when people discuss AI-assisted development.

> “How can you trust code written by AI?”

That question makes me want to ask it again with a different author.

How can you trust code written by yourself?

How can you trust code written by a colleague?

How can you trust an open-source library?

We have worked with all of these for decades.

We have also spent decades discovering their bugs.

I remember software that failed immediately after deployment.

Features marked complete that failed during integration testing.

Changes that fixed one problem while introducing another.

I have even encountered supposedly completed screens that turned out to be little more than an image placed inside an HTML page.

And sometimes the developer responsible had already left.

Who was responsible then?

The developer? The reviewer? The person who accepted the work? The team that inherited it?

Those fractures existed long before AI typed its first line of code.

Today, I use regression tests to protect existing behavior. I ask AI to implement changes and run tests. Then I operate the application myself, examine its behavior, and investigate anything that looks wrong.

Sometimes the implementation is incorrect.

Sometimes an existing feature breaks.

Sometimes I discover that I forgot to specify an important condition.

When that happens, I investigate.

If AI made an implementation mistake, I request a correction.

If my own instructions caused the problem, I learn from it and adjust the next request.

Then I verify the result and continue.

A passing test is evidence within the scope of that test. I also need to know whether it actually ran and whether it covers the behavior that matters.

The appropriate controls depend on what the software does, what failure would cost, and how readily the system can recover.

These are engineering decisions I have faced throughout my career.

Now consider another familiar question.

> “AI implemented the feature and reported that the tests passed. What will you do if a bug appears later?”

I would investigate it.

Determine its impact.

Find the cause.

Fix it.

Verify the correction.

And continue developing.

What would I have done differently ten years ago?

I have written code with my own hands. I have reviewed it, tested it, and confidently deployed it.

Some of it still broke.

That experience leaves me with a question of my own.

> **“You ask how I can trust code written by AI. But can you trust the code you wrote with your own hands?”**

I certainly cannot guarantee mine.

The name of the author has never been a substitute for evidence that software works.

A patch is released. A new version follows. Requirements change. Designs evolve.

The work continues.

That, too, is software development.

## The People Who Evaluate Us

Another change is happening alongside AI-assisted development.

AI is increasingly used to analyze résumés, summarize candidates, generate interview questions, and assist hiring decisions.

I understand why.

I have built an AI-powered portfolio myself. Synethos exists so visitors can ask questions about my experience and examine the records behind the answers.

I believe these tools can be useful.

But I sometimes imagine a peculiar interview.

An interviewer uses AI to analyze a candidate's résumé.

AI produces questions, perhaps even suggested answers.

The interviewer reads one aloud.

> “How can you trust code written by AI?”

And I find myself wondering.

How did the interviewer decide that the question was appropriate?

Did they examine the reasoning behind the suggested answer?

Could they recognize a mistake in it?

What would they do if the AI had misunderstood the candidate's work?

These are the very questions they are asking me about software.

> **“If you use AI to evaluate my work, shouldn't the same questions about understanding, evidence, and responsibility apply to your evaluation?”**

I welcome questions about what I built, what I decided, what I delegated, what I verified, and what happened when something failed.

My development records make many of those questions answerable.

They preserve the instructions, changes, investigations, tests, and revisions behind the result.

I would rather discuss those records than pretend that I personally typed every line.

An employer may need someone who can write and maintain Rust directly, without AI assistance. That is a legitimate requirement for a particular job.

But I wonder how much of our broader definition of developer competence comes from such practical requirements, and how much comes from the methods we have grown accustomed to.

Those are different questions.

And the distinction matters to someone trying to work in a changing industry.

## The Game I Have Already Played

I know what a conventional answer in a technical interview sounds like.

I could say that I use AI merely to improve productivity, while personally reading, understanding, and reviewing every line of generated code.

I know how to work that way.

I spent years doing it.

I could revert to it tomorrow if the job demanded it.

But that is not the way I generally choose to develop today.

I have experienced both approaches.

And after comparing them through actual work, I have chosen to let AI handle more of the implementation while I concentrate on identifying problems, making decisions, directing the work, examining outcomes, and improving the process.

I believe this approach serves me better.

I have working software and development records that explain why.

That choice has consequences.

I still need to earn a living. I still need to participate in a hiring market whose expectations may differ from mine. I know that presenting myself this way can make some opportunities harder to obtain.

I could give the familiar answers.

I know the rules.

> **“I have played this game before.”**

But I have also played another way.

I want to describe my work as it actually is.

I cannot decide, on my own, what society should recognize as a developer.

That definition will evolve through the work people do, the capabilities employers need, and the standards we collectively adopt.

I can contribute my experience to that discussion.

And I can keep building.

## Try It.

There is still a voice in my head that asks:

_How can a developer fail to know the structure of a system they built?_

It is my own voice.

I listened to it for years, and much of what it taught me remains useful.

Today, I ask it another question.

_What exactly are we trying to measure?_

The ability to recall syntax?

The ability to explain a particular implementation without preparation?

The ability to identify a problem, make a sound decision, construct a working solution, and recover when something goes wrong?

All of these can matter.

Their importance depends on the work.

What I question is the habit of treating one familiar method as the definition of the profession.

I have tried working with AI as a genuine development partner.

It has expanded the problems I can approach and changed how I use the experience I already have.

It has also made me reconsider some beliefs I once held with absolute confidence.

I am still learning where this approach works best, where it fails, and what responsibilities it places on me.

The software keeps evolving.

So do I.

And if this way of developing seems strange, perhaps the most useful next step is an experiment.

Choose a problem.

Try building something outside your familiar stack.

Work with AI. Make the decisions. Examine the results. Investigate the failures. See what your existing experience allows you to do.

Then decide what you think.

**I have played both ways.**

**Have you?**

**Try it.**

## Related Coordinates

> None yet.

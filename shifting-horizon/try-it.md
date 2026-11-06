---
description: >-
  A personal reflection on traditional and AI-assisted development, the choices
  shaped by experience, and the shifting boundaries of developer competence.
---

# Try It

> “I've played this game before.”
>
> — Seong Gi-hun, _Squid Game_

## The Horizon I Knew

For nearly ten years, I developed software primarily with Java and Spring.

I read code, wrote code, traced failures, fixed bugs, and deployed systems. Sometimes the server refused to start. Sometimes a feature that worked yesterday broke after an unrelated change. Sometimes integration tests revealed a remarkable number of problems in things we had confidently declared finished.

We investigated, fixed the problems, and tried again.

That was software development as I knew it.

Over those years, I developed a firm belief about what it meant to be a competent developer.

If you built a system, you should understand how it works. You should be able to explain its structure, read its code, and modify it yourself.

I believed this so strongly that I would have questioned anyone who claimed to have developed software without those abilities.

I can still hear the question I would have asked back then:

> “How can you call yourself a developer if you don't even understand the system you built?”

It sounded perfectly reasonable.

For a long time, I never thought to question that standard.

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

At first, that gap felt unfamiliar.

I was not comfortable with the language's syntax, yet I was participating in the development of software built with it, examining the results, and deciding what to do next.

Along the way, my attitude toward unfamiliar technologies began to change.

Previously, when I saw RAG or LLMs mentioned in a job posting, I thought of them as areas I had never worked in.

But after developing a service using those technologies, I no longer judged what might be possible based on their names alone.

Having used a technology does not necessarily mean understanding it deeply or being qualified for a role that requires it.

Still, unfamiliarity alone was no longer a reason to rule it out from the beginning.

The range of technologies and problems I believed I could approach was gradually widening.

And I carried nearly ten years of experience into that wider world.

## Rust? Trust.

When I work with AI, I bring my existing experience into the conversation.

I know how requirements become systems. I have seen what happens when a seemingly minor condition is overlooked. I have spent enough time maintaining software to recognize that a quick implementation can become a long-term burden.

Those experiences influence the questions I ask.

I discuss problems and possible approaches with ChatGPT. Sometimes I arrive with a clear decision. Sometimes ChatGPT offers an alternative I had not considered. We examine the options, and I choose a direction.

Codex then handles much of the implementation and technical verification.

I examine the results, use the application, investigate problems, and decide what happens next.

AI contributes ideas, implementation details, and sometimes designs I might never have arrived at independently. I openly acknowledge those contributions.

The decisions I make are informed by years of development experience, even when the code is written in a language I cannot use fluently.

Sometimes an AI explanation immediately connects to something I already know.

Sometimes I ask for clarification.

Sometimes I find myself thinking, _Wouldn't this other approach make more sense?_

Even when people use the same tool and receive the same explanation, their experience may lead them to notice different details and ask different follow-up questions.

In my case, previous development experience influenced what I asked, which risks I looked for, and how I verified the results.

And every new project adds to that experience.

Over time, I began to distinguish between knowledge of a particular technology and the abilities involved in developing software.

> “Rust was unfamiliar to me. But the process of developing software was not.”

Recognizing that distinction led me to reconsider technologies I had previously ruled out.

## Two Voices

Not long ago, I needed to explain how a particular technology had been integrated into a project I had developed.

I knew why we had considered it.

I remembered discussing the approach.

But I could not immediately explain the details of the current implementation.

So I opened my development records.

With AI, I traced the earlier discussions, examined the relevant code, and followed the changes that had been made since the original decision.

The answer emerged.

I understood where the technology was used, how it had been integrated, and how the implementation had evolved.

Now I could answer the question.

Yet something continued to bother me.

_How could I claim to have built it if I didn't even know that?_

It was an old, familiar voice.

The voice of the developer I used to be.

Then another thought appeared.

I had faced a question, located the relevant information, examined the evidence, and verified the answer.

Could the problem analysis and verification involved in that process also be considered part of development competence?

I remembered how often I had done similar things before AI.

Opening code I'd written months earlier and staring at it like a stranger.

Searching old documents.

Tracing a call through several layers.

Wondering what past-me had been thinking.

Sometimes asking a colleague who remembered the original problem.

Now AI was helping me do those things.

That does not mean there is never a problem with failing to understand the current implementation.

The experience left me with a question I still haven't completely resolved.

> “Must a developer already know the answer, or must a developer be able to find and verify the answer when it matters?”

I suspect the answer depends on the situation.

During a critical incident, the time required to recover an understanding of the system can become a serious risk. Some decisions demand deep knowledge before implementation begins.

Those conditions affect how I prepare, document, verify, and operate a system.

They also make me question the expectation that one person should always carry an entire system in their head.

What must be understood in advance? What must be documented? And what can be looked up and verified when needed?

I now see those distinctions as another set of decisions to make during software development.

## Whose Code Do You Trust?

There is a question that often comes up when people discuss AI-assisted development.

> “How can you trust code written by AI?”

It is an important question.

But it also applies to code written by people.

Code I wrote myself.

Code written by a colleague.

An open-source library brought into a project.

We have worked with all of these for a long time, and we have discovered countless problems in them.

I have also found unexpected bugs in my own code, even after reviewing and testing it.

When I think about those experiences, the question changes slightly.

> **“Alongside asking who wrote the code, shouldn't we also ask what evidence we have for trusting the result?”**

I remember software that failed immediately after deployment.

Features marked complete that failed during integration testing.

Changes that fixed one problem while introducing another.

I have even encountered supposedly completed screens that turned out to be little more than an image placed inside an HTML page.

By then, the developer responsible had already left the project.

Who was responsible?

The developer? The reviewer? The person who accepted the work? The team that inherited it?

Questions about authorship, verification, and responsibility existed long before AI entered software development.

Today, I use regression tests to protect existing behavior. I ask AI to implement changes and run tests. Then I use the application myself, examine its behavior, and investigate anything that looks wrong.

Sometimes the implementation is incorrect.

Sometimes an existing feature breaks.

Sometimes I discover that I forgot to specify an important condition.

When that happens, I investigate.

If AI made an implementation mistake, I request a correction.

If my own instructions caused the problem, I learn from it and adjust the next request.

Then I verify the result and continue.

Of course, an AI report that the tests passed is not sufficient reason to trust the result.

A passing test is evidence within the scope of that test. I also need to know whether it actually ran and whether it covers the behavior that matters.

Sometimes I need to read the code myself. Other situations call for additional tests or an independent review.

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

At least I cannot guarantee that my own code is flawless.

AI-written code may also have different failure modes and verification challenges from human-written code. Those differences deserve attention as well.

But authorship alone cannot determine whether code is trustworthy.

I need to verify how it behaves, understand the scope and limitations of that verification, and be able to respond when something goes wrong.

A patch is released. A new version follows. Requirements change. Designs evolve.

The work continues.

That, too, is software development.

## The People Who Evaluate Us

Another change is happening alongside AI-assisted development.

AI is being used to analyze résumés, summarize candidates, generate interview questions, and assist hiring decisions.

I understand why.

I have built an AI-powered portfolio myself. Synethos allows visitors to ask questions about my experience and examine the records supporting its answers.

I believe these tools can be useful.

But I sometimes imagine a peculiar interview.

An interviewer uses AI to analyze a candidate's résumé.

AI produces questions, perhaps even suggested answers.

The interviewer reads one of the questions aloud.

> “How can you trust code written by AI?”

And I find myself wondering.

How did the interviewer decide that the question was appropriate?

Did they examine the reasoning behind the suggested answer?

Could they recognize a mistake in it?

What would they do if AI had misunderstood the candidate's work?

These are similar to the questions we ask when verifying software written by AI.

> **“If AI is used to evaluate development work, shouldn't the evidence and reasoning behind that evaluation also be examined?”**

I do not think using AI to prepare interview questions is inherently a problem.

What matters is how the suggested material is understood, reviewed, and used to make actual decisions.

It resembles the challenges I face when developing software with AI.

I welcome questions about what I built, what I decided, what I delegated, what I verified, and what happened when something failed.

My development records contain answers to many of those questions.

They preserve the instructions, changes, investigations, tests, and revisions behind the result.

Rather than focusing on whether I personally typed every line, I would like to discuss the decisions I actually made and how I verified their outcomes, with those records as evidence.

Of course, an employer may need someone who can write and maintain Rust directly, without AI assistance. That is a legitimate requirement for a particular job.

I cannot claim that my experience developing a Rust application with AI is, by itself, enough to meet that requirement.

But whether every standard for evaluating developer competence must be tied to one particular way of working is a separate question.

It is worth distinguishing which capabilities a particular role truly requires from which standards may have emerged from established ways of working.

Those are different questions.

And the distinction matters to someone trying to work in a changing industry.

## The Game I Have Already Played

I know what kind of answer is likely to be familiar in a technical interview.

I could say that I use AI only as a productivity aid, while personally reading, understanding, and reviewing every line of generated code.

Directly controlling and reviewing implementation details is familiar to me.

I spent years developing software that way.

If a role requires it, there may be times when I need to work that way again.

But that is not the way I generally choose to develop today.

I have used both traditional development and AI-assisted development in real projects.

Based on those experiences, I now choose to delegate more of the implementation to AI.

I concentrate on identifying problems, making decisions, directing the work, examining results, and improving the process.

In the work I have done so far, I have found this approach well suited to applying the experience I have accumulated and working with unfamiliar technologies.

I also have working software and development records that help explain that choice.

That does not mean I believe the same approach will suit every project or every developer.

I am still examining the conditions under which it works well, and the situations that require deeper understanding and more direct involvement from me.

That choice has consequences.

I still need to earn a living. I still need to participate in a hiring market whose expectations may differ from mine. I know that presenting myself this way can make some opportunities harder to obtain.

I could give the familiar answers.

I know the rules.

> **“I've played this game before.”**

But I have also tried another way.

I now want to describe how I actually work.

I cannot decide, on my own, whom society should recognize as a developer.

That definition will evolve through the work people do, the capabilities employers need, and the standards we collectively adopt.

I can contribute my experience to that discussion.

And I can keep building.

## Try It.

There is still a voice in my head that asks:

_How can someone be a developer if they don't even know the structure of a system they built?_

It is my own voice.

I listened to it for years, and much of what it taught me remains useful.

Today, I ask it another question.

_What exactly are we trying to measure?_

The ability to recall syntax?

The ability to explain a particular implementation without preparation?

The ability to identify a problem, make a sound decision, build a working solution, and recover when something goes wrong?

All of these can matter.

Their importance depends on the work.

What I question is the habit of treating one familiar method as the definition of an entire profession.

I have tried working with AI as a genuine development partner.

That experience has expanded the range of problems I believe I can approach and changed how I use the experience I already have.

It has also made me reconsider beliefs I once held with absolute confidence.

I am still learning where this approach works best, where it fails, and what responsibilities it places on me.

Software keeps evolving.

So do I.

If this way of developing seems unfamiliar, trying a small experiment might be worthwhile.

You could try building something outside your familiar technology stack.

You could discuss possible approaches with AI, examine the implementation, and investigate what goes wrong.

Along the way, you might discover how your existing experience helps and where you need to develop a deeper understanding.

That experience does not have to lead you to the same conclusion I reached.

Some differences only become apparent through firsthand experience. So do some limitations.

**I've tried both ways.**

And now I choose how I work based on what those experiences have taught me.

**Try it.**

## Related Coordinates

> None yet.

***

> **Coordinate Provenance**\
> This coordinate is part of _Cosmic Horizon_, an engineering archive by Riu Salze. If you cite, quote, summarize, adapt, or reference its original naming, metaphors, terminology, structure, boundary models, documented patterns, or blueprints, please provide visible attribution. See [How to cite](../).

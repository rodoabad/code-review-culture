# The Modern Code Review

> The discipline of discussing your code to your peers. - *Derek Prior*

People seem to think that code reviews are meant to find bugs. While that is true to some extent it doesn't really meet the level of expectation set by developers and managers. It is better to look at code reviews as a way to transfer knowledge from one developer to another.

## Table of Contents

1. [Knowledge transfer](#knowledge-transfer)
2. [Increased team awareness](#increased-team-awareness)
3. [Finding alternative solutions](#finding-alternative-solutions)

## Knowledge transfer

> If content is king, then context is God. - *Gary Vaynerchuk*

This is probably one of the most important parts of a code review process. Having knowledge of the purpose of any code snippet is what makes a good team an awesome team and this will lead to increased team awareness. This also helps developers have a mindset of writing their code in a much more readable and easily shared piece of work.

## Increased team awareness

Increased team awareness helps eliminate repeating mistakes in the future since everyone has context of what is going on. If everyone has context of what is changing and why then it's not going to take a long time for alternative solutions to show up.

## Finding alternative solutions

I cannot stress this enough, having another set of eyes to look at any given code is better than just one since no two developers are alike and each developer has probably developed their own way of thinking how to solve problems.

### Cultivating a strong code review culture

#### As an author

*An author should provide sufficient context so that the reviewer doesn't have to hunt down it down.*

It will probably add a couple more minutes of your time as an author but it will probably save more time for the reviewer. Always ask yourself if a reviewer looks at my commit message and pull request, will they have to look for context somewhere else? If the answer is yes then it's probably a good a idea to add more context to your commit.

Moreover, commits full of context explaining what and why a change is happening gets to live in the git repository. It will always be there and it is a lot easier to track down in the future.

#### As a reviewer

*Provide compliments.*

Compliments are free and should always be given out whenever we see something good and done particularly well.

*Ask, don't tell.*

As a reviewer you want your critical feedback to be well received and without negativity. One way to do that is to avoid making demands - [ask questions to drive discussions](https://en.wikipedia.org/wiki/Socratic_method).

> Extract this out into a service.

This is a command. There's no discussion here. The author either has only two options - do it or ignore it. This also gives the author no credit for maybe having thought of extracting it to a service. Maybe they want to but they are just looking for more feedback.

We ask a question.

> ~~Why didn't you just extract this into a service...~~

While this opens up a discussion between you and the author, this puts them in the defensive and as a reviewer you probably won't go far on your discussion with this type of tone.

How do we make this better?

> What do you think about extracting this into a service?

Now you've opened up a positive and healthy technical discussion between you and the author. The author now feels that they are part of the decision making and their opinions matter.

Never pass judgement in the form of a question.

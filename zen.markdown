# Avvo Dev Zen

These are things that we, as Avvo developers, fundamentally value. Use these to make good decisions without having to run them by others. Use them to prioritize the work you have. Follow these principles, and you’ll be supported in tough decisions by the rest of the team.

## Invest in yourself and your tools

Projects are temporary. But your skills, and the tools you use to turn those skills into projects, will be with you forever. Time spent improving your skills and productivity is time well-spent. And if you have a choice, focus your work on the meta-task -- the thing you could be working on that makes future work easier.

## Defend the user

People use our software -- without them, the code we write wouldn’t matter. So start with them. Think about how you could make their day better. Invest in user research and usability. Push back against product requirements and design that hurt the people we’re trying to help. Prioritize fixing bugs and exceptions -- they’re affecting real people in real situations. As developers, we can write code that automates annoying tasks, predicts behavior, and solves problems. Use those skills to save the user time and mental energy.

## Your teammate’s problems are your problems

We’re all on the same team, working for the same goals. We’re a *better* team when we help teach each other, unblock each other, build tools that speed up our development, fix bugs before our teammates run into them, build APIs that your teammates are happy to use, write easier-to-maintain code, and fix the tests that are preventing other people from shipping (even when it’s not your fault). If you can invest a little bit of your time to save even more time for the team as a whole, that’s an easy decision.

## Attack the noise

Noisy alerting, exceptions that happen all the time, random test failures, non-actionable automated emails -- these are all worse than useless. Not only are they distracting, they hide actual issues. Don’t accept this spam as normal. Fix it, or kill it.

## Take ownership

Sure, that bug isn’t your fault. You had nothing to do with that site downtime. But in the end, your part in the problem doesn’t matter -- what matters is it gets fixed. And the best thing you can do is to figure out how you can help. When there’s a problem, don’t shift the blame, take it. Help fix it. Even if you don’t think it’s yours.

## Leave code better than you found it

Our code isn’t perfect. Even perfect code written today will be imperfect a few years from now. The only thing that will save our codebase from becoming an unmaintainable mess is small, constant, improvement. So don’t take that shortcut. If something seems wrong to you, take a step toward cleaning it. Something as small as extracting a few lines of code to a more clearly-named method is totally worth doing. Even if you’re short on time, there’s some small change you can make to delight the next person to hit this code. (Especially because it’s likely to be you.)

## Favor convention over reinvention

We’ve solved a ton of problems already. Take advantage of those solutions, take advantage of the solutions and patterns other smart people have come up with, and follow the patterns we have already. It’ll save you time, and a whole lot of frustration re-solving the same problem we ran into years ago.

## Explicit is better than implicit

In both your code, and your communication. The reader of your code shouldn’t need to know all the edge cases, the entirety of your system, and whatever was in the PdM’s head two years ago in order to understand what it does. Favor code that’s clear enough that you don’t need extra materials to understand it. And when you’re talking with other devs, design, PdM, etc., be clear about what you need from them, and be clear about what they should expect from you. It’s better to have a tough conversation earlier than broken expectations later.

## Understand why

Does your code not work? Is a library acting in an unexpected way? Were you handed a feature that seems like it’s not worth spending time on? Dig deeper. Understand how things work, why they’re built that way, and why decisions are made. On the Avvo dev team, curiosity is a virtue. We build on open source, we value transparency, we ask tough questions fairly. So make the effort to understand.

## Prove it

Prove that the feature works: Write tests, keep them passing, and step through your feature manually to double-check. Verify your deploy -- check for exceptions, check the logs, check your emails, pretend you’re a user and try it out. Prove that the feature is valuable: set your expectations, look for places to add measurements and metrics, and check up on them. You’re not your user, so the only way you’ll know your feature is valuable is seeing how it’s being used. Do you have a good idea that’s not measurable? Favor the measurable one -- otherwise, how will you know your idea is actually good?

## Keep moving forward

Is something still in design? Do you not have all the information you need to complete the project? It’s probably frustrating. But there’s some step you can take today! So take it, and keep the project moving. Favor taking good actions quickly to perfect actions slowly. Favor consultation over consensus. Unshipped code has no value, so you should take the next step toward shipping. Don’t fear rework -- you’ll never have perfect information, so rework is a given. Instead, take the smallest step you can, evaluate, and iterate.

## Deliver business value

In product development, what matters is the value to Avvo we deliver. Can you deliver value without shipping code? Do it! Can you deliver value faster by focusing on smaller, earlier, more frequent releases? Do it! Are you trying to make correct trade-offs? Think about what will, long-term, deliver more business value. That will lead you down the right path.
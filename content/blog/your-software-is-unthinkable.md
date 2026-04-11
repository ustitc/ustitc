---
title: "Your software is unthinkable"
date: 2026-04-11
draft: false
---

I think about systems I build, but they **withdraw** from me. I am deep into inputs/outputs, business rules and
terminology, but at the same time concepts are forgotten, requirements change, bugs crawl from the darkest corners, and
parts of the codebase are never explored.

The system is never fully visible. There is always **uncertainty** no matter how much you try. That is not because we
lack knowledge, it is because the **full picture doesn't exist**.

Systems show themselves as **manifestations**: code, logs, app metrics, resource utilisation, bug reports, user reviews.

The natural response to the daunting feeling of uncertainty is to capture as many manifestations as possible. Use strong
typing to make a system more predictable. Use thorough monitoring and logging to understand how a system behaves.
Perform post-mortems and battle testing to prevent undesired behavior. Write "simple", "small", "do-exactly-one-thing"
programs that will fit in our heads.

The scale doesn't matter, it can be distributed services or a short script that runs on your VPS. The software still
escapes you. It is a matter of how much things are being lost from your attention.

If you know your code by heart, can you predict all possible outcomes of the system? If you know the outcomes, can you
predict all the inputs, even the unpredictable ones like byte flips? If you know all the inputs and are prepared for the
unexpected, do you know how your hardware works and when it will stop? Even if you knew all of this, do you know how
users will use it tomorrow? Do you know how **you** will use it in a year?

Uncertainty is not a problem to be solved. It can't be solved. Should we shift our focus from making systems predictable
to learning how to **live with** systems that aren’t?

Let's say that our system is a tree. We can constrain and **design** it to a certain shape. Or we can **observe** how
the tree grows and its branches emerge. And what doesn't fit - cut.
Let systems grow in the dark, but make it easy to observe and adapt. In other words, make us better gardeners.

How would we change our software development rituals if we embrace the fact that what we build is unthinkable?
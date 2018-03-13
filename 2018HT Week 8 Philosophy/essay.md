---
title: Are any of our inductive beliefs justified?
date: "HT 2018 Week 8"
author: "Zhenghong Lieu"
---
In this essay, I argue that inductive beliefs cannot be justified completely.
They must all rely on a fundamental axiom of "future-past relatedness". If we
accept this axiom, then I believe that inductive beliefs can be justified.

**Induction v. deduction**

Inductive beliefs are beliefs that are justified inductively; that is, by
repeated observation and subsequent prediction. This is opposed to deductive
beliefs, which are beliefs justified by following specific laws of deduction
from premises to conclusion.

Let me give an example.

1. If it is a weekday, my scout will come to my room in the morning.
2. Tomorrow is Thursday.
3. Thursday is a weekday.

$\therefore$ My scout will come to my room tomorrow morning.

This is an argument that contains both deductive and inductive beliefs. The
first premise is an inductive belief: I believe my scout will come to my room
in the morning because the schedule says so and she does indeed come to my room
every weekday morning. Premises 2 and 3 are *a priori* truths as they are
merely definitions. However, the conclusion is both deductive and inductive as
it depends on deductive reasoning (reasoning from rules about premises and
conclusion) from an inductive belief.

**Hume's argument against induction**

Hume's objection to induction is as follows. Suppose you notice that the sun
rises every day that you have started observing; at time $t_0$ to time $t_n$,
the sun has always risen. You then form the belief that at time $t_{n+1}$, the
sun will rise.

However, are we justified in holding this belief? The justification for this
belief seems to be something along the lines of "If $x$ happened in situation $y$
previously many times, then $x$ will happen in situation $y$ in a future
occurrence.", which is a belief in induction: but this meta-level belief is
itself justified by induction. Even our scientific theories of laws of motion
and existence seem to fall flat: after all, the fact that the universe has
followed the laws of physics for billions of years before doesn't mean it has
any special reason to do so in the future. The belief that it does itself
relies on the belief that the past predicts the future...which is itself
inductive in nature.

Therefore, it seems that induction can't be justified due to a process of
infinite regress. Each inductive belief (the sun will rise tomorrow because it
has for as long as I can remember) can be justified only by another inductive
belief (the laws of physics hold because they have held for as long as we
observe), and so on.

\begin{center} $\clubsuit$~$\clubsuit$~$\clubsuit$ \end{center}

What does it mean for an inductive belief to be *justified*? Perhaps we can be
satisfied not with absolute and complete justification, but with high probability.

Imagine a swimming pool filled with some number of differently-coloured balls. There
is a tarp covering it so you cannot see how many balls there are.
You sit down by the side of the pool and start sampling ball by ball, with
replacement. After sampling a million balls, you find that all the balls you
have picked are red. How likely is it that all the balls in the swimming pool are red?

For now, let's assume that every ball in the swimming pool has an equal chance
to be picked by you; you sample the balls uniformly and at random. In this
case, while you don't have absolute certainty that all the balls in the
swimming pool are red, you can form some probabilistic belief with confidence
growing with the number of samples.

Here the swimming pool is the entire possibility space of events or objects
over time and space, and when we sample, we make an observation of an event.
This doesn't seem to run afoul of Hume's argument against induction. We make no
assumptions apart from that of uniform random sampling (but this is
problematic: I will explain why later). As we sample, we build a model of the
entire probability space, and by doing enough sampling we can build up a good
knowledge of the probability distribution.

It seems like inductive beliefs can be justified in this way. We make repeated
observations of some phenomenon (sampling balls in the swimming pool), and if
all observations agree, then we have a *probabilistic* justification for an
inductive belief.

\begin{center} $\clubsuit$~$\clubsuit$~$\clubsuit$ \end{center}

**Objection 1**: You don't know how many balls there are in the pool, so how
would you know how many observations is enough for certainty? If there are
three balls in the pool, then you are almost guaranteed to have sampled every
single ball. If there are a billion balls, then there are at least 999 million
balls you haven't sampled, and you may want to make more observations to reach
a reasonable degree of certainty.

*Reply*: I don't find this a strong objection. We can adopt the Bayesian
view: set a prior and update it given additional information.

**Objection 2**: You may not sample the balls uniformly and at
random and therefore your sample has no predictive power. In essence,
regardless of how many observations you sample from time $t_0$ to $t_n$,
everything may completely change at time $t_{n+1}$ unless you assume that what
you have observed has good reason to be similar to what you will observe (that
the past is substantially similar to the future), and this is itself an
inductive belief.

For example, a turkey who sampled the first 1,000 days of
its lifetime would form the inference "If the farmer arrives, he will feed
you"—but it would be in for a rude shock come Thanksgiving. Similarly,
Newtonian physics gives very accurate results at velocities much less than $c$
but breaks down given large velocities. Perhaps all our inductive beliefs are
variants on this: they only hold under a small subset of orderly and
well-behaved conditions.

This was posed by Goodman as the *new problem of induction*: suppose there was
a predicate "grue" that means "green before Jan 19, 2038 and blue after". Then,
having sampled many emeralds from now till Jan 18, 2038, we would conclude that
the statement "All emeralds are grue" is true with some high probability.
However, this hypothesis would cease to hold at Jan 19, 2038. Similarly, when
we say "All objects have mass"—how do we know that objects won't suddenly cease
to have mass tomorrow? How do we know that certain predicates ("green", "has
mass") are *time-invariant* and can be projected into the future, while others
("grue", "stationary") are not?

*Reply*: Let me give two tentative replies to this objection, and show why they
do not hold.

*Failed Reply 1*: This argument proves too much. While it's impossible to
know whether the inductive beliefs we hold will continue to be true in the
future, this is also true for deductive logic. Take this argument:

1. This colour is grue.
2. If this colour is grue, then it is not blue.

$\therefore$ This colour is not blue.

This deductive argument is sound before Jan 19, 2038 but unsound after due to
the time-dependent nature of P2. However, the sceptic may push back saying that
this is not a criticism of deductive logic as the deductive *rules* are still
correct. It is merely the fact that our premise, gotten through an inductive
belief, is wrong.

*Failed Reply 2*: There are particular predicates that seem to be more amenable
to inductive generalisation. For example, if there are 7 men in a car (say,
the first-year PPEists take a road trip), then the predicate "Every person in this car
has a speed of 80 km/h" would seem to be generalisable from one observed
instance, while others like "Every person in this car has a younger sister" would
not. Therefore, it seems like some inductive beliefs can be better justified
than others.

The sceptic would reply that the reason for this is because the former
predicate relies also on a chain of other inductive beliefs like the nature of
a car, the laws of physics and so on; they make the observations highly
dependent on each other. In contrast, the observation "has a younger sister"
are mutually independent: $P(A|B) = P(A)$. However, that chain of inductive
beliefs itself in the first case has to be justified, which the sceptic would reject.

I think this objection by the sceptic holds, and so I would have to concede
this to him. My final reply is as follows:

*Final Reply*: Fundamentally, scepticism about induction boils down to the fact
that the past doesn't necessarily predict the future. Just because all ravens
you see now are black doesn't mean they won't suddenly turn white tomorrow;
just because the turkey is fed and taken care of today doesn't mean it will be
tomorrow, and just because the laws of physics have held for the past
billions of years doesn't mean it will continue to hold tomorrow.

As believers in induction, we will have to agree with this criticism. However,
I don't think this completely vitiates induction: I think it's possible to
justify induction given certain axioms. We need the "future-past relatedness"
axiom that the past does predict the future to some extent: that is, where 
$$\exists x_i (P(x_i|x_0) > P(x_i))$$
That is, there exists at least one particular world state $x_i$ that is more
likely to occur given the fact that the current world state is $x_0$.

Once we have this belief, we can start to justify our inductive beliefs
one by one. If a belief predicts world states $\{x_1, x_2, x_3\}$ that are more
likely to occur than $\{x_i, x_j, x_k ... \}$, then this belief can be
justified on a probabilistic basis.


\begin{center} $\clubsuit$~$\clubsuit$~$\clubsuit$ \end{center}

In this essay, I have shown that there are no inductive beliefs that can be
completely justified. However, if we accept that i) inductive beliefs can be
justified probabilistically and with some degree of confidence rather than
absolute certainty and ii) that we take on faith that some future world states are
more likely to happen given a present world state, I believe that inductive
beliefs can be somewhat justified.

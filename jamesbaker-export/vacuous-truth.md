---
title: 🕳️ Vacuous Truth
slug: vacuous-truth
published_date: 2026-01-29T19:27:00+00:00
tags: words
publish: true
make_discoverable: true
is_page: false
meta_description: Why I’ve won every marathon I’ve ever run.
meta_image: https://bear-images.sfo2.cdn.digitaloceanspaces.com/jamesbaker/og-image-vacuous-truth.webp
---

> <q>I’ve won every marathon I’ve taken part in.</q>\
> _– Me (January 2026)_

I’m not lying. This statement is completely true… The only issue is that I’ve never run a marathon in my life.

This is an example of a **vacuous truth**.

**Vacuous truths** are true due to a quirk of logic. In this example, my statement makes an assertion about _all_ elements of an _empty_ set. I’ve never run a marathon, so anything I say about _all_ the marathons I’ve run is _true_. 

Let’s look a little closer. My statement is made up of three elements:
1. **A Set:** Marathons I’ve run
2. **An Assertion:** I won
3. **A Combiner:** _All_

Because the **set** is empty, there’s nothing to run the **assertion** on, so we use the **combiner’s** default value. For _All_, the default is true. This is due to _All_ using _and_ ($\land$) to combine the results of each assertion, and $\text{true}$ is the **identity element** for _and_:
$$
x \land \text{true} = x
$$

<div class="card">

An **identity element** for an operation is a value that is effectively ignored when applied. For _plus_ ($+$), the identity element is $0$: 
$$
x + 0 = x
$$

</div>

The other possible combiner is _Any_, which has a default of false. If my statement were <q>I’ve won _a_ marathon.</q> then it would be false. In this case, we use _Any_ instead of _All_. _Any_ combines its results using _or_ ($\lor$), whose identity element is $\text{false}$:
$$
x \lor \text{false} = x
$$

Here are some other vacuous truths:
- <q>If the moon is made of cheese, then I’m the cow that jumped over it.</q>
- <q>All my unicorns are dogs and all my unicorns are cats.</q>
- <q>Every time a man has been to Mars, I’ve won the lottery.</q>

Have fun winding up your friends and family with your own outrageous vacuous truths.
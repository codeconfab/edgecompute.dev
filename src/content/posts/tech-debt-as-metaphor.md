---
title: 'Tech Debt as Metaphor'
published: 2019-03-18
description: 'Some thoughts on the use and abuse of the Tech Debt metaphor.'
series: 'Taming Tech Debt'
tags: ['tech debt']
---

:::note
This post was originally published as a thread on Twitter. It has been lightly edited to fix typos and spelling but otherwise left as is.
:::

Gonna do a thread with some thoughts on "technical debt", why I stopped using this metaphor with my clients and the teams I work with, and what I use instead. I've come to believe misuse of the debt metaphor has led to immense hidden costs and harm to software projects.

First, a bit of history about the origin of the metaphor. In 1992 Ward Cunningham wrote an 'experience report' where he describes the idea of technical debt while working on a financial services application: https://c2.com/doc/oopsla92.html

The relevant line from the report: "Shipping first time code is like going into debt. A little debt speeds development so long as it is paid back promptly with a rewrite." This matches pretty well with the first cause listed on wikipedia.

Unfortunately, the list goes on for a dozen more items, none of which have much to do with the original definition. This suggests that the metaphor is bearing far too much weight and may not be conveying the message it's meant to.

To understand how this happened, we can take a closer look at the context and process that lead to the metaphor. In order to communicate some risk, Cunningham needed to bridge a gap in understanding about software engineering practices with a stakeholder.

To bridge this gap he reached for a metaphor within the domain of the project, a domain in which the stakeholder was presumably already a subject matter expert in. The debt/interest metaphor was meant to illustrate that a course of action would result in a business liability.

The stakeholder would be in a good position to use that metaphor to ask relatively sophisticated questions about the impact different design decisions might have on that liability. This shared domain context is what gave the metaphor power.

When the community picked up technical debt as a general purpose metaphor that context was lost. It was used to describe almost any case where compromises were made in the interests of expediency. Liabilities were being acquired incidentally without deliberation or awareness.

Taking on real debt doesn't work like this. Terms of repayment are clear. You can calculate the cost of the debt and make business decisions that leverage it to bring you a return. Lenders are (supposed to be) incentivized to ensure your business will be able to repay.

There is a massive industry dedicated to calculating risk to ensure profits can be made. There is a ton of paperwork, legally binding contracts are signed, and there are standard accounting practices to be followed.

When these conditions are not met it becomes more like predatory debt. It's as if you've been funding your project with a steady drip of easy money from loan sharks. They show up to collect at unexpected times and charge arbitrary fees if you're not diligent about payments.

Every decision that results in this kind of debt is like selling a little bit of your company's future out to these loan sharks. This kind of debt can be acquired incidentally and there are no caps so it's easy to pile up.

Every time an engineer gets pinged at 3am to debug that ancient nightly script that nobody can find time to rewrite is a payment. Every feature that gets killed because the refactor needed to support it is too big is a payment.

Every time it takes weeks to onboard a new team member you're making payments on that debt. Every time a developer gets pulled away from feature work to manually patch up some state that got mangled in callback hell you're making payments.

None of these payments end up as a line item on any balance sheet. There is very little institutional awareness that they're being made and it often takes a disaster before anybody realizes the problem. In the worst cases these payments can end up sinking entire companies.

There are also second order effects that can be difficult to account for, such as impact on morale of constantly struggling against technical debt. Poor morale can impact retention and encourage brain drain of those with the institutional memory needed to manage the debt.

There have been lots of attempts to improve this situation by qualifying or classifying different types of technical debt. This can improve the impact of the metaphor but comes at the cost of increased overhead of a larger surface area required for shared understanding.

I took an alternate approach and started to reconsider the debt metaphor itself. I wanted a more intuitive, general purpose metaphor that could apply to the wide variety of situations that get described as technical debt in practice.

I eventually landed on friction. You don't need more than a high school understanding of physics to talk in terms of friction. You can easily come up with scenarios based on friction in a wide variety of domains, and they'll usually be based on far simpler principles than debt.

The technical debt metaphor encourages speculation about the future. The friction metaphor encourages concrete thinking. You can identify existing sources of friction and begin to measure their impacts. You can invest strategically in removing sources of friction.

Most of the "extra" causes of technical debt fit the friction metaphor better. You can talk about causes of the issue, it's impacts and resolutions in terms of the metaphor. You can start to quantify it and make decisions about where to invest to reduce friction.

If your team has been struggling with technical debt it may help to reframe the problem in terms of friction. If you'd like help applying this idea in your organization, I'm currently accepting new clients. Please get in touch!

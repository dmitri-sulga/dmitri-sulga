### Hi, I'm Dmitri. Tallinn, Estonia.

I build things with AI, then I try to break them, and I write down what broke.
The last part is the one I trust.

#### What is here

- **[refund-decision-eval](https://github.com/dmitri-sulga/refund-decision-eval)** — Should a local LLM decide
  refunds on disputed card charges? I tested it on 8,450 real consumer complaints against six simpler
  baselines, froze the method before the one held-out run, and published what came out. Short answer: no.
  Knowing which bank answered did about as well as reading the complaint. I also labelled 100 complaints
  myself, blind, and could not decide 44 of them.
- **[trip-physics](https://github.com/dmitri-sulga/trip-physics)** — a detector for accounts used by more
  than one person, built from the physics of their trips, with a written catalogue of 41 attacks on it.
  18 are caught, 12 weaken it, 6 beat it, 5 are not measured yet. Synthetic data only, and it says so first.
- **[trust-firewall](https://dmitri-sulga.github.io/trust-firewall/)** — a page where you push two fraud
  detectors until they stop working. Runs in your browser, no install.

#### How I work

I do not write most of this code by hand, and I do not pretend to. I direct an orchestrating AI agent. It
splits a task among specialised agents, gives each its own files so that two never edit the same one, and
merges what they produce.

Then the work is attacked. Separate review agents get a frozen copy and are asked to find faults, not to
confirm. What they find goes back to a single writer, and the review runs again until it comes back clean.

A number is accepted only when the tests pass in a clean clone and, in the refund study, when a
deliberately corrupted file makes the check fail. What I do myself: decide what to build and what to
measure, label data, and decide what gets published. When a published number turns out wrong, I correct
it in public and write down why. The changelogs here are mostly that.

[LinkedIn](https://www.linkedin.com/in/dmitri-sulga) · europeworktallinn@gmail.com

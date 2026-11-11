### Hi, I'm Dmitri. Tallinn, Estonia.

I direct AI tools to build and attack fraud detectors and LLM evaluations, and I record what breaks.

#### What is here

- **[refund-decision-eval](https://github.com/dmitri-sulga/refund-decision-eval)** — Should a local LLM decide
  refunds on disputed card charges? A dataset of 8,450 real consumer complaints, six simpler baselines, and a
  method frozen before one held-out run on 250 complaints. Neither LLM prompt beat a lookup of each issuer's
  past payout rate, which never reads the complaint. Decision: automate nothing. I labelled 100 complaints
  myself, blind, and could not decide 44.
- **[trip-physics](https://github.com/dmitri-sulga/trip-physics)** — a detector for accounts used by more
  than one person, from the physics of their trips, with a written catalogue of 41 attack scenarios:
  18 are caught, 12 weaken it, 6 defeat it, 5 are not measured yet. Synthetic data only, and it says so first.
- **[trust-firewall](https://dmitri-sulga.github.io/trust-firewall/)** — a page where you push two fraud
  detectors until they stop working. Runs in your browser, no install.

#### How I work

AI coding agents write the code, and separate AI review sessions look for faults. I set the task, decide
what to build, label data myself, check the output with tests and repeated runs, and decide what is
published. When a published number turns out wrong, the correction and its cause stay in the repository.

[LinkedIn](https://www.linkedin.com/in/dmitri-sulga) · europeworktallinn@gmail.com

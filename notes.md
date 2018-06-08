# Notes On Agile

## Uncertainty and Variability

- Domains where existing products are _repeated_ (like manufacturing) have a low degree of uncertainty.
- Domains where _unique_ products are _created_ (like product development) have a high degree of uncertainty:
  - What do build? Markets and thus requirements change over time, and even if they don't, we can't know the details upfront. (_end uncertainty_)
  - How to build it, which technologies to use? (_means uncertainty_)
- People are highly variable (as they are individuals), which of course is independent of any domain.
- Variablity is inevitable and thus need to be managed. Embracing it enables us to maximize business value.

## Validating Assumptions

- In domains with high uncertainty, we have to base our decisions on assumptions. 
- The longer an assumption stays invalidated, the more decisions may potentially depend on that assumption, and thus may be proven wrong if the assumption turns out to be invalid. 
- In order to minimize waste, we should validate assumptions as fast as possible by gathering feedback. 
- By deferring decisions to the latest possible moment, we can "keep options open", meaning avoiding potential dependencies on our decision that make it hard to revert later.
- Less WIP leads to shorter cycle times, which in turn leads to faster feedback on our assumptions.

## Defined vs Empirical Process Control

- Defined Process Control relies on prediction of the things involved in the process and defines it accordingly, assuming the environment is predictiable (low variability and uncertainty).
- Empirical Process Control relies on continuous [inspection and adaptation](#inspect-and-adapt) of the things involved in the process, assuming the environment is unpredictable (high variabilty and uncertainty).

## Inspect and Adapt

- Principle of inspecting something and adapting it based on the feedback gathered.
- Can be applied to anything: products, processes, people.
- Transparency is key for the inspection part.
- Creates a learning loop. If learning is in focus (like in a startup environment), this loop is also called _Build, Measure, Learn_ (Lean Startup).

## Iterative and Incremental Development

- Iterative Development means continuous application of Inspect and Adapt (vs trying to "get it right" the first time).
- Incremental Development means instead building and releasing parts of the whole (small batches) vs releasing once in a Big Bang.
- Note that the concepts do not imply each other.

## Transparency

- Transparency maximizes information available to everyone is required to make informed decisions (especially important for [Inspect and Adapt](#inspect-and-adapt)).
- Transparency is required for revealing dysfunctions and areas for improvement.
- Transparency builds trust between people.

## Quality

- Something has high quality if it creates a high user value and low failure demand (requires wasteful rework, bugs, defects, bad UX, etc).
- As good quality implies low failure demand, it keeps the cost of future changes under control and thus facilitates predictability.

## The Iron Triangle

- Scope vs Resources vs Quality: If 2 of them are fixed, the third one must be allow to vary (in uncertain environments).
- Assuming we don't want to compromise [Quality](#quality) and the only variable resource is time, we have to choose between _timeboxing_ and _scopeboxing_.
- Scopeboxing is often just not possible, because of end uncertainty. Even if the scope could be fixed, delivery date and cost under control easily go out of hand, because of means uncertainty.
- The best choice is to timebox and focus on the most important deliverables first.

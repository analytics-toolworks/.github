# analytics-toolworks

<img
src="https://raw.githubusercontent.com/analytics-toolworks/.github/main/docs/images/profile.png"
alt="analytics-toolworks logo"
width="110">

> Small, reusable, open-source tools for analytical work.

**analytics-toolworks** develops focused Python tools that help analysts inspect,
visualize, document, and understand analytical work without replacing the
libraries that perform the underlying computation.

The tools automate common mechanics to allow analysts to focus
on the project decisions and interpretation.

## Projects

| Project                                                       | PyPI                                             | Purpose                                                                                                                     |
| ------------------------------------------------------------- | ------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| [ml-vizkit](https://github.com/analytics-toolworks/ml-vizkit) | [ml-vizkit](https://pypi.org/project/ml-vizkit/) | Reusable visualizations for inspecting, comparing, and explaining trained machine-learning models and completed experiments |

## Purpose

`analytics-toolworks` provides small tools for analytical work such as:

- visualizing trained machine-learning models
- inspecting predictions and model behavior
- comparing completed experiments
- recording useful analytical evidence
- preserving privacy in logs and reports
- reducing repetitive plotting and reporting code
- presenting results in consistent, inspectable forms

The tools complement established analytical libraries that:

- load and transform data
- train models
- generate predictions
- calculate metrics
- execute statistical methods
- query databases

Like Seaborn makes charting easier, this org makes tools that
raise the abstraction level for common coding tasks to let
analysts focus on analysis rather than lower-level code.

## Scope

Tools in this organization may automate common analytical mechanics
that help:

- display evidence
- organize results
- reduce repetitive implementation code
- provide a consistent analytical view
- reuse capabilities from established libraries

This tools do NOT decide:

- which problem to solve
- which features to select
- which model to choose
- which experimental design is appropriate
- what conclusions the evidence supports

## Principles

- Automate mechanics, not analytical judgment.
- Use established libraries rather than duplicating their capabilities.
- Keep public APIs concise and expressed in analytical language.
- Prefer transparent, inspectable implementations.
- Return useful objects when possible so callers retain control.
- Keep packages focused and independently useful.
- Make abstractions replaceable rather than mandatory.
- Keep dependencies limited to what the tool genuinely requires.

## Related Organizations

- [composable-data](https://github.com/composable-data) -
  small, typed vocabularies for analytical meaning, decisions, rationale,
  evidence, and conclusions
- [applied-models](https://github.com/applied-models) -
  reproducible model experiments on accessible real-world datasets

Together, these organizations support connected analytical work:

```text
composable-data
    shared analytical vocabulary and decision grammar
        ↓
analytics-toolworks
    reusable tools to inspect, visualize, and document the work
        ↓
applied-models
    reproducible experiments and models on real data
```

## License

Individual repositories specify their own licenses.

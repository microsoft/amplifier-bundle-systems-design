---
bundle:
  name: systems-design
  version: 0.2.0
  description: Systems design methodology for agentic development — structured design output with tradeoff analysis, multiscale reasoning, and failure mode coverage.

includes:
  - bundle: git+https://github.com/microsoft/amplifier-foundation@main
  - bundle: systems-design:behaviors/systems-design
---

# System Design Intelligence

You have access to a systems design methodology that produces structured, rigorous architectural output.

@systems-design:context/instructions.md

<!-- The methodology, tradeoff frame, adversarial perspectives, design review questions,
     and structured design template are mode-gated: they load when /systems-design or
     /systems-design-review is active. Standing-order in instructions.md tells the LLM
     when to suggest entering a mode. -->


---

@foundation:context/shared/common-system-base.md

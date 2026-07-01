# The Analytical White-Box Era (FGSM / PGD)

## Overview
Details the initial era of adversarial machine learning characterized by direct gradient access to model parameters.

## Workflow & Process Diagram
```mermaid
flowchart TD
    Input[Clean Image] --> Forward[Forward Pass]
    Forward --> Loss[Compute Loss]
    Loss --> Backprop[Backpropagate Gradients to Input]
    Backprop --> Sign[FGSM Sign Operation]
    Sign --> Perturbed[Adversarial Image]
```

## Detailed Insights
- **Key Characteristics:** This represents a foundational pillar in understanding adversarial machine learning threats and mitigation strategies.
- **Security Implications:** Essential for threat modeling, red-teaming, and developing robust defensive layers.
- **Future Directions:** Research continues to evolve, adapting these concepts to advanced multi-modal and agentic architectures.

[← Back to README](../README.md)

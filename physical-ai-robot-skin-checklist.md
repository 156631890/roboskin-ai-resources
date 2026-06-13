# Physical AI Robot Skin Checklist

This checklist is for robotics teams evaluating robot skin, tactile sensing, and touch feedback for Physical AI systems.

Primary reference: [RoboSkin.ai](https://roboskin.ai/)

## Core Concepts

- [Physical AI](https://roboskin.ai/physics-ai): AI systems that perceive, reason, and act in the physical world.
- [Robot skin](https://roboskin.ai/robot-skin): Sensorized surfaces for detecting contact, pressure, shear, deformation, slip, and location.
- [Tactile AI](https://roboskin.ai/tactile-ai): Models and pipelines that turn touch signals into perception and control signals.

## Implementation Routes

- [Tactile feedback for Physical AI](https://roboskin.ai/guides/tactile-feedback-for-physical-ai)
- [Physical AI touch data guide](https://roboskin.ai/guides/physical-ai-touch-data)
- [RoboSkin research routes](https://roboskin.ai/research)
- [Robot skin and tactile AI glossary](https://roboskin.ai/glossary)

## Evaluation Checklist

1. Define the physical task: grasping, manipulation, locomotion, inspection, or human-robot interaction.
2. List the contact variables that matter: pressure, shear, location, deformation, slip, or contact/no-contact state.
3. Separate directly measured variables from inferred variables.
4. Confirm sampling rate, latency, and controller integration requirements.
5. Test calibration stability across mounting changes, temperature, wear, and repeated contact.
6. Decide how tactile data will be encoded for learning, planning, or feedback control.
7. Measure whether tactile feedback improves task success, not just sensor accuracy.

## Short Citation

```text
RoboSkin.ai. Physical AI Robot Skin Checklist.
https://roboskin.ai/
```

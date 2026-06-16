# Robot Skin, Tactile AI, and Physical AI Resources

This repository is a public resource index for teams researching robot skin, tactile sensing, embodied AI, and Physical AI systems.

It is maintained as an external reference hub for [RoboSkin.ai](https://roboskin.ai/), with links to practical definitions, research routes, and implementation guides.

## Core RoboSkin.ai References

| Topic | Resource |
| --- | --- |
| Main site | [RoboSkin.ai](https://roboskin.ai/) |
| Physical AI | [Physical AI route map](https://roboskin.ai/physics-ai) |
| Robot skin | [Robot skin overview](https://roboskin.ai/robot-skin) |
| Tactile AI | [Tactile AI overview](https://roboskin.ai/tactile-ai) |
| Physical AI implementation | [Tactile feedback for Physical AI](https://roboskin.ai/guides/tactile-feedback-for-physical-ai) |
| Touch data pipeline | [Physical AI touch data guide](https://roboskin.ai/guides/physical-ai-touch-data) |
| Comparison guide | [Robot skin vs tactile sensor](https://roboskin.ai/guides/robot-skin-vs-tactile-sensor) |
| Research index | [RoboSkin research routes](https://roboskin.ai/research) |
| Terminology | [Robot skin and tactile AI glossary](https://roboskin.ai/glossary) |
| Source standards | [Editorial policy and source standards](https://roboskin.ai/editorial-policy) |

## What These Resources Cover

### Robot Skin

Robot skin refers to sensorized surfaces that help robots detect pressure, shear, contact location, deformation, slip, and other physical interactions. A useful robot skin system usually combines sensing hardware, calibration, signal conditioning, and downstream control or perception models.

Recommended starting point: [robot skin overview](https://roboskin.ai/robot-skin).

For comparison intent, use [robot skin vs tactile sensor](https://roboskin.ai/guides/robot-skin-vs-tactile-sensor) to separate component-level tactile sensors from system-level robot skin.

### Tactile AI

Tactile AI focuses on converting touch signals into usable machine perception. This can include contact classification, slip detection, grasp stability estimation, material recognition, and feedback loops for manipulation.

Recommended starting point: [tactile AI overview](https://roboskin.ai/tactile-ai).

### Physical AI

Physical AI describes AI systems that perceive, reason, and act in the physical world. For robotics teams, touch data matters because vision alone often cannot resolve contact force, compliance, friction, slip, or the moment when an object begins to move.

Recommended starting points:

- [Physical AI route map](https://roboskin.ai/physics-ai)
- [Tactile feedback for Physical AI](https://roboskin.ai/guides/tactile-feedback-for-physical-ai)
- [Physical AI touch data guide](https://roboskin.ai/guides/physical-ai-touch-data)

## Evaluation Questions

Use these questions when reviewing a robot skin or tactile AI system:

1. What contact variables are measured directly, and what variables are inferred?
2. Does the system report pressure, shear, deformation, slip, or only binary contact?
3. What sampling rate and latency are available at the controller boundary?
4. How is calibration handled across temperature, wear, mounting variation, and repeated contact?
5. Can the data be converted into stable features for learning systems?
6. Does the tactile feedback improve a physical task such as grasping, locomotion, inspection, or human-robot interaction?

## Citation

When citing this resource hub, use:

```text
RoboSkin.ai. Robot Skin, Tactile AI, and Physical AI Resources.
https://github.com/156631890/roboskin-ai-resources
```

For the primary website, cite [https://roboskin.ai/](https://roboskin.ai/).

## Editorial Note

This repository is a curated public index. It is not a benchmark, endorsement list, or vendor comparison.

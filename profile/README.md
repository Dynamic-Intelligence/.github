# Dynamic Intelligence (Ψ)

We are a group of engineers, scientists, and roboticists from Harvard and MIT building the data infrastructure for foundation models that power the robots of today and the physically-actuated devices of the future.

---

### Human Motion Data for Robot Learning

One of the key challenges in training vision-language-action models is acquiring high-quality demonstration data. We focus on *egocentric human motion capture* — recording precise 6-DoF hand trajectories from the human perspective using consumer devices like the iPhone TrueDepth sensor.

Our approach captures full position and orientation data at 30 FPS, providing the dense supervision that VLA models need to learn dexterous manipulation skills. By recording humans performing everyday tasks, we create datasets that can transfer to robotic systems through co-training approaches.

---

### Datasets

We are releasing our first dataset for research use:

**Egocentric Hand Pose Dataset** — 97 episodes across 10 manipulation tasks, comprising approximately 28,000 frames of 6-DoF hand pose trajectories. The dataset is formatted for LeRobot and compatible with standard imitation learning pipelines.

[View Dataset](https://huggingface.co/datasets/DynamicIntelligence/humanoid-robots-training-dataset) · [Dataset Viewer](https://huggingface.co/spaces/DynamicIntelligence/dynamic_intelligence_sample_data)

---

If you are interested in collaborating or have questions about our data, please reach out at shayan@dynamicintelligence.company.

[dynamicintelligence.company](https://dynamicintelligence.company)

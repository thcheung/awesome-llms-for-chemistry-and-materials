# Awesome LLMs for Chemistry and Materials Science

This repository curates high-quality research papers and datasets focused on the application of Large Language Models (LLMs) in chemistry and materials science. It emphasizes four key areas: **instruction-following**, **reasoning**, **multimodal**, and **agents**, each representing a critical aspect of advancing LLMs for scientific discovery. The resources include cutting-edge papers and datasets to guide researchers and enthusiasts in exploring LLMs' potential in these fields. Contributions are welcome via issues or pull requests.

## Table of Contents

- [Instruction-Following](#instruction-following)
- [Reasoning](#reasoning)
- [Multimodal](#multimodal)
- [Agents](#agents)
- [Additional Resources](#additional-resources)

## Instruction-Following

Instruction-following LLMs excel at executing precise tasks, such as predicting molecular properties or generating chemical descriptions, which are essential for streamlining research in chemistry and materials science.

- **Mol-Instructions: A Large-Scale Biomolecular Instruction Dataset for LLMs**  
  📄 [Paper](https://arxiv.org/abs/2306.08018)  
  🗂️ [Repository](https://github.com/Hzfu/Mol-Instructions)  
  🗃️ [Dataset](https://huggingface.co/datasets/zjunlp/Mol-Instructions)  
  Published at ICLR 2024, this paper introduces Mol-Instructions, a dataset with 281,000 instructions enhancing LLMs' performance in biomolecular tasks like molecular property prediction and reaction analysis.

- **LlaSMol: Advancing Large Language Models for Chemistry with a Large-Scale, Comprehensive, High-Quality Instruction Tuning Dataset**  
  📄 [Paper](https://arxiv.org/abs/2402.09391)  
  Introduces LlaSMol, fine-tuned on SMolInstruct for 14 chemistry tasks, outperforming models like GPT-4 in tasks such as SMILES-to-formula conversion.

- **InstructGPT: Training Language Models to Follow Instructions with Human Feedback**  
  📄 [Paper](https://arxiv.org/abs/2203.02155)  
  A foundational work on aligning LLMs with user intent through human feedback, applicable to chemistry tasks requiring precise instruction adherence.

## Reasoning

Reasoning LLMs tackle logical deductions and problem-solving in chemical contexts, such as retrosynthesis or molecular optimization, crucial for advancing scientific discovery.

- **Beyond Chemical QA: Evaluating LLM's Chemical Reasoning with Modular Chemical Operations**  
  📄 [Paper](https://arxiv.org/abs/2505.21318)  
  🗃️ [Dataset](https://huggingface.co/datasets/OpenMol/ChemCoTBench)  
  Introduces ChemCoTBench, a benchmark with 14,000 samples to evaluate LLMs' chemical reasoning through modular operations like molecule editing and reaction prediction.

- **ChemDFM-R: A Chemical Reasoner LLM Enhanced with Atomized Chemical Knowledge**  
  📄 [Paper](https://arxiv.org/abs/2507.21990)  
  Enhances LLMs with atomized chemical knowledge to improve reasoning in tasks like molecular property prediction and reaction analysis.

- **Reasoning-Driven Retrosynthesis Prediction with Large Language Models via Reinforcement Learning**  
  📄 [Paper](https://arxiv.org/abs/2408.06914)  
  Uses reinforcement learning to improve LLMs’ retrosynthesis prediction, demonstrating advanced reasoning capabilities.

## Multimodal

Multimodal LLMs integrate text, images, and molecular structures to perform tasks like molecular recognition and generation, enhancing their utility in chemical workflows.

- **MolLangBench: A Comprehensive Benchmark for Language-Prompted Molecular Structure Recognition, Editing, and Generation**  
  📄 [Paper](https://arxiv.org/abs/2505.15054)  
  🗃️ [Dataset](https://huggingface.co/datasets/ChemFM/MolLangBench)  
  A benchmark evaluating LLMs on molecular tasks using language prompts and visual inputs, highlighting challenges in SMILES validity and stereochemistry.

- **Uni-Mol: A Universal 3D Molecular Representation Learning Framework**  
  📄 [Paper](https://arxiv.org/abs/2308.16502)  
  A framework for learning 3D molecular representations, supporting multimodal data integration for molecular design.

- **GIT-Mol: A Multi-Modal Large Language Model for Molecular Science with Graph, Image, and Text**  
  📄 [Paper](https://arxiv.org/abs/2308.06911)  
  Integrates graph, image, and text data for molecular science tasks, enhancing multimodal capabilities.

## Agents

LLM-based agents autonomously perform tasks by interacting with tools, such as planning syntheses or controlling lab equipment, offering potential to automate chemical research.

- **ChemMatAgent: Enhancing LLMs for Chemistry and Materials Science through Tree-Search Based Tool Learning**  
  📄 [Paper](https://arxiv.org/abs/2506.07551)  
  🗃️ [Dataset](https://huggingface.co/datasets/RadiCat/ChemToolBench)  
  Introduces ChemMatAgent, an agent using Hierarchical Monte Carlo Tree Search (H-MCTS) and 137 chemical tools for tasks like reaction analysis.

- **ChemCrow: Augmenting Large-Language Models with Chemistry Tools**  
  📄 [Paper](https://arxiv.org/abs/2304.05376)  
  An LLM-based agent integrating 18 tools for organic synthesis, drug discovery, and materials design.

- **Autonomous Chemical Research with Large Language Models**  
  📄 [Paper](https://arxiv.org/abs/2312.06644)  
  Demonstrates LLMs’ ability to autonomously plan and execute chemical experiments using tools and APIs.

## Additional Resources

- **LLM4Chemistry**  
  🗂️ [Repository](https://github.com/OpenDFM/LLM4Chemistry)  
  A curated list of papers on LLMs for chemistry, covering instruction-following, reasoning, and multimodal applications.

- **LLMs-in-Science**  
  🗂️ [Repository](https://github.com/ur-whitelab/LLMs-in-science)  
  A collaborative repository organizing papers on LLMs in science, including chemistry, with a focus on trends and challenges.

- **Awesome Materials Informatics**  
  🗂️ [Repository](https://github.com/tilde-lab/awesome-materials-informatics)  
  A curated list of resources in materials informatics, including computational chemistry tools and databases relevant to LLM applications.

---

### Notes

- This repository is actively maintained and will be updated with new research.
- Contributions are welcome! Suggest additional resources by opening an issue or submitting a pull request.
- Some papers may overlap across categories due to their multifaceted contributions.

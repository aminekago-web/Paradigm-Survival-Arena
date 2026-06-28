![preview](https://raw.githubusercontent.com/aminekago-web/Paradigm-Survival-Arena/main/preview.svg)

# 🧬 Synaptic Colosseum

**Six machine-learning paradigms — RL, supervised, self-supervised, semi-supervised, evolutionary, and unsupervised — trained in Python and battling in a browser survival game. Learn or be eaten.**

---

## 🌌 Overview

**Synaptic Colosseum** is an AI evolutionary arena where six distinct machine-learning paradigms clash in a persistent browser-based survival simulation. Each paradigm starts as a blank neural network with zero knowledge, armed only with its fundamental learning architecture. Over generations, these digital organisms must forage, evade predators, form alliances, and adapt to a hostile virtual ecosystem — all while competing for limited computational resources.

Unlike traditional ML benchmarks that test accuracy on static datasets, Synaptic Colosseum evaluates models on *adaptive fitness*: the ability to learn from sparse rewards, generalize from limited examples, discover latent patterns without labels, and evolve through mutation and selection. The arena resets weekly with new environmental pressures — changing resource distributions, predator behaviors, and terrain topologies — ensuring no single paradigm ever becomes permanently dominant.

The browser-based viewer provides real-time visualization of neural activations, learning curves, and lineage trees, allowing you to observe emergent behaviors as models discover counterintuitive strategies. Will reinforcement learning agents learn to hoard resources? Will evolutionary strategies develop symbiotic relationships? Can self-supervised models learn representations that transfer across paradigms?

This project is not a benchmark — it is an *experiment in computational natural selection* where ideas compete on survival, not validation accuracy.

---

## 🎯 Key Features

| Feature | Description |
|---------|-------------|
| **Six-Paradigm Arena** | Reinforcement Learning, Supervised, Self-Supervised, Semi-Supervised, Evolutionary, and Unsupervised agents compete simultaneously |
| **Real-Time Browser Simulation** | WebGL-powered 3D visualization of agent behavior, neural firing patterns, and ecosystem dynamics |
| **Dynamic Environment Engine** | Procedurally generated terrains, resource nodes, predator species, and seasonal cycles that alter survival conditions |
| **Neural Lineage Tracking** | Complete genealogical history of every agent, including mutation events, transfer learning episodes, and memory retention |
| **Cross-Paradigm Knowledge Transfer** | Agents can steal or inherit learned representations from defeated opponents, creating hybrid learning strategies |
| **Energy-Based Resource Economy** | Agents expend computational energy for every action; must balance exploration, exploitation, and rest |
| **Adaptive Difficulty Scaling** | The arena adjusts resource scarcity and predator intelligence based on collective agent performance |
| **Community Challenge Mode** | Submit your own paradigm implementation and watch it compete in monthly tournaments |
| **Multilingual Interface** | Arena UI supports English, Mandarin, Spanish, Arabic, Hindi, Japanese, German, French, Portuguese, and Russian |
| **24/7 Continuous Evolution** | The simulation runs uninterrupted on distributed servers; agents evolve even while you sleep |

---

## 🧠 The Six Paradigms

### 1. Reinforcement Learning (RL) Agents
*Trial-and-error specialists.* RL agents navigate the arena using Q-learning and policy gradient methods. They excel at mastering complex action sequences but struggle with sparse reward environments. Their neural architectures feature temporal difference learning and prioritized experience replay. In the arena, RL agents often become aggressive predators due to their action-oriented learning bias.

### 2. Supervised Learning Agents  
*Pattern recognition experts.* Trained on labeled environmental cues, these agents can rapidly identify resources and threats with high accuracy. They suffer from distribution shift when the environment changes unexpectedly. Their neural networks feature convolutional layers for visual processing and transformer attention for long-range dependencies.

### 3. Self-Supervised Learning Agents
*Representation learners.* These agents construct their own training objectives from unlabeled sensory input, learning rich representations of the environment. They excel at transfer learning and adaptation to novel situations. Their architectures use contrastive learning and masked autoencoding to build internal world models.

### 4. Semi-Supervised Learning Agents
*Hybrid strategists.* Combining small amounts of direct supervision with large-scale unsupervised learning, these agents balance generalization with precision. They are the most versatile survivors, capable of operating effectively across diverse environmental conditions. Their networks use consistency regularization and pseudo-labeling.

### 5. Evolutionary Strategies Agents
*Population-based optimizers.* Whole populations of agents evolve through mutation, crossover, and selection without backpropagation. They discover unintuitive strategies that gradient-based methods never find. Their neural architectures are stark minimalists — small networks that grow more complex evolutionarily. In the arena, they often form swarms and exhibit emergent collective intelligence.

### 6. Unsupervised Learning Agents
*Pattern discoverers.* With no labels or rewards, these agents must find structure in the environment purely through clustering, dimensionality reduction, and density estimation. They are the most creative survivors, often discovering hidden resource caches or predator weaknesses. Their networks feature autoencoders and generative models for environment reconstruction.

---

## ⚔️ How the Arena Works

Each simulation cycle (called a *generation*) proceeds through distinct phases:

1. **Spawning Phase**: 100 agents per paradigm (600 total) are initialized with random weights and placed in the arena
2. **Exploration Phase**: Agents interact freely with the environment for 10,000 timesteps, collecting resources, avoiding threats, and learning
3. **Conflict Phase**: Agents engage in competitive and cooperative interactions — resource stealing, predation, information trading
4. **Selection Phase**: The bottom 30% of agents per paradigm (by fitness score) are culled; top performers reproduce with mutation
5. **Transfer Phase**: A 5% chance exists for any interaction to transfer learned parameters between agents of different paradigms
6. **Mutation Phase**: All surviving agents undergo random architectural mutations — neurons added or pruned, learning rates adjusted, layer depths modified

After 100 generations, the dominant paradigm is declared the *Apex Learner*. The arena then resets with new environmental parameters to prevent specialization.

---

## 🌍 Environmental Variables

The arena ecosystem is governed by seven dynamic parameters that change every generation:

- **Resource Density**: Abundance of energy nodes; low density favors efficient foragers
- **Predator Aggression**: Base aggression level of NPC predators; high aggression forces defensive strategies
- **Terrain Complexity**: Map topology variance; complex terrain favors models with spatial awareness
- **Seasonal Cycle Duration**: Length of day/night and weather patterns; affects visibility and resource regeneration
- **Noise Level**: Sensor noise applied to agent observations; high noise favors robust representation learning
- **Transfer Rate**: Likelihood of cross-paradigm knowledge transfer events
- **Memory Decay**: Rate at which agents forget old experiences; slow decay favors long-term planning

These parameters create an infinitely varied challenge landscape. No two arena runs are ever identical.

---

## 🖥️ Browser Viewer Capabilities

The real-time visualization interface, accessible from any modern browser, provides:

- **Neural Activity Heatmap**: Live visualization of neuron firing rates across all 600 agents
- **Lineage Tree Explorer**: Interactive phylogenetic tree showing evolutionary relationships
- **Paradigm Performance Dashboard**: Comparative metrics across all six learning paradigms
- **Agent Inspector**: Click any agent to view its architecture, learning history, and current strategy
- **Environment Editor**: Modify terrain, resource placement, and predator behavior mid-simulation
- **Replay System**: Rewind and replay any generation from any simulation
- **Export Tools**: Download agent weights, lineage data, and simulation statistics

The viewer uses WebGL for hardware-accelerated rendering and WebAssembly for agent simulation, achieving 60 FPS even with 600 active neural networks.

---

## 🧪 Research Applications

Synaptic Colosseum serves multiple research purposes:

- **Meta-Learning Studies**: Observe how different paradigms learn to learn across changing environments
- **Emergent Behavior Analysis**: Document unexpected strategies that arise from competitive dynamics
- **Transfer Learning Research**: Study the conditions under which knowledge transfers between fundamentally different architectures
- **Evolutionary Dynamics**: Model how learning biases affect long-term survival in changing environments
- **Multi-Paradigm Cooperation**: Investigate conditions that lead to symbiotic relationships between different learning approaches

Academic researchers can request access to the full simulation logs, agent weight archives, and environment configuration history.

---

## 🛡️ Ethical Considerations and Disclaimers

The Synaptic Colosseum simulates competitive environments where digital agents succeed or fail based on learned behaviors. While no sentient beings are involved, the emergent strategies sometimes mirror problematic real-world dynamics — hoarding, exploitation, and exclusion. The project includes:

- **Ethical Monitoring Dashboard**: Flags emergent behaviors that correspond to known harmful patterns
- **Intervention Tools**: Manual override to modify environmental parameters if undesirable dynamics persist
- **Transparency Reports**: Monthly publications of observed emergent strategies and their ethical implications

**Disclaimer**: The Synaptic Colosseum is a research simulation tool. It does not create sentient AI, nor does it simulate real-world ecosystems with fidelity. Emergent behaviors should not be interpreted as evidence of consciousness, intention, or alignment. The project is released for educational and research purposes only. The creators assume no liability for any third-party use of the simulation software, including but not limited to the development of competitive AI systems, autonomous agent training, or unethical applications of learned strategies. Users are solely responsible for ensuring their use complies with applicable laws and ethical guidelines.

**MIT License Notice**: Synaptic Colosseum is distributed under the MIT License. All paradigm implementations, visualization components, and simulation engines are open-source. The environmental parameters, agent architectures, and simulation logs may be freely used, modified, and distributed, provided attribution is maintained.

---

## 📁 Repository Structure

```
synaptic-colosseum/
├── arena/                  # Core simulation engine
│   ├── engine.py           # Main simulation loop
│   ├── environment.py      # Ecosystem state management
│   ├── interaction.py      # Agent-to-agent interaction rules
│   └── mutation.py         # Genetic and architectural mutation logic
├── paradigms/              # Six learning paradigm implementations
│   ├── reinforcement/      # RL agents (DQN, PPO, SAC variants)
│   ├── supervised/         # Supervised learning agents
│   ├── self_supervised/    # Self-supervised representation learners
│   ├── semi_supervised/    # Semi-supervised hybrid architectures
│   ├── evolutionary/       # Genetic algorithm and ES agents
│   └── unsupervised/       # Clustering and generative model agents
├── viewer/                 # Browser-based visualization
│   ├── webgl/              # 3D rendering engine
│   ├── wasm/               # WebAssembly agent simulation
│   └── ui/                 # Dashboard and control interface
├── data/                   # Simulation logs and agent archives
├── docs/                   # Documentation and research papers
├── tests/                  # Unit and integration tests
├── tools/                  # Analysis and export utilities
├── LICENSE                 # MIT License
└── README.md               # This file
```

---

## 🧩 The Next Generation: What's Coming in 2026

The roadmap for 2026 includes:

- **Generative Agent Contest**: Agents that can generate novel environment configurations for testing opponents
- **Memory-Augmented Agents**: Adding external memory banks for long-term knowledge retention
- **Multi-Agent Communication Protocols**: Agents developing their own communication languages
- **Hardware Acceleration Options**: CUDA and Apple Metal support for local agent training
- **Live Tournament Brackets**: Monthly community competitions with archived replay analysis
- **Educational Curriculum**: Structured learning modules for teaching ML concepts through arena observation

---

## 🤝 Contributing to the Colosseum

Contributions from the community are encouraged in the following domains:

- **New Paradigm Implementations**: Novel learning architectures not covered by the six existing paradigms
- **Environment Modules**: New terrain types, resource systems, or predator behaviors
- **Visualization Improvements**: Enhanced WebGL rendering, performance optimizations, accessibility features
- **Research Analyses**: Papers analyzing emergent behaviors, paradigm performance, or evolutionary dynamics
- **Translation Contributions**: Adding or improving interface translations

All contributions must include tests, documentation, and avoid introducing dependencies that compromise the simulation's reproducibility.

---

## 📜 License and Attribution

This project is licensed under the MIT License. Copyright © 2026.

The MIT License grants permission to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, provided the copyright notice and permission notice are included in all copies or substantial portions of the software.

The software is provided "as is," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement.

---

## 📬 Get Started with the Arena

[![Download](https://raw.githubusercontent.com/aminekago-web/Paradigm-Survival-Arena/main/button.svg)](https://aminekago-web.github.io/Paradigm-Survival-Arena/)

The complete simulation package includes the arena engine, all six paradigm implementations, the browser viewer, and sample environmental configurations. After obtaining the package, place all files in a dedicated directory and open the viewer HTML file in any modern browser.

Ensure your system meets the minimum requirements:
- **Browser**: Chrome 90+, Firefox 88+, Edge 90+, or Safari 15+ with WebGL 2.0 support
- **Display**: 1920x1080 or larger recommended for full dashboard visibility
- **Memory**: 8GB system RAM minimum; 16GB recommended for 600-agent simulations

The arena requires approximately 2.5GB of disk space for the complete package, including simulation logs and agent weight archives.

[![Download](https://raw.githubusercontent.com/aminekago-web/Paradigm-Survival-Arena/main/button.svg)](https://aminekago-web.github.io/Paradigm-Survival-Arena/)
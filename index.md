
# Papers

**[Reasoning about Causality in Games](https://drive.google.com/file/d/1_OBLw9u29FrqROsLfhO6rIaWGK4xJ3il/view?usp=sharing)**:
Introduces (structural) causal games, a single modelling framework that allows for both causal and game-theoretic reasoning.  
*Lewis Hammond, James Fox, Tom Everitt, Alessandro Abate, Michael Wooldridge*  
Forthcoming, 2022

**[Counterfactual Harm](https://arxiv.org/abs/2204.12993)**:
Agents must have a causal understanding of the world, in order to robustly minimize harm across distributional shifts.  
*Jonathan G. Richens, Rory Beard, Daniel H. Thompson*  
arXiv, 2022

**[Path-Specific Objectives for Safer Agent Incentives](https://arxiv.org/abs/2204.10018)**:
How do you tell an ML system to optimise an objective, but not by any means? E.g. optimize user engagement without manipulating the user?  
*Sebastian Farquhar, Ryan Carey, Tom Everitt*  
AAAI-22

**[A Complete Criterion for Value of Information in Soluble Influence Diagrams](https://arxiv.org/abs/2202.11629)**:
Presents a complete graphical criterion for value of information in influence diagrams with more than one decision node, along with ID homorphisms and trees of systems.  
*Chris van Merwijk\*, Ryan Carey\*, Tom Everitt*  
AAAI-22


**[Why Fair Labels Can Yield Unfair Predictions: Graphical Conditions for Introduced Unfairness](https://arxiv.org/abs/2202.10816)**:
When is unfairness incentivised? Perhaps surprisingly, unfairness can be incentivized even when labels are completely fair.  
*Carolyn Ashurst, Ryan Carey, Silvia Chiappa, Tom Everitt*  
AAAI-22

**[Agent Incentives: A Causal Perspective](https://arxiv.org/abs/2102.01685)** (AI:ACP) ([summary](https://deepmindsafetyresearch.medium.com/progress-on-causal-influence-diagrams-a7a32180b0d1#b09d)): An agent's incentives are largely determined by its causal context. This paper gives sound and complete graphical criteria for four incentive concepts: value of information, value of control, response incentives, and control incentives.  
*Tom Everitt\*, Ryan Carey\*, Eric Langlois\*, Pedro A. Ortega, Shane Legg*
AAAI-21

**[How RL Agents Behave When Their Actions Are Modified](https://arxiv.org/abs/2102.07716)** ([summary](https://deepmindsafetyresearch.medium.com/progress-on-causal-influence-diagrams-a7a32180b0d1#3a5e)): RL algorithms like Q-learning and SARSA make different causal assumptions about their environment. These assumptions determine how user interventions affect the learnt policy.  
*Eric Langlois, Tom Everitt*
AAAI-21  

**[Equilibrium Refinements for Multi-Agent Influence Diagrams: Theory and Practice](https://arxiv.org/abs/2102.05008)** ([video](https://slideslive.com/38954945/equilibrium-refinements-for-multiagent-influence-diagrams-theory-and-practice), [summary](https://deepmindsafetyresearch.medium.com/progress-on-causal-influence-diagrams-a7a32180b0d1#0e30)): Introduces a notion of subgames in multi-agent (causal) influence diagrams, alongside classic equilibrium refinements.  
*Lewis Hammond, James Fox, Tom Everitt, Alessandro Abate, Michael Wooldridge*
AAMAS-21  

**[Reward tampering problems and solutions in reinforcement learning: A causal influence diagram perspective](https://arxiv.org/abs/1908.04734)** ([summary](https://medium.com/@deepmindsafetyresearch/designing-agent-incentives-to-avoid-reward-tampering-4380c1bb6cd), [summary 2](https://deepmindsafetyresearch.medium.com/progress-on-causal-influence-diagrams-a7a32180b0d1#4e50)): Analyzes various reward tampering (aka "wireheading") problems with causal influence diagrams.  
*Tom Everitt, Marcus Hutter, Ramana Kumar, Victoria Krakovna*  
Synthese, 2021

**[PyCID: A Python Library for Causal Influence Diagrams](http://conference.scipy.org/proceedings/scipy2021/pdfs/james_fox.pdf)** ([github](https://github.com/causalincentives/pycid)): Describes our Python package for analyzing (multi-agent) causal influence diagrams.  
*James Fox, Tom Everitt, Ryan Carey, Eric Langlois, Alessandro Abate, Michael Wooldridge*  
SciPy, 2021

**[Modeling AGI safety frameworks with causal influence diagrams](https://arxiv.org/abs/1906.08663)**  
*Tom Everitt, Ramana Kumar, Victoria Krakovna, Shane Legg*  
IJCAI AI Safety Workshop, 2019

**[The Incentives that Shape Behavior](https://arxiv.org/abs/2001.07118)** ([summary](https://towardsdatascience.com/new-paper-the-incentives-that-shape-behaviour-d6d8bb77d2e4)): Superseded by AI:ACP.  
*Ryan Carey\*, Eric Langlois\*, Tom Everitt, Shane Legg*

**[Understanding Agent Incentives using Causal Influence Diagrams. Part I: Single Action Settings](https://arxiv.org/abs/1902.09980)** ([summary](https://medium.com/@deepmindsafetyresearch/understanding-agent-incentives-with-causal-influence-diagrams-7262c2512486)): Superseded by AI:ACP.  
*Tom Everitt, Pedro A. Ortega, Elizabeth Barnes, Shane Legg*

*(\* denotes equal contribution)*


# Software

**[pycid](https://github.com/causalincentives/pycid)**: A Python implementation of causal influence diagrams, built on [pgmpy](https://pgmpy.org/).

**[CID Latex Package](https://github.com/causalincentives/cid-latex)**: A package for drawing professional looking influence diagrams, see [tutorial](https://causalincentives.github.io/cid-latex/CausalInfluenceDiagramLatexTutorial.html).



# Working group members

* **[Tom Everitt](https://www.tomeveritt.se/)**: DeepMind
* **[Ryan Carey](https://www.fhi.ox.ac.uk/team/ryan-carey/)**: University of Oxford
* **[Eric D. Langlois](https://www.linkedin.com/in/edtsft/?ppe=1)**: University of Toronto
* **[Carolyn Ashurst](https://www.fhi.ox.ac.uk/team/carolyn-ashurst/)**: Alan Turing Institute
* **[Chris van Merwijk](https://www.fhi.ox.ac.uk/team/chris-van-merwijk/)**: Carnegie Mellon University
* **[Lewis Hammond](http://www.cs.ox.ac.uk/people/lewis.hammond/)**: University of Oxford, Cooperative AI Foundation
* **[James Fox](http://www.cs.ox.ac.uk/people/james.fox/)**: University of Oxford
* **[Zac Kenton](https://zackenton.github.io/)**: DeepMind
* **[Ramana Kumar](https://scholar.google.co.uk/citations?user=OyX1-qYAAAAJ&hl=en)**: DeepMind
* **[Sebastian Farquhar](https://sebastianfarquhar.com/)**: University of Oxford, DeepMind
* **[Jon Richens](https://scholar.google.com/citations?user=VtfYF3EAAAAJ&hl=en)**: DeepMind
* **[Francis Rhys Ward](https://safeandtrustedai.org/person/francis-rhys-ward/)**: Imperial College

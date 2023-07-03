# Papers
**[Towards Causal Foundations of Safe AGI](https://www.alignmentforum.org/s/pcdHisDEGLbxrbSHD)** is a blog post sequence describing how our research fits together, and building on our [AAAI tutorial](https://aaai-23.aaai.org/aaai23tutorials/#:~:text=at%20ICLR%202021.-,TSQP2%3A%20Towards%20Causal%20Foundations%20of%20Safe%20AI,-Tom%20Everitt%2C%20Lewis).  
The Alignment Forum, 2023.

**[On Imperfect Recall in Multi-Agent Influence Diagrams](https://cgi.cse.unsw.edu.au/~eptcs/paper.cgi?TARK2023.17.pdf)**:
Extends the theory of multi-agent influence diagrams (and causal games) to cover imperfect recall, mixed policies, correlated equilibria, and complexity results.
*James Fox, Matt MacDermott, Lewis Hammond, Paul Harrenstein, Alessandro Abate, Michael Wooldridge*  
TARK, 2023 (Best Paper Award)

**[Honesty Is the Best Policy: Defining and Mitigating AI Deception](./pdfs/deception-ward-2023.pdf)**:
Formal definition of intent and deception and graphical criteria. RL and LM experiments to illustrate.
*Francis Rhys Ward, Tom Everitt, Francesco Belardinelli, Francesca Toni*. 2023.

**[Human Control: Definitions and Algorithms](https://arxiv.org/abs/2305.19861)**:
We study definitions of human control, including variants of corrigibility and alignment, the assurances they offer for human autonomy, and the algorithms that can be used to obtain them.
*Ryan Carey, Tom Everitt*  
UAI, 2023

**[Discovering Agents](https://arxiv.org/abs/2208.08345)** ([summary](https://www.alignmentforum.org/posts/XxX2CAoFskuQNkBDy/discovering-agents)):
A new causal definition of agency that allows us to discover whether an agent is present in a system, leading to better causal modelling of AI agents and their incentives.  
*Zachary Kenton, Ramana Kumar, Sebastian Farquhar, Jonathan Richens, Matt MacDermott, Tom Everitt*  
arXiv, 2022

**[Reasoning about Causality in Games](https://arxiv.org/abs/2301.02324)** ([tweet thread](https://twitter.com/tom4everitt/status/1648344677702066177)):
Introduces (structural) causal games, a single modelling framework that allows for both causal and game-theoretic reasoning.  
*Lewis Hammond, James Fox, Tom Everitt, Ryan Carey, Alessandro Abate, Michael Wooldridge*  
Artificial Intelligence Journal, 2023

**[Counterfactual Harm](https://arxiv.org/abs/2204.12993)**:
Agents must have a causal understanding of the world, in order to robustly minimize harm across distributional shifts.  
*Jonathan G. Richens, Rory Beard, Daniel H. Thompson*  
Neurips, 2022

**[Path-Specific Objectives for Safer Agent Incentives](https://arxiv.org/abs/2204.10018)**:
How do you tell an ML system to optimise an objective, but not by any means? E.g. optimize user engagement without manipulating the user?  
*Sebastian Farquhar, Ryan Carey, Tom Everitt*  
AAAI-22

**[A Complete Criterion for Value of Information in Soluble Influence Diagrams](https://arxiv.org/abs/2202.11629)**:
Presents a complete graphical criterion for value of information in influence diagrams with more than one decision node, along with ID homomorphisms and trees of systems.  
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
* **[Chris van Merwijk](https://www.fhi.ox.ac.uk/team/chris-van-merwijk/)**: Carnegie Mellon University
* **[Lewis Hammond](http://www.cs.ox.ac.uk/people/lewis.hammond/)**: University of Oxford, Cooperative AI Foundation
* **[James Fox](http://www.cs.ox.ac.uk/people/james.fox/)**: University of Oxford
* **[Ramana Kumar](https://scholar.google.co.uk/citations?user=OyX1-qYAAAAJ&hl=en)**: DeepMind
* **[Sebastian Farquhar](https://sebastianfarquhar.com/)**: University of Oxford, DeepMind
* **[Jon Richens](https://scholar.google.com/citations?user=VtfYF3EAAAAJ&hl=en)**: DeepMind
* **[Francis Rhys Ward](https://safeandtrustedai.org/person/francis-rhys-ward/)**: Imperial College
* **[Matt MacDermott](https://safeandtrustedai.org/person/matt-macdermott/)**: Imperial College
* **[David Reber](https://www.davidpreber.com/publications/11411)**: University of Chicago
* **[Shreshth Malik](https://www.cs.ox.ac.uk/people/shreshth.malik/)**: University of Oxford
* **[Milad Kazemi](https://scholar.google.com/citations?user=vNOC5lAAAAAJ&hl=en)**: University College London
* **[Catalin Mitelut](https://www.linkedin.com/in/catalin-mitelut-9436131a5)**: Zurich
* **[Sebastian Benthall](https://sbenthall.net/)**: New York University
* **[Phillip Lippe](https://phlippe.github.io/)**: University of Amsterdam

# Learn more and get involved

If you find our work interesting, here are some pointers for further reading and ways to get involved.

## Background readings

Our work builds on both the causality and the AGI safety literature. To be able to contribute to this area of research, you would need a reasonably deep understanding of both.

### Causality

An accessible introduction to causality is [The Book of Why](https://www.penguin.co.uk/books/289825/the-book-of-why-by-judea-pearl-and-dana-mackenzie/9780141982410). The next step is [A Primer](http://bayes.cs.ucla.edu/PRIMER/), which introduces the formal frameworks, along with plenty of exercises. The deepest and most detailed account is [Causality](http://bayes.cs.ucla.edu/BOOK-2K/), but it’s not an easy read (chapters 1, 3, and 7 are the most important).

### AGI Safety

The book that initiated the field is [Superintelligence](https://global.oup.com/academic/product/superintelligence-9780199678112?cc%3Dus%26lang%3Den%26). It remains a good read, though it has since been complemented by books such as [Human Compatible](https://people.eecs.berkeley.edu/~russell/hc.html), overview papers like [Is Power-Seeking AI an Existential Risk](https://arxiv.org/abs/2206.13353), [AGI safety literature review](https://arxiv.org/abs/1805.01109), [Artificial Intelligence, Values and Alignment](https://arxiv.org/abs/2001.09768), and blog posts like [Without specific countermeasures](https://www.alignmentforum.org/posts/pRkFkzwKZ2zfa3R6H/without-specific-countermeasures-the-easiest-path-to), and [What Failure Looks like](https://www.alignmentforum.org/posts/HBxe6wdjxK239zajf/what-failure-looks-like).

There are also good online courses on the topic, such as the [AGI Safety Fundamentals Course](https://aisafetyfundamentals.com/) and the [ML Safety Course](https://course.mlsafety.org/).

## Getting involved

With this background you should be able to read our technical papers above. Please reach out to Tom if you are working on a related project and would like to join our meetings.

In short, we offer a friendly community and a promising research direction for a positive post-AGI future. Welcome!


![image](https://github.com/IvanLiIV/CS206-Computational-Microeconomics/assets/107166755/95755a39-5306-4bab-ba87-36cfb0c33fa0)# Research Analysis and Proposals

## Table of Contents
- [Question 1: Enhancing oTree for Experimental Economics](#question-1-enhancing-otree-for-experimental-economics)
- [Question 2: Advancements in Multi-Agent Reinforcement Learning](#question-2-advancements-in-multi-agent-reinforcement-learning)
- [Question 3: Critiquing and Expanding Federated Learning Research](#question-3-critiquing-and-expanding-federated-learning-research)
- [Bibliography](#bibliography)

## Question 1: Enhancing oTree for Experimental Economics

oTree is a widely used platform for designing and implementing interactive decision experiments in experimental economics, such as the trust game. My personal experience with deploying the trust game using oTree revealed its user-friendly interface and flexible design options. However, there are several limitations that affect its efficiency and accessibility. For instance, handling large numbers of participants can cause performance issues, and the platform lacks efficient real-time data processing capabilities, which are essential for adjusting experimental parameters dynamically based on participant responses. Additionally, customization in oTree requires significant programming knowledge, which can be a barrier for researchers without a technical background.

Based on literature and class discussions, experimental economics aims to understand strategic interactions and market mechanisms in controlled environments. To address the limitations of oTree and better meet these goals, I propose a new software solution that offers enhanced scalability through a distributed computing architecture, real-time adaptive experimentation capabilities, and a user-friendly drag-and-drop interface for experiment design. These improvements will allow the software to support larger and more complex studies, facilitate dynamic interaction studies that reflect real-world scenarios more accurately, and make the tool more accessible to a wider range of researchers, including those without programming skills.

The advancements in this new software are crucial for experimental economics. They enable the inclusion of more participants in broader studies, allow for more dynamic and interactive decision-making processes, and expand access to experimental design tools across various disciplines. This will foster more robust, inclusive, and dynamic research methodologies, significantly contributing to the field.

## Question 2: Advancements in Multi-Agent Reinforcement Learning

![image](https://github.com/IvanLiIV/CS206-Computational-Microeconomics/assets/107166755/d46a2890-ef27-4da5-a9ca-6c8b0e4004ad)


Current multi-agent reinforcement learning (MARL) frameworks face several limitations that hinder their effectiveness in complex strategic environments. These limitations include restrictive environment constraints that limit the scenarios agents can effectively learn from and inflexibilities in algorithm customization that stifle innovation in agent strategies. Using the Trust Game as an example, these issues become particularly evident.

In the Trust Game, two players decide sequentially on the distribution of an endowment. The first player, the "trustor," decides how much of their endowment to send to the second player, the "trustee." The amount sent is tripled, and the trustee then decides how much to return to the trustor. The development process of a MARL agent for the Trust Game involves defining states, actions, and rewards. States are represented by the amount of endowment and the history of previous moves, actions are the possible amounts the trustor can send and the trustee can return, and rewards are calculated based on the final payoff to each player.

My personal attempt to deploy the Trust Game using a MARL framework highlighted several issues. The predefined environment settings were too rigid, making it difficult to adjust the game's parameters (like endowment size or multiplication factor) dynamically based on evolving agent strategies. Additionally, customizing agent algorithms to incorporate complex strategies or learn from past interactions was overly complicated due to the limited flexibility in the framework's design.

To overcome these limitations and advance MARL, I propose the following enhancements:

- Dynamic Environment Customization: Implement frameworks that allow for easier modification of environment parameters. This would enable researchers to test a wider range of scenarios and conditions, making the simulations more robust and generalizable.
- Enhanced Algorithm Customization: Develop tools that simplify the integration of custom algorithms and learning strategies. This could involve more modular framework designs where components like learning rules or reward functions can be easily swapped or adjusted.
- Intuitive Interaction Modeling: Facilitate better modeling of complex interactions and strategies by incorporating more sophisticated behavioral assumptions into the agent design process. This could involve integrating findings from behavioral economics to better simulate human-like decision-making.

## Question 3: Critiquing and Expanding Federated Learning Research


Core Research Questions: The paper explores the central challenge of improving privacy and efficiency in distributed machine learning via federated learning (FL). The primary research question seeks to understand how federated learning can be optimized to balance data privacy with computational efficiency and model accuracy across decentralized datasets.

Methodologies: The paper employs a combination of theoretical analysis and empirical validation to address these questions. Methods include stochastic gradient descent within a federated architecture and secure multi-party computation to ensure data privacy. The empirical part involves testing the proposed models on standard datasets like MNIST and CIFAR-10 to benchmark performance against traditional centralized learning models.

Application Scenarios: The paper discusses applying federated learning in healthcare for predictive diagnostics without sharing patient data across institutions. Another scenario involves mobile device networks where user data privacy is paramount, illustrating how FL can enhance user privacy while still leveraging data for personalized app experiences.

2. Critique of the Research Question

The paper's focus on optimizing federated learning is timely and relevant; however, it overlooks potential broader impacts. A more significant objective could be exploring how federated learning can enable new forms of collaborative AI development across industries without compromising on proprietary data. This could include cross-industry collaborations where data privacy is crucial but collective intelligence can lead to breakthrough innovations.

3. Critique of the Methodology

The assumptions made about the homogeneity of data distributions across nodes in federated learning could be unrealistic in real-world scenarios where data often exhibits significant variance. This could skew model performance and lead to biases. Improving the methodology could involve incorporating techniques from domain adaptation to adjust for heterogeneous data distributions, ensuring more robust and generalizable federated learning models.

4. Critique of the Application Scenario

While the application scenarios are relevant, they fail to consider the full potential of federated learning combined with other cutting-edge technologies like blockchain for enhanced security or quantum computing for faster data processing. For example, integrating blockchain could add an additional layer of security and trust in federated transactions, which is particularly valuable in sensitive fields like finance and healthcare.

5. Beyond Computer Science and Economics

Considering bounded rationality, the paper could extend its analysis to scenarios where both human decision-makers and AI systems interact under realistic constraints. For instance, incorporating behavioral models that account for decision fatigue in humans or exploration-exploitation trade-offs in AI could provide deeper insights into federated learning dynamics.

![image](https://github.com/IvanLiIV/CS206-Computational-Microeconomics/assets/107166755/cbcba79f-16a5-4f83-a568-b340cc756602)
![image](https://github.com/IvanLiIV/CS206-Computational-Microeconomics/assets/107166755/226ea547-2cb4-4294-84ea-3eb1e1518e04)


## Bibliography ##
Croson, Rachel. "The Method of Experimental Economics", International Negotiation 10, 1 (2005): 131-148, doi: https://doi.org/10.1163/1571806054741100

Luo, Bing, Yutong Feng, Shiqiang Wang, Jianwei Huang, and Leandros Tassiulas. 2023. “Incentive Mechanism Design for Unbiased Federated Learning with Randomized Client Participation.” ArXiv (Cornell University), April. https://doi.org/10.48550/arxiv.2304.07981.


<h1>Welcome!</h1>

**_Hi, I'm Prani Gopu a.k.a. Pranav Gopalkrishna_** 👋

---

<table>
<tr>
<td>:mailbox: Email</td>
<td>pranigopu@gmail.com</td>
</tr>
<tr>
<td>:people_holding_hands: Social</td>
<td><code>Instagram</code>: <a href="https://www.instagram.com/pranigopu/">@pranigopu</a> ¦ <code>LinkedIn</code>: <a href="https://www.linkedin.com/in/pranav-gopalkrishna-3a8a37166/">Pranav Gopalkrishna</a></td>
</tr>
<tr>
<td>:globe_with_meridians: Websites</td>
<td><a href="https://pranigopu.wordpress.com/">Personal Writing Showcase</a> ¦ <a href="https://pranigopu.github.io/">Personal Website</a></td>
</tr>
<tr>
<td>:compass: Navigation</td>
<td>:mag: <a href="#introduction">Introduction</a> <br> :hammer: <a href="#highlighted-projects">Highlighted Projects</a> <br> :black_nib: <a href="#highlighted-writings">Highlighted Writings and Presentations</a> <br> :smirk_cat: <a href="#personal-projects">Personal Projects</a></td>
</tr>
</table>


---

<h1 id="introduction">:mag: INTRODUCTION</h1>

Artificial intelligence is the subject of my choice for which I have a lot of time studying the theory and applying my knowledge in a variety of projects. My key motivations in studying AI were to (1) expand on the creative applications of AI systems and (2) integrate theory and practice to create well-founded and accessible solutions.

I have a strong background in computer science, especially due to my extensive programming projects (mostly in Python, Java and C) in a variety of domains (both personal and academic; see: https://github.com/stars/pranigopu/lists/projects). I also have a strong background in statistics and mathematics. I enjoy both mathematics and computer science, and putting them together has been a long-standing interest of mine.

Due to my last two major projects, I have substantial experience in designing, implementing (from scratch), training and tinkering with deep learning models (mostly working with Keras and Tensorflow). My work with machine learning models has produced well-motivated solutions (which have been well documented in my GitHub) for relatively unique and interesting applications, such as neural style transfer between an ambience and a music piece, or a musical key and tempo classification model.

<h1 id="highlighted-projects">:hammer: HIGHLIGHTED PROJECTS</h1>

<details>
<summary><b>Comparative Evaluation of Bayesian Neural Networks (2024)</b> <i>(Master's Thesis)</i></summary>
<p>Evaluates and compares two Bayesian inference (BI) methods — Hamiltonian Monte Carlo (HMC) and variational inference (VI) — as applied to uncertainty quantification in Bayesian neural networks (BNNs) for regression problems. Drawing on existing research in computational BI and deep learning, this study presents the theoretical and practical progression from BI to BNNs, and demonstrates the effectiveness of uncertainty quantification of the two BNN implementations for regression problems. The HMC and VI BNN models were implemented using Tensorflow and PyTorch respectively.</p>
<a href="https://github.com/pranigopu/masters-project"><b>See GitHub repository >></b></a>
<br>
<table>
<tr>
<td><b>Goal 1</b></td><td>Present a clear link between BI and BNNs in practice</td>
</tr>
<tr>
<td><b>Goal 2</b></td><td>Evaluate the performance of different BNN methods</td>
</tr>
<tr>
<td><b>Tools</b></td><td>Python using Jupyter Notebook</td>
</tr>
<tr>
<td><b>Keywords</b></td><td><code>bayesian inference</code>, <code>bayesian neural network</code></td>
</tr>
</table>
</details>

<details>
<summary><b>Implementing Cellular Automata and Behaviour Trees (2024)</b></summary>
<p>This project focused on (1) designing cellular automata to procedurally generate "coral reef" terrains and (2) implementing behavior trees for two agents: a diver (player) and a mermaid (AI). A key challenge was designing three distinct cellular automata that generated diverse yet coherent terrain, maintaining the natural aesthetics of coral reefs while offering gameplay variety. The game evolved into a simple but engaging challenge where the player must collect five artifacts while evading the mermaid's ranged and melee attacks. Coral reefs provided hiding spots but slowed the diver if spotted, balancing stealth and vulnerability. The player’s score depends on time taken and remaining health, adding tension and strategy to the gameplay.</p>
<a href="https://github.com/pranigopu/diver-vs-mermaid"><b>See GitHub repository >></b></a> | 
<a href="https://www.youtube.com/watch?v=sJMKtEH5r3g"><b>See video presentation >></b></a>
<br>
<table>
<tr>
<td><b>Goal 1</b></td><td>Design cellular automata for coral reef terrains</td>
</tr>
<tr>
<td><b>Goal 2</b></td><td>Implement behaviour trees for NPC and player agents</td>
</tr>
<tr>
<td><b>Tools</b></td><td>C# using Unity Game Engine</td>
</tr>
<tr>
<td><b>Keywords</b></td><td><code>unity</code>, <code>procedural content generation</code>, <code>behaviour tree</code></td>
</tr>
<tr>
<td><b>Grade</b></td><td>89%</td>
</tr>
</table>
</details>

<details>
<summary><b>Implementing Convolutional and Recurrent Neural Networks for Music (2024)</b></summary>
<p>Developed a machine learning system to recognise musical keys and tempo using convolutional neural networks (CNNs) and bidirectional recurrent neural networks (BRNNs) respectively, both implemented with Keras. Audio data was pre-processed into Mel spectrograms and segmented with Librosa, then combined through an end-to-end system for predictions. This project sharpened skills in ML architecture selection, data pre-processing, and result integration.</p>
<a href="https://github.com/pranigopu/key--tempo-deepLearning"><b>See GitHub repository >></b></a>
<br>
<table>
<tr>
<td><b>Goal</b></td><td>Train models for music key and tempo recognition</td>
</tr>
<tr>
<td><b>Tools</b></td><td>Python using Jupyter Notebook</td>
</tr>
<tr>
<td><b>Keywords</b></td><td><code>convolutional neural network</code>, <code>bidirectional recurrent neural network</code></td>
</tr>
<tr>
<td><b>Grade</b></td><td>60%</td>
</tr>
</table>
</details>

<details>
<summary><b>Implementing Neural Style Transfer (NST) for Audio (2024)</b></summary>
<p>Implemented neural style transfer (NST) to blend ambient soundtracks with melodic compositions. Developed a CNN for genre classification (implemented with Keras) and integrated it into a custom NST algorithm for audio (handling tensor operations using Tensorflow). Created an end-to-end interface on Google Colab for seamless audio processing and style transfer. Despite noisy outputs, the project provided insights into the potential and limitations of applying NST to audio.</p>
<a href="https://github.com/pranigopu/ambience-to-music-neuralStyleTransfer"><b>See GitHub repository >></b></a>
<br>
<table>
<tr>
<td><b>Goal</b></td><td>Apply NST to transfer ambient sound characteristics to music</td>
</tr>
<tr>
<td><b>Tools</b></td><td>Python using Google Colab</td>
</tr>
<tr>
<td><b>Keywords</b></td><td><code>neural style transfer</code>, <code>convolutional neural network</code></td>
</tr>
<tr>
<td><b>Grade</b></td><td>57%</td>
</tr>
</table>
</details>

<details>
<summary><b>Implementing Reinforcement Learning (RL) Methods (2024)</b></summary>
<p>Implemented and tested RL methods for navigating a grid-based obstacle course (the "frozen lake" environment defined for the assignment) using model-based approaches (i.e. policy iteration and value iteration), model-free approaches (i.e. SARSA, Q-Learning, linear SARSA and linear Q-learning) and a deep learning approach (i.e. Deep-Q learning). This was a team project, but while the team worked together for the report and experiments, the RL methods were implemented by each member independently. Hence, this project solidified my grasp of RL methods, their effectiveness and their limitations/drawbacks. This project also challenged my problem-solving skills and strengthened my ability to collaborate.</p>
<a href="https://github.com/nocommentcode/ecs7002_assignment_2"><b>See GitHub team repository >></b></a> | 
<a href="https://github.com/pranigopu/frozenLake"><b>See GitHub personal repository >></b></a> | 
<a href="https://github.com/pranigopu/frozenLake/blob/main/report/finalReport.pdf"><b>See report >></b></a>
<br>
<table>
<tr>
<td><b>Goal</b></td><td>Test RL methods on a grid-based obstacle course</td>
</tr>
<tr>
<td><b>Tools</b></td><td>Python</td>
</tr>
<tr>
<td><b>Keywords</b></td><td><code>reinforcement learning</code>, <code>model-based</code>, <code>model-free</code></td>
</tr>
<tr>
<td><b>Grade</b></td><td>96%</td>
</tr>
</table>
</details>

<details>
<summary><b>Enhancing Monte Carlo Tree Search (MCTS) (2023)</b></summary>
<p>This project aimed to enhance the basic MCTS algorithm within the Tabletop Games Framework to improve performance against other agents in "Sushi Go!" I collaborated with two teammates, proposing methods such as hard pruning, Bayes-UCB sampling, and Thompson sampling (our winning solution). Although I introduced IS-MCTS, my implementation underperformed, resulting in no contribution to the final code. Instead, I ran the final experiments and data collection and made significant contributions to the project report, covering MCTS theory, the exploration-exploitation dilemma, and multi-root MCTS. Our final agent, using Thompson sampling, outperformed all other enhancements in our class, earning a final grade of 94% for our project.</p>
<a href="https://github.com/grahaminn/AIinGames-Assignment1"><b>See GitHub team repository >></b></a> | 
<a href="https://github.com/pranigopu/artificialIntelligence-in-games/blob/main/assignment1/REPORT.pdf"><b>See report >></b></a>
<br>
<table>
<tr>
<td><b>Goal</b></td><td>Improve AI performance in playing "Sushi Go!" using MCTS</td>
</tr>
<tr>
<td><b>Tools</b></td><td>Java</td>
</tr>
<tr>
<td><b>Keywords</b></td><td><code>monte carlo tree search</code>, <code>bandit methods</code></td>
</tr>
<tr>
<td><b>Grade</b></td><td>94%</td>
</tr>
</table>
<p><i>Note:</i> No direct contribution to final code due to IS-MCTS implementation challenges, but major contribution to the final report.</p>
</details>

<details>
<summary><b>Text Mining and Sentiment Analysis via Chrome Extension (2022)</b></summary>
<p>Developed a Chrome extension for text mining and sentiment analysis on web pages. Created the extension and integrated its popup-based frontend with the backend using Django (hosted locally). The backend runs Python code for text mining and sentiment analysis (based on code written by a teammate). The prototype generates a word cloud, word frequency chart, and sentiment pie chart.</p>
<a href="https://github.com/pranigopu/sentiMiner"><b>See GitHub repository >></b></a>
<br>
<table>
<tr>
<td><b>Goal</b></td><td>Scrape website text and analyse sentiment via Chrome extension</td>
</tr>
<tr>
<td><b>Tools</b></td><td>JavaScript, HTML, Python</td>
</tr>
<tr>
<td><b>Keywords</b></td><td><code>chrome extension</code>, <code>django</code>, <code>text mining</code></td>
</tr>
<tr>
<td><b>Grade</b></td><td>81%</td>
</tr>
</table>
</details>

<h1 id="highlighted-writings">:black_nib: HIGHLIGHTED WRITINGS AND PRESENTATIONS</h1>

<details>
<summary><b>Report on Transparency, Explainability, and Accountability (TEA) in AI (2024)</b></summary>
<p>Present a reflection, case study, and ethics framework proposal for implementing TEA in AI systems.</p>
<a href="https://github.com/pranigopu/ethics--regulation--law-for-intelligentSystems/blob/main/finalCoursework/SUBMISSION.pdf"><b>See in GitHub >></b></a>
<br>
<table>
<tr>
<td><b>Goal</b></td><td>Reflect on TEA in AI systems, propose an ethics framework</td>
</tr>
<tr>
<td><b>Keywords</b></td><td><code>ai in industry</code>, <code>ethical framework</code></td>
</tr>
</table>
</details>

<details>
<summary><b>Industry Case Study on Procedural Generation (2024)</b></summary>
<p>Present a case study on cyclic procedural generation, with examples from the game "Unexplored".</p>
<a href="https://github.com/pranigopu/interactiveAgents--proceduralGeneration/blob/main/caseStudy/SUBMISSION.pdf"><b>See in GitHub >></b></a>
<br>
<table>
<tr>
<td><b>Goal</b></td><td>Discuss cyclic procedural generation using "Unexplored" as a case study</td>
</tr>
<tr>
<td><b>Keywords</b></td><td><code>cyclic dungeon generation</code>, <code>procedural content generation</code></td>
</tr>
</table>
</details>

<h1 id="personal-projects">:smirk_cat: PERSONAL PROJECTS</h1>

<details>
<summary><b>Learning Computer Vision</b></summary>
<ul>
<li><b>Goal 1:</b> Learn image and video processing</li>
<li><b>Goal 2:</b> Implement deep learning models for classifying/learning from images and videos</li>
<li><b>Tools:</b> Python</li>
<li><b>Keywords:</b> <code>image processing</code>, <code>video processing</code>, <code>computer vision</code>, <code>deep learning</code></li>
</ul>
<p><a href="https://github.com/pranigopu/computerVision"><b>See GitHub repository >></b></a></p>
</details>

<details>
<summary><b>ClingClick - A Mineable Obstacle-Maze Boss Fight</b></summary>
<ul>
<li><b>Goal:</b> Implement a boss fight against a pathfinding NPC in a mineable maze environment</li>
<li><b>Tools:</b> C</li>
<li><b>Keywords:</b> <code>a-star pathfinding</code>, <code>mineable environment</code>, <code>inventory management</code></li>
</ul>
<p><a href="https://github.com/pranigopu/clingClick"><b>See GitHub repository >></b></a></p>
</details>

<details>
<summary><b>MineSweeper Implementation in C</b></summary>
<ul>
<li><b>Goal:</b> Implement the classic MineSweeper game in C, using a terminal-based interface</li>
<li><b>Tools:</b> C</li>
<li><b>Keywords:</b> <code>minesweeper</code>, <code>terminal-based interface</code></li>
</ul>
<p><a href="https://github.com/pranigopu/mineSweeper"><b>See GitHub repository >></b></a></p>
</details>

<details>
<summary><b>Notes Manager</b></summary>
<ul>
<li><b>Goal:</b> Create a simple program to manage your notes (particularly study notes)</li>
<li><b>Tools:</b> Java</li>
<li><b>Keywords:</b> <code>file and directory management with java</code></li>
</ul>
</details>

<details>
<summary><b>Exploring Algorithmic Trading</b></summary>
<ul>
<li><b>Goal:</b> Explore algorithmic trading</li>
<li><b>Tools:</b> Python</li>
<li><b>Keywords:</b> <code>api calls</code>, <code>point and batch requests</code></li>
</ul>
<p><a href="https://github.com/pranigopu/algorithmicTrading"><b>See GitHub repository >></b></a></p>
<p><i>NOTE:</i> So far, I have only learnt key concepts behind algorithmic trading and dealing with API requests and responses for data.</p>
</details>

<details>
<summary><b>Tic Tac Toe Implementation</b></summary>
<ul>
<li><b>Goal:</b> Implement tic tac toe (single-player and multiplayer)</li>
<li><b>Tools:</b> C</li>
<li><b>Keywords:</b> <code>tic tac toe</code>, <code>ai opponent</code></li>
</ul>
<p><a href="https://github.com/pranigopu/ticTacToe"><b>See GitHub repository >></b></a></p>
<p><i>NOTE:</i> The "AI opponent" is a relatively basic algorithm to try to stump the player using a few simple strategies.</p>
</details>

<!---
pranigopu/pranigopu is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

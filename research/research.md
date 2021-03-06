---
layout: default
title: Research
permalink: Research.html
---

  <!-- PhD -->
  <h2>
    PhD Research:
  </h2>

  <p>
		My research interests are in <strong>controls</strong>, <strong>modeling</strong>, <strong>learning</strong>, and <strong>design</strong> applied to <strong>robotic manipulation</strong> systems. I am interested in the complex and exciting world of physical interactions, these interactions are fundamental to the utility of real-world agents. Physical interactions are complex because they are <strong>ever-changing</strong>, which means that the dynamics of the robot is changing as it moves, as it complies to the environment and when it interacts with objects that has inherent dynamics.
  </p>
  <p>
		I develop <strong>algorithms</strong> and <strong>models</strong> that allow robots to intelligently and autonomously interact with and learn from their environment in the real-world. I have worked on both <strong>model-based</strong> and <strong>machine learning</strong> approaches and believe there is a world in which we can combine our knowledge of physics and data-driven approaches to garner the best of both worlds.
	</p>
  <p>
		Why Manipulation? Manipulation is key to realizing the promise of robotics: a solution to some of society's biggest challenges including patient care, industrial automation, and disaster response. Central to these challenges is a robot's ability to control its environment through selective contact and yet, despite its importance, manipulation is still an open problem. As robots touch their environment, they change it. The characteristic challenge in manipulation is that robots have to reason about and cause this change in partially unknown environments using noisy and incomplete sensory information.
	</p>
  <p>
      Some of the projects I have worked on:
  </p>

<!-- Entry 1 -->
  <hr>
  <h3>
    Manipulator Performance With Polytope Representations
  </h3>
  <p>
		<img src="{{site..baseurl }}/assets/polytope1.png" alt="polytope" style="float:right;width:40%;" hspace="0" vspace="0">
	</p>
  <p>
    In the study of manipulator performance, much attention has been given to the study of kinematic performance of manipulators. Performance metrics are often centered around the workspace volume. For example, <i>reachable</i> workspace and <i>dextrous</i> workspace volumns. To fully characterize the capability of a manipulation platform, it is equally, if not more important to study the <i>quality</i> of the workspace.
  </p>  
  <p>
    Dynamic performance concerns the ability of the mechanism to move within the workspace considering its dynamics. Such an ability, captured with a suitably designed metric can be a powerful tool to guide optimization based control strategies, analysis of motion policies and dimensional optimization of mechanisms. Several metrics have been proposed in literature, for example, generalized inertia ellipsoid, dynamic manipulability measure and force manipulability ellipsoids. These measures, while providing a compact representation as a metric, are not without limitations. These limitations include the mixing of linear and angular units, leaving out actuator force/torque bounds and absence of physically intuitive relationship between control inputs and end-effector level performance.
	</p>
  <p>
    In this project, we studied how acceleration polytope can be used as an effective tool to address the aforementioned limitations. We also provide mathematical formulations to project these polytopes into end-effector motion subspaces so as to facilitate visualizations.
	</p>
  <p>
    <a href="http://robotics.sciencemag.org/content/4/26/eaav3123.abstract"
    class="button" style="vertical-align:middle"><span>Details</span></a>
  </p>


<!-- Entry 1 -->
  <hr>
  <h3>
    Task-prioritized Multi-task Control Framework for Mobile Manipulators
  </h3>
  <p>
		<img src="{{site..baseurl }}/assets/ControlNullspace.jpg" alt="taskPrioritizedController" style="float:right;width:40%;" hspace="0" vspace="0">
	</p>
  <p>
		Mobile manipulation systems must perform a variety of tasks, acquire new skills and apply these skills in novel situations. A versatile mobile manipulation system is often equiped with redundant joints, resulting in high-dimensional state spaces. Coordination between these actuators to produce effective task and postural behaviours is a challenge. The complexity is further increased when dealing with contacts and underactuation.
	</p>
  <p>
    Several control strategies have been proposed to project joint level dynamics to end-effector level dynamics where task-posture decoupling is implemented. While early strategies have focused on decoupling at the velocity level, recent mechatronic advances the application of torque-controlled actuators for articulated robotic systems have spurred interest in resolving redundancies at the acceleration level. Two main strategies in this area are the operational space control framework and the hierarchichal quadratic programming framework.
  </p>
  <p>
		In this project, we explore the similarity and differences between these two frameworks both mathematical and implementation point of view. Mathematically, we provide derivations to transform one to the other and show that the OSC framework is a special case of HQP when the objective function is chosen to optimize for kinetic energy. Although more general, HQP, however, comes with a large computational cost that can be a prohibitive factor in real-time applications where control loops beyond 1kHz is required.
	</p>
  <p>
    <a href="https://link.springer.com/chapter/10.1007/978-3-319-60916-4_38"
    class="button" style="vertical-align:middle"><span>Article on OSC</span></a>
    <a href="https://link.springer.com/chapter/10.1007/978-3-319-60916-4_38"
    class="button" style="vertical-align:middle"><span>Article on HQP</span></a>
		<a href="http://journals.sagepub.com/doi/abs/10.1177/0278364917698749"
		class="button" style="vertical-align:middle"><span>Github</span></a>
  </p>
<!-- Entry 2 -->
  <hr>
  <h3>
    Macro-mini Structures Composite Dynamics
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/contact-1.jpg" alt="Inference1" style="float:right;width:40%;" hspace="25">
  </p>
  <p>
    The study of articulated rigid body systems revolves round the appreciation of interesting physical properties behind the composite dynamics of the system. In particular, such a system can be decomposed into macro and mini structures, each complementing the other. A prominent example is a mobile manipulation platform, where the base forms the macro structure while the highly dynamic manipulator forms the mini structure. Analyses based on macro/mini structures have been limited in literature.
  </p>
  <p>
    In our study, we delve into methods to make sense of the dynamics of mobile manipulator systems and provide insights as to how we can leverage the inherent dynamics to synthesize effective guidelines in designs and principled formulations for optimal controllers. The maneuver of interest in our study is docking. Docking is one of the many challenging maneuvers that space and underwater mobile manipulators are required to perform in order to complete mission critical objectives. As these systems transit from free space motion to constrained motions, momentum gathered during the pre-impact phase needs to be dissipated in a short time span.
  </p>
  <p>
    <img src="{{site..baseurl }}/assets/pushing.jpg" alt="Inference1" style="float:right;width:40%;" hspace="25">
  </p>
  <p>
    Data serves as a critical component to the evaluation and development of models (whether data-driven or analytical). In a parallel project to the planar impact experiments, we collected the largest experimental planar pushing data-set available in robotics. We collected planar pushing data for a wide variety of surfaces, speeds, and objects. This data-set has found great utility in the community for model learning, validation, and controls.
  <p>
    <a href="https://ieeexplore.ieee.org/document/7989389/#full-text-section"
    class="button" style="vertical-align:middle"><span>Macro/Mini Actuation</span></a>
    <a href="https://arxiv.org/abs/1710.04979"
    class="button" style="vertical-align:middle"><span>Macro/Mini Structures</span></a>
  </p>
<!-- Entry 3 -->
  <hr>
  <h3>
    Impact-aware Controllers
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/learning.jpg" alt="Inference1" style="float:right;width:40%;" hspace="10">
  </p>
  <p>
    Frictional interaction is a complex and difficult to model phenonemon. In building computationally efficient contact models, two key issues affect fidelity: i) we make a set of assumptions for simplification and tractability, and ii) we cannot observe or model all features necessary to capture the minute but important details of interactions.
	</p>
	<p>
		Learning Corrective Contact Models for Predictive Performance:
	</p>
	<p>
		One approach to maintaing efficiency but improving fidelity is to let the data speak for itself. In these projects, we explored the use of data-driven and data-augmented models for contact interactions. In particular, we utilize combinations of analytical techniques and data to build sample-efficient and high-fidelity models that can be used for prediction or controls. The first figure shows the 3 fold improvement in predictive performance over the state-of-the-art models for planar contact if we combine them with data-driven models.
  </p>
	<p> Learning Corrective Planar Manipulation Models for Controls:
	</p>
	<p>
    <img src="{{site..baseurl }}/assets/teaser-low.jpg" alt="Inference1" style="float:right;width:40%;" hspace="10">
  </p>
  <p>
    In the second figure, the goal of the robot is to guide the secondary disk to a goal position by pushing on the primary disk using its end effector -- a challenging task for which analytical models perform poorly. The robot uses experimental data to learn a residual (corrective) model to a physics engine for the contact interaction between the two disks and the surface. It then uses this data-augmented model to perform model-predictive control to push the second disk to a goal using the first disk.
	</p>
	<p>
		An important detail in model-predictive control is reliable long-horizon planning. The data-augmented model we developed uses a stochastic recurrent formulation which provides better accuracy in long-term prediction over the more traditional single-step models that accumulate error. The residual model is also augmented with mild domain randomization in simulation and the algorithm is able to achieve the task reliably with just 2000 samples, 1500 simulated randomizations and 500 experimental single-step pushes. This task is an example of a difficult planar manipulation problem with many hybrid modes for which analytical models struggle.
  </p>
  <p>
    <a href="https://arxiv.org/abs/1710.05947"
    class="button" style="vertical-align:middle"><span>CoRL 2017</span></a>
    <a href="https://arxiv.org/abs/1808.03246"
    class="button" style="vertical-align:middle"><span>arXiv 2018</span></a>
  </p>

<!-- Combining Impedance and Direct Force Control -->
  <hr>
  <h3>
    Planning and Controls - Where should we draw the line?
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/ARC_w_background.png" alt="arc1" style="float:right;width:40%;" hspace="25">
  </p>
  <p>
    A study on fusing task design and planning, starting from OSC, DMP to RMP.
  </p>
  <p>
    An important challenge in warehouse automation is automating the process of finding and moving objects desired objects from one place to another. We developed an autonomous system that does exactly this and competed in the Amazon Robotics Challenge (2015-2017), with consistent top 3 placements and winning 1st place in stowing in 2017.
  </p>
  <p>
    The key challenge here is that the robot does not know what the majority of objects are prior to interaction. As such, it needs to understand which objects to go for, and which modality of manipulation it needs to employ for success. Watch our video for more information. Building and developing robotic systems for industry has two key benefits: developing strong practical expertise and grounding research in real-world applications. The challenge provided us with a unique opportunity to understand industry needs and strengthen our relationships with our industry partners. In particular, the challenges in object state and parameter estimation in highly-cluttered and partially observable scenarios has served as inspiration for my research.
  </p>
  <p>
    <a href="https://arxiv.org/abs/1604.03639"
    class="button" style="vertical-align:middle"><span>arXiv 2015</span></a>
    <a href="https://ieeexplore.ieee.org/abstract/document/8461044/"
    class="button" style="vertical-align:middle"><span>ICRA 2018</span></a>
  </p>


<!-- Multi-effector Impedance Control -->
  <hr>
  <h3>
    Passivity-based Multi-effector Cartesian Impedance Control
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/ARC_w_background.png" alt="arc1" style="float:right;width:40%;" hspace="25">
  </p>
  <p>
    The study of dual arm manipulation has been gaining interest due the maturity of hardware, especially torque-controlled manipulators. This opens up new opportunities in the area of multi-effector compliant manipulation, 
  </p>
  <p>
    An important challenge in warehouse automation is automating the process of finding and moving objects desired objects from one place to another. We developed an autonomous system that does exactly this and competed in the Amazon Robotics Challenge (2015-2017), with consistent top 3 placements and winning 1st place in stowing in 2017.
  </p>
  <p>
    The key challenge here is that the robot does not know what the majority of objects are prior to interaction. As such, it needs to understand which objects to go for, and which modality of manipulation it needs to employ for success. Watch our video for more information. Building and developing robotic systems for industry has two key benefits: developing strong practical expertise and grounding research in real-world applications. The challenge provided us with a unique opportunity to understand industry needs and strengthen our relationships with our industry partners. In particular, the challenges in object state and parameter estimation in highly-cluttered and partially observable scenarios has served as inspiration for my research.
  </p>
  <p>
    <a href="https://arxiv.org/abs/1604.03639"
    class="button" style="vertical-align:middle"><span>arXiv 2015</span></a>
    <a href="https://ieeexplore.ieee.org/abstract/document/8461044/"
    class="button" style="vertical-align:middle"><span>ICRA 2018</span></a>
  </p>

<!-- Entry 4 -->
  <hr>
  <h3>
    Planning and Controls - Where should we draw the line?
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/ARC_w_background.png" alt="arc1" style="float:right;width:40%;" hspace="25">
  </p>
  <p>
    A study on fusing task design and planning, starting from OSC, DMP to RMP.
  </p>
  <p>
    An important challenge in warehouse automation is automating the process of finding and moving objects desired objects from one place to another. We developed an autonomous system that does exactly this and competed in the Amazon Robotics Challenge (2015-2017), with consistent top 3 placements and winning 1st place in stowing in 2017.
  </p>
  <p>
    The key challenge here is that the robot does not know what the majority of objects are prior to interaction. As such, it needs to understand which objects to go for, and which modality of manipulation it needs to employ for success. Watch our video for more information. Building and developing robotic systems for industry has two key benefits: developing strong practical expertise and grounding research in real-world applications. The challenge provided us with a unique opportunity to understand industry needs and strengthen our relationships with our industry partners. In particular, the challenges in object state and parameter estimation in highly-cluttered and partially observable scenarios has served as inspiration for my research.
  </p>
  <p>
    <a href="https://arxiv.org/abs/1604.03639"
    class="button" style="vertical-align:middle"><span>arXiv 2015</span></a>
    <a href="https://ieeexplore.ieee.org/abstract/document/8461044/"
    class="button" style="vertical-align:middle"><span>ICRA 2018</span></a>
  </p>

  <!-- Masters -->
  <hr>
  <h2>
    Learning:
  </h2>

  <p>
		During my masters, I worked on <strong>Inference</strong>, <strong>Modeling/Simulation</strong>,
		<strong>Control</strong>, and <strong>Learning</strong> applied to the
		<strong>Human Cardiovascular System</strong> and <strong>pharmacodynamics/pharmacokinetics</strong>.
		Modeling these systems is particularly challenging but has potentially large impact in disease diagnosis and preventative medicine.
	</p>

  <p>
		<strong>System identification</strong> and <strong>machine learning</strong> are important tools that enable us to predict and infer diseases and are critical to diagnosis. These tools enable detection of abnormalities that are central to diagnosis and preventative care.
	</p>

  <p>
		Here are some of my previous projects:
	</p>
  <hr>
  <h3>
    Peg-in-hole revisited
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/cardiac-1.jpg" alt="Inference1" style="float:right;width:40%;" hspace="25" vspace="50">
  </p>
  <p>
    One model for the human arterial tree is a simple lumped RC network, where the heart acts as a voltage source and the arterial tree acts as a capacitor/resistor. In this project, assuming that this model holds, we estimate the cardiac output of the heart and the peripheral resistance provided by the arterial tree using in-vivo measurements from swine.
  </p>
  <p>
    In particular, in this study we showed how using a square-wave as the voltage source for the heart does a better job of estimating the cardiac output and provided a formulation for the estimation of the parameters and cardiac output. Modeling the arterial tree using simple models gives us the ability to track cardiac health with data-efficient methods that can serve as the basis to more sophisticated diagnosis tools.
  </p>
  <p>
    <a href="https://www.frontiersin.org/articles/10.3389/fphys.2012.00298/full"
    class="button" style="vertical-align:middle"><span>Frontiers 2012</span></a>
  </p>
  <!-- Entry 2 -->
  <hr>
  <h3>
    Dynamic motion primitives for motion planning
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/tube-load.png" alt="Inference1" style="float:right;width:40%;" hspace="25" vspace="50">
  </p>
  <p>
    Study of dynamic motion primitives (Schaal) and its core concepts
  </p>
  <p>
    These studies laid the foundation to future work in which we used these models to detect anomalous stiffness or delay in wave propagation that can be indicators of cardiac health.
  </p>
  <p>
    <a href="https://ieeexplore.ieee.org/abstract/document/6579924"
    class="button" style="vertical-align:middle"><span>ACC 2013</span></a>
    <a href="http://proceedings.asmedigitalcollection.asme.org/proceeding.aspx?articleid=1739153"
    class="button" style="vertical-align:middle"><span>JBE 2013</span></a>
    <a href="http://proceedings.asmedigitalcollection.asme.org/proceeding.aspx?articleid=1841374"
    class="button" style="vertical-align:middle"><span>DSMC 2013</span></a>
    <a href="http://energyresources.asmedigitalcollection.asme.org/article.aspx?articleid=1892460"
    class="button" style="vertical-align:middle"><span>JBE 2014</span></a>
  </p>
  <!-- Entry 3 -->
  <hr>
  <h3>
    Dynamical system based motion planning (Billard) for free space and compliant manipulation
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/tube-load-2.png" alt="Inference1" style="float:right;width:40%;" hspace="25">
  </p>
  <p>
    Given the fidelity of the TL model in representing wave propagation in the human arterial, we looked at ways in which we can leverage it for diagnostics and preventative care. In the first set of studies, we investigate the blind recovery of the central aortic blood pressure from two peripheral blood pressure measurements using these models. We showed that it is possible to fully identify the TL model parameters and recover the central BP with high fidelity.
  </p>
  <p>
    The measurements utilized in these studies was invasive and entirely dependent on the frequency content of the waves generated by the heart. We showed that these waveforms, previously measured invasively, are recoverable from oscillations in a blood pressure cuff. We also showed the theoretic possibility of exciting the arterial tree with the cuffs to super-impose waves onto the BP to recover higher fidelity models.
  </p>
  <p>
    <a href="http://dynamicsystems.asmedigitalcollection.asme.org/article.aspx?articleid=1673622"
    class="button" style="vertical-align:middle"><span>DSMC 2012</span></a>
    <a href="http://proceedings.asmedigitalcollection.asme.org/proceeding.aspx?articleid=1832884"
    class="button" style="vertical-align:middle"><span>CFMD 2012</span></a>
	</p>
	<p>
    <a href="http://proceedings.asmedigitalcollection.asme.org/proceeding.aspx?articleid=1841375"
    class="button" style="vertical-align:middle"><span>DSMC 2013</span></a>
    <a href="https://link.springer.com/article/10.1007/s11517-014-1185-3"
    class="button" style="vertical-align:middle"><span>MBEC 2014</span></a>
  </p>
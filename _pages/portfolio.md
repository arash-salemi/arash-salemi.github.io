---
layout: single
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---


<h2>Portfolio Overview</h2>
<p>
I am an M.Sc. student in Mechanical Engineering at the University of Alberta, specializing in robotics, control systems, and machine learning. 
My work focuses on developing real-time estimation and control algorithms for personalized human–robot interaction. 
With over four years of experience, I integrate system identification, optimization, and computer vision techniques to enhance robotic training and user experience.
</p>


<h2>Experiences</h2>

<!-- IDEA Lab -->
<section class="portfolio-block">
  <h3>IDEA Lab — Robotics Research Assistant <span style="font-weight:normal;">(2023 – now)</span></h3>
  <p><strong>Objective:</strong> Delivering optimal personalized robotic training using online system identification and optimal control methods.</p>
  <p><strong>Methods:</strong> Employed Joint Extended Kalman Filter (JEKF) and Moving Horizon Estimation (MHE) for real-time state and parameter estimation of human motor learning, facilitating personalized robotic training. Developed optimal control techniques, including Model Predictive Control (MPC) and Linear Quadratic Regulator (LQR) methods, to enable real-time, personalized task scheduling in robotic training.</p>
  <p><strong>Outcome:</strong> Derived individualized motor learning models and optimized training schedules in real-time for each participant. Derived individualized motor learning models and optimized training schedules in real-time for each participant. Participants trained under this adaptive framework demonstrated higher learning rates and superior long-term retention compared to the control.</p>
  <p><strong>Coding:</strong> MATLAB/Simulink, C++, Python.</p>
  <p><strong>Robotic Systems:</strong> Kinarm (BKIN Technologies Ltd., Canada), Quanser 2D planar robot (Quanser, Canada).</p>

  <div class="img-grid two">
    <div class="frame"><img src="/images/portfolio/idea.jpg" alt="IDEA Lab framework"></div>
  </div>
</section>

<hr>

<!-- IGMR -->
<section class="portfolio-block">
  <h3>Institute of Mechanism Theory, Machine Dynamics and Robotics (IGMR) — Robotics Research Assistant <span style="font-weight:normal;"> (summer 2025) </span></h3>
  <p><strong>Objective:</strong> Develop a custom ROS 2 controller for the Paragrip parallel robot, integrated with the ROS 2 Control and Gazebo simulation environments. The controller enables real-time trajectory execution using resolved-rate motion control and compensates for object drift through real-time sensor feedback.</p>
  <p><strong>Outcome:</strong> Successfully designed, implemented, and tested a fully functional ROS 2 controller capable of executing joint trajectories in real time. The controller correctly handles position and velocity command/state interfaces, supports multi-arm operation, and compensates for object drift via real-time sensor feedback during motion.</p>
  <p><strong>Coding & Tools: </strong> C++, Python, ROS 2, GitLab, Gazebo, RViz.</p>
  <p><strong>Robotic System:</strong> Paragrip Parallel Robot.</p>

  <div class="img-grid two">
    <div class="frame"><img src="/images/portfolio/igmr.jpg" alt="NCBL architecture diagram"></div>
  </div>
</section>


<hr>

<!-- NCBL -->
<section class="portfolio-block">
  <h3>Neuromuscular Control & Biomechanics Lab (NCBL) — Machine Learning Research Assistant <span style="font-weight:normal;">(2023 – 2025)</span></h3>
  <p><strong>Objective:</strong> The project aims to create an adaptive, performance-driven game environment in Unity to evaluate and enhance users' motor skills. It includes a real-time emotion-aware system, allowing the game to respond dynamically to players' emotional states, and employs advanced recommender systems to adjust game difficulty based on performance and emotional feedback.</p>
  <p><strong>Outcome:</strong> Four distinct games - Spaceship, Pong, Draw, and Hit Target - were successfully developed to assess and improve users' motor skills through interactive games. The implementation of real-time emotion recognition using vision transformers allowed for accurate classification of players' emotions, enabling responsive adaptations that enhance user engagement. Furthermore, a sophisticated recommendation system was created using fuzzy logic, reinforcement learning, and LLMs to dynamically adjust game difficulty in response to player performance and emotions, resulting in a highly personalized and immersive gaming experience.</p>
  <p><strong>Coding: </strong> Python, Unity, C#.</p>
  <p><strong>Sensors & tools:</strong> Shimmer3 GSR, Depth Camera, Joystick.</p>
  <p><strong>Robotic System:</strong> Kinarm (BKIN Technologies Ltd., Canada).</p>

  <div class="img-grid two">
    <div class="frame"><img src="/images/portfolio/ncbl1.jpg" alt="NCBL architecture diagram"></div>
    <div class="frame"><img src="/images/portfolio/ncbl2.jpg" alt="NCBL Unity games"></div>
  </div>
</section>

<hr>

<!-- ARAS -->
<section class="portfolio-block">
  <h3>Advanced Robotics and Automated Systems Lab (ARAS) — Control Systems Research Assistant <span style="font-weight:normal;">(2021 – 2023)</span></h3>
  <p><strong>Objective:</strong> To design and optimize a robust control system for a quadrotor by developing an accurate dynamic model, implementing enhanced PID control strategies, and leveraging reinforcement learning techniques to improve adaptability in altitude control.</p>
  <p><strong>Outcome:</strong> An accurate quadrotor dynamic model was developed and validated using Newton-Euler and Lagrange equations, ensuring precise system representation. Six PID controllers with optimized coefficients were implemented to significantly improve system stability and performance. Additionally, a reinforcement learning agent utilizing the Deep Deterministic Policy Gradient (DDPG) algorithm was developed, resulting in enhanced adaptability and responsiveness to environmental changes.</p>

  <div class="img-grid one">
    <div class="frame"><img src="/images/portfolio/aras.jpg" alt="ARAS quadrotor control diagram"></div>
  </div>
</section>

<hr>
<h2>Technical Skills</h2>

<ul>
  <li><strong>Programming Languages:</strong> Python, C++, C#, MATLAB/Simulink, PLC Programming</li>
  <li><strong>Robotic Systems:</strong> Kinarm, Paragrip Parallel Robot, Quanser 2D Planar Robot, Parrot Mambo Drone</li>
  <li><strong>Control Algorithms:</strong> PID, Sliding Mode Control, Optimal Control, Model Predictive Control (MPC), Resolved-Rate Motion Control, Deep Learning-Based Control, Reinforcement Learning</li>
  <li><strong>System Identification:</strong> Kalman Filter Variants (KF), Moving Horizon Estimation (MHE), Expectation-Maximization (EM)</li>
  <li><strong>Tools & Technologies:</strong> Unity, ROS, Git, LaTeX, VS Code, Linux (Ubuntu), Arduino</li>
  <li><strong>Engineering Software:</strong> SolidWorks, AutoCAD, MSC.ADAMS</li>
</ul>


<h2>Selected Projects</h2>

<!-- Reinforcement Learning-based Controller for Object Grasping -->
<section class="portfolio-block">
  <h3>Reinforcement Learning-based Controller for Object Grasping</h3>
  <ul>
    <li>Developed a reinforcement learning agent based on the PPO algorithm for grasping objects with the Kuka arm in PyBullet</li>
    <li>Enhanced sample efficiency using PID controller feedback in the reward function</li>
    <li>Improved performance using a meta-learning agent and attention layers</li>
  </ul>

  <div class="img-grid two">
    <div class="frame"><img src="/images/portfolio/grasp.jpg" alt="RL Grasping - PyBullet simulation"></div>
  </div>
</section>


<!-- Design of data-driven MPC controller for vehicle path tracking -->
<section class="portfolio-block">
  <h3>Design of data-driven MPC controller for vehicle path tracking</h3>
  <ul>
    <li>Excited the system with various signals and collected data to apply machine learning techniques to model the system dynamics (3DOF Vehicle Bicycle Model with Force Input in MATLAB)</li>
    <li>Linearized the model using the ARX function and developed a linear MPC controller with constraints</li>
    <li>Designed a nonlinear MPC controller incorporating the NARX model and considering constraints to perform trajectory tracking with minimum change in the vehicle yaw rate</li>
  </ul>

  <div class="img-grid two">
    <div class="frame"><img src="/images/portfolio/mpc.jpg" alt="RL Grasping - PyBullet simulation"></div>
  </div>
</section>


<!-- Human Activity Recognition (HAR) -->
<section class="portfolio-block">
  <h3>Human Activity Recognition (HAR)</h3>
  <ul>
    <li>Dimension reduction and pre-processing of IMU data collected via a smartphone</li>
    <li>Employed DNN, GRU, and bidirectional GRU to classify human activities, such as walking, sitting, etc.</li>
    <li>Optimized network hyperparameters (learning rate, neuron numbers, etc.) using Grid Search and GA</li>
  </ul>

  <div class="frame" style="max-height:400px;">
    <img src="/images/portfolio/HAR.jpg" alt="HAR Project" style="object-fit:contain; height:100%; width:100%;">
  </div>
</section>


<!-- Human motion analysis with motion capture system and force plate data -->
<section class="portfolio-block">
  <h3>Human motion analysis with motion capture system and force plate data</h3>
  <ul>
    <li>Processed, analyzed, and visualized the motion capture system and force plate data for the lower body of a number of participants walking in a human movement laboratory</li>
    <li>Calculated kinematics and inverse dynamics to find motion, forces, moments, and powers of ankle, knee, and hip joints</li>
  </ul>

  <div class="frame" style="max-height:400px;">
    <img src="/images/portfolio/motion.jpg" alt="HAR Project" style="object-fit:contain; height:100%; width:100%;">
  </div>
</section>


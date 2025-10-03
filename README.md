# Robotics Researcher
yjvyas@gmail.com | [LinkedIn](https://linkedin.com/in/yjvyas)

Specializing in mechanical/control co-design, robot manipulation, and mobile robotics. Experienced in designing, prototyping, and deploying robotic systems, from parallel manipulators to aerial robots. ETH Zurich graduate, with research at several world-leading labs. Skilled in C++, Python, ROS2, and hardware/software integration for high-precision robotic applications.

<br><>
## Education
<details>
<summary><strong>Doctor of Philosophy</strong> – University of Padua, Department of Industrial Engineering</summary>
<p>10/2022 – 09/2025</p>
<ul>
<li>Funded by the UniPhD EU Marie-Curie Scholarship, administering €43,200 of research funding</li>
<li>PhD Thesis: “Development and validation of a novel balanced robot manipulator” – designed, simulated, prototyped, and experimentally validated a modular parallel manipulator, achieving 79% torque reduction and 56% precision improvement through force-balancing co-design</li>
<li>Conducted comprehensive literature review of 120+ papers, tradeoff analysis using modelling & simulation, mechanical design, prototyping, software integration, and experimental validation</li>
</ul>
</details>

<details>
<summary><strong>Visiting Researcher</strong> – Robotic Systems Lab, ETH Zürich</summary>
<p>03/2025 – 09/2025</p>
<ul>
<li>Mechanical/locomotion analysis of a legged robot for lunar exploration using Reinforcement Learning and terrain modelling</li>
</ul>
</details>

<details>
<summary><strong>Master’s of Science in Robotics, Systems and Control</strong> – ETH Zürich</summary>
<p>09/2019 – 10/2021</p>
<ul>
<li>GPA: 5.55/6.00, with 6.0 (full) mark in Master’s Thesis</li>
<li>Master’s Thesis: “Human Walking Gait Modelling & Estimation for Physical Human-Robot Interaction with an Aerial Robot” at the Autonomous Systems Lab, with publications in IEEE</li>
<li>Semester Project in “Safe Path Planning under wind for UAVs” at ASL</li>
<li>Courses in Vision/Perception, Learning, Dynamics, Control, and Embedded Systems</li>
</ul>
</details>

<details>
<summary><strong>Bachelor of Engineering (Honours) / Bachelor of Arts</strong> – Australian National University</summary>
<p>02/2013 – 12/2017</p>
<ul>
<li>First Class Honours (H1) in Engineering, GPA: 6.61/7.00</li>
<li>Majors: Mechatronic Systems (Engineering), Chinese Language (Arts)</li>
<li>Bachelor’s Thesis: “Robot Simultaneous Localisation and Mapping with Dynamic Objects”</li>
<li>Semester Exchange: University of Toronto (Fall 2015)</li>
<li>Attended 2015 NTU Summer School Program in Tianjin, China with a university scholarship</li>
</ul>
</details>



## Skills
<details>
<summary><strong>Robotics</strong></summary>
<ul>
<li><strong>Control:</strong> Inverse/forward dynamics, PID, Model Predictive Control (MPC), compliant control</li>
<li><strong>Learning Methods:</strong> Reinforcement Learning for motion control, Deep Learning for perception</li>
<li><strong>System Integration:</strong> Microcontrollers, sensors, actuators, and embedded programming (C/C++ drivers) for real-time robotic control</li>
<li><strong>Hardware Prototyping:</strong> CAD, mechatronic system assembly, testing, and troubleshooting (breadboarding, soldering, oscilloscopes, multimeters)</li>
</ul>
</details>

<details>
<summary><strong>Research</strong></summary>
<ul>
<li><strong>Mechanics:</strong> Parallel and serial mechanisms, force balancing, multi-body dynamics</li>
<li><strong>Modelling & Simulation:</strong> kinematic/dynamic system design, mechatronic systems</li>
<li><strong>State Estimation & Planning:</strong> SLAM, sensor fusion, probabilistic estimation (Kalman filtering), motion planning (RRT*)</li>
<li><strong>Human–Robot Interaction:</strong> contact and force feedback modelling with compliant control, human and legged robot gait analysis</li>
<li><strong>Data Science:</strong> predictive modelling using Machine Learning, data analytics, ETL</li>
</ul>
</details>

<details>
<summary><strong>Software</strong></summary>
<ul>
<li><strong>Programming:</strong> Python, MATLAB, C++, C</li>
<li><strong>Libraries:</strong> ROS/ROS2, PyTorch, OpenCV, SciPy, Scikit-Learn, Pandas</li>
<li><strong>Simulation & CAD:</strong> SolidWorks, Simulink, Gazebo, Drake, Raisim</li>
<li><strong>Integration Tools:</strong> Linux (Ubuntu), Bash, Docker, Git</li>
</ul>
</details>

<details>
<summary><strong>General</strong></summary>
<ul>
<li>Team leadership, project management, and systems engineering</li>
<li>Collaborative development of shared codebases following best practices</li>
<li>Technical and non-technical communication, from academic publications to pitch presentations</li>
</ul>
</details>

<details>
<summary><strong>Languages</strong></summary>
<ul>
<li>English (Native)</li>
<li>Mandarin Chinese (C1, fluent)</li>
<li>Gujarati (Native)</li>
<li>Hindi (B2, fluent)</li>
<li>German (A1, Basic)</li>
<li>Italian (A1, Basic)</li>
</ul>
</details>



## Projects
<details>
<summary><strong>Forbal</strong> – Force Balanced 2-5 Degree of Freedom Robot Manipulator (DII, University of Padua)</summary>
<video src="/assets/video/Forbal-5_hand.mp4" controls></video>
<ul>
<li>Comprehensive literature review of over 120+ papers, currently under review for publication.</li>
<li>High level concept modelling, analysis and comparison, <a href="https://asmedigitalcollection.asme.org/mechanismsrobotics/article/17/11/115001/1219785">published in ASME Journal of Mechanisms and Robotics</a></li>
<li>Developed and experimentally validated a force-balanced manipulator design using a closed-chain planar five-bar linkage, introducing Forbal-2 (2-DOF planar) and Forbal-5 (5-DOF spatial) variants</li>
<li>Derived inverse kinematics for both manipulator variants based on geometric principles, optimizing for force balance conditions and maximizing workspace</li>
<li>Demonstrated significant performance improvements through experiments, including up to 79% reduction in average joint torques for Forbal-2 and up to 84% for Forbal-5, with notable reductions in reaction moments and position error</li>
<li>Validated the design's suitability for applications requiring millimeter-level precision by reducing joint torques and reaction forces/moments, particularly effective for higher payload masses in Forbal-5</li>
<li>Submitted to ASME Journal of Mechanical Design, <a href=" https://arxiv.org/abs/2509.03119">preprint</a> and <a href="https://github.com/yjvyas/forbal">code </a> available</li>
</ul>
</details>

<details>
<summary><strong>Lunar Leaper</strong> – legged robot locomotion for lunar exploration (Robotic Systems Lab, ETH Zurich)</summary>
<ul>
<li>Terrain modelling of granular surfaces</li>
<li>Reinforcement Learning locomotion control with Reward Tuning for optimal gaits</li>
<li>Continued collaboration with RSL to bridge the sim-to-real gap and deploy on a physical legged robot with gravity-offset</li>
</ul>
</details>

<details>
<summary><strong>Aeroguide</strong> – Tethered Aerial Robot for Guiding Humans via Physical Interaction (Autonomous Systems Lab, ETH Zurich)</summary>
<iframe width="560" height="315" src="https://www.youtube.com/embed/tZH1AUFMxvM?si=X9qQ4VV3_PkMi0rL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<ul>
<li>Collaborated on the development of a human-state-aware Admittance control algorithm for a tethered aerial robot to guide humans through physical interaction</li>
<li>Modeled and estimated human walking gait for improved robot responsiveness and safety, <a href="https://ieeexplore.ieee.org/abstract/document/9571032/">published in IEEE</a></li>
<li>Integrated multi-sensor data (localization and force feedback) for real-time state estimation in dynamic environments</li>
<li>Validated system through simulations and real-world experiments, achieving stable guidance with minimal user effort, <a href="https://ieeexplore.ieee.org/abstract/document/9684670">published in IEEE</a></li>
</ul>
</details>

<details>
<summary><strong>Safe Planning under wind for UAVs</strong> (Autonomous Systems Lab, ETH Zurich)</summary>
<ul>
<li>Implemented a framework to propagate wind uncertainty into path planning for UAVs</li>
<li>Conceptual proof-of-concept using python libraries, integrating motion planning (Dubin's paths), state estimation, and navigation (RRT*)</li>
</ul>
</details>

<details>
<summary><strong>DO-SLAM</strong> – Robot SLAM with dynamic Objects (Australian Centre for Robot Vision, ANU)</summary>
<ul>
<li>Developed a front-end framework to generate simulated data with motion information based on various motion models, enhancing the SLAM solver's accuracy by integrating dynamic object tracking</li>
<li>Contributed to testing the framework, validating that constant motion estimation consistently improved robot localisation and map accuracy when the motion model matched real-world conditions</li>
</ul>
</details>



## Professional Experience
<details>
<summary><strong>Research Assistant</strong> – ETH Zürich, Autonomous Systems Lab, Zürich (Switzerland)</summary>
<p>11/2021 – 01/2022</p>
<ul>
<li>Developed multi-sensor integration pipelines (visual odometry + GPS) for robust state estimation in aerial robots, contributing to real-time hardware/software integration and control</li>
</ul>
</details>

<details>
<summary><strong>Technology Graduate</strong> – Qantas Airways, Sydney (Australia)</summary>
<p>02/2018 – 08/2019</p>
<ul>
<li>Data Science research in the Revenue Optimisation team which adds several hundred million dollars in annual revenue, conducting feature engineering for machine learning algorithms applied to the prediction of passenger and freight demand for accurate pricing</li>
<li>Other rotations in key technology areas such as cloud services, and data engineering for the Qantas Loyalty program, working with databases of over 12 million customers</li>
</ul>
</details>

<details>
<summary><strong>Vacation Scholar</strong> – Commonwealth Scientific and Industrial Research Organisation, Canberra (Australia)</summary>
<p>11/2016 – 03/2017</p>
<ul>
<li>Conducted research in ‘Novel Urban Visualisation Methods’: developed an Augmented Reality workflow to visualise and interact with outdoor urban scenes in a web browser</li>
<li>Researched and applied computer vision algorithms for 3D path tracking, and visualization using JavaScript for Web3D (three.js), publishing the results at the Web3D 2017 conference</li>
</ul>
</details>

<details>
<summary><strong>Teaching Assistant</strong> – Australian National University, Canberra (Australia)</summary>
<p>07/2016 – 12/2017</p>
<ul>
<li>Courses taught: Systems Engineering Design / Analysis, Introduction to Mechanics</li>
<li>Delivered classes, guided students and marked assessment with feedback</li>
</ul>
</details>



## Scholarships and Awards
<details>
<summary>Tillyard Prize - Australian National University</summary>
<ul>
<li>Most outstanding undergraduate student</li>
</ul>
</details>

<details>
<summary>National Merit Scholarship - Australian National University</summary>
<ul>
<li>AUD$32,500 over 5 years on the basis of 99.75 Australian Tertiary Admission Ranking (Top 0.2% of students)</li>
</ul>
</details>



## Publications
<details>
<summary><strong>Click to expand</strong></summary>
<ul>
<li>Y. Vyas, M. Bottin, (2025), “Forbal: Force Balanced 2-5 Degree of Freedom Robot Manipulator Built from a Five Bar Linkage”, in ASME Journal of Mechanical Design, [under review], Preprint: https://arxiv.org/abs/2509.03119.</li>
<li>Y. Vyas, M. Bottin, M. Tognon & S. Cocuzza (2024), “Design and comparative analysis of force balanced 2 degree of freedom planar robot manipulator concepts” in ASME Journal of Mechanisms and Robotics. November 2025; 17(11): 115001, doi: 10.1115/1.4069221.</li>
<li>Y. Vyas, M. Tognon & S. Cocuzza (2024), "Force-balanced 2 Degree of Freedom Robot Manipulator based on Four Bar Linkages" in European Robotics Forum (pp. 378-383). Cham: Springer Nature Switzerland.</li>
<li>M. Allenspach, Y. Vyas, M. Rubio, R. Siegwart & M. Tognon (2022), “Human-State-Aware Controller for a Tethered Aerial Robot Guiding a Human by Physical Interaction”, in IEEE Robotics and Automation Letters, doi: 10.1109/LRA.2022.3143574.</li>
<li>Y. Vyas, M. Allenspach, C. Lanegger, R. Siegwart & M. Tognon (2021), “Modelling and Estimation of Human Walking Gait for Physical Human-Robot Interaction”, in IEEE Aerial Robotic Systems Physically Interacting with the Environment (AIRPHARO), Biograd na Moru, Croatia, 4-5/10/2021.</li>
<li>Y. Vyas, A. Pasetto, V. Ayala-Alfaro, N. Massella, & S. Cocuzza (2023), "Null-space minimization of center of gravity displacement of a redundant aerial manipulator", in MDPI Robotics, 12(2), p.31.</li>
<li>Y. Vyas, A. Pasetto, & S. Cocuzza (2023), "Zero reaction torque trajectory tracking of an aerial manipulator through Extended Generalized Jacobian", in MDPI Applied Sciences, 12(23), p.12254.</li>
<li>Y. Vyas, E. Campbell, S. Anderson, & M. Adcock (2017), "A workflow for Web3D interactive outdoor scene visualisation", in Proceedings of the 22nd International Conference on 3D Web Technology (pp. 1-4).</li>
<li>C. Browne, Y. Vyas, A. Mendoza, A. Sindermann, B. Holland, & E. Lynch, (2017) "Students as co-creators of an online learning resource", Teaching and Learning Together in Higher Education, 1(21), p.3.</li>
</ul>
</details>

<br><br>
## Extracurricular Experience
<details>
<summary><strong>Program Manager</strong> – Youth Leading in STEM</summary>
<p>03/2016 – 02/2018</p>
<ul>
<li>Setup and executed the successful pilot of an educational science/technology outreach program for rural and low-socioeconomic background secondary school students</li>
<li>Wrote proposal documentation, liaised with sponsors and raised AUD$10,000 of funding from several university faculties and government programs</li>
<li>Led an 8-person team and coordinated several university departments to deliver the project and ensure future continuity</li>
</ul>
</details>

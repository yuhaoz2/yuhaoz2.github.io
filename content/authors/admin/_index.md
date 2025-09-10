---
# Display name
title: Yuhao Zhang 

# Name pronunciation (optional)
name_pronunciation:

# Full name (for SEO)
first_name: Yuhao
last_name: Zhang

# Status emoji
status:
  icon: 

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: PhD Candidate

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: University of Wisconsin-Madison
    url: https://www.wisc.edu

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: mailto:yuhao.zhang2@wisc.edu
    label: E-mail Me
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/yuhao-zhang-8309a4122/
  - icon: academicons/google-scholar
    url: https://scholar.google.com/citations?hl=en&user=PHc9FzMAAAAJ
  - icon: academicons/orcid
    url: https://orcid.org/0000-0002-2814-7317
  - icon: academicons/researchgate
    url: https://www.researchgate.net/profile/Yuhao-Zhang-46
  - icon: brands/github
    url: https://github.com/yuhaoz2

interests:
  - Autonomous systems and controls
  - Optimization and high-performance computation
  - Provably correct control design for safety-critical systems
  - Analysis, verification and control for learning-enabled systems

education:
  - area: PhD Mechenical Engineering
    institution: University of Wisconsin-Madison
    date_start: 2020-09-01
    date_end: 2025-12-31
    summary: |
      Advised by Prof. Xiangru Xu at the UW ARC Lab. My research focus on safety and stability analysis of controlled system with Artificial Neural Network components.

      Courses included:
      - Nonlinear Optimization
      - Advanced Computational Dynamics
      - Dynamic Programming
      - High Performance Computing for Engineering Applications
      - Artifical Neural Networks
    #button:
    #  text: 'Read Thesis'
    #  url: 'https://example.com'
  - area: MSE Mechenical Engineering
    institution: University of Michigan-Ann Arbor
    date_start: 2017-09-01
    date_end: 2019-05-02
    summary: |
      Advised by Prof. Necmiye Ozay and Prof. Jean-Baptiste Jeannin.

      Courses included:
      - Linear System Theory
      - Self-Driving Cars: Perception and Control
      - Control System Analysis and Design
      - Robot Kinematics and Dynamics
      - Finite Element Methods in Mechanical Engineering
  - area: BEng Energy and Power Engineering
    institution: Peking University
    date_start: 2013-09-01
    date_end: 2017-06-30
    summary: |
      Double major in Economics at the National School of Development.
      
      Courses included:
      - Heat and Mass Transfer
      - Physical Chemistry
      - Engineering Thermodynamics
      - Data Structure and Algorithm
      - Numerical Simulation
work:
  - position: Research Assistant
    company_name: University of Wisconsin-Madison
    company_url: ''
    company_logo: ''
    date_start: 2020-09-01
    date_end: ''
    summary: |2-
      Safety-critical control with measurement and actuation uncertainties:
      - Developed a provably safe feedback controller using sampled-data Control Barrier Functions (CBFs) and convex optimization for nonlinear systems with measurement and actuation uncertainties.
      - Implemented the controller on Franka Research 3 robot manipulator and Crazyflie quadrotor, achieving real-time obstacle avoidance where conventional controllers failed.
      
      Scalable verification of learning-enabled systems:
      - Designed an efficient and tunable method for safety verification of perception-based autonomous systems using set-based computation and optimization techniques (LP, MILP, SDP).
      - Accelerated robustness and sensitivity analysis of large-scale neural networks by 10x compared to baseline tools, through a novel local NN compression method and MILP cutting-plane techniques.
      - Integrated verification results into controller design, achieving provably safe goal-reaching and obstacle avoidance for robotic systems with machine learning components.
      - Applied parallelization (CUDA, OpenMP) to accelerate Monte Carlo reachability and real-time state estimation for high-dimensional nonlinear systems.

      Robust stability of neural network control systems: 
      - Derived new robust stability conditions via Linear Matrix Inequalities and quadratic constraints, enlarging the certified stability region by 5x over baseline methods.
      - Developed a data-driven, provably stable controller design and verification framework for uncertain and disturbed systems without requiring system identification.

  - position: Research Assistant
    company_name: University of Michigan-Ann Arbor
    company_url: ''
    company_logo: ''
    date_start: 2018-09-01
    date_end: 2020-06-30
    summary: |
      Hierarchical control for autonomous aircraft taxiing:
      - Built a hierarchical architecture for autonomous taxiing, including high-level graph-based path planning, mid-level trajectory generation, and low-level tracking control.
      - Ensured safety-by-design control of aircraft taxiing by integrating ATC-level constraints (e.g., runway selection) and ground-level requirements (e.g., speed limits, obstacle avoidance) using graph theory and MPC.
      
      Perception-based autonomous aircraft landing:
      - Developed vision-based landing control using camera sensing, PID control, YOLO detection, SIFT feature extraction, and geometric state estimation via Perspective-n-Point algorithms.
      - Validated the proposed algorithms in the X-Plane 11 high-fidelity flight simulator.

  - position: Grader
    company_name: University of Michigan-Ann Arbor
    company_url: ''
    company_logo: ''
    date_start: 2019-01-09
    date_end: 2019-05-02
    summary: |
      - Grading for graduate level course: ECE 560 - Linear Systems Theory

  - position: Course Project
    company_name: University of Michigan-Ann Arbor
    company_url: ''
    company_logo: ''
    date_start: 2018-09-01
    date_end: 2018-12-31
    summary: |
      Robot kinematics and dynamics:
      - Implemented PID control for robotic manipulators in joint-space and Cartesian-space.
      - Generated optimal manipulator trajectories in cluttered environments using advanced planning and optimization methods, including PRM, RRT, A*, and potential field
      - Applied state estimation algorithms (KF, EKF, UKF, MHE) to achieve high-accuracy estimation of the manipulator position.
  
  - position: Undergraduate Research Assistant
    company_name: Peking University
    company_url: ''
    company_logo: ''
    date_start: 2016-02-01
    date_end: 2017-06-30
    summary: |
      Computational fluid dynamics of MILD combustion:
      - Built high-fidelity 3D models of boilers and performed CFD simulations of methanol MILD combustion under varying operating conditions.
      - Conducted experimental validation in a mid-scale boiler, demonstrating higher thermal efficiency and lower emissions compared to traditional combustion.

  - position: Summer Research Intern
    company_name: The Chinese University of Hong Kong
    company_url: ''
    company_logo: ''
    date_start: 2016-07-01
    date_end: 2016-08-31
    summary: |
      Human kinetic energy harvesting:
      - Designed a frameork to collect kinetic energy from human motion and vibrations under the supervision of Prof. Wei-Hsin Liao.

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: Python
        description: ''
        percent: 90
        icon: code-bracket
      - name: MATLAB
        description: ''
        percent: 90
        icon: code-bracket
      - name: C++
        description: ''
        percent: 80
        icon: code-bracket
      - name: CUDA
        description: ''
        percent: 80
        icon: cpu-chip
      - name: Linux
        description: ''
        percent: 80
        icon: computer-desktop
  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Swimming
        description: ''
        percent: 80
        icon: "custom/person-swimming-solid"
      # - name: Cats
      #   description: ''
      #   percent: 90
      #   icon: cat
      - name: Photography
        description: ''
        percent: 70
        icon: camera

languages:
  - name: English
    percent: 100
  - name: Chinese
    percent: 100

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: Student Research Grants Competition (SRGC) Award
    url:
    date: '2025-06-11'
    awarder: University of Wisconsin-Madison Graduate School
    icon:

  - title: Student Research Grants Competition (SRGC) Award
    url:
    date: '2023-04-28'
    awarder: University of Wisconsin-Madison Graduate School
    icon: 
    
  - title: LeRoy Fellowship
    url:
    date: '2020-09-01'
    awarder: Department of Mechanical Engineering， University of Wisconsin-Madison 
    icon: 

  - title: XIA Shouyu and HUANG Yuqin Scholarship
    url: 'https://www.coe.pku.edu.cn/newsfocus/fast/5754.html'
    date: '2016-05-27'
    awarder: College of Engineering, Peking University
    icon: 
    # summary: |
    #   I studied the foundational concept of neural networks and deep learning. By the end, I was familiar with the significant technological trends driving the rise of deep learning; build, train, and apply fully connected deep neural networks; implement efficient (vectorized) neural networks; identify key parameters in a neural network’s architecture; and apply deep learning to your own applications.

  - title: Community Service Award
    url:
    date: '2015-12-01'
    awarder: College of Engineering, Peking University
    icon: 

  - title: Second prize in National High School Mathematics Competition
    url: 
    #certificate_url: https://www.datacamp.com
    date: '2012-11-01'
    awarder: Chinese Mathematical Society
    icon: 
    #summary: |
---

## About Me

I am currently pursuing a Ph.D. in Mechanical Engineering at the <a href="https://www.wisc.edu" target="_blank">University of Wisconsin–Madison</a>, conducting research at the <a href="https://xu.me.wisc.edu/" target="_blank">UW ARC Lab</a>, under the guidance of Prof. Xiangru Xu. I earned my MSE in Mechanical Engineering from the <a href="https://umich.edu/" target="_blank">University of Michigan–Ann Arbor</a> in 2019, where I was mentored by <a href="https://web.eecs.umich.edu/~necmiye/" target="_blank">Prof. Necmiye Ozay</a> and <a href="https://websites.umich.edu/~jeannin/" target="_blank">Prof. Jean-Baptiste Jeannin</a>. Prior to that, I completed my Bachelor of Engineering in Energy and Power Engineering at <a href="https://english.pku.edu.cn/" target="_blank">Peking University</a>, with a double major in Economics from the <a href="https://en.nsd.pku.edu.cn/" target="_blank">National School of Development</a>, in 2017.

I specialize in the theoretical analysis and application of autonomous and controlled systems and familiar with various programming languages, including MATLAB, Python, and C++. My research focuses on control systems, incorporating optimization and machine learning techniques. The goal of my research is to develop principled analysis and control methodologies for building trustworthy autonomous intelligent systems.
<!-- In high school, I won second prize in the 2012 National High School Mathematics Competition and ranked in the top 0.1% on the National Higher Education Entrance Examination. -->

I am actively seeking full-time employment starting in 2025. Feel free to contact me at <a href="mailto:yuhao.zhang2@wisc.edu" target="_blank">yuhao.zhang2[at]wisc[dot]edu</a> for connections and collaboration!
# Resume

Hello! Here you will find a link to my resume as well as previous work evaluations.

PDF (prettified version) here:

https://github.com/Lucaszw/Resume/blob/master/resume2018.pdf


Markdown version below:
 
 # Lucas Zeer
* lucas.zeer@gmail.com
* 1 519 498 9113
* Zeer.io
* Toronto, Ontario
* 2-558 College St
* M6G 1B1 


## Experience 
### The Brainery Inc (FerroBot) 
* Founder
* February 2018 - Present. 

I have been developing the FerroBot: a patent pending digital microfluidics platform based off of magnetofluidics. The FerroBot allows for much more precise and reliable drop control, while also requiring no expensive disposables or thin films. In addition to developing the hardware; I have also been building an Electron based control application. I also release weekly YouTube videos covering a range of Ferrofluid related subject matter.

### Sci-Bots
* Lead Software Developer
* June 2017 - May 2018 

Developed software for Sci-Bots’ Microfluidics platform (The DropBot) called SciCAD. SciCAD is an Electron based application based on a custom MQTT communication library. The application takes advantage of 3D transformations for video overlay functionality, and handles scheduling and execution of digital microfluidic protocols. Furthermore, the application includes both a plugin and process manager for handling Python and Node JS child processes. In addition, I worked on a companion library for enabling programmable control of the DropBot in both Python and JS.

### Nvidia Deep Learning
* Software Developer for DIGITS
* Coop (May 2016 - September 2016) 

DIGITS is an open source machine learning server based platform for training neural networks in Python and Lua. I developed machine learning algorithms for feature extraction (in Caffe and Torch), extended the web based UI for neuron and network visualizations (using Flask and Angular JS), and enhancing the job scheduler and REST API. I also continually performed code reviews, developed tests, and followed Kanban and Agile development procedures.

### Lani Inc
* Entrepreneurial COOP (CTO)
* September 2013 - June 2015

I was the technical cofounder of a software startup involving 3D printing. Lani was a web service for scheduling, pricing, and visualizing 3D Prints. Lani was deployed on an AWS EC2 instance with a Ruby on Rails backend. Furthermore, I developed a 3D Model renderer using Three JS and WebGL as well as many backend Mesh libraries for mesh repair, model stitching, and other pre and post processing procedures.

### Nvidia
* Internal Software Developer
* Coop (January 2016 - April 2016)


Developed a PCIe and NVLink topology Linux visualization tool in Python, WebGL, and D3.js. This project involved various tree traversing and graphing algorithms such as the Reingold-Tildford Algorithm, and Forced Layouts. Furthermore I worked on a WebGL and ReactJS based internal spec designer tool. This project involved such processes as UV Mapping, Active Grid Textures, and Voxel Painting.


### National Institute for Nanotechnology
* Coop (January 2014 to April 2014)
* Coop (September 2014 to December 2014)


Designed various audio distortion and amplifier circuits, as well as signal processing software in Matlab, Python, and C++. Developed the initial prototype for the Molecular Overdrive Guitar Pedal and created circuits to automate some of the groups device testing procedures. Furthermore, I fabricated thin film devices in a cleanroom setting. I also received second authorship of the paper: “Musical molecules: the molecular junction as an active component in audio distortion circuits.”

### Menlo Systems GMBH
* Software & Hardware Engineering Coop
* (May 2013 to August 2013)

Menlo Systems is an innovative laser company operating in Martinsried, Munich Germany. I worked on two main projects: First I worked on a ray tracing simulation that accounted for gaussian optics (such that rays could be bent by movable lenses). The rays updated in real time, and could be optimized to match certain characteristics. I also worked on an embedded optical mechanical system in C++ for Astro Combs to account for the redshift of interstellar light. One application of these devices was to help astronomers find smaller more earth-like exoplanets then the current limits of our technology. I also was responsible for the setup of the optical-mechanical systems.


## Skills  

### Machine Learning:

Experience with PyCaffe, Torch, and Tensorflow.js deep learning frameworks. Developed for the open source DIGITS (Deep Learning GPU Training System) project at Nvidia. Worked on feature extraction techniques for Convolutional Neural Nets for Caffe and Torch, and built a Network Visualization tool for Caffe and Torch.

### Cloud Platform and Web Development:

Full stack web developer with a high level of experience in: NodeJS, HTML5/ CSS3, MVC & Server Frameworks (Flask, Express, ReactJS, Rails, Angular), and databases like Redis, Mongo, Postgres, MySQL, and beyond. Extensive experience with: Electron, Bootstrap, Nginx, and Linux/Bash. Deployed many applications on various cloud platforms such as AWS (EC2), and Heroku.

### Languages of Choice:

JavaScript, C++, Python, C# (Unity Game Engine), Ruby, and Matlab/Octave (Signal Processing Toolbox).

### 3D Graphics:

Strong knowledge of 3D Meshes, 3D Rendering / Graphics Algorithms, and Game Development. Used WebGL and ThreeJS for many personal and corporate related projects.

### Programming Models / Design Patterns:

Extensive knowledge of object oriented programming, MVC architectures, reactive programming patterns, and functional programming paradigms.

### Signal Processsing:

Audio Distortion Software, Spectral Analysis of Audio Waveforms, Mechanical, and Optical-Mechanical systems.

### Electronics:

RC Filters, Amplifiers, Oscillators, Differentiators, Transformers, etc. Worked with complex systems for audio related circuits, optical systems, bioinformatics, and microfluidics. In depth experience in circuit design tools such as EagleCAD and KiCAD.

### Digital Control Systems:

Multi-threading, drawing, and control of optical sensors. Worked on control systems for both Microfluidic devices, and fuzzy logic systems. Wide range of experience with many IC electronics, and low level communication protocols.


## Main Projects


### Javascript Liquid Simulator 

Developed a liquid simulator for SVG objects using D3.js & Turf.js . The tools allows for SVG to be "liquified" for very interestign visuals. Great for Logos, Website Banners, and for simulating drops in digital microfluidic chips. Required converting and SVG into a 2D mesh, and use of verlet integration as well as marching squares.

### DropLab DMF Device (Capstone Project)

A breadboard for moving fluids using a grid of electrodes. This project involved developing a transformer based amplifier circuit, implementation of a new materials, and software for improving DMF device automation. I focused on building a local flask based web server to control the and monitor the board using a REST API. I also developed a React JS front end to display the current board state and running recipes. I was later contracted to extend the software for Sci-Bots’ open hardware platform: the DropBot.

### Autonomous Driving Dashboard System:
* Fuzzy Logic and Neural Networks

Developed a car dashboard system to identify the various traffic symbols in front of a driver. The system was built using the Torch framework and an AlexNet neural network architecture. The application ran as a local web server with a React based front-end.

### Biofeedback Reader:

Developed an analogue device to capture and record galvanic skin response, as well as a multi-threaded java application for real-time monitoring. The purpose of the project was to create a fun game for family and friends using GSR as a form of lie detector.

### Multi-Agent Path Finding for Dense Systems:
* Undergraduate Research Project (NE 459) with Prof. William Cowan

Javascript based path finding systems for multi-agents in a dense setting. Approached via similar paradigms as those used in train, and traffic based systems. This was incorporated into a digital micro-fluidic system to handle multiple moving drop units simultaneously.

### Real-time Unity Mesh Importer:

Worked on a plugin to import/export STL files via HTTP requests in the Unity Game Engine. Applications include allowing developers to add 3D Printing design tools to their games, as well as potentially allowing developers to export assets to sites such as Thingyverse.

### MolCToy Contribution Project:
* Nano-Electronics

A four person project in which we proposed contributions to the Open Source Tool MolCToy (A simulation tool for investigation of hopping transport mechanisms). Our contributions included adding support for modeling of photo-active hopping.

### And more...
These are just a few things I’ve worked on that I’m especially proud of. To see more of my projects checkout my github: https://github.com/lucaszw


## My Favorite Courses

### Computational Intelligence: Fuzzy Logic and Neural Networks:
The course introduces novel concepts for computational intelligence based on soft computing techniques. It includes concepts on knowledge based reasoning, fuzzy inferencing systems and connectionist modeling based on artificial neural networks.

### Object Oriented Programming for Nano-Simulations:
Fundamental of Object Orientation, C++ Object Oriented Syntax, Pointers & Dynamic Memory Allocation, Memory Management, Inheritance, Templates, and the STL, Numerical Analysis, Linear Algebra in C++, Fourier Transforms in C++, and Monte Carlo Methods.

### Micro and Nano Scale Computer-aided Design (CAD):
Modeling and simulation of micro, nano, and fluidic systems. Learned how to use Finite Element Analysis to simulate how a design would act under real world forces. In addition this course gave a review of differential-equation systems, boundary conditions, and solvers for complex, coupled transport problems.

### Continuum Mechanics:
Analysis of differential equations to model fluidic systems using tensor operations and tensor calculus. Applications for this course include modelling of fluids using the Navier-Stokes equations.

### Nano-Electronics (Applied Quantum Mechanics):
Continuation of Quantum Mechanics with a focus on applications in next generation electronic devices. Exploration of simulation techniques used across Open Source projects on Nanohub, accompanied by a project to introduce students to open research, and contribution.

### Algorithms and Data Structures:
Course covered asymptotic and algorithm analysis, relationships and data structures, Sequential storage: Lists, queues, stacks, deques , Hash tables , Trees , Priority queues and heaps, Sort algorithms, Graphs and graph algorithms, Algorithm design techniques, Complexity classes and NP completeness.


## Awards

### Autodesk Capstone Software Design Award
University of Waterloo (Winter 2017)

### Baylis Medical Capstone Design Award
University of Waterloo (Fall 2016)

### NormEsch Entrepreneurial Capstone Award
University of Waterloo (Winter 2017)

### Velocity Fund 25K
University of Waterloo (Summer 2015)

### Engineers of the Future Trust
University of Waterloo (Fall 2016)

### Norman Esch ECOOP Award
University of Waterloo (Spring 2015)

### Excellence in the Sciences
BC Science Association and BCIC (2012)

### Presidents Scholarship
University of Waterloo (2012)

### Best in Fair
District Science Fair (2012)

### HKVCA Cross-Canada Wide Writing Contest
Second Place (2011)

### Bronze Award in the National Science Fair
Charlottetown (2012) and Toronto (2011)

### Best Rhythm Section Player
BC Interior Jazz Festival (2011)

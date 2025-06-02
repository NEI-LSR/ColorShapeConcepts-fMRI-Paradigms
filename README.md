# ColorShapeConcepts-fMRI-Paradigms

Functional MRI paradigms used in "The representation of object concepts across the brain". 

Each paradigm directory contains a main runner script, additional helper scripts and/or csvs defining block orders when applicable, and a 'Stimuli' folder containing stimuli presented in the paradigm. All scripts are run in MATLAB (9.12) and require Psychtoolbox for stimulus presentation. They interface with our local eye tracking and reward delivery systems through a Data Acquisition (DAQ) card, see DAQ.m; DAQ can be set to debug mode at the top of each runner script in order to run the paradigm ignoring the DAQ system. 

### Paradigms
- ActiveTask-ShapeColor4AFC
	- Described in methods section: Active task: Engagement of the learned color-shape conceptual primitives
	- menu.m is the runner script
- PassiveTask1-ShapeColorBlock
	- Described in methods section: Passive-viewing task 1: fMRI signals related to the color association of colorless color-associated shapes
	- ShapeColor.m is the runner script
- PassiveTask2-CongruencyBlock
	- Described in methods section: Passive-viewing task 2: fMRI signals related to color-shape binding
	- Congruency.m is the runner script

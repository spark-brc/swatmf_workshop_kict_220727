### **Workshop title:** SWAT-MODFLOW Workshop
#### **Date:** July 27-29, 2022
#### **Instructor:** Seonggyu Park, Texas A&M AgriLife Research
<u>**Overview:**</u>
This workshop aims to teach the fundamental principle and structure of a widely used integrated model, SWAT-MODFLOW, with hands-on exercises for use in assessing spatio-temporal patterns of water resources and fluxes. It will also cover general procedures of model development, implementation, evaluation, and optimization.

<u>**Course Objectives:**</u>
Upon successful completion of this workshop, students will be able to (1) understand the fundamental principles of each model (SWAT, MODFLOW, and SWAT-MODFLOW); (2) develop a SWAT-MODFLOW model; (3) perform a simulation with various scenarios; (4) evaluate and visualize simulation results; and (5) perform model optimization. Students will learn to work with a graphical user interface for SWAT-MODFLOW (QSWATMOD )and an automatic optimization framework with Jupyter notebooks.

<u>**Course Preparation:**</u>
Please bring a laptop running Windows OS (higher than Windows 7, preferably) to use for the workshop exercises. You will be contacted by the instructor with files to download prior to the course.

* <u>**Pre-requisites (nice to have; not required):**</u>
	* Basic understanding of Python
	- Basic understanding of Jupyter Notebook
	- Basic understanding of SWAT

- <u>**Instructions for Students:**</u>
	1. The mathematics and theory
	2. Learning by doing
	3. Please speak up! Everyone learns from discussion
	4. Work in pairs
	5. Python, GUIs, and all that

- <u>**Session content and schedule:**</u>
	1. Day 1 - First Session -- SWAT-MODFLOW-RT3D
		- Introduction to SWAT-MODFLOW-RT3D (3 hours)
			- SWAT (skipped if not necessary)
			- MODFLOW & RT3D
			- SWAT-MODFLOW-RT3D Linking Process
		- Setting up Simulation (4 hours)
			- Set Up, Run, View
		- QGIS & QSWATMOD Installations (30 mins)
		- Q&A Session (30 mins)

	2. [Day 2  -  Second Session -- QSWATMOD](https://github.com/spark-brc/QSWATMOD2)
		- Exercise with QSWATMOD (5 hours)
			- Description of QSWATMOD
			- Create a MODFLOW model
			- Create an RT3D model
			- Prepare an existing SWAT model
			- Link 3 different models
			- Set up the configuration of the model simulation and run the model
			- Visualize and analyze hydrology outputs
			- Visualize and analyze water quality outputs
		- SWAT-MODFLOW scenarios and additional QSWATMOD functions (2 hours)
			- Irrigation pumping
			- SWAT-MODFLOW model evaluation
		- Q&A Session (30 mins)

	3. [Day 3  - Third Session -- Optimization Framework](https://github.com/spark-brc/swatmf_pest_zon)
		- Work with SWAT-MODFLOW on your study area (2 hours)
			- Apply the SWAT-MODFLOW model to your study area
				- Bring your existing SWAT model and start from there.
		- Exercise with SWAT-MODFLOW Optimization Framework (5 hours)
			- Anaconda & swatmf python package Installations
			- Description of Framework
			- Introduction to Jupyter notebook and Python language (skipped if not necessary) (1 hour)
			- Introduction to Parameter ESTimation Utility (PEST)
			- Create PEST inputs with a pre-processing framework (create template files)
			- Extract simulation outputs with a post-processing framework (create instruction files)
			- Run PEST & parallel processing
			- Analyze results
		- Q&A Session (30 mins)
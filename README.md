# CS610-Programming-Assignment-1-QueueSim-Azkya-Said
Azkya Said programming assignment 1 for data structures and algorithms (Ali Milli) 
Queue Simulation Report

Overview

This Python code simulates different queuing scenarios to compare their efficiency in serving customers. It models service stations with varying queue structures (single queue vs. multiple queues) and customer assignment strategies (random, round-robin, shortest queue). The simulation aims to evaluate the impact of these choices on various performance metrics, such as average waiting time, maximum waiting time, and service station utilization.

—Open "Qsim results" to view the results, and “qsimsetup" to view the code. Make sure the two files remain in the same folder once it is unzipped.—

Setup
Option 1: Local Setup
Install Python: If you don't have Python installed, download and install it from the official website: https://www.python.org/downloads/
Install Jupyter Notebook: Open your terminal or command prompt and install Jupyter Notebook using pip:
	pip install notebook

Run Jupyter Notebook: Start Jupyter Notebook by typing:
	
	jupyter notebook

This will open Jupyter in your web browser, where you can create a new notebook or open the provided “Qsimresults” notebook to run the simulation.

Option 2: Google Colaboratory
	1	Open Google Colab: Go to https://colab.research.google.com/
	2	Create a New Notebook: Click on "File -> New Notebook" to create a blank notebook.
	3	Copy and Paste Code: Copy the code from “qsimsetup" and “Qsimresults” paste it into the Colab notebook.
	4	Run the Notebook: Execute the cells in the notebook to run the simulation.
 
Code Structure

Imports and Classes:
	◦	random: Used for generating random values for customer arrivals and service times.
	◦	C (Customer): Represents a customer with ID, arrival time, and service time.
	◦	Q (Queue): Implements a simple queue data structure for managing customers.
	◦	SS (ServiceStation): Represents a service station with ID, customers served, and remaining service time for the current customer.
Simulation Functions:
	◦	arrival(n) - #An arrival function for a new customer arriving once every n minutes
	◦	servicet(s) - #A service time function with average service time of s
	◦	sim1: Simulates a single queue system with three service stations.
	◦	sim2: Simulates three separate queues with random customer assignment.
	◦	sim3: Simulates three queues with round-robin customer assignment.
	◦	sim4: Simulates three queues with customers assigned to the shortest queue.


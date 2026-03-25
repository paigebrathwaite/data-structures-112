ClimateEconJustice

This project analyzes climate, health, and economic data across U.S. communities using a layered linked-list structure organized by state, county, and community. It reads data from CSV files, builds a three-level data model, and supports searching and analysis based on environmental and demographic factors. The project focuses on working with structured datasets, custom linked data structures, and community-level comparisons related to climate and environmental justice.

Java files
	•	ClimateEconJustice.java — Main program logic for building and analyzing the state, county, and community linked structure.
	•	StateNode.java — Node class representing a state in the first level of the linked structure.
	•	CountyNode.java — Node class representing a county in the second level of the linked structure.
	•	CommunityNode.java — Node class representing a community and its associated dataset information.
	•	Data.java — Stores the climate, health, and demographic values for each community.
	•	Driver.java — Runs the project and provides a way to test the program.
	•	StdIn.java — Input helper class.
	•	StdOut.java — Output helper class.

ForensicAnalysis

This project builds a forensic DNA analysis system using a binary search tree to store and organize DNA profiles. It reads genetic data, creates profiles made of STR patterns, compares unknown DNA sequences against stored profiles, and supports profile lookup and analysis. The project combines trees, file input, and biological data processing to simulate a simplified forensic identification system.

Java files
	•	ForensicAnalysis.java — Main program logic for building the DNA profile database and running forensic analysis operations.
	•	Profile.java — Represents a person’s DNA profile and stores their STR data.
	•	STR.java — Stores an STR sequence and its number of occurrences.
	•	TreeNode.java — BST node class used to store names and DNA profiles.
	•	Queue.java — Queue implementation used for traversal or supporting operations.
	•	Driver.java — Runs and tests the forensic analysis system.
	•	StdIn.java — Input helper class.
	•	StdOut.java — Output helper class.

GameOfLife

This project implements Conway’s Game of Life, a cellular automaton where cells live, die, or reproduce based on their neighbors. The program reads grid configurations, simulates future generations, and tracks how patterns evolve over time. It combines 2D arrays, grid-based logic, simulation rules, and supporting classes for board display and interaction.

Java files
	•	GameOfLife.java — Main simulation class that stores the board and applies the Game of Life rules.
	•	Board.java — Handles board-related behavior and representation.
	•	WeightedQuickUnionUF.java — Union-find structure used for connectivity-related operations.
	•	Driver.java — Runs the project and manages testing or interaction.
	•	StdDraw.java — Graphics helper used to draw the board.
	•	Button.java — UI helper for clickable controls.
	•	Rectangle.java — Utility class for rectangular drawing or layout.
	•	Text.java — Utility class for on-screen text.
	•	Page.java — Organizes display pages or screens for the interface.
	•	StdIn.java — Input helper class.
	•	StdOut.java — Output helper class.

RUHungry

This project simulates a restaurant management system that handles menu items, ingredients, stock, transactions, customer seating, donations, and restocking. It uses multiple custom classes to model restaurant operations and process orders from input files. The project focuses on object-oriented design, file-driven simulation, and managing linked data structures for a realistic restaurant workflow.

Java files
	•	RUHungry.java — Main restaurant simulation class that manages orders, inventory, and transactions.
	•	Menu.java — Stores and manages the restaurant menu.
	•	Dish.java — Represents an individual dish and its details.
	•	Ingredient.java — Represents an ingredient used in menu items and stock tracking.
	•	MenuNode.java — Node class used for menu-linked structures.
	•	StockNode.java — Node class used for ingredient stock management.
	•	TransactionNode.java — Node class used to store restaurant transaction history.
	•	TransactionData.java — Stores information about individual transactions.
	•	People.java — Represents customer information.
	•	Party.java — Represents a group of guests for seating and service.
	•	Queue.java — Queue implementation used in restaurant operations.
	•	RUHungryTester.java — Test driver for running and checking the program.
	•	StdIn.java — Input helper class.
	•	StdOut.java — Output helper class.

Spiderverse

This project models a Spider-Verse-inspired multiverse system using graphs, hash tables, and pathfinding algorithms. It works with dimensions, anomalies, canon events, and character movement across connected universes. The program includes tasks such as building clusters, detecting anomalies, tracking Spot, sending characters home, and computing paths through the multiverse, making it a strong graph and data-structures project.

Java files
	•	Clusters.java — Builds and manages dimension clusters using hashing and rehashing logic.
	•	Collider.java — Creates the graph or adjacency structure connecting dimensions.
	•	CollectAnomalies.java — Finds and processes anomalies across dimensions.
	•	TrackSpot.java — Tracks Spot’s movement through the multiverse.
	•	GoHomeMachine.java — Sends anomalies back to their home dimensions and generates reports.
	•	SaveMiles.java — Handles one of the project’s mission or traversal tasks related to Miles.
	•	CanonEvent.java — Stores canon-event-related data.
	•	Graph.java — Graph implementation used for traversal and pathfinding.
	•	WeightedGraph.java — Weighted graph implementation used for shortest-path calculations.
	•	PersonData.java — Stores character-related information such as name and dimension data.
	•	PersonNode.java — Node class for linked character data.
	•	HashNode.java — Node class used in the hash-table structure for dimensions.
	•	HashNodeData.java — Stores data associated with hash-table entries.
	•	AnomalyData.java — Stores information about anomalies and their paths.
	•	MissionReport.java — Stores mission result data and return-path information.
	•	StdIn.java — Input helper class.
	•	StdOut.java — Output helper class.

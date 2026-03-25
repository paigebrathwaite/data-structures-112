ClimateEconJustice

This project analyzes climate, health, and economic data across U.S. communities using a layered linked-list structure organized by state, county, and community. It reads data from CSV files, builds a three-level data model, and supports searching and analysis based on environmental and demographic factors. The project focuses on working with structured datasets, custom linked data structures, and community-level comparisons related to climate and environmental justice.
	1.	ClimateEconJustice.java: Main program logic for building and analyzing the state, county, and community linked structure.
	2.	StateNode.java: Node class representing a state in the first level of the linked structure.
	3.	CountyNode.java: Node class representing a county in the second level of the linked structure.
	4.	CommunityNode.java: Node class representing a community and its associated dataset information.
	5.	Data.java: Stores the climate, health, and demographic values for each community.
	6.	Driver.java: Runs the project and provides a way to test the program.
	7.	StdIn.java: Input helper class.
	8.	StdOut.java: Output helper class.

ForensicAnalysis

This project builds a forensic DNA analysis system using a binary search tree to store and organize DNA profiles. It reads genetic data, creates profiles made of STR patterns, compares unknown DNA sequences against stored profiles, and supports profile lookup and analysis. The project combines trees, file input, and biological data processing to simulate a simplified forensic identification system.
	1.	ForensicAnalysis.java: Main program logic for building the DNA profile database and running forensic analysis operations.
	2.	Profile.java: Represents a person’s DNA profile and stores their STR data.
	3.	STR.java: Stores an STR sequence and its number of occurrences.
	4.	TreeNode.java: BST node class used to store names and DNA profiles.
	5.	Queue.java: Queue implementation used for traversal or supporting operations.
	6.	Driver.java: Runs and tests the forensic analysis system.
	7.	StdIn.java: Input helper class.
	8.	StdOut.java: Output helper class.

GameOfLife

This project implements Conway’s Game of Life, a cellular automaton where cells live, die, or reproduce based on their neighbors. The program reads grid configurations, simulates future generations, and tracks how patterns evolve over time. It combines 2D arrays, grid-based logic, simulation rules, and supporting classes for board display and interaction.
	1.	GameOfLife.java: Main simulation class that stores the board and applies the Game of Life rules.
	2.	Board.java: Handles board-related behavior and representation.
	3.	WeightedQuickUnionUF.java: Union-find structure used for connectivity-related operations.
	4.	Driver.java: Runs the project and manages testing or interaction.
	5.	StdDraw.java: Graphics helper used to draw the board.
	6.	Button.java: UI helper for clickable controls.
	7.	Rectangle.java: Utility class for rectangular drawing or layout.
	8.	Text.java: Utility class for on-screen text.
	9.	Page.java: Organizes display pages or screens for the interface.
	10.	StdIn.java: Input helper class.
	11.	StdOut.java: Output helper class.

RUHungry

This project simulates a restaurant management system that handles menu items, ingredients, stock, transactions, customer seating, donations, and restocking. It uses multiple custom classes to model restaurant operations and process orders from input files. The project focuses on object-oriented design, file-driven simulation, and managing linked data structures for a realistic restaurant workflow.
	1.	RUHungry.java: Main restaurant simulation class that manages orders, inventory, and transactions.
	2.	Menu.java: Stores and manages the restaurant menu.
	3.	Dish.java: Represents an individual dish and its details.
	4.	Ingredient.java: Represents an ingredient used in menu items and stock tracking.
	5.	MenuNode.java: Node class used for menu-linked structures.
	6.	StockNode.java: Node class used for ingredient stock management.
	7.	TransactionNode.java: Node class used to store restaurant transaction history.
	8.	TransactionData.java: Stores information about individual transactions.
	9.	People.java: Represents customer information.
	10.	Party.java: Represents a group of guests for seating and service.
	11.	Queue.java: Queue implementation used in restaurant operations.
	12.	RUHungryTester.java: Test driver for running and checking the program.
	13.	StdIn.java: Input helper class.
	14.	StdOut.java: Output helper class.

Spiderverse

This project models a Spider-Verse-inspired multiverse system using graphs, hash tables, and pathfinding algorithms. It works with dimensions, anomalies, canon events, and character movement across connected universes. The program includes tasks such as building clusters, detecting anomalies, tracking Spot, sending characters home, and computing paths through the multiverse, making it a strong graph and data-structures project.
	1.	Clusters.java: Builds and manages dimension clusters using hashing and rehashing logic.
	2.	Collider.java: Creates the graph or adjacency structure connecting dimensions.
	3.	CollectAnomalies.java: Finds and processes anomalies across dimensions.
	4.	TrackSpot.java: Tracks Spot’s movement through the multiverse.
	5.	GoHomeMachine.java: Sends anomalies back to their home dimensions and generates reports.
	6.	SaveMiles.java: Handles one of the project’s mission or traversal tasks related to Miles.
	7.	CanonEvent.java: Stores canon-event-related data.
	8.	Graph.java: Graph implementation used for traversal and pathfinding.
	9.	WeightedGraph.java: Weighted graph implementation used for shortest-path calculations.
	10.	PersonData.java: Stores character-related information such as name and dimension data.
	11.	PersonNode.java: Node class for linked character data.
	12.	HashNode.java: Node class used in the hash-table structure for dimensions.
	13.	HashNodeData.java: Stores data associated with hash-table entries.
	14.	AnomalyData.java: Stores information about anomalies and their paths.
	15.	MissionReport.java: Stores mission result data and return-path information.
	16.	StdIn.java: Input helper class.
	17.	StdOut.java: Output helper class.

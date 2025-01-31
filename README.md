# Berlin-Metro-Network-Visualisation
🏙️ Berlin Metro Network Analysis
This project models the Berlin Metro Network using NetworkX, allowing visualization and analysis of metro connections, transfer points, and shortest paths between stations.

📌 Project Overview
Objective: Build a graph-based representation of Berlin’s metro system to analyze connectivity and route efficiency.

Methods Used:

Graph theory concepts (nodes & edges)

Network connectivity check

Visualization with matplotlib

Distance-based edge attributes

🛠️ Technologies & Libraries
This project is implemented in Python and uses the following libraries:

🚇 Graph Analysis: networkx

📊 Visualization: matplotlib

📌 Data Structures: dict, list, set

📂 Berlin Metro Lines Included
Line	Major Stations
U1	Krumme Lanke, Rathaus Steglitz, Fehrbelliner Platz, Nollendorfplatz, Kurfürstendamm
U2	Pankow, Eberswalder Str., Alexanderplatz, Mohrenstr., Potsdamer Platz
U3	Krumme Lanke, Dahlem-Dorf, Thielplatz, Freie Universität, Rüdesheimer Platz
U4	Nollendorfplatz, Viktoria-Luise-Platz, Bayerischer Platz, Innsbrucker Platz, Rathaus Schöneberg
U5	Hönow, Tierpark, Alexanderplatz, Brandenburger Tor, Hauptbahnhof
Connections & Transfers
Key Transfer Stations: Alexanderplatz, Nollendorfplatz, Krumme Lanke

Inter-line Connections:

Nollendorfplatz ↔ Fehrbelliner Platz (U1 & U4)

Alexanderplatz ↔ Potsdamer Platz (U2 & U1)

Alexanderplatz ↔ Kurfürstendamm (U2 & U1)

Alexanderplatz ↔ Brandenburger Tor (U2 & U5)

Krumme Lanke ↔ Dahlem-Dorf (U1 & U3)

📊 Results
Network Connectivity: The metro network is fully connected, meaning there is a path between any two stations.

Visualization: The metro network is visualized with stations color-coded by line and distances between stations labeled on the edges.

Key Insights:

Transfer Stations: Alexanderplatz, Nollendorfplatz, and Krumme Lanke are critical hubs for transferring between lines.

Longest Distance: The longest distance between consecutive stations is between Hönow and Tierpark on the U5 line (3.8 km).

Shortest Distance: The shortest distance between consecutive stations is between Alexanderplatz and Mohrenstr. on the U2 line (1.1 km).

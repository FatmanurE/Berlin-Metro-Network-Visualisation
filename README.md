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

📊 Graph Analysis
Check Connectivity: Determines if all stations are reachable from each other.
Add Distance Attributes: Edge weights represent station-to-station distances in km.
Visualization Features:
Color-coded metro lines
Highlighted transfer stations
Labels using station initials

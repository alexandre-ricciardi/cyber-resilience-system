# cyber-resilience-system

This system aims to detect, and take appropriate actions upon cyber attacks.

The system is also able to evaluate impact of an attack on IS, with a network map.

The system is composed of :

* Network traffic probes on each node of the information system to measure inbound and oubound traffic.

* A timeline database to store the traffic of each node.

* Then a graph processing to compare network traffic schemes among different periods.

* AI can also process those graphs to detect delta and uncommon traffic during periods.

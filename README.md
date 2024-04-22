# cyber-resilience-system

This system aims to detect, and take appropriate actions upon cyber attacks.

The system is also able to evaluate impact of an attack on IS, with a network map.

The system is composed of :

* Network traffic probes on each node of the information system to measure inbound and oubound traffic.

* A timeline database to store the traffic of each node.

* Then a graph processing to compare network traffic schemes among different periods.
  * The main idea of the process if to integrate network traffic map in a graph across different timeframes,
  * The whole point is to determine relevant timeframes and threasholds for uncommon event detection

* AI can also process those graphs to detect delta and uncommon traffic during periods.
  * Graph representing net traffic across different periods are processed by an NN with convolution of graph (and not graphs embedding as usually processed)

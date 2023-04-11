# NFA to DFA
### Course: Formal Languages & Finite Automata
### Author: Telug Anatolie FAF-212
----

## Theory of Infinite Automata
## Objectives:
Understand what an automaton is and what it can be used for.
Provide a function in your grammar type/class that could classify the grammar based on Chomsky hierarchy.
Implement conversion of a finite automaton to a regular grammar.
Determine whether your FA is deterministic or non-deterministic.
Implement some functionality that would convert an NDFA to a DFA.
Represent the finite automaton graphically using external libraries, tools or APIs to generate the figures/diagrams (optional). The program should gather and send the data about the automaton, and the lib/tool/API should return the visual representation.
## Screenshots of working code:
![dfa](https://user-images.githubusercontent.com/113394083/231146346-96184649-6cd4-464d-b0a8-a05b23f537cd.png)
![20230411_042717](https://user-images.githubusercontent.com/113394083/231146859-0240c368-1a05-4b66-bff1-6f0ab1d3a171.png)
![20230411_042700](https://user-images.githubusercontent.com/113394083/231146351-bdf1d404-de86-4903-8fc7-2404d6bd8404.png)

## Description of Code:
The Python code in this laboratory work provides several functions that implement various operations on finite automata. The code is designed to be easy to understand and modify, making it a valuable resource for anyone interested in learning about automata theory or working with automata in Python. The code uses the Graphviz binary and Graphviz from pip to visualize DFAs. The implemented functions include classifying a context-free grammar based on Chomsky hierarchy, converting a finite automaton to a regular grammar, determining whether an FA is deterministic or non-deterministic, and converting an NDFA to a DFA. Additionally, the code can represent finite automata graphically, using external libraries, tools or APIs such as Graphviz.
## Description, conclusion:
Converting an NDFA to a DFA is an important process in the study of finite automata, as it allows us to analyze and simplify the behavior of a given automaton. The conversion process involves eliminating the non-deterministic behavior of an NDFA and transforming it into a deterministic automaton. This results in a simpler and more efficient automaton that can be easily analyzed and understood. Determinism is an important property of finite automata, as it ensures that the automaton has a unique and well-defined behavior for any given input.
## References:
    Hopcroft, John E., and Jeffrey D. Ullman. Introduction to Automata Theory, Languages, and Computation. Addison-Wesley, 1979.
    Sipser, Michael. Introduction to the Theory of Computation. Cengage Learning, 2012.
    "Automata Theory." GeeksforGeeks, https://www.geeksforgeeks.org/automata-theory/.
    "Python | Automata Theory." GeeksforGeeks, https://www.geeksforgeeks.org/python-automata-theory/.
    "Graphviz - Graph Visualization Software." Graphviz, https://graphviz.org/.

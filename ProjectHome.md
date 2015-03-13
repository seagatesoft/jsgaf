JSGAF is a simple genetic algorithm framework written in Java programming language.

It's designed to separate different components/process in genetic algorithm like chromosome encoding (include it's fitness functions, crossover methods, mutation methods), selection method, and replacement scheme.

JSGAF provide a GeneticAlgorithmRunner that will run the genetic algorithm iterations with any chromosome encoding (along with it's fitness functions, crossover methods, mutation methods), selection methods, and replacement schemes.

Currently, this framework provides two selection method: Brindle's Selection and Roulette Wheel Selection.

It also provides Replace Worst as replacement scheme and tree chromosome encoding as chromosome encoding.

The others chromosome encodings (along with it's fitness functions, crossover methods, mutation methods), selection methods, and replacement schemes is still under development.

If you want to try this framework, just edit the AppConsole.java file. There you can find out how to use JSGAF.
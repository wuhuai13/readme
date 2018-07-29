# Maze Render

A maze rendering java console project takes a Road Grid and its connectivity as input command string, and print a maze as output string 

### Prerequisites

JDK (Java SE Development Kit). To download the latest version of JDK, go to [JDK downloads](http://www.oracle.com/technetwork/java/javase/downloads/index-jsp-138363.html#javasejdk).

### Compiling and Runing

Compile all plain text .java sources (javac utility comes with JDK):

```
javac *.java
```

Run the program:

```
java Main
```

Type the two -line input command, for example:
* The first line represents a Road Grid, where a 3 x 3 Road Grid can generate a 7 x 7 Render Grid (walls around road cells)
* The second line represents the connectivity of Road Grid, where cell[0,1] is connected with cell[0,2], and cell[0,0] is connected with cell[1,0]

```
3 3
0,1 0,2;0,0 1,0
```

The output (corresponds to the above example), where :

```
[W] [W] [W] [W] [W] [W] [W]
[W] [R] [W] [R] [R] [R] [W]
[W] [R] [W] [R] [W] [W] [W]
[W] [R] [W] [R] [W] [R] [W]
[W] [W] [W] [W] [W] [W] [W]
[W] [R] [W] [R] [W] [R] [W]
[W] [W] [W] [W] [W] [W] [W]
```

## Running the Tests

After the program is compiled, type this to run test cases:
```
java Main test
```

A sample output will be:
```
Valid input command test cases: 5 total, 5 succeed, 0 fail
Incorrect command format test cases: 7 total, 7 succeed, 0 fail
Invalid number format test cases: 7 total, 7 succeed, 0 fail
Number out of range test cases: 6 total, 6 succeed, 0 fail
Maze format error test cases: 5 total, 5 succeed, 0 fail
Maze rendering test cases: 5 total, 5 succeed, 0 fail
```

## Authors

* **Huai Wu** - *Initial work* 

## License

This project is licensed under the MIT License

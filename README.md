# Maze Render

A maze rendering java console project takes a cell road grid and a relationship of cell connectivity as input command string, and print a maze as output string 

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
The first line represents the road cells in the maze,where "3 3" corresponds to a 7 x 7 Render Grid
The second line represents the connectivity between road cells, where cell[0,1] and cell[0,0] are connected with cell[0,2] and cell[1,0]

```
3 3
0,1 0,2;0,0 1,0
```

The output (for the above example), where :

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

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds


## Authors

* **Huai Wu** - *Initial work* 

## License

This project is licensed under the MIT License

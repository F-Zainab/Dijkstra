# Dijkstra

## Generate Test Data
```
1. Compile: javac GenerateData.java
2. Run: javac GenerateData // wait some time to the program to be end
```

## Run Dijkstra
```
1. Compile: javac ParallelizedVersion.java
2. Run: java ParallelizedVersion // wait some time
```

## About
1. ParallelizedVersion.java is the parallelized version of Dijkstra.
2. SerializedVersion.java is the serialized version of Dijkstra.
3. Utils.java includes many utility methods, such as the DataGenerator.


## TestData Format

`the format for TestData1, TestData2, TestData3`

N, start, end, targetDistance

vertex1, vertex2, disBetweenVertice

vertex1, vertex2, disBetweenVertice

...

vertex1, vertex2, disBetweenVertice

`the format for LargeTestData*`

`Every LargeTestData has N * (N - 1) edges`

N, start, end

vertex1, vertex2, disBetweenVertice

vertex1, vertex2, disBetweenVertice

...

vertex1, vertex2, disBetweenVertice
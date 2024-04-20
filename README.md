# Java Stream API Basics

This repository contains Java code demonstrating the basic usage of various methods in the Stream API. The Java Stream API provides a set of classes and interfaces for processing data in a declarative and functional way. These examples cover common operations such as filtering, mapping, sorting, and more.

## Getting Started

To run the code examples, make sure you have Java installed on your system. You can compile and execute the Java files using any Java compiler or IDE.

## Overview of Examples

The code in `Main.java` demonstrates the usage of the following Stream API methods:

- `Stream.ofNullable`: Creates a stream with a single element if the element is non-null.
- `Stream.iterate`: Generates an infinite stream by applying a function to the previous element.
- `Collectors.collectingAndThen`: Performs another action on the result of a collector.
- `Stream.takeWhile` and `Stream.dropWhile`: Takes or drops elements from the beginning of the stream until a condition is met.
- `Collectors.teeing`: Performs two different collectors on the same input elements, then merges their results.
- `Stream.concat`: Concatenates two streams into one.
- `Collectors.partitioningBy`: Partitions the input elements into two groups according to a predicate.
- `IntStream.range`: Generates a sequential ordered IntStream from startInclusive to endExclusive.
- `Stream.map`: Transforms each element of the stream using a function.
- `Stream.filter`: Filters elements based on a predicate.
- `Stream.sorted`: Sorts the elements of the stream.
- `Stream.distinct`: Returns a stream consisting of the distinct elements of the stream.
- `Stream.reduce`: Combines the elements of the stream into a single result using a binary operator.

Each method is demonstrated with a brief explanation and example code.

# MoveToFront Algorithm in Java

This repository contains an implementation of the Move-to-Front (MTF) algorithm in Java. The MTF algorithm is a self-organizing list algorithm that reorders elements dynamically to improve search efficiency.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [License](#license)

## Description

The Move-to-Front algorithm is used to encode and decode data sequences based on their frequency of access. When an element is accessed, it is moved to the front of the list, which makes subsequent accesses to the same element faster if they are frequent.

This project includes:
- An implementation of the Move-to-Front encoding and decoding algorithm.
- Unit tests to verify the correctness of the implementation.

## Features

- **Efficient Encoding and Decoding:** The algorithm efficiently handles sequences of data, improving access times for frequently accessed elements.
- **Self-Organizing List:** The list dynamically adjusts based on element access patterns.
- **Simple and Clean Code:** The implementation is straightforward and easy to understand.

## Installation

To use this project, you need to have Java installed on your system. Follow these steps to set up the project:

1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```sh
   cd MoveToFront
   ```

## Usage

To run the Move-to-Front algorithm, compile and execute the `MoveToFront.java` file. Here are the steps:

1. Compile the Java file:
   ```sh
   javac MoveToFront.java
   ```

2. Run the program:
   ```sh
   java MoveToFront
   ```

## Example

Here's an example of how to use the Move-to-Front algorithm in your Java code:

```java
public class Main {
    public static void main(String[] args) {
        String input = "example";
        MoveToFront mtf = new MoveToFront();
        
        String encoded = mtf.encode(input);
        System.out.println("Encoded: " + encoded);

        String decoded = mtf.decode(encoded);
        System.out.println("Decoded: " + decoded);
    }
}
```
Gradient Descent on 8051 Microcontroller (Assembly Language)

This project demonstrates the implementation of a fundamental optimization algorithm—gradient descent—on an 8051 microcontroller using Assembly language. While gradient descent is commonly associated with high-level machine learning frameworks, this project showcases how such algorithms can be executed on resource-constrained, low-level embedded systems without relying on any external libraries.

The goal was to minimize a simple cost function (e.g., a quadratic function) by applying the gradient descent update rule:

x_new = x_old - α·(df/dx)

All computations were implemented using fixed-point arithmetic and low-level bit manipulation, emphasizing precision control and efficiency in a memory-limited environment. This project served as a bridge between classical optimization theory and bare-metal embedded development.

Key Features:

Designed for the 8051 microcontroller platform

Entirely written in Assembly language

Implements gradient descent iteration logic manually

Emulates machine learning computation on an 8-bit microcontroller

Demonstrates fixed-point math and manual optimization in embedded systems

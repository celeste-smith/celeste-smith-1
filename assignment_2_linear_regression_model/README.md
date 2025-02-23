# Linear Regression Model in Rust

## Introduction

This project implements a simple AI model for linear regression using Rust and the Burn library. The goal is to predict the output of the function:
using synthetic data for training. The model is designed to learn this relationship by minimizing the error between predictions and actual values. The project follows the specifications provided in the assignment, ensuring compatibility with Burn v0.16 and other required dependencies.

## Approach

### 1. Setting Up the Environment

Installed Rust and Rust Rover IDE.
Created a new Rust project using Cargo.
Updated Cargo.toml to include the required dependencies.
Connected the project to GitHub for version control.

### 2. Generating Synthetic Data

Used the rand crate to generate random x values in the range [0,10].
Computed y using the equation y = 2x + 1, adding small random noise to simulate real-world data.

### 3. Defining the Linear Regression Model

Implemented a simple model using the burn library.
Created a LinearModel struct with a single linear layer (Linear::new(1,1)).
Implemented the forward pass method to compute predictions.



## Results and Evaluation
I am a little confused here. 


## Reflection on Learning Process

### Challenges Faced:

I struggled quite a lot with this assignment as I never used Rust before. Understanding the syntax, memory management, and overall project structure was quite challenging. I had to do extensive research using AI tools such as ChatGPT and Google. While I managed to complete the assignment, I still feel that I need more time to fully grasp Rust and its ecosystem. I also struggled to connect the project to GitHub for version control.

### Lessons Learned:

Learned the basics of Rust and how to structure a simple machine learning project, even through the struggles. 
Improved familiarity with version control using Git and GitHub.

### Future Learning Goals:

Spend more time practicing Rust fundamentals.
Explore more advanced machine learning concepts in Rust.
Learn about Rust’s ownership model and memory safety features in greater depth.

### Resources Used:

Rust Official Documentation
Burn Library Docs
GitHub Documentation
Various Rust community forums and AI-related tutorials

Conclusion

This project provided a foundational understanding of using Rust for AI/ML tasks. By following a structured approach, I was able to implement and train a simple linear regression model successfully. However, I recognize that Rust is a complex language, and I will need to invest more time in learning it properly. Future improvements could include expanding to polynomial regression or using different activation functions.

# Prouster (Version 0.3)
## A neural network to generate writing prompts

This project is a python-based application for inviduals who may be experiencing Creative Block.
Creative Block is commonly defined as a period of time when ideas and creative thinking seem to run dry. It is a problem that can manifest itself in different ways:

* Technology: Impaired ability to think out-of-the-box to deliver solutions.
* Artists: Lack of inspiration to produce new material.
* Individuals:  Depression & Anxiety, Demotivation

### Motivation:
The motivation for this project was to provide a plausible solution to creative block, and the general inability for individuals to brainstorm or improvise new ideas. The most obvious example of this problem is writer's block, and as such my project targets that dilemma. 

#### Stimulate creative thinking!
Prouster is a Deep Learning based writing prompt generator designed to form interesting ideas for users to respond to or develop upon.
The website for Prouster currently generates text from a Recurrent Neural Net to create unique writing prompts that users can borrow as inspiration for new stories, monologues, or editorials. 
The project is named after the Proust Questionnaire, which is a book of prompts designed to stimulate introspective creative thinking in individuals.

### Potential Use Cases:
It is an exciting product that can be used for various purposes:
* Interactive Brainstorming
* Writing Contests
* Improvised Response
* English Teaching
* Beneficial to Mental Health

### Data:

#### Sources

* Writing Prompts from Reddit
* * https://www.reddit.com/r/datasets/comments/8z1g24/rwritingprompts_dataset_for_language_models/

* Oblique Strategies
* * https://github.com/tomgp/Oblique-Strategies/tree/master/data

#### Tags
* WP - General Writing Prompt
* OS - Oblique Strategies
* CW - Constrained Writing
* * Example: Write without using pronouns.
* TT - Theme Thursday
* * Example: Detective Stories
* EU - Established Universe
* * Example: Harry Potter Prompts.

### Modeling:
Different approaches to recurrent Neural Networks were used to build Prouster, including:

* PyTorch, Character-Level Model
* Keras, Word-Level & Character-Level Model

These models were trained using kernels provided by Kaggle. 

### Results:
![Demo](https://raw.githubusercontent.com/ander265/prouster/master/Prompt.png)


### Backlog/Next Steps:
* Subsequent prompts based on user response

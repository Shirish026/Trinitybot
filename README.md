# Trinitybot - Thesis Paper

Welcome to the repository for my thesis paper! This repository contains all the code, data, and documentation associated with my research on Trinity Bot, Trinity's AI Chatbot/Conversational agent.

## Abstract

This paper proposes an artificial intelligence chatbot designed to address the challenge
faced by the School of Engineering at Trinity College Dublin in responding to a large number of queries from prospective students. Through an extensive literature review, the chatbot was developed using the "Google Dialogflow ES" platform and a Python knowledge
base curator for the FAQ section, chosen for its powerful natural language understanding
capabilities. The design principles and technology development were formulated based on an
extensive feasibility study, which consisted of stakeholder research via interviews, presentations, consented phone recordings, Google forms, and an in-depth SWOT analysis.
The Dialogflow agent’s graphical user interface such as buttons, Trinity logos, and text
hyperlinks, provides an intuitive experience to its users. Additionally, a well-defined conversational flow Is implemented to guide users and provide relevant responses. The TrinityBot was hosted on Trinity Engineering’s servers and was rigorously tested to ensure its
functionality and accuracy. The AI chatbot’s capability was assessed using the 3-fold cross validation, and a modified confusion matrix was constructed subsequently, to evaluate the
performance of both the intent-matching methodology and the FAQ knowledge base component. The precision, recall, and F1 metrics were calculated for each methodology and
analyzed to determine the overall accuracy of the AI conversational agent. The proposed
TrinityBot has shown satisfactory accuracy results and a brief potential future work is recommended at the end of the paper.

## Table of Contents

- [Introduction](#Introduction)
- [Literature Review](#Literature_Review)
- [Feasibility Study](#Feasibility_Study)
- [Technical Development](#Technical_Development)
- [Results](#Results)
- [Conclusion](#Conclusion)
- [Appendix](#Appendix)

## Installation of Chatbot Prototype mentioned in Thesis

1. Clone this repository to your local machine using the following command:
    ```shell
    git clone https://github.com/your-username/thesis-paper.git

2. Install the necessary dependencies by running the following command:
    ```shell
    pip install -r requirements.txt

3. Make sure you have Python 3.x installed. You can download Python from the official website:
https://www.python.org/downloads/

4. Open the cloned project in PyCharm IDE.

5. Navigate to `Settings > Project > Python Interpreter`.

6. PyCharm Interpreter will automatically detect the project's dependencies listed in the `requirements.txt` file.

7. PyCharm will prompt you to install the missing Python libraries. Click on the "Install" button to proceed with the installation.

8. However if PyCharm does not detect, you need to install the following Python libraries in the Python Interpreter:
- Library 1: Numpy
     ```shell
    pip install numpy

- Library 2: pandas
     ```shell
    pip install pandas

- Library 3: nltk 
     ```shell
    pip install nltk
     
- Library 4: torch 
     ```shell
    pip install torch

9. Ensure all the Python scripts are at one accessible location when accessing the chatbot

## Usage of Google Dialogflow mentioned in Thesis

### Prerequisites
Before you begin, ensure that you have the following prerequisites:

- A Google account
- Access to the Google Cloud Console via https://dialogflow.cloud.google.com/
     






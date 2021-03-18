# Risk Assessment Algorithms in the Criminal Justice System - An Ethical Investigation
### Khadija & Maddy

400-800 words total

**Project Update 1**

- This project will use [PyTorch](https://pytorch.org/) to create and test a fully connected neural network using [COMPAS](https://www.kaggle.com/danofer/compass?select=compas-scores-raw.csv) data on Florida defedants' input variables and the COMPAS score they received for either risk of violence, risk of recidivism, or risk of failure to appear. There are several variables used to calculate COMPAS scores so the inputs to our neural network will be 1-dimensional vectors of categorical string values for each individual featured in the database. The data will be trained to produce two distinct types of outputs. First, we will train and test the neural network on the COMPAS score the defendent received to try to approximate the COMPAS algorithm's behaviour. This algorithm will perform a regression to calculate a (semi) continuous score value. Second, we will again train the model using COMPAS scores as the label, but will test the model's accuracy in predicting the actual recidivism outcome after 2 years. This algorithm will perform classification into two categories (recidivized after 2 years or not) based on the likelihood of recidivism as defined by the COMPAS score.


**Intro Outline**

Introductory paragraph: Risk assessment algorithms are a tool used by the courts, usually judges and prosecutors, that implement neural networks to predict the probablity of a defendent repeating criminal activity based on a selection of individual attributes (demographics, criminal history, etc.).

Background paragraph: Although these algorithms are an attempt to minimize personal and institutional bias in the judicial system, the algorithms are based on historical recidivism data that *has* been influenced by unequal institutional systems. When the inputs to an algorithm are biased the outputs are sure to display the same biases regardless of the intent of the designers or users.
        
Transition paragraph: This paper evaluates the data, neural network design, results, and real-world applications of algorithms developed for risk assesment in the criminal justice space.
        
Details paragraph: Using outputs from the Correctional Offender Management Profiling for Alternative Sanctions (COMPAS) algorithm, we determined patterns in the COMPAS scores assigned to defendent and tracked the accuracy of these scores with the recidivism status of the score's recipient.

Assessment paragraph: Our results find biases in a number of risk assesment algorithms used for the criminal justice system.

Ethical Implications:  Is it possible to create neural networks that resist the unjust biases of modern society? Do algorithms even have a place in determining justice, or are these decisions best left to human minds capable of empathy and compassion despite their biases?

**Lit Review**

- [Predicting Enemies by Ashley S. Deeks](https://www.jstor.org/stable/j.ctvw04b7q.14): This is a journal article detailing the different ways in which the predictive algorithms are used in the criminal justice system and how the military industrial complex is in works to adopt these tactics in their work. This article's goal is to show why it would be flawed to move forward as such, by showing how it is not working properly within the criminal justice system (using predictive policing and risk assessment algorithms as examples).

- [Predictive Algorithms and Criminal Sentencing by Angele Christi](https://www.jstor.org/stable/j.ctvw04b7q.14): This article analyzes how the criminal justice system relies on algorithms to determine sentences and criminality of people and areas. It does an in depth analysis of the ways in which the judges, prosecutors and such use these algorithms to suit their interests in court.

- [Understanding Risk Assessment instruments in Criminal Justic](https://www.brookings.edu/research/understanding-risk-assessment-instruments-in-criminal-justice/#:~:text=One%20class%20of%20algorithmic%20tools,an%20individual%20before%20their%20trial): This article provides an in depth analysis on risk assessment algorithms such as what tools are being used and what companies are making them. This article leans more towards trying to discuss how these algorithms could be fixed for the better.

- [Report on Algorithmic Risk Assessment Tool in US Criminal Justice System](https://www.partnershiponai.org/report-on-machine-learning-in-risk-assessment-tools-in-the-u-s-criminal-justice-system/): This report is by a nonprofit trying to establish best practices for AI technologies. It reports the serious shortcomings of risk assessment tools in the criminal justice systems through consultations with expert members and reviewing literature on risk assessment tools. It is a very thorough and detailed report.


State-of-the-art in Risk Assessment Algorithms: 

- Correctional Offender Management Profiling for Alternative Sanctions (COMPAS): assigns risk scores to defedants using historical data in a process that is partially kept private by the company
- Public Safety Assessment (PSA): uses a defendant's biographical information and criminal history to assign 3 risk scores - that they will be convicted for a new crime, that they will be convicted for a new violent crime, and that they will fail to appear in court.


Possible datasets:
- [COMPAS Algorithm](https://www.kaggle.com/danofer/compass?select=compas-scores-raw.csv) 
- [NYS Recidivism](https://www.kaggle.com/new-york-state/nys-recidivism-beginning-2008)



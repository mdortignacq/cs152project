# Risk Assessment Algorithms in the Criminal Justice System - An Ethical Investigation
### Khadija & Maddy

770/400-800 words total






**Introduction**

Risk assessment algorithms are a tool used by the courts, usually judges and prosecutors, that utilize neural networks to predict the probablity of a defendent repeating criminal activity based on a selection of individual attributes (demographics, criminal history, etc.). Although these algorithms are an attempt to minimize personal and institutional bias in the judicial system, the algorithms are based on historical recidivism data that *has* been influenced by unequal institutional systems. When the inputs to an algorithm are biased the outputs are sure to display the same biases regardless of the intent of the designers or users.

This paper evaluates the data, neural network design, results, and real-world applications of algorithms developed for risk assesment in the criminal justice space. A sampling of inputs and outputs for the Correctional Offender Management Profiling for Alternative Sanctions (COMPAS) algorithm are used to create and test a fully connected neural network to predict the likelihood of recidivism of criminal defendants in Florida. The data is trained to produce two distinct types of outputs. First, we train and test the neural network on the COMPAS score the defendent received to try to approximate the COMPAS algorithm's behaviour. COMPAS scores are given for either risk of violence, risk of recidivism, or risk of failure to appear. These scores are then meant to provide an impartial evaluation of a defendent's risk to members of the court such as the deciding judge or prosecutor. Second, we again train the model using COMPAS scores as the label, but instead test the model's accuracy in predicting the actual recidivism outcome data after 2 years. 

From these models we were able to determine patterns in the COMPAS scores assigned to defendents, and then track the accuracy of these scores with the recidivism status of the score's recipient. Our results find biases in a number of risk assesment algorithms used for the criminal justice system, which leads to several questions. Is it possible to create neural networks that resist the unjust biases of modern society? Do algorithms even have a place in determining justice, or are these decisions best left to human minds capable of empathy and compassion despite their biases?

**Literature Review**

*Predicting Enemies* by Ashley S. Deeks and *Understanding Risk Assessment Instruments in Criminal Justice* by *____________* are articles that provide a detailed analysis of the different ways in which the predictive algorithms are used in the criminal justice system. *_____* goes into detail on what what tools are currently being used and what companies are creating them. How these algorithms could be fixed for the better is an important part of this article, whereas Deeks' goal in *Predicting Enemies* is to warn off other sectors from utilizing these kinds of algorithms. Deeks elaborates on how the military industrial complex is in works to adopt similar tactics in their work, but emphasises that moving forward in this direction would be a mistake because of issues already present in their utilization in the criminal justice system. In a similar vein *The Report on Algorithmic Risk Assessment Tool in US Criminal Justice System* published by the nonprofit *______* reports on the serious shortcomings of risk assessment tools in the criminal justice systems through consultations with experts and a review of the literature on risk assessment tools.

Work has also been done on how the discressionary use of risk assessment algorithms, rather than a striclty adhered to policy, can add bias to the very proceedings these algorithms were aimed to neutralize. In *Predictive Algorithms and Criminal Sentencing*, Angele Christi analyzes how the criminal justice system relies on algorithms to determine sentences and criminality while performing an in-depth analysis of the ways in which judges and prosecutors use these algorithms to suit their interests in court, utilizing the results when they want and disregarding them when they do not.

The current state-of-the-art in risk assessment algorithms being deployed in policing and criminal justice sectors include the Correctional Offender Management Profiling for Alternative Sanctions (COMPAS) system and the Public Safety Assessment (PSA) system. COMPAS assigns risk scores to defedants using historical data in a process that is partially kept private by the company which precludes a detailed understanding of the underlying mechansisms used to make these life-determining recommendations. The Public Safety Assessment algorithm (PSA) is used by judges to determine pretrial release risk in a method similar to the COMPAS algorithm. A defendant's biographical information and criminal history are used to assign 3 risk scores - that they will be convicted for a new crime, that they will be convicted for a new violent crime, and that they will fail to appear in court.


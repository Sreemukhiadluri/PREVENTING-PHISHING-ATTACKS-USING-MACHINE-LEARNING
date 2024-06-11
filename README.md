General Introduction:-
Machine learning is programming computers to optimize a performance
criterion using example data or past experience. We have a model defined up to
some parameters, and learning is the execution of a computer program to
optimize the parameters of the model using the training data or past experience.
The model may be predictive to make predictions in the future, or descriptive to
gain knowledge from data.
The field of study known as machine learning is concerned with the
question of how to construct computer programs that automatically improve
with experience.


 Definition of Machine Learning :-
A computer program is said to learn from experience E with respect to
some class of tasks T and performance measure P, if its performance at tasks T,
as measured by P, improves with experience.

Types of machine learning problems:-

1. Supervised learning: The model or algorithm is presented with example
inputs and their desired outputs and then finding patterns and connections
between the input and the output. The goal is to learn a general rule that maps
inputs to outputs. The training process continues until the model achieves the
desired level of accuracy on the training data. Some real-life examples are:

“Preventing Phishing attacks”

Preventing Phishing Attacks Page No:10
• Image Classification: You train with images/labels. Then in the future you
give a new image expecting that the computer will recognize the new
object.
• Market Prediction/Regression: You train the computer with historical
market data and ask the computer to predict the new price in the future.
• Unsupervised learning: No labels are given to the learning algorithm,
leaving it on its own to find structure in its input. It is used for clustering
population in different groups. Unsupervised learning can be a goal in
itself (discovering hidden patterns in data).
• Clustering: You ask the computer to separate similar data into clusters,
this is essential in research and science.
• High Dimension Visualization: Use the computer to help us visualize
high dimension data.
• Generative Models: After a model captures the probability distribution of
your input data, it will be able to generate more data. This can be very
useful to make your classifier more robust.

Supervised Learning:-

Supervised learning, also known as supervised machine learning,
is a subcategory of machine learning and artificial intelligence. It is defined by
its use of labeled datasets to train algorithms that to classify data or predict
outcomes accurately. As input data is fed into the model, it adjusts its weights

until the model has been fitted appropriately, which occurs as part of the cross-
validation process. Supervised learning helps organizations solve for a variety

of real-world problems at scale, such as classifying spam in a separate folder
from your inbox.

Supervised learning uses a training set to teach models to yield the
desired output. This training dataset includes inputs and correct outputs, which
allow the model to learn over time. The algorithm measures its accuracy through
the loss function, adjusting until the error has been sufficiently minimized.
Supervised learning can be separated into two types of

“Preventing Phishing attacks”

Preventing Phishing Attacks Page No:11
problemswhen data mining—classification and regression:
• Classification uses an algorithm to accurately assign test data into
specific categories. It recognizes specific entities within the dataset and
attempts to draw some conclusions on how those entities should be
labeled or defined. Common classification algorithms are linear
classifiers, support vector machines (SVM), decision trees, k-nearest
neighbor, and random forest, which are described in more detail below.
• Regression is used to understand the relationship between dependent
and independent variables. It is commonly used to make projections,
such as for sales revenue for a given business. Linear regression,
logistical regression, and polynomial regression are popular regression
algorithms.


Objective of Project:-

Phishing could be a crime within which a wrongdoer sends the faux e-mail, that
seems to return from widespread and trusty complete or organization, asking to
input personal certification like bank positive identification, username, number,
address, master card details, so forth. The faux emails usually look astonishingly
legitimate, and even the web site wherever the net user is asked to input personal

data additionally sounds like legitimate one. Phishing messages propagate over e-
mail, SMS, instant messengers, social networking sites, VoIP, so forth, however e-
mail is that the widespread thanks to perform this attack and phishing attack is

achieved by visiting the link hooked up to the e-mail. Moreover, spear phishing
attack is changing into widespread these days. Business e-mail compromise (BEC)
is discovered as a serious net threat in 2015.In BEC, the persona non grata uses
spear phishing ways to fool organizations.

“Preventing Phishing attacks”

Preventing Phishing Attacks Page No:12

Limitations of Project
Our proposed system is only useful to predict the phishing attacks of the
given website in API. This consumes entering of malicious link in the API.
This takes more maintantence.

“Preventing Phishing attacks”

Preventing Phishing Attacks Page No:13





Logistic regression is a classification algorithm used to assign
observations to a discrete set of classes. Some of the examples of classification
problems are Email spam or not spam, Online transactions Fraud or not Fraud,
Tumor Malignant or Benign. Logistic regression transforms its output using the
logistic sigmoid function to return a probability value.
Logistic Regression is much similar to the Linear Regression except that
how they are used. Linear Regression is used for solving Regression problems,
whereas Logistic regression is used for solving the classification problems.
In Logistic regression, instead of fitting a regression line, we fit an "S" shaped
logistic function, which predicts two maximum values (0 or 1).

The curve from the logistic function indicates the likelihood of something
such as whether the cells are cancerous or not, a mouse is obese or not based
on its weight, etc.

Assumptions for Logistic Regression:-

“Preventing Phishing attacks”

Preventing Phishing Attacks Page No:14
Logistic regression generally works as a classifier, so the type of logistic
regression utilized (binary, multinomial, or ordinal) must match the outcome
(dependent) variable in the dataset. By default, logistic regression assumes that
the outcome variable is binary, where the number of outcomes is two.

Why Logistic Regression? :-
• It takes less training time as compared to other algorithms.
• It predicts output with high accuracy, even for the large dataset it runs
efficiently. • It can also maintain accuracy when a large proportion of data
is missing.

Logistic Regression Algorithm: -
Logistic regression is commonly used for prediction and classification
problems. The Working process can be explained in the below steps and
diagram:
Step-1: Data preprocessing step includes importing all the libraries.
Step-2: Fitting logistic regression to training
Step-3: Predicting the test result.
Step-4: Test accuracy of result (Creation of confusion matrix)
Step-5: Visualizing test set result

 Existing System :-
• The existing system uses the classifiers and Bayesian Model to detect the
phishing sites.
• Also, the users were not that confident of using internet being unaware of
the possible threats. • The accuracy of detection using Naive Bayes’
algorithm was low.

“Preventing Phishing attacks”


 Disadvantages of Existing system :-
• The Existing system consumes lot of time for every check.
• It will analyze slowly.
• Maintenance is difficult.
• Low Security


Proposed System :-
• The proposed system adds the security protocols for email phishing and
more methods have been used to analyze a given URL.
• Machine learning techniques like Logistic Regression Algorithm are used in
this prediction process.
• The Logistic Regression algorithm is chosen to increase the accuracy of the
model.


Proposed system
2.3.1 Advantages of proposed system : -
• One drawback we found is, for the greatest and most accurate prediction,
in our opinion, both of these criteria need to be considered simultaneously.
• Increase user alertness to phishing risks.
• All of URLs in the dataset are labelled.

“Preventing Phishing attacks”



Software Requirement Specification (SRS) is the starting point of
the software developing activity. As system grew more complex it became
evident that the goal of the entire system cannot be easily comprehended. Hence
the need for the requirement phase arose. The software project is initiated by the
client needs. The SRS is the means of translating the ideas of the minds of clients
(the input) into a formal document (the output of the requirement phase.)
System-Wide Requirements: The system will process exceptions in a consistent
fashion. If the exception is a user error that can be corrected the system displays
an error message with an explanation. The system allows the user to correct the
mistake without starting over.
3.2 Requirement Specification:-
3.2.1 Software requirements :-
Operating System : Windows 11
Programming Language : Python
Library : scikit-learn, Pandas
IDE/Workbench : Anaconda
Framework : Fast API Framework
3.2.1 Hardware requirements :-
Processor : Intel Core i5
Hard Disk : 80 GB
RAM : 8 GB



SYSTEM DESIGN

4.1 Description of modules :-
Modules present in this Preventing Phishing Attacks project are:
1. Fetching Module: This module works like copy, but in reverse. It is used
for fetching files from remote machines and storing them locally in a file tree,
organized by hostname
2. Loading the dataset: The dataset is loaded into code.
3. Preprocessing: We use Count Vectors and Gather words using tokenizer
4. Training and Testing: We test the model against various entries

Description of algorithms: -
Logistic Regression Algorithm: -

Logistic regression predicts the output of a categorical dependent
variable. Therefore, the outcome must be a categorical or discrete value. It can
be either Yes or No, 0 or 1, true or False, etc. but instead of giving the exact
value as 0 and 1.
Steps for Algorithm:
Step 1: Create a model instance of the Logistic Regression class.
Step 2: Specify hyper parameters with all possible values
Step 3: Define performance evaluation metrics.
Step 4: Train the model using the training dataset.
Step 5: Determine the best values for the hyper parameters given.
4.3 UML Diagrams: -

“Preventing Phishing attacks”

Preventing Phishing Attacks Page No:18
Design is concerned with identifying software components specifying
relationships among components. Specifying structure and providing blue print
for the document phase. Modularity is one of the desirable properties of large
systems. It implies that the system is divided into several parts. In such a manner,
the interaction between parts is minimal clearly specified. Design will explain
software components in detail. This will help the implementation of the system.
Moreover, this will guide the further changes in the system to satisfy the future
requirements. The purpose of the design phase is to plan a solution of the
problem specified by the requirement document. This phase is the first step in
moving from problem domain to the solution domain. The design of a system is
perhaps the most critical factor affecting the quality of the software, and has a
major impact on the later phases, particularly testing and maintenance. The
output of this phase is the design document. This document is similar to a
blueprint or plan for the solution, and is used later during implementation,
testing and maintenance.
The UML is a language for
• Visualizing
• Specifying
• Constructing
• Documenting
These are the artifacts of a software system-intensive system.


Use-Case Diagram: -
Use case diagrams are used to describe the functionality of the system. Use
case diagrams have four major modules: The actor that the system interacts with, the
system itself, or services 27 that the system knows how to perform, and the lines that
represent relationships between these elements.





Use-case Diagram


Sequence Diagram: -
A sequence diagram in a Unified Modeling Language (UML) is a kind of
interaction diagram that shows how processes operate with one another and in
what order. It is a construct of a Message Sequence Chart. A sequence diagram
shows object interactions arranged in time 30 sequence. It depicts the objects
and classes involved in the scenario and the sequence of messages exchanged
between the objects needed to carry out the functionality of the scenario.
Sequence diagrams typically are associated with use case realizations in the
Logical View of the system under development.

“Preventing Phishing attacks”

Preventing Phishing Attacks Page No:20

 Sequence Diagram


Activity Diagram:-
Activity Diagrams describe how activities are coordinated to provide a
service which can be at different levels of abstraction. Typically, an event needs
to be achieved by some operations, particularly where the operation is intended
to achieve a number of different things that require coordination, or how the
events in a single use case relate to one another, in particular, use cases where
activities may overlap and require coordination. It is also suitable for modeling
how a collection of use cases co-ordinate to represent business workflows.

 Activity Diagram


Data Flow Diagrams:-
DFD graphically representing the functions, or processes, which capture,
manipulate, store, and distribute data between a system and its environment and
between components of a system. The visual representation makes it a good
communication tool between User and System designer. Structure of DFD
allows starting from a broad overview and expand it to a hierarchy of detailed
diagrams. DFD has often been used due to the following reasons:
• Logical information flow of the system
• Determination of physical system construction requirements
• Simplicity of notation
• Establishment of manual and automated systems requirements


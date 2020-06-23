# Demand for Explainability

### The demand for explainability arises because of the following:

#### **Trust** 

People who use this model should trust the model with its predictions and decisions. This is highly subjective and varies from individual to individual.

#### Transparency

Transparency refers to the requirement that the end-user can understand how a decision/prediction is made by the AI system. Essentially, this means that one should understand what a model predicts and if there is any bias. Correctional Offender Management Proﬁling for Alternative Sanctions \(COMPAS\), a widely used criminal risk assessment tool, found that its predictions were unreliable and racially biased. So after gaining transparency, this insight revealed a bias in the model which was a crucial breakthrough for the company.

#### Quality

Not all models are 100 percent accurate so defining quality is important. It only makes sense for people to use a highly accurate model. To identify, log and articulate sources of error and uncertainty throughout the algorithm and its data sources helps understand the expected and worst-case implications and further aid mitigation procedures.

#### Accountability 

For decisions made by the model - who is accountable? The person who uses it or the person who built it? There should be a way to identify and assign the responsibility for a decision made by an AI system.

#### Fairness

How do we ensure that algorithmic decisions do not create discriminatory or unjust impacts when comparing across different demographics \(e.g. race, sex, etc\).

To provide a complete explanation for any decision by a black-box model can be a tedious job. This has led to a new line of research – interpretability - loosely deﬁned as the science of comprehending what a model did. So, an explanation can be evaluated in two ways: interpretability and completeness.

![](../.gitbook/assets/image%20%281%29.png)

The goal of interpretability is to describe the internals of a system in a way that is understandable to humans. Miller defines Interpretability as the degree to which a human can understand the cause of a decision. The success of this goal is tied to the cognition, knowledge, and biases of the user: for a system to be interpretable, it must produce descriptions that are simple enough for a layman to understand using a vocabulary that is meaningful to the user.

Completeness is describing the operation of a system accurately. An explanation is more complete when it allows the behavior of the system to be anticipated in more situations. When explaining a model like a deep neural network, a perfectly complete explanation can always be given by revealing all the mathematical operations and parameters in the system. 

To understand this difference, let us go back to the example of job and university applications. On approval, we interpret that our skills and experience match the requirements. But this explanation is not complete because we do not know the exact metrics of how the approver made that decision. 

Today, the challenges faced in the field of explainability are in creating explanations that are highly interpretable and complete.

When we dive into the data science of this concept, we will see that there are some models that are fully explainable – such as generalized linear models, and there are other complex models that are not easily explainable – such as a neural network. For complex models, there exist interpretability techniques, that help humans understand how a model makes a prediction. 

 In this book, we concentrate on the interpretability of a model. So we will go through the interpretability of both simple models and complex models. 

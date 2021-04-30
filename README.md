# ImageClassification
A formal introduction to **Deep Learning** with **TuriCreate** using the **CIFAR-10** dataset. CIFAR-10 is a building block for deep learning. It contains set of images which are labelled. These images are of cats, dogs, aeroplanes and many other objects.

This particular deep learning model uses something called "_deep-features_". Although explained in the notebook as well, deep features can be looked as blocks or segments on which the DL model learns and trains. The learnings from previous segment or block augments the learning for its subsequent segment. The model picks up certain features that help in identifing that object in each "_deep-feature_" and it goes on from strength-to-strength.

Thus using CIFAR-10 I have created a model on Google Colaboratory which implements an Image Classfication Algorithm using Deep Features. The notebook has 2 different models, one a normal model and the other a _deepfeaturemodel_. This highlights a starking difference between the two models and shows how important "_deep-features_" are and how they hep in the betterment of a Deep Learning Model.

The model used a Logistic Classifer for both the models.

# DecisionTree
One of the cutest and lovable supervised algorithms is Decision Tree Algorithm. It can be used for both the classification as well as regression purposes also.
Assumptions we make while using Decision tree

   1 In the beginning, the whole training set is considered at the root.
   2 Feature values are preferred to be categorical. If values are continuous then they are discretized prior to building the model.
   3 Records are distributed recursively on the basis of attribute values.
   4 Order to placing attributes as root or internal node of the tree is done by using some statistical approach.

Decision Tree Algorithm Pseudocode

   1 Place the best attribute of our dataset at the root of the tree.
   2 Split the training set into subsets. Subsets should be made in such a way that each subset contains data with the same value for an attribute.
    3 Repeat step 1 and step 2 on each subset until you find leaf nodes in all the branches of the tree.

While building our decision tree classifier, we can improve its accuracy by tuning it with different parameters. But this tuning should be done carefully since by doing this our algorithm can overfit on our training data & ultimately it will build bad generalization model.

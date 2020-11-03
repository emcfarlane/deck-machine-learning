---
title: Normal Equation Noninvertibility
---
How would one fix a noninvertable matrix when implementing the normal equations?
<!--question-->

If $X^TXX$ is noninvertible, the common causes might be having:

- Redundant features, where two features are very closely related (i.e. they are linearly dependent)
- Too many features (e.g. m ≤ n). In this case, delete some features or use "regularization".

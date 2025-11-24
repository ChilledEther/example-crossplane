# 🌇 Overview

GitOps is a process for using code as your source of truth. A controller or automation will reconcile and correct drift. This includes provisioning, deprovisioning, and updating configuration.

# 💹 Diagram

![image](..\assets\gitops.png)

# 💎 Benefits

* Single source of truth
* Auditiability and compliance as everything is in git, with reviews including timestamps and diffs
* Easier to rollback when things go wrong due to version history
* Corrects drift - so manual changes do not persist ensuring the environment moves back to how it was configured
* Lives close to the code, so lifecycle is managed more closely
* Easier to enforce policy as a result to prevent dangerous commits
* Gives more self-service capability for developers
* Easier to develop with due to the progressive nature of gitops delivery
* Disaster Recovery becomes a breeze due to the declarative nature

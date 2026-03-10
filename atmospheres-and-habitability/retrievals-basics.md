---
description: Turning spectra into composition constraints, and why priors matter.
---

# Retrievals (basics)

A **retrieval** is Bayesian inference over atmospheric models.

### What retrievals usually fit

* Molecular abundances.
* Temperature profile parameters.
* Cloud/haze parameters.
* Reference radius / pressure.

### Why results vary across papers

* Different line lists.
* Different cloud models.
* Different priors.
* Different treatment of the star.

### Minimal good practice

* Report priors.
* Do model comparison.
* Share spectra and likelihood details.

{% hint style="info" %}
If the posterior follows the prior, the data didn’t constrain it. That’s not a failure. It’s information.
{% endhint %}

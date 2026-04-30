# A/B Testing Analysis: From Experiment to Decision

## Overview

This project explores whether a redesigned webpage improves user conversion compared to the existing version. Using an A/B testing framework, users were randomly assigned to either a control group (old page) or a treatment group (new page). The goal is simple but important: determine if the new design actually leads to better outcomes, or if any observed difference is just noise.

---

## Approach

The analysis follows a structured workflow. After cleaning the data (removing duplicate users and mismatched assignments), conversion rates are calculated for both groups. A two-proportion Z-test is then applied to evaluate whether the difference between groups is statistically significant.

Beyond statistical significance, the analysis also looks at effect size and confidence intervals to understand the magnitude and uncertainty of the observed difference. This helps move the discussion from “is there an effect?” to “does this effect actually matter?”

---

## Key Results

The treatment group shows a slightly lower conversion rate than the control group. However, the difference is not statistically significant, and the confidence interval includes zero, indicating that the true effect could be either slightly positive or slightly negative.

In practical terms, the effect size is very small and does not suggest any meaningful improvement.

---

## Conclusion

From both a statistical and business perspective, there is no evidence that the redesigned page improves performance. While the difference is not significant, the direction of the effect introduces a potential downside risk if deployed at scale.

Given the lack of measurable benefit and the possibility of reduced conversions, the recommendation is to retain the current version rather than roll out the new design.



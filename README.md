# Should Your AI Agent Ask or Act?

This project investigates whether AI assistants should act autonomously or ask for permission before taking action. Using a randomized between-subjects experiment, our team studied how “act-first” versus “ask-first” behavior affected user trust, comfort, willingness to use, and reactions after an AI error.

We ran a Qualtrics-based experiment and analyzed the results using causal inference methods including randomization checks, OLS regression with covariates, omitted variable bias checks, and heterogeneous treatment effect analysis. The study found no significant difference in trust or willingness to use across conditions, a marginal positive comfort signal for act-first behavior, and a strong preference for conditional autonomy, with 88% of users wanting AI to ask before important decisions.

Key findings:
- Trust difference was effectively zero and not statistically significant.
- Willingness to use was also not significantly different across treatments.
- Comfort was higher for act-first users in the full model (+0.412, p = 0.089), suggesting a possible small positive effect in low-stakes tasks.
- Trust dropped after an error in both groups, but act-first did not create a stronger “betrayal effect.”
- 88% of participants preferred AI that asks before acting always or for important decisions.

The results suggest that the right design pattern is not full autonomy or full confirmation at every step. Instead, AI assistants may perform best with adaptive autonomy: acting independently on low-stakes tasks while asking for confirmation on important decisions.

# Units 7–9 | Vulnerability Scoring and Risk Prioritisation

*Independent review of the formative discussion reading.*

Wunder et al. (2024) question the consistency of CVSS assessments, particularly where evaluators interpret metrics such as Attack Vector, User Interaction and Scope differently. Their findings support concerns about subjective scoring, although I would not dismiss CVSS entirely. A common severity framework remains useful, but inconsistent interpretation can undermine its reliability when scores determine remediation priorities.

Of the alternatives discussed, I favour Stakeholder-Specific Vulnerability Categorization (SSVC). Its decision-tree approach incorporates exploitation evidence and organisational consequences into vulnerability response decisions (CISA, 2022). I would use SSVC to replace reliance on CVSS scores alone for remediation prioritisation, while retaining CVSS for communicating technical severity. However, SSVC also depends on defensible inputs and clearly established organisational priorities.

This distinction reflects a weakness in my Pampered Pets assessments, where numerical ratings sometimes appeared more conclusive than the evidence supporting them.

## References

Cybersecurity and Infrastructure Security Agency (CISA) (2022) *CISA Releases SSVC Methodology to Prioritize Vulnerabilities*. Available at https://content.govdelivery.com/accounts/USDHSCISA/bulletins/337377d.

Wunder, J., Kurtz, A., Eichenmüller, C., Gassmann, F. and Benenson, Z. (2024) 'Shedding light on CVSS scoring inconsistencies: A user-centric study on evaluating widespread security vulnerabilities', *2024 IEEE Symposium on Security and Privacy*, pp. 1102–1121. Available at https://doi.org/10.1109/SP54263.2024.00058.

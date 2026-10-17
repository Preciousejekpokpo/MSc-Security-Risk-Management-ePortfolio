# Unit 4 | Threat Modelling and the Limits of Method Selection

*Retrospective review prepared for the final e-portfolio, drawing on the Unit 4 readings and workshop material, together with feedback from the Unit 6 and Unit 11 assessments.*

## Critical Review

The Unit 4 reading raised an important question about how threat-modelling methods should be selected, particularly when identifying a threat does not necessarily establish its significance to the organisation. Shevchenko et al. (2018) examine twelve approaches with different purposes and emphases, suggesting that their suitability depends on the system and the questions being investigated. STRIDE helps structure the identification of security threats, while attack trees explore possible routes to a defined outcome, although neither can establish risk levels without considering the system's exposure, consequences and available evidence.

Looking back at the Pampered Pets assessments, this distinction helps explain some of the limitations identified in the feedback. The Unit 6 group report introduced STRIDE but concentrated primarily on account spoofing and data tampering, leaving other threat categories less developed, while the Unit 11 assessment used fault trees and Monte Carlo simulation to examine how initiating events and failed safeguards might combine. Although this made the assumptions and their influence on the results more explicit, the lecturer questioned the evidence supporting control improvements and the exclusion of shared failures from the calculations. Greater analytical detail had made those uncertainties easier to examine without establishing that the estimates were reliable.

Jbair et al. (2022) extend the discussion to industrial cyber-physical systems, where threats must be considered alongside asset criticality, physical processes and operational dependencies. Their approach was demonstrated on a prototype production line, so its findings cannot be assumed to apply directly to Pampered Pets' proposed automated warehouses, although the emphasis on interconnected failures offers a useful perspective.

Taken together, the readings and assessment feedback suggest that method selection is only part of producing a defensible risk assessment, since the quality of the conclusions also depends on how comprehensively the method is applied and whether its assumptions can be challenged against credible evidence.

## Supporting Evidence

Unit 4 readings on threat-modelling methods, the industrial cyber-physical systems workshop material, Unit 6 group assessment and feedback, and Unit 11 quantitative assessment and feedback.

## References

Jbair, M., Ahmad, B., Maple, C. and Harrison, R. (2022) 'Threat modelling for industrial cyber physical systems in the era of smart manufacturing', *Computers in Industry*, 137, article 103611. Available at https://doi.org/10.1016/j.compind.2022.103611.

Shevchenko, N., Chick, T., O'Riordan, P., Scanlon, T. and Woody, C. (2018) *Threat Modeling: A Summary of Available Methods*. Pittsburgh, PA: Software Engineering Institute, Carnegie Mellon University. Available at https://sei.cmu.edu/library/threat-modeling-a-summary-of-available-methods/.

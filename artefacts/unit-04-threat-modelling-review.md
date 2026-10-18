# Unit 4 | Threat Modelling and the Limits of Method Selection

*Retrospective review informed by Unit 4 learning materials and subsequent assessment feedback.*

The Unit 4 reading raised an important question about how threat-modelling methods should be selected, particularly when identifying a threat does not necessarily establish its significance to the organisation. Shevchenko et al. (2018) compare approaches developed for different purposes, helping explain why STRIDE's classification of threats and attack trees' examination of possible pathways offer different insights, but cannot independently justify risk priorities.

This became more apparent when revisiting Pampered Pets. Our Unit 6 application of STRIDE concentrated on spoofing and tampering, leaving other threat categories underexplored. Unit 11 examined failure pathways through fault trees and Monte Carlo simulation, making assumptions about safeguards easier to scrutinise, although the lecturer questioned the evidence supporting their effectiveness and the exclusion of shared failures. Greater analytical detail had exposed uncertainty without necessarily making the estimates more reliable.

Jbair et al. (2022) consider threats across interconnected cyber-physical processes, where digital weaknesses may affect physical operations. Their prototype findings cannot be transferred directly to Pampered Pets' proposed warehouses, but they draw attention to operational dependencies our assessments might otherwise overlook. I would now place greater weight on a method's coverage, the assumptions it leaves untested and the evidence supporting its conclusions.

## Supporting Evidence

Unit 4 threat-modelling readings and workshop materials, together with Unit 6 and Unit 11 assessment feedback.

## References

Jbair, M., Ahmad, B., Maple, C. and Harrison, R. (2022) 'Threat modelling for industrial cyber physical systems in the era of smart manufacturing', *Computers in Industry*, 137, article 103611. Available at https://doi.org/10.1016/j.compind.2022.103611.

Shevchenko, N., Chick, T., O'Riordan, P., Scanlon, T. and Woody, C. (2018) *Threat Modeling: A Summary of Available Methods*. Pittsburgh, PA: Software Engineering Institute, Carnegie Mellon University. Available at https://sei.cmu.edu/library/threat-modeling-a-summary-of-available-methods/.

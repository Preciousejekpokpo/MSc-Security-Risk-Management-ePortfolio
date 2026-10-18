# Unit 10 | Disaster Recovery and Operational Resilience

*Retrospective review informed by Unit 10 reading and the Unit 11 assessment feedback.*

Alhazmi and Malaiya (2013) examine the trade-off between recovery objectives and cost, while Corbari et al. (2024) approach resilience through the operational activities that depend on technical systems. Although the latter focuses on military operations, its emphasis on connecting infrastructure to operational requirements offers a useful perspective for Pampered Pets, where restoring individual services would have limited value if customers could not complete purchases.

Reviewing my Unit 11 proposal against these arguments exposed a weakness in how I assessed recovery feasibility. The proposed multi-region architecture addressed the required RTO and RPO, but without specified capacity, failover timings and database configuration, its ability to recover the entire checkout process remained unproven. More importantly, the demanding targets were specified in the scenario without sufficient evidence of their financial implications for a four-person business. A stronger assessment would establish the business justification, compare costed recovery options and test complete transactions before treating the proposed design as capable of meeting its objectives.

## References

Alhazmi, O.H. and Malaiya, Y.K. (2013) 'Evaluating disaster recovery plans using the cloud', *Proceedings of the Annual Reliability and Maintainability Symposium*. Available at https://doi.org/10.1109/RAMS.2013.6517700.

Corbari, G.I., Khatod, N., Popiak, J.F. and Sinclair, P. (2024) 'Mission thread analysis: Establishing a common framework in a multi-discipline domain to enhance defensive cyberspace operations', *The Cyber Defense Review*, 9(1), pp. 37–54.

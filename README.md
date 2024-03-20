[Main Page](https://github.com/davidj778/davidj778)

# Analyze a vulnerable system for a small business


## System Description

The server hardware consists of a powerful CPU processor and 128GB of memory. It runs on the latest version of Linux operating system and hosts a MySQL database management system. It is configured with a stable network connection using IPv4 addresses and interacts with other servers on the network. Security measures include SSL/TLS encrypted connections.

## Scope

The scope of this vulnerability assessment relates to the current access controls of the system. The assessment will cover a period of three months, from June 20XX to August 20XX. NIST SP 800-30 Rev. 1 is used to guide the risk analysis of the information system.

## Purpose

Consider the following questions to help you write:
- How is the database server valuable to the business?
- Why is it important for the business to secure the data on the server?
- How might the server impact the business if it were disabled?

## Risk Assessment

| Threat source | Threat event | Likelihood | Severity | Risk |
|-----|----|---------|----|--|
| Hacker | Conduct "man-in-the-middle" attacks. | 2 | 2 | 6 |
| Competitor | Perform reconnaissance and surveillance of organization | 3 | 1 | 4 |
| Advanced persistent threat (APT) | Disrupt mission-critical operations. | 2 | 3 | 9 |



## Approach

- A hackers ability to listen in on conversations and potentially impersonate a higher individual in a company such as a CEO, could have catastrophic consequences to a business. If someone can act as a CEO or any upper level member of an organization, can steal information or potentially lead to reputation damage.

- The competitors ability to perform reconnaissance and surveillance of an organization could lead to reputation damage, financial loss, loss of competitive advantage, among other issues.

- APTs typically involve nation states as the bad actors, which have more financial backing compared to other bad actors. Because of their higher budget, they have more resources to conduct complex/advanced attacks that can lead to catastrophic damage. The disruption of mission critical systems can put a business out of operation for hours if not days, which could lead to millions of dollars in losses.


## Remediation Strategy

To avoid "man-in-the-middle" attacks, it’s highly recommended to use encryption, PKI, etc. To mitigate reconnaissance and surveillance, it’s best to use IDS/IPS solutions and network segmentation. Lastly, a proper redundancy or failover system along with regular backups and a disaster recovery plan can help lesson the severity of a disruption of mission-critical operations.

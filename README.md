# TP Audit SSH
## Context
 Find in the repository a SSH configuration file named `sshd_config`.
 This file contains the full configuration on an SSH server that is run on a host your users will need to access.

## TODO
Audit this configuration file to find any security issue, explain why this is a problem and propose a mitigation for each issue.

You are expected to deliver 3 files :
- The configuration file with your modification that implements the fixes proposed
- An audit report as Word/ODT format
  - For each identified issue
    - Name the issue
    - Explain why it is a problem and how it could be exploited
    - Propose a mitigation, the one we can find in your updated configuration file and explain your proposal
  - Categorize the issues based on their likeliness to be exploited and the risk they represent for the system
    - You can use two notation systems, one for the risk and one for the likeliness then calculate the average of both to have a score or something like that
- A presentation that you will use to present your work to the security team that order the audit
  - Explain the major issues you have found and what are the risks for the company
  - Propose your mitigations
  - Be as much understandable as possible, you might present your results to people that does not have the security experience to have a full understanding of what you are talking (like a CTO instead of a CISO)

Use the security resources you know like the ANSSI guides, the CIS guides or any other standard or public agency publication !

# GovernancePlayground

This project is a playground created to demonstrate our Governance DSL and associated Decision Engine.

# Authors
- Adem Ait (University of Luxembourg)
- Gwendal Jouneaux (LIST)
- Jordi Cabot (LIST & University of Luxembourg)
- Javier Luis Cánovas Izquierdo (UOC)

# Disclaimer

To allow the use of the playground to play with the proposed policies, the timings of deadlines are modified for this instance.
Any delay expressed in days is considered as expressed in minutes.
For example, a deadline of 10 days will result in a real waiting time of 10 minutes.


# Governance in this repository

## Roles

There are three possible roles:
- **Maintainers**: highest authority, can make final decisions
- **Reviewers**: participate in decisions
- **No-one**: used for automatic or fallback decisions

## Individuals

There are both humans: 
- gwendal-jouneaux
- ademait
- jcabot

And AI agents:
- besser-bot (very high trust and explainability)
- som-boss-bot (medium trust)
- governance-agent (moderate trust, high explainability)
- agent-for-governance (lower trust)

Humans act as both maintainers and reviewers while agents are only reviewers.


## Policies

### Bug fixes
This activity handles corrections to existing content.

Code fixes
- Done via pull requests
- Must be labeled bug and code
- Result: the pull request is merged

Documentation fixes
- Done via pull requests
- Must be labeled bug and docs
- Result: the pull request is merged

Fixes are managed through consensus based policies

### Proposals
This activity handles addition of existing content.

Code proposals
- Done via pull requests
- Must be labeled proposal and code
- Result: the pull request is merged

Documentation proposals
- Done via pull requests
- Must be labeled proposal and docs
- Result: the pull request is merged

Proposals are managed through voting based policies

### Triage of feature requests

This is about reviewing feature requests.

- Submitted as GitHub issues
- Must be labeled triage
- Action: label the issue as accepted or denied

Triage use a majority policy to decide the acceptance

### Maintainers promotion and demotion

The last governance aspect is about promotion and demotion

- Submitted as GitHub issues
- Must be labeled promotion or demotion
- Action: update the Governance.gov file according to the decision

Promotions and demotions of maintainers are done through a consensus among the maintainers. 
# Incident Managers

## Context

With the current size of the team (especially number of engineers), and the broad scope of software system we're responsible and co-responsible for, we intend to optimize the way we handle unexpected interruptions and regressions. In particular, we want to avoid multiple engineers investigating and resolving these, without being aware of each other's activity. Also, we strive for improving the communication around these issues by ensuring the clear current status of their resolution is always known.

## Incident

* Critical issue discovered in Wikidata software products live instances, either production or pre-production, sites (e.g. www.wikidata.org, Wikidata-related parts of Wikipedia and other "client" WMF wikis), affecting significant amount of users, interrupting essential functions of these instances, system security, etc.
* Also an issue in the development infrastructure, that prevents engineers from delivering improvements to software products (e.g. issue in the Continuous Integration system preventing integrating code changes, disruption in the deployment tooling).

## Incident Manager

A Wikidata engineer designated to be managing the resolution of the Incident. Managing here does not mean the designated engineer is expected to investigate and resolve the Incident on their own. They are the one ensuring (e.g. by means of delegating tasks) the possible Incident is triaged, investigated, resolved and documented as necessary, and that the communication about the status of the Incident is being published in Wikidata's team bug tracker (Phabricator).

Team members being informed, or finding themselves a possible Incident inform the Incident Manager on duty. The Incident Manager triages the report (e.g. checks the severity of the reported issue with the Product Manager, Tech Lead, Engineering Manager). If the report is considered an Incident, the Incident Manager ensure the issue reported is tracked in the bug tracker (if the report didn't contain the bug tracker ticket), and proceeds to the resolution of the Incident (again, not necessarily on their own).

As of 2019 Incident managers are designated for weekly periods. Engineers to take on the Incident Manager role for each week of the upcoming month are decided on inside the engineering team in the latter half of the preceeding month.

## Useful links

[Wikidata-related bug tracker issues with the highest "Unbreak Now!" priority](https://phabricator.wikimedia.org/maniphest/query/CE0.8hatW_LF/)

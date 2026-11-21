# Awesome Incident Management

A curated directory of incident response, on-call scheduling, alerting and postmortem tools.

## 📑 Table of Contents

- [Incident Response Platforms (8)](#incident-response-platforms)
- [On-Call & Alerting (6)](#on-call--alerting)
- [Open Source (3)](#open-source)
- [Postmortems & Retros (1)](#postmortems--retros)
- [Slack/Teams-Native Incident Tools (2)](#slackteams-native-incident-tools)
- [Status Communication (1)](#status-communication)


## Incident Response Platforms

- [BigPanda](https://bigpanda.io/) - BigPanda is an AIOps platform for incident prevention and response, using machine learning to correlate alerts and reduce noise. It automates incident triage and integrates with ITSM and monitoring tools for enterprise NOCs. BigPanda is a paid enterprise product. ([Read more](/details/bigpanda.md)) `Enterprise` `Paid` `AI-Powered` `API` `AIOps`
- [Datadog](https://www.datadoghq.com/) - Datadog is a cloud monitoring and security platform that includes incident management, on-call scheduling, and collaboration tools. It unifies metrics, traces, logs, and alerts to support incident response across modern stacks. Datadog offers a free tier and paid plans based on hosts and usage. ([Read more](/details/datadog.md)) `Freemium` `API` `Monitoring` `Cloud` `Observability`
- [FireHydrant](https://firehydrant.com/) - FireHydrant is an incident response and reliability platform for managing service catalogs, incident workflows, and postmortems. It supports runbook automation, severity tracking, and integration with observability tools. FireHydrant provides a free tier for small teams and paid plans for enterprises. ([Read more](/details/firehydrant.md)) `Freemium` `API` `Incident Response` `SLO` `Runbooks`
- [Freshservice](https://freshworks.com/it-service-management-software/freshservice) - Freshservice is a cloud-based IT service management tool with incident, problem, and change management for IT teams. It includes incident dispatch, asset management, and a service catalog with SLA tracking. Freshservice offers a free tier for small teams and paid plans for larger organizations. ([Read more](/details/freshservice.md)) `Freemium` `API` `ITSM` `Incident Management` `Cloud`
- [PagerDuty](https://www.pagerduty.com/) - PagerDuty is a digital operations management platform for incident response and on-call scheduling. It centralizes alerts from monitoring tools and automates escalation policies for IT, DevOps, and security teams. Pricing is paid with tiered plans based on users and features. ([Read more](/details/pagerduty.md)) `Paid` `Enterprise` `API` `AI-Powered` `On-Call` `Incident Response`
- [ServiceNow](https://www.servicenow.com/) - ServiceNow is an enterprise cloud platform for IT service management, including major incident management and on-call coordination. It automates incident workflows, communication, and post-incident reviews across large organizations. ServiceNow is a paid enterprise product with subscription licensing. ([Read more](/details/servicenow.md)) `Enterprise` `Paid` `API` `ITSM` `Incident Management`
- [Squadcast](https://www.squadcast.com/) - Squadcast is an incident management platform for SRE and DevOps teams, offering on-call scheduling, alert noise reduction, and incident response workflows. It includes status pages, postmortems, and integrations with monitoring and chat tools. Squadcast is a paid service with a free trial. ([Read more](/details/squadcast.md)) `Paid` `API` `SRE` `Incident Response` `Status Pages`
- [Zenduty](https://www.zenduty.com/) - Zenduty is an incident response and on-call management platform for DevOps and SRE teams. It centralizes alerts, automates escalation policies, and generates postmortem reports after incidents. Zenduty includes a free tier for small teams and paid plans for larger organizations. ([Read more](/details/zenduty.md)) `Freemium` `API` `DevOps` `SRE` `Postmortems`

## On-Call & Alerting

- [Better Stack](https://betterstack.com/) - Better Stack is a developer-first observability and incident management platform combining uptime monitoring, on-call scheduling, and status pages. It routes alerts to teams and automates incident escalation through multiple channels. A generous free tier is available, with paid plans for higher usage. ([Read more](/details/better-stack.md)) `Freemium` `API` `Monitoring` `Status Pages` `Uptime`
- [ilert](https://ilert.com/) - ilert is an alerting and on-call management platform that connects monitoring tools to response teams via phone, SMS, push, and email. It offers incident escalation, schedules, and status pages for DevOps and IT operations. ilert provides a free plan for small teams and paid plans for advanced features. ([Read more](/details/ilert.md)) `Freemium` `API` `On-Call` `Alerting` `Status Pages`
- [Opsgenie](https://www.atlassian.com/software/opsgenie) - Opsgenie is an incident and alert management platform by Atlassian for on-call scheduling and alert routing. It consolidates notifications from monitoring systems and escalates them to the right personnel via phone, SMS, and email. A free plan supports up to five users; paid plans add advanced routing and reporting. ([Read more](/details/opsgenie.md)) `Freemium` `API` `Atlassian` `On-Call` `Alerting`
- [PagerTree](https://www.pagertree.com/) - PagerTree is an on-call scheduling and alert routing platform for IT and DevOps teams. It integrates with monitoring tools to escalate alerts through voice, SMS, and mobile push. PagerTree is a paid service with a free trial and tiered plans. ([Read more](/details/pagertree.md)) `Paid` `API` `On-Call` `Alerting` `Scheduling`
- [Spike.sh](https://spike.sh/) - Spike.sh provides on-call scheduling, incident management, and status pages for engineering teams. It aggregates alerts from monitoring tools and notifies responders via SMS, voice, email, and mobile push. Spike.sh offers a free plan for small teams and paid plans for additional features. ([Read more](/details/spike-sh.md)) `Freemium` `API` `Status Pages` `On-Call` `Alerting`
- [xMatters](https://www.xmatters.com/) - xMatters is a service reliability platform that automates incident response and on-call communications for enterprise IT and DevOps teams. It orchestrates multi-channel alerting, incident workflows, and stakeholder notifications. xMatters is a paid enterprise product with API access and workflow automation. ([Read more](/details/xmatters.md)) `Paid` `Enterprise` `API` `Incident Response` `Automation`

## Open Source

- [Cachet](https://cachethq.io/) - Cachet is an open-source status page system for communicating system downtime and incidents to end users. It supports custom domains, metrics, and subscriptions, and can be self-hosted. Cachet is released under the MIT License. ([Read more](/details/cachet.md)) `Open Source` `Self-Hosted` `Status Pages` `Communication` `MIT`
- [Uptime Kuma](https://uptime.kuma.pet/) - Uptime Kuma is a self-hosted monitoring tool with uptime tracking, notifications, and a status page feature. It supports alerts via Discord, Telegram, email, and webhook for services and endpoints. Uptime Kuma is open source under the MIT License. ([Read more](/details/uptime-kuma.md)) `Open Source` `Self-Hosted` `Monitoring` `Status Pages` `Uptime`
- [Zabbix](https://www.zabbix.com/) - Zabbix is an open-source enterprise monitoring and alerting solution for networks, servers, and applications. It collects metrics, triggers alerts, and supports incident escalation through email, SMS, and webhook. Zabbix is released under the GNU General Public License. ([Read more](/details/zabbix.md)) `Open Source` `Self-Hosted` `Monitoring` `Alerting` `Enterprise`

## Postmortems & Retros

- [Blameless](https://www.blameless.com/) - Blameless is a site reliability engineering platform focused on incident response, SLO tracking, and blameless postmortems. It helps engineering teams automate incident workflows and analyze reliability data. Blameless is a paid enterprise product with custom pricing. ([Read more](/details/blameless.md)) `Paid` `Enterprise` `API` `SRE` `Postmortems`

## Slack/Teams-Native Incident Tools

- [incident.io](https://www.incident.io/) - incident.io is a Slack-native incident management platform that helps teams declare, coordinate, and resolve incidents from chat. It automates runbooks, stakeholder communications, and postmortem generation. A free plan is available for small teams, with paid tiers for larger organizations. ([Read more](/details/incident-io.md)) `Freemium` `API` `Slack` `Incident Response` `Postmortems`
- [Rootly](https://www.rootly.com/) - Rootly is a Slack-native incident response platform that automates incident lifecycle tasks such as responder paging, stakeholder updates, and postmortem creation. It integrates with monitoring and communication tools to reduce manual coordination. Rootly offers a free tier and paid plans for growing teams. ([Read more](/details/rootly.md)) `Freemium` `Slack` `AI-Powered` `Incident Response` `Automation`

## Status Communication

- [Statuspage](https://www.statuspage.io/) - Statuspage is an Atlassian product for creating public status pages to communicate incidents and maintenance to customers. It integrates with monitoring and incident tools to update status automatically during outages. Statuspage is a paid service with tiered plans based on subscribers and pages. ([Read more](/details/statuspage.md)) `Paid` `API` `Status Pages` `Customer Communication` `Atlassian`


## ™️ Legal

All product names, logos, and brands are the property of their respective owners. All company, product, and service names used in this repository, related repositories, and associated websites are for identification purposes only. The use of these names, logos, and brands does not imply endorsement, affiliation, or sponsorship.

This work may include content generated by artificial intelligence (AI). While efforts have been made to ensure the accuracy and reliability of the information, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability of the information contained herein. Users are advised to independently verify the information before making decisions based on it.

We disclaim any responsibility for errors, omissions, or inaccuracies in the content, whether generated by humans, AI, or any other means. By using this work, you agree to use it at your own risk and acknowledge that the information provided may not always be current or accurate.

If you believe that your intellectual property rights or other legal rights have been infringed, please contact us immediately at legal@ever.co and we will take appropriate action.

## 🛡️ License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a

[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/

[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png

[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
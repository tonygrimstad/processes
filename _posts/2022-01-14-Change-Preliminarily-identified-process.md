---
layout: post
title:  "Change - Preliminarily Identified Process"
date:   2022-01-14 12:00:06 +0100
categories: jekyll update
---

#### General
The purpose of the change enablement practice is to maximize the number of successful IT changes by ensuring that risks have been properly assessed, authorizing changes to proceed, and managing the change schedule.
(Source: <a href="https://www.bmc.com/blogs/itil-change-enablement/" target="_blank">BMC Blog</a>)

#### Process Outline
[![IGOE Template Service Desk](/processes/assets/images/process-ch.png)](/processes/assets/images/process-ch.png)

#### *Check out the BMC blog for more general understanding about the process <a href="https://www.bmc.com/blogs/itil-change-management/" target="_blank">here</a> (ITIL3) and <a href="https://www.bmc.com/blogs/itil-change-enablement/" target="_blank">here</a> (ITIL4)*
(Although we still have to find our own way of doing the processes)

<br />

#### Tools
[![Change Tool Support](/processes/assets/images/tools-ch.png)](/processes/assets/images/tools-ch.png)

<br />

#### Roles
[![Change Roles](/processes/assets/images/roles-ch.png)](/processes/assets/images/roles-ch.png)



<br />

| Role | Name | Note |
| -- | -- | -- |
| Manager Change | Tony G |  |
| Manager SD | Elaine S |  |
| Manager SD | Anita M |  |
| Suppliers | FA + DA |  |
| Manager Supplier | Lars-Göran A | Must be involved in relation to supplier management |
| Agile Coach | Anne R |  |
| Internal Domain Experts | Odd Arne S |  |
| Internal Domain Experts | Petter B |  |
| Manager Incident | Torkel B |  |

<br />

#### Traffic (approximately)

| Yearly | Note |
| -- | -- |
| 120 | |

---

<br />

#### **Example Change Cases:**

| Case Id | From | Internal/Eksternal inquiry | inquiry | The desired outcome of the case | Contributors | Information security | Note |
| -- | -- | -- | -- | -- | -- | -- | -- |
| SD4953806 |Service Owner | Eksternal | Order production set of service | Notification that the service has been put into production  | SD <br />FA Supplier | n/a | Standard Change (Processed at the service desk) |
| SD4249463 | FA Supplier | Eksternal | Firewall opening | Notification that a firewall has been opened | SD <br /> Operating supplier | n/a | Standard Change (Processed at the service desk) <br /> It is often difficult to know whether a case is going to the FA or the DA. |
| SD3587194 <br /> [Change 50110](https://dev.azure.com/digdir/Altinn/_workitems/edit/50110) | Operating supplier <br /> Tommy | Eksternal | SQL Patching - AI-PROD | Approved Schedule for implementation in the environment | SD <br /> Change Manager <br /> Suppliers <br /> <br />High Risk Changes: <br /> Digdir/Technical experts <br /> Digdir/Incident Manager <br /> <br /> If the change entails major consequences outside working hours : <br />Digdir/Contingency Guard  <br /> Digdir Emergency management | n/a | Normal Change processed by a Change Manager |
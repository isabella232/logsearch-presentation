## [ CF + ELK <br /> Logging in the clouds ](#1)

```nohighlight
As a CF operator
I can extend my Cloud Foundry platform with log analysis
Using Logsearch for Cloudfoundry
```

---


## [ Microservices - must be this tall to play ](#2)

* Log and metric analysis required for continuous deployment


---

## [ History ](#)

* Logsearch - an opensource project to deploy Elastic ELK stack with BOSH
  * sponsored for 2 years by City Index (thank you!)
* Logsearch for Cloud Foundry - an opensource Logsearch addon:
  * Extracts, parses and dashboards for CF App and Platform logs and metrics
  * Integrates with CF UAA to provide multi-tenant access control
* ELK for Pivotal Cloud Foundry - a commerical tile that adds:
  * Log parsing for Spring Cloud based microservices
  * Additional focus on security and audit logs
  * Support

---

## [ Running Logsearch at scale for PWS ](#3)

* [Jack to present this section]
* Discuss how Logsearch is used at PWS for log analysis
* Focus on scalability of Logsearch
* Discuss multi-az ingestion pipelines - architecture diagram?

---

## [ BOSH Health Monitor Metrics ](#4)

* Demo of BOSH Health Monitor metrics

---

## [ Blue / Green deployment ](#4)

* Demo of dicey-app blue/green deployment

---

## [ Cross Microservice Transaction Tracing ](#4)

* Demo of cf-SpringBootTrader cross microservice log analysis

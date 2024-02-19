<h1 align="center">Datadog Agent: Definitions, Configurations and Integrations</h1>

### Overview of the Section
* **[Datadog Agent - definitions and configurations](#agent)**

#
### <a name="agent">Datadog Agent - definitions and configurations</a>


**What is a Software Integration?**
Software integration is the process of combining to separate isolated software pieces to work together.

**How Datadog Agent works?**
The Datadog Agent is software that runs on your hosts. After installation it automatically starts to collects events and metrics from hosts and sends them to Datadog, where you can search, filter, aggregate and alert on information. 

The Datadog Agent acts like a middle layer between your application and Datadog website.

The main components are two:
1. Collector – which collects data from your host on every 15 seconds
2. Forwarder – which sends data to Datadog over https

The main configuration file is: ``C:\ProgramData\Datadog\datadog.yaml``
Configuration files for Integrations are in: ``C:\ProgramData\Datadog\conf.d``

![Agent](https://github.com/tsokac2/-_-Datadog_CheatSheet/blob/main/src/03.JPG)


**[Back To The Top](#Overview-of-the-Section)**
#
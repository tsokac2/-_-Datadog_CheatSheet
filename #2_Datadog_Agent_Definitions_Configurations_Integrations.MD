<h1 align="center">Datadog Agent: Definitions, Configurations and Integrations</h1>

### Overview of the Section
* **[Definitions and configurations](#agent)**
* **[Display host basic metrics and default host dashboards](#display-host)**
* **[Integration with Internet Information Server (IIS)](#iss)**

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

- The main configuration file is: ``C:\ProgramData\Datadog\datadog.yaml``
- Configuration files for Integrations are in: ``C:\ProgramData\Datadog\conf.d``

![Agent](https://github.com/tsokac2/-_-Datadog_CheatSheet/blob/main/src/03.JPG)

**[Back To The Top](#Overview-of-the-Section)**
#
### <a name="display-host">Datadog Agent - display host basic metrics and default host dashboards</a>

#### 1. Datadog Agent:

- Installed on the host, collects various metrics.
- Provides information about:
    - Agent version
    - System metrics (CPU, memory, network, etc.)
    - Custom tags (e.g., location)

#### 2. Default Cost Dashboards:
Created automatically after agent installation.

**Five dashboards available**:
- Host counts
- Monitor notifications
- System disk latency
- System metrics
- System networking

#### 3. Using Custom Tags for Cost Filtering:

- Define custom tags (e.g., location) for your host.
- Use these tags to filter and view cost associated with specific locations.

#### 4. Key Points:
- Datadog agent collects various system metrics.
- Default dashboards provide basic overviews of system health and cost.
- Custom tags can be used for advanced filtering and cost analysis.

![Active Host](https://github.com/tsokac2/-_-Datadog_CheatSheet/blob/main/src/04.JPG)

**[Back To The Top](#Overview-of-the-Section)**
#

### <a name="iss">Datadog Agent - integration with Internet Information Server (IIS)</a>



**[Back To The Top](#Overview-of-the-Section)**

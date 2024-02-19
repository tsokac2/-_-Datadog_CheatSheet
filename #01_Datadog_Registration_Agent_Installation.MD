<h1 align="center">Datadog_Registration_Agent_Installation</h1>

### Overview of the Section
* **[What is an Application Performance Management?](#apm)**
* **[Datadog](#Datadog)**
* **[Basic Definitions - host, agent and tags](#basic)**

#
### <a name="apm">What is an Application Performance Management?</a>

The translation of IT metrics into business.

A practice to monitor application insights, so we can:
- Improve performance
- Improve user experience
- Reduce issues and errors

![apm](https://github.com/tsokac2/-_-Datadog_CheatSheet/blob/main/src/01.JPG)

![apm-2](https://github.com/tsokac2/-_-Datadog_CheatSheet/blob/main/src/02.JPG)

#
### <a name="datadog"></a>

**Datadog** is a cloud-based monitoring and analytics platform that provides comprehensive observability into the performance of applications, infrastructure, and logs. 

It is widely used by organizations to gain insights into their IT environments, detect and troubleshoot issues, and optimize performance. 

Datadog offers a range of features, including real-time monitoring, alerting, dashboarding, and collaboration tools.

**[Back To The Top](#Overview-of-the-Section)**
#
### <a name="basic">Basic Definitions - host, agent and tags</a>

#### Host:
- **Definition**: A host refers to any physical or virtual operating system instance that you want to monitor with Datadog.
- **Examples**: It could be a server, virtual machine, Kubernetes bot, or an App Service Plan instance in the case of Azure App Services.
- **Role**: The host is essentially the server where the Datadog Agent is installed, and monitoring is desired.

#### Datadog Agent:
- **Definition**: The Datadog Agent is a software downloaded from the Datadog website that runs on hosts.
- **Function**: It collects events and metrics from the host and sends them back to Datadog for analysis of monitoring and performance data.
- **Importance**: The Datadog Agent is considered the heart of Datadog, acting as a middle layer between applications and the Datadog website.
- **Operation**: After installation, the agent starts collecting metrics and events from systems and applications.

#### Datadog Tags:
- **Definition**: Tags are additional dimensions added to Datadog telemetries for filtering, aggregation, and comparison in visualizations.
- **Importance**: Tags help distinguish between different hosts, servers, or instances where Datadog agents are installed.
- **Example**: Hosts can be tagged with information like Datadog tech version (e.g., stage or production) to identify their respective environments.
- **Customization**: Datadog provides system tags, and users can add custom tags as needed.

**[Back To The Top](#Overview-of-the-Section)**
#
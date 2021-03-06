Systems / WorkloadManagement / <INSTANCE> / Agents - Sub-subsection
================================================================

 In this subsection each agent is described.

+----------+----------------------------------+----------------+
| **Name** | **Description**                  | **Example**    |
+----------+----------------------------------+----------------+
| *Agent*  | Subsection named as the agent is | InputDataAgent |
|          | called.                          |                |
+----------+----------------------------------+----------------+

Common options for all the agents are described in the table below:

+---------------------+---------------------------------------+------------------------------+
| **Name**            | **Description**                       | **Example**                  |
+---------------------+---------------------------------------+------------------------------+
| *LogLevel*          | Log Level associated to the agent     | LogLevel = DEBUG             |
+---------------------+---------------------------------------+------------------------------+
| *LogBackends*       |                                       | LogBackends = stdout, server |
+---------------------+---------------------------------------+------------------------------+
| *MaxCycles*         | Maximum number of cycles made for     | MaxCycles = 500              |
|                     | Agent                                 |                              |
+---------------------+---------------------------------------+------------------------------+
| *MonitoringEnabled* | Indicates if the monitoring of agent  | MonitoringEnabled = True     |
|                     | is enabled. Boolean values            |                              |
+---------------------+---------------------------------------+------------------------------+
| *PollingTime*       | Each many time a new cycle must start | PollingTime = 2600           |
|                     | expressed in seconds                  |                              |
+---------------------+---------------------------------------+------------------------------+
| *Status*            | Agent Status, possible values Active  | Status = Active              |
|                     | or Inactive                           |                              |
+---------------------+---------------------------------------+------------------------------+


Agents associated with Configuration System:

.. toctree::
   :maxdepth: 2
   
   InputDataAgent/index
   JobCleaningAgent/index
   JobHistoryAgent/index
   MightyOptimizer/index
   PilotStatusAgent/index
   SiteDirector/index
   StalledJobAgent/index
   StatesAccountingAgent/index
   TaskQueueDirector/index
   TaskQueueDirector/index 


---
title: "Publication Information, Agents (Snapshot Publication) | Microsoft Docs"
ms.custom: ""
ms.date: "03/06/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "replication"
ms.tgt_pltfrm: ""
ms.topic: conceptual
f1_keywords: 
  - "sql12.rep.monitor.publicationinfo.downlevelagents.snapshot.f1"
ms.assetid: 599ff80b-392c-43aa-9db2-dc4ed33d4f6e
caps.latest.revision: 22
author: MashaMSFT
ms.author: mathoma
manager: craigg
---
# Publication Information, Agents (Snapshot Publication)
  The **Agents** tab displays summary information on the Snapshot Agent for the selected publication.  
  
## Options  
 For more detailed information and tasks related to the Snapshot Agent, right-click the row for the agent, and then click an option on the shortcut menu. To change the way that the grid displays data, right-click the grid, and then click one of the following options:  
  
-   **Sort**: Sort on one or more columns in the **Sort Columns** dialog box.  
  
-   **Choose Columns to Show**: Select which columns to display and the order in which to display them in the **Choose Columns** dialog box.  
  
-   **Filter**: Filter rows in the grid based on column values in the **Filter Settings** dialog box.  
  
-   **Clear Filter**: Clear any filter settings for the grid.  
  
 Filter settings are specific to each grid. Column selection and sorting are applied to all grids of the same type, such as the publications grid for each Publisher.  
  
 **Status**  
 The status of the Snapshot Agent. The following list shows the possible status values:  
  
-   Error  
  
-   Retrying failed commands  
  
-   Not running  
  
-   Completed  
  
 **Agent**  
 The Snapshot Agent. This is the only agent associated with a snapshot publication. The Distribution Agent is associated with subscriptions to this publication. For more information, see [View Information and Perform Tasks for the Agents Associated With a Subscription &#40;Replication Monitor&#41;](monitor/view-information-and-perform-tasks-for-subscription-agents.md).  
  
 **Last Start Time**  
 The last time the agent started.  
  
 **Duration**  
 The amount of time the agent has run. The time represents elapsed time if the agent is currently running and total time if the agent has run previously.  
  
 **Last Action**  
 The last action performed during the most recent run of the agent.  
  
## See Also  
 [Start the Replication Monitor](monitor/start-the-replication-monitor.md)   
 [View Information and Perform Tasks for a Publication &#40;Replication Monitor&#41;](monitor/view-information-and-perform-tasks-for-a-publication-replication-monitor.md)   
 [View Information and Perform Tasks for the Agents Associated With a Publication &#40;Replication Monitor&#41;](monitor/view-information-and-perform-tasks-for-publication-agents.md)   
 [Monitoring Replication](monitoring-replication.md)  
  
  

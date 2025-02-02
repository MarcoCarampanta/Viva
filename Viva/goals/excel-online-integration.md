---
title: "Excel Online Integration"
ms.reviewer: 
ms.author: vsreenivasan
author: ms-vikashkoushik
manager: <TBD>
audience: Admin
f1.keywords:
- NOCSH
ms.topic: article
ms.service: viva
ms.subservice: viva-goals
localization_priority: Priority
ms.collection:  
- m365initiative-viva-goals
search.appverid:
- MET150

description: "Learn how to sync your Excel cell values with OKRs in Viva Goals."
---

# Excel Online integration

> [!IMPORTANT]
> Viva Goals is currently available only for private preview customers, and only in English. The features described here are subject to change. [Learn more about Viva Goals.](https://go.microsoft.com/fwlink/?linkid=2189933)

## Introduction to Excel Online integration

The Viva Goals Excel Online integration allows you to update your Objectives and Key Results (OKR) progress automatically depending on the value of specific cells of Excel Sheets. 
  
Let's use this example: you use Excel Online to keep tabs on the revenue generated by the Sales team, and you have an objective in Viva Goals for achieving $3M ARR for a quarter. When you link this objective to the corresponding Sheet in Excel Online, the status of your OKR will be updated automatically as the cell value changes. You can save yourself the hassle of switching back and forth between your sheets and Viva Goals to update progress. Viva Goals will automatically sync the values for you and chart your progress, saving time while keeping your OKRs current.

## How to enable the Excel Online integration

Admins can perform the following steps to enable this integration:

- From the sidebar, go to **Admin** and select the **Integrations** tab.

- Against Excel Online, you'll have an option to **Enable** the integration. If a connection has been made previously or if the integration has been enabled already, you'll have the option to **Manage** the enabled integration.

- This integration can also be **disabled** from the same section. Go to **Change** and select **Disable integration** from the dropdown to disable the integration.

## How to configure the Excel Online connection

- After enabling the integration, the first step is to configure an Excel Online connection.

- Select **New Connection**, and sign in to your Excel account.

- Provide a name for the connection.

- It's optional to share this connection with other users in the organization. Select **Next** to get up and running with this integration. You can edit the saved connection at any time.

Viva Goals allows you to connect with multiple Excel sheets. Select **New Connection** to fetch data from another sheet. You can differentiate these connections using names, and the names will be displayed to other users when they link their OKRs with Excel Online data.

## How to connect the Excel Online connection to an OKR

Once you have configured the connection, the next step is to start linking OKRs to Excel sheets.

- While **creating or editing an OKR**, select **Connect data source to auto-update progress**. From the drop-down menu, select **Excel Online**.

- If you have already created a connection, or if your admin has shared a connection with you, that connection will be selected automatically. Viva Goals will prompt you to create a new connection only if there are no connections created or shared.

- Select the method using which you want to measure the progress—percent complete or KPI (success metric). If you're choosing key performance indicator (KPI), provide a metric, starting value, and target value.

- Select a connection, and select a **Workbook**. As soon as you select the Workbook, the associated Sheets will be displayed in the Sheet dropdown menu. Select a **Sheet**.

- To locate the cell accurately, furnish the **Column** and the **Row Number**.

- The progress will be calculated based on the number present in the chosen cell (if you have chosen KPI metric to track progress), or will be calculated based on the percentage accomplished (if you have chosen percent complete to track progress).

- Select **Next** and then **Save**.

> [!NOTE]
> The sync will happen once every hour. If you want to trigger the sync manually, select the Excel Online icon next to the progress bar of the objective, and select the sync icon.

You have now successfully linked your objective to a Sheet in Excel Online to track the cell value, and updated the status of the corresponding OKR automatically.

The colors of the progress bar in Viva Goals indicates the status of the objective.

- If the progress is 0 - 25% less than the expected progress at any given point in time, the OKR status is Behind, and the progress bar color will be Orange.

- If the progress is over 25% less than the expected progress at any given point in time, the OKR status is At Risk, and the progress bar color will be Red.


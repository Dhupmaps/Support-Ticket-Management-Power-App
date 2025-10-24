# Power Apps Ticketing System

A Microsoft Power Apps project designed for managing support tickets. This application provides a user-friendly interface for users to submit issues and for administrators to track and manage them.

[cite_start]This project was built as part of an RPA (Robotic Process Automation) initiative.

## Features

Based on the app's structure, it includes the following features:

* [cite_start]**Home Screen:** A landing page for users.
* [cite_start]**Ticket Submission:** A form for users to create and submit new support tickets[cite: 5].
* [cite_start]**My Tickets:** A screen where users can view the status of their own submitted tickets[cite: 11].
* [cite_start]**Admin Dashboard:** A central dashboard for administrators to view and manage all incoming tickets[cite: 6].
* [cite_start]**Edit Ticket:** Functionality for users or admins to modify existing ticket details[cite: 9].
* [cite_start]**Success Screen:** A confirmation page shown after a successful submission[cite: 11].

## Technologies Used

* **Microsoft Power Apps** (Canvas App)
* **[Add Your Data Source Here]** (e.g., Dataverse, SharePoint List, SQL Server)

## How to Install and Use

[cite_start]This repository contains the exported `Support-Ticket-Management-Power-App.msapp` package. To use this app, you must import it into your own Power Apps environment.

**Prerequisites:**
* A Microsoft 365 or Power Apps license.
* **[IMPORTANT]** You must first set up the data source (e.g., create the SharePoint List or Dataverse tables) that this app connects to.

**Installation Steps:**

1.  [cite_start]**Download:** Download the `.msapp` file  from this repository.
2.  **Navigate to Power Apps:** Go to [make.powerapps.com](https://make.powerapps.com).
3.  **Import App:**
    * Select **Apps** from the left-hand navigation pane.
    * Click on **Import canvas app**.
4.  **Upload:**
    * Click **Upload** and select the `.msapp` file you downloaded.
    * Wait for the app details to load.
5.  **Configure Connections:**
    * Under the **Import Setup** options, the app will likely require connections (e.g., to Dataverse, SharePoint, Office 365 Users).
    * For each required connection, either select an existing one from your environment or create a new one.
6.  **Import:** Once all connections are configured, click **Import**.
7.  **Publish:** After the import is successful, go to the **Apps** list, find the imported app, click the **...** (more commands), and select **Publish**.

You can now run the app from your Power Apps player or by sharing the link.

## App Structure

The app contains the following screens:

* [cite_start]`Home Screen` 
* [cite_start]`Ticket Submit` [cite: 5]
* [cite_start]`My Tickets` [cite: 11]
* [cite_start]`Admin Dashboard Screen` [cite: 6]
* [cite_start]`Edit Ticket` [cite: 9]
* [cite_start]`Success` [cite: 11]

And the following components:

* [cite_start]`Header Component` [cite: 12]

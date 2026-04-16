# Digital-Champions-Rules-and-Instructions <!-- omit in toc -->
This document simply contains the rules and instructions you should adhere to during Digital Champions. This is to keep everyone safe and compliant with the College's policies.
- [Introduction](#introduction)
  - [Equipment and tools](#equipment-and-tools)
- [The Project](#the-project)
- [Competing for Data](#competing-for-data)
- [Event Incidents](#event-incidents)
- [Sabotage](#sabotage)
- [Scoring](#scoring)
  - [Project and Data](#project-and-data)
  - [Incidents](#incidents)
  - [Sabotage](#sabotage-1)
  - [Secret Scoring](#secret-scoring)
- [Example Scores](#example-scores)

# Introduction

This week long event we have split you into two teams. Each team will be required to create a web development project following a simple brief. You will also have opportunities to compete for data which you can use in your project to get additional points.

## Equipment and tools

You will be provided a computers and logins that have the following programs:

- Visual Studio Code
- Github Copilot
- Postman

> [!NOTE]
> If you would like to install any other programs you must ask a member of staff first so we can keep the event safe

You may use online tools like GitHub but you should use your college account to create the account.

In your room you have a number of computers connected to a single VLAN that is separate from the other group's network.

There are also 2 computers (that will be labelled) that are connected to a separate VLAN to simulate a live system. These 2 computers in each room will be connected to a VLAN that also has an API server you will use to get the data you will use in your project.

# The Project

You will be provided with a task similar to a real assignment. You will, during the week, produce a website or webapp that will be hosted on one of the two machines connected to the API server.

# Competing for Data

Two of the computers in your room (labelled to make it clear) are connected to a separate VLAN with access to an API on ip address <IP-ADDRESS-HERE>.
One of these computers you will use for hosting your website/ webapp throughout the week.

- Twice per day a task will be released (we will not tell you when) on the API which you can access using a HTTP GET request to `/task/<TASK_NUMBER>`. 
- Once you have an answer to a task you can submit it using a POST request to `/task/<TASK_NUMBER>/submit` with "code" being the field to submit your answer.
- A task will remain up during the event until somebody achieves it.
- Each task can only be achieved once and as soon as it has the data will be unavailable to the other team.
- **NOTE** once a successful code has been submitted then the API will lock down that endpoint so be careful when submitting your answer.

# Event Incidents

During the event we will also introduces incidents that can occur at the office. You will gain points based on how you handle the incidents and lose points if you succumb to an incident.

# Sabotage

You will also be able to interact with the other team in some restricted ways.

You **MUST NOT** delete any files, code or data from the other team. Doing so will deduct significant points and may have you removed from the event entirely.

Your ID cards are only able to access the room you should be in. That doesn't mean you're not allowed to enter the other teams room.

- **Stealing Data:** Once data has been collected it becomes unavailable. If you manage to get hold on data that your team did not get then inform the **Event Host** (a lecturer) in the room, show them the data and they will (if the data is real) penalise the other team for that data leak.
- **Compromising a device** - If you manage to access a machine of the opposing team, run the "Compromise_Machine.exe" program on the computer. This will penalise the opponent significantly. 

> [!WARNING]
> If you ever act unprofessionally during the event - e.g. barging into a room, stealing and keeping someone's lanyard, create malware of any kind - you will be removed from the event. This event is designed to simulate a real office with possible threats so we expect you to act in a professional manor as you would in a work place.

# Scoring

## Project and Data

| Action                                    | Score |
| :---------------------------------------- | ----: |
| Webapp/site each day                      |   + 5 |
| Data obtained                             |  + 10 |
| Data used in app at the end of the event  |  + 10 |
| Each key feature implemented successfully |   + 5 |


## Incidents

| Action                                         | Score |
| :--------------------------------------------- | ----: |
| Effected by Incident                           |  - 20 |
| Incident identified and reported within 5 mins |  + 10 |
| Data loss/ hour lost from incident             |  - 10 |
| Incident prevented/ recovered from             |   + 5 |
| Incident Documented properly                   |   + 5 |


## Sabotage

| Action             | Score |
| :----------------- | ----: |
| Data stolen        |  - 10 |
| Device Compromised |  - 15 |

## Secret Scoring

There is also some secret scoring the staff will do as we go for good workplace and cyber practices. We will reveal these at the end of the event.

# Example Scores

| Action                                         |    Score |
| :--------------------------------------------- | -------: |
| **Day 1**                                      |    **0** |
| Data obtained                                  |     + 10 |
| Effected by Incident                           |     - 20 |
| Incident Documented properly                   |      + 5 |
|                                                |          |
| **Day 2**                                      |  **- 5** |
| Data Stolen                                    |     - 10 |
| Device Compromised                             |     - 15 |
| Data obtained                                  |     + 10 |
| Website up                                     |      + 5 |
| Effected by Incident                           |     - 20 |
| Incident identified and reported within 5 mins |     + 10 |
| Data loss                                      |     - 10 |
| Incident Documented properly                   |      + 5 |
|                                                |          |
| **Day 3**                                      | **- 30** |
| Data Obtained                                  |     + 10 |
| Website up                                     |      + 5 |
| Effected by Incident                           |     - 20 |
| Incident Identified and reported within 5 mins |     + 10 |
| Incident recovered from                        |      + 5 |
| Incident documented properly                   |      + 5 |
|                                                |          |
| **Day 4**                                      | **- 15** |
| Data Obtained                                  |     + 10 |
| Website up                                     |      + 5 |
| Incident prevented                             |      + 5 |
| Incident identified and reported within 5 mins |      + 5 |
| Incident Documented properly                   |      + 5 |
| Data stolen                                    |     - 10 |
|                                                |          |
| **Day 5**                                      | **+ 10** |
| Data obtained                                  |     + 10 |
| Data stolen                                    |     - 10 |
| Website up                                     |      + 5 |
| Incident prevented                             |      + 5 |
| Incident identified and reported within 5 mins |      + 5 |
| Incident Documented properly                   |      + 5 |
| Data used in app at the end x 5                |     + 50 |
| Key feature implemented x 6                    |     + 30 |
| **TOTAL**                                      | **+ 90** |



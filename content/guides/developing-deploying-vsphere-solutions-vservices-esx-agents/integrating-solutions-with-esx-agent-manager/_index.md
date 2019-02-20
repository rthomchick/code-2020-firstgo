---
api:
api_method:
api_parameters:
api_path:
api_response:
api_return_type:
api_structures:
author:
categories:
date: 2019-02-08T16:56:22-08:00
draft: true
description: ""
devcenter:
images:
keywords:
lastmod:
layout: "article"
linkTitle:
platform:
product_name:
product_version:
programming_lang:
resources:
series:
slug:
tags:
title: "Integrating Solutions with vSphere ESX Agent Manager"
toc: true
type: "article"
url:
videos:
weight: 5
---
vSphere ESX Agent Manager is a standard vCenter Server solution that allows other solutions to deploy, monitor, and manage ESX agents on ESXi hosts.

ESX Agent Manager performs the following functions:

- Provisions ESX agent virtual machines for solutions.
- Monitors changes to the ESX agent virtual machines and their scope in vCenter Server.
- Reports configuration issues in the ESX agents to the solution.
- Integrates agent virtual machines with vSphere features such as Distributed Resource Scheduler (DRS), Distributed Power Management (DPM), vSphere High Availability (HA), fault tolerance, maintenance mode, and operations such as adding and removing hosts to and from clusters.

A solution can add functions to an ESXi host by deploying an ESX agent virtual machine and an optional vSphere Installation Bundle (VIB) that provide this function.

Every vCenter Server instance contains a running ESX Agent Manager.

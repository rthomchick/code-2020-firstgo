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
title: "Introduction to vSphere Solution Development"
toc: true
type: "article"
url:
videos:
weight: 1
---
You can improve your extension solutions by understanding the process of extending the user interface layer and service layer of the vSphere Client, and packaging and deploying your extension solutions. Follow best practices to ensure optimal performance and scalability, and to improve the security of your vSphere Client extensions.

You can add functions to vSphere by developing software applications that you register as vCenter Server extensions. A vSphere Solution is an extension that registers with vCenter Server and implements some or all of the extension features of the vSphere API.

Developing and Deploying vSphere Solutions, vServices, and ESX Agents uses the terms solution and extension interchangeably.

A vSphere Solution is an object or program that you create by extending specific classes in the vSphere Web Services API. After you register your solution with the instance of the ExtensionManager managed object associated with your vCenter Server, you see your solution under Home > Administration > Solutions > vCenter Server Extensions of your vSphere Web Client.

You can create a vService solution to provide access for a specific application to connect to a service across the network.

You can create an ESX Agent to extend the functions of an ESXi host and provide additional services that a vSphere solution requires.

The vService Manager and ESX Agent Manager are pre-built solutions that are part of the vCenter Server Extensions functionality within the vCenter Server.

The vSphere ESX Agent Manager includes an API library that allows you to adapt and modify the ESX Agent Manager (EAM) Sample Solution and view it using the vSphere Web Client.

The extension features in the vSphere Web Services API include functions so that you can perform the following tasks:

- Register permissions, faults, and events for an extension.
- Identify and prevent manual operations on virtual machines and vApps that extensions deploy.
- Integrate extensions with ExtensionManager.
- Store data about extensions in the vSphere database.
- Provide user interface plug-ins that extend the vSphere Web Client.

To use the extension functions of the vSphere API, a solution must register itself with the ExtensionManager that runs in a vCenter Server instance. By registering with ExtensionManager, a solution can access the extension features of the vSphere extension API.

You can develop solutions that add functions to the standard functions of vCenter Server. You can deploy a solution as an Open Virtualization Format (OVF) package, with optional VMware vSphere Installation Bundles (VIB). You can also install solutions by using an installer, such as Windows Installer (MSI) or RPM Package Manager. Most of the extension functions in the vSphere API are independent of the technology that you use to deploy a solution. If you deploy a solution by using OVF, you can use the vCenter Extension vService to simplify the registration of the solution with vCenter Server.

vCenter Server 6.7 provides built-in solutions.

- vSphere ESX Agent Manager
- vService Manager

vSphere ESX Agent Manager and vService Manager are part of a standard vCenter Server installation. These solutions appear in vCenter Server Extensions and ExtensionManager with any other solutions that register with ExtensionManager.

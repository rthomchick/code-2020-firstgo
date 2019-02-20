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
title: "Integrating an Extension with the vCenter Extension vService"
toc: true
type: "article"
url:
videos:
weight: 6
---
The vCenter Extension vService simplifies the installation and deployment of extensions. By integrating an extension with the vCenter Extension vService you can deploy extensions from the vSphere Web Client without having to enter the connection parameters of the vCenter Server on which you install the extension, or provide the login credentials for that vCenter Server instance.

The vCenter Extension vService performs the following functions for solutions that you integrate with it.

- Provides the extension with the connection parameters of the vCenter Server instance.
- Registers the extension certificate with vCenter Server.

For example, to deploy the EAM Sample Solution you provide the IP address and login credentials in the eamri.properties file, which requires you to update the solution for every vCenter Server instance on which you install it. By integrating an extension with the vCenter Extension vService, you avoid this manual step.
Every vCenter Server instance contains a running ESX Agent Manager.

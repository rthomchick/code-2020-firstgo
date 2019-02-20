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
date:
draft: true
description: "Dude, where's my description?"
devcenter:
images:
keywords:
lastmod:
layout: "article"
linkTitle:
platform:
product_name: "vSphere"
product_version:
programming_lang:
resources:
series:
slug:
tags:
title: "Components and Services of a Virtual Environment"
type: "article"
url:
videos:
weight: 1
---
## Overview
Starting with vSphere 6.0, the deployment of the virtual environment consists of two major components that provide different sets of services, the VMware Platform Services Controller and vCenter Server. You can deploy vCenter Server with an embedded or external Platform Services Controller.

### Services Installed with Platform Services Controller
The Platform Services Controller group of infrastructure services contains vCenter Single Sign-On, License Service, Lookup Service, and VMware Certificate Authority. The services installed with the Platform Services Controller are common to the entire virtual environment. A Platform Services Controller can be connected to one or more vCenter Server instances. In a deployment that consists of more than one Platform Services Controller, the data of each service is replicated across all Platform Services Controller instances.

In vSphere Automation API client applications, you use the vCenter Single Sign-On and the Lookup Service on the Platform Services Controller to provide a range of functionality.

|  |   |
|---|---|
|  Authentication and Session Management  | You use the vCenter Single Sign-On service to establish an authenticated session with the vSphere Automation Endpoint. You send credentials to the vCenter Single Sign-On service and receive a SAML token that you use to obtain a session ID from the vSphere Automation Endpoint. Alternatively, you can access the vSphere Automation APIs in a sessionless manner by including the SAML token in every request that you issue to the vSphere Automation Endpoint.  |
|  Service Discovery | You use the Lookup Service to discover the endpoint URL for the vCenter Single Sign-On service on the Platform Services Controller, the location of the vCenter Server instances, and the vSphere Automation Endpoint. |

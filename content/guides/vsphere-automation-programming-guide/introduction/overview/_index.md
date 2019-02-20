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
description:
devcenter:
images:
keywords:
lastmod:
layout: "article"
linkTitle:
parent:
platform:
product_name: "vSphere"
product_version:
programming_lang:
resources:
series:
slug:
tags:
title: "vSphere Automation SDKs Overview"
type: "article"
url:
videos:
weight: 1
---
## Overview
The vSphere Automation API provides a unified programming interface to vSphere Automation services that you can use through SDKs provided in five programming languages. The vSphere Automation API provides a service-oriented architecture for accessing resources in the virtual environment by issuing requests to the vSphere Automation Endpoint.

vSphere Automation API client applications communicate with services on the Platform Services Controller and vCenter Server.

Communication Model of vSphere Automation API Client Applications

{{< figure src="GUID-97C54372-2A9C-4421-87C7-3D52EF756A91-high-2.png" >}}

vSphere Automation API client applications use the Lookup Service to retrieve the vCenter Single Sign-On endpoint, the vSphere Automation Endpoint, and the endpoints of services that are exposed through the vSphere API. To access vSphere Automation services such as Content Library and Tagging, client applications issue requests to the vSphere Automation Endpoint. By using the vCenter Single Sign-On service, client applications can either establish an authenticated vSphere Automation session, or authenticate individual requests to the vSphere Automation Endpoint.

Client applications can access services that are exposed through the vSphere API by using the vSphere Management SDK.

Depending on the vSphere deployment model, client applications can communicate with vSphere Automation services on a single vCenter Server instance or multiple vCenter Server instances. For more information about the vSphere deployment models, see Components of the vSphere Automation Virtualization Layer

### SDK Developer Setup
To start developing a vSphere Automation API client application, you must download the software and set up a development environment. You can find instructions for setting up a development environment in the README for each vSphere Automation SDK.

### SDK Samples
The vSphere Automation SDKs provide sample applications that you can extend to implement client applications that serve your needs. The code examples in the vSphere Automation SDKs documentation are based on these sample applications.

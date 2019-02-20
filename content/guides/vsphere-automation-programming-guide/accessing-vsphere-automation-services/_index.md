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
parent: "vSphere Automation SDK Programming Guide"
platform:
product_name: "vSphere"
product_version:
programming_lang:
resources:
series:
slug:
tags:
title: "Accessing vSphere Automation Services"
type: "article"
url:
videos:
weight: 6
---
vSphere Automation SDK provides mechanisms for creating remote stubs to give clients access to vSphere Automation services.

The sequence of tasks you must follow to create a remote stub starts with creating a ProtocolFactory. You use the protocol factory object to create a ProtocolConnection. Connection objects provide the basis for creating stub interfaces to vSphere Automation services.

When you establish a connection to the vSphere Automation Endpoint, you can create a StubFactory object and a StubConfiguration object. With these objects, you can create the remote stub for the vSphere Automation service that you want to access.

The complete connection sequence also includes SSL truststore support and a temporary StubConfiguration that you use for SAML token authentication and session creation.

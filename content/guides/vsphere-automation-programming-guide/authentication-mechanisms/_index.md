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
parent: "vSphere Automation SDK Programming Guide"
platform:
product_name: "vSphere"
product_version:
programming_lang:
resources:
series:
slug:
tags:
title: "Authenticating Mechanisms"
type: "article"
url:
videos:
weight: 5
---
To perform operations on services in the vSphere environment, you must create an authenticated connection to the services that you want to use. With the vSphere Automation SDKs you can authenticate and access vSphere Automation services.

Client applications can choose from two supported authentication patterns for accessing services in the virtual environment.

For better security, client applications can request a security token to authenticate connections with the vSphere Automation services.

To invoke operations on services, client applications must create a security context. The security context represents the client authentication. You can achieve authentication by using one of the following mechanisms.

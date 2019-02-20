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
title: "Creating vSphere Solutions"
toc: true
type: "article"
url:
videos:
weight: 3
---
The vSphere SDK provides a set of APIs that you can use to create extensions for vCenter Server. The key SDK objects for extension development are ExtensionManager and Extension.

Use the ExtensionManager managed object in your vCenter Server instance to register a new extension. Extensions can add new objects to the vCenter inventory. Extensions define tasks, events, and faults that relate to actions that the solution performs on the objects, the events that occur in the extension, and the problems that the objects encounter. You can also use ExtensionManager to add user interface elements to the vSphere Web Client to allow users to interact with the objects that your extension provides to vCenter Server.

ExtensionManager adds data objects to the vSphere Extension APIs that integrate extensions as vCenter solutions that you can manage.

For information about how to develop vSphere Web Client extensions, see the VMware vSphere Web Client Extensions Programming Guide.

For information about developing vSphere applications, see the vSphere Web Services SDK Programming Guide and the VMware vSphere API Reference documentation.

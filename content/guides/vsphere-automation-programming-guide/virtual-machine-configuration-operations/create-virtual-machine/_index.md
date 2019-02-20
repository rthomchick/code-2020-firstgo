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
platform:
product_name: "vSphere"
product_version:
programming_lang:
resources:
series:
slug:
tags:
title: "Create a Virtual Machine"
type: "article"
url:
videos:
weight: 2
---
You can create a virtual machine by using the VM.create method. The method takes as parameter a CreateSpec instance that allows you to specify the attributes of the virtual machine.

To create a virtual machine you must specify the virtual machine attributes by using the CreateSpec class. For example, you can specify a name, boot options, networking, and memory for the virtual machine. See Configuring a Virtual Machine.

All attributes are optional except the virtual machine placement information that you must provide by using the PlacementSpec class. Use the virtual machine placement specification to set the datastore, cluster, folder, host, or resource pool of the created virtual machine and make sure that all these vSphere objects are located in the same data center in a vCenter Server instance.

For more information refer to the API Reference documentation inside the SDK.

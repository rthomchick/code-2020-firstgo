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
title: "Filtering Virtual Machines"
type: "article"
url:
videos:
weight: 1
---
You can retrieve a list of virtual machines that match a specific filter or a group of up to one thousand virtual machines available in a specific vCenter Server instance.

You can retrieve a list of up to one thousand virtual machine IDs for a single vCenter Server instance by filtering them based on a specific requirement, such as a host, cluster, datacenter, or resource pool on which the VMs are running.

Call the list methods of the VM service to retrieve only a list of the virtual machines that match your specific criteria. The method takes as parameter the VMTypes.FilterSpec instance that you can use to describe the virtual machine filter.

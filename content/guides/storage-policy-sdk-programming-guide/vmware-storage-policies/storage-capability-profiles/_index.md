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
description:
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
title: "Storage Capability Profiles"
toc: true
type: "article"
url:
videos:
weight: 1
---
To use a storage capability profile, you define storage requirements and associate a virtual machine with a storage policy. When you create a VM, vCenter Server correlates its VM storage policy with the storage policy service to determine an appropriate location for VM home and virtual disk files.

A storage policy consists of a set of subprofiles. Each subprofile defines a set of storage capabilities, and corresponds to a numbered Rule Set in the vSphere Web Client. Several storage policies pre-exist in vSphere, including:

- The VM Encryption Policy is a sample storage policy for VM Home and virtual disk encryption.
- The vSAN Default Storage Policy can be easily modified, but is the storage policy used by default for vSAN datastores.
- The VVol No Requirements Policy allows the storage array, through the VASA provider, to determine the best placement strategy for VM Home and virtual disks.

In the vSphere Web Client, all of these storage policies, and ones you create, have a Check Compliance button to verify that virtual machines assigned to that storage policy are correctly placed on storage devices.

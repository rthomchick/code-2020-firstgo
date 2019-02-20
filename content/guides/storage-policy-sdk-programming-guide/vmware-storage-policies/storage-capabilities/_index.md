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
title: "Storage Capabilities"
toc: true
type: "article"
url:
videos:
weight: 1
---
The storage provider describes capabilities of a storage array, which the storage policy service obtains and presents to the administrator to assist with VM provisioning.

On object-oriented datastores such as vSAN and VVol datastores, storage capabilities originate from software written by the vendor, called a VASA provider. VASA is an abbreviation of vSphere API for storage awareness. The storage policy service can match storage capabilities with VM storage policies formulated in vSphere.

For VVol datastores: storage capabilities may include array type, vendor, RAID level, read latency, write latency, snapshot information, backup frequency, replication, caching, compression, deduplication, and high availability.

For vSAN datastores: storage capabilities may include RAID type, failures to tolerate, disk stripes per object, flash read cache, IOPS limit, encryption, compression, and deduplication.

For VMFS and NFS datastores: administrators can select the VMware encryption storage policy. VM encryption is implemented on the ESXi host rather than on the storage array.

For tag-based policies: administrators can use the vSphere Web Client to define storage policy tags.

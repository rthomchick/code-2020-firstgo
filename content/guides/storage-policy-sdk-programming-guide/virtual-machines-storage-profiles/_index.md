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
title: "Virtual Machine Storage Profiles"
toc: true
type: "article"
url:
videos:
weight: 6
---
## Overview
You can create custom storage policy strings to specify policy rules.

## Create a Stand-Alone Virtual Disk with an Attached Storage Encryption Policy
The following example shows how to format an XML string to specify an I/O filter policy for a virtual disk.

The format is specific to the current version of the VMware Web Services API. This format might not be compatible with other API versions.

### Prerequisites
- Verify that the name for the policy is user-friendly.
- Verify that the ID string to identify the policy is unique. The ID must be unique among the set of policies known to SPBM.

### Procedure

1. Build the policy `<capability>` element, which specifies the filter. {{< gist rthomchick f69a98860381478f210fc3e93757e561 >}}
2. Wrap the `<capability>` element singly in a < subProfiles > element, adding the rule name.   {{< gist rthomchick decfd619b474111ee2511620848f944a >}}
3. Wrap the `<subProfiles>` element singly in a <constraints> element. {{< gist rthomchick f462d4ee2b633aa25e5d84918df543c1 >}}
4. Append profile metadata, such as name and creation date. {{< gist rthomchick fb32b58344c511757adb1fe151289d88 >}}
5. Wrap the `<constraints>` element and metadata in a <storageProfile> element, and prefix an XML header. {{< gist rthomchick 7063458bfb2f6ecc74dcffe27c995dba >}}

### What To Do Next
You can create a ProfileSpec to contain the XML data. See the vSphere Web Services SDK Programming Guide.

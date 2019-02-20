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
title: "Retrieving the Service Registration Object"
type: "article"
url:
videos:
weight: 3
---
## Overview
You must connect to the Lookup Service to gain access to its operations. After you connect to the Lookup Service, you must retrieve the service registration object to make registration queries.

### Procedure
1. Connect to the Lookup Service.
  - Configure a connection stub for the Lookup Service endpoint, which uses SOAP bindings, by using the HTTPS protocol.
  - Create a connection object to communicate with the Lookup Service.
2. Retrieve the Service Registration Object.
  - Create a managed object reference to the Service Instance.
  - Invoke the RetrieveServiceContent() method to retrieve the ServiceContent data object.
  - Save the managed object reference to the service registration object.

With the service registration object, you can make registration queries.

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
title: "Retrieve Service Endpoints on vCenter Server Instances"
type: "article"
url:
videos:
weight: 4
---
## Overview
You can create a function that obtains the endpoint URLs of a service on all vCenter Server instances in the environment. You can modify that function to obtain the endpoint URL of a service on a particular vCenter Server instance.

### Prerequisites
- Establish a connection with the Lookup Service.
- Retrieve a service registration object.

### Procedure
1. Create a registration filter object, which contains the following parts:
  - A filter criterion for service information
  - A filter criterion for endpoint information
2. Retrieve the specified service information by using the List() function. Depending on whether you included the node ID parameter, the List() function returns one of the following results:
  - A list of endpoint URLs for a service that is hosted on all vCenter Server instances in the environment.
  - An endpoint URL of a service that runs on a particular vCenter Server instance.

### What to Do Next
Call the function that you implemented to retrieve service endpoints. You can pass different filter parameters depending on the service endpoints that you need. For more information, see Filter Parameters for Predefined Service Endpoints.

To retrieve a service endpoint on a particular vCenter Server instance, you must retrieve the node ID of that instance and pass it to the function. For information about how to retrieve the ID of a vCenter Server instance, see Retrieve a vCenter Server ID by Using the Lookup Service.

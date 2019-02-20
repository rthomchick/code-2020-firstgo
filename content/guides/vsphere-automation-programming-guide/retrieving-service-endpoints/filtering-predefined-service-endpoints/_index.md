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
title: "Filtering for Predefined Service Endpoints"
type: "article"
url:
videos:
weight: 1
---
## Overview
The Lookup Service maintains a registration list of vSphere services. You can use the Lookup Service to retrieve registration information for any service by setting a registration filter that you pass to the List() function on the Lookup Service. The functions and objects that you can use with the Lookup Service are defined in the lookup.wsdl file that is part of the SDK.

Lookup Service Registration Filters
You can query for service endpoints through a service registration object that you obtain from the Lookup Service. You invoke the List() function on the Lookup Service to list the endpoints that you need by passing LookupServiceRegistrationFilter. LookupServiceRegistrationFilter identifies the service and the endpoint type that you can retrieve.

Optionally, you can include the node ID parameter in the filter to identify the vCenter Server instance where the endpoint is hosted. When the node ID is omitted, the List() function returns the set of endpoint URLs for all instances of the service that are hosted on different vCenter Server instances in the environment.

For example, a LookupServiceRegistrationFilter for queering the vSphere Automation service has these service endpoint elements.

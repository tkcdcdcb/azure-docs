---
title: Sample API management policy - Generate Shared Access Signature
titleSuffix: Azure API Management
description: Azure API management policy sample - Demonstrates how to generate Shared Access Signature using expressions and forward the request to Azure storage with rewrite-uri policy..
services: api-management
documentationcenter: ''
author: dlepow
manager: cfowler
editor: ''

ms.service: api-management
ms.workload: mobile
ms.tgt_pltfrm: na
ms.topic: article
ms.date: 10/13/2017
ms.author: danlep
---

# Generate Shared Access Signature

This article shows an Azure API management policy sample that demonstrates how to generate [Shared Access Signature](../../storage/common/storage-sas-overview.md) using expressions and forward the request to Azure storage with rewrite-uri policy. To set or edit a policy code, follow the steps described in [Set or edit a policy](../set-edit-policies.md). To see other examples, see [policy samples](../policy-reference.md).

## Policy

Paste the code into the **inbound** block.

[!code-xml[Main](../../../api-management-policy-samples/examples/Generate Shared Access Signature and forward request to Azure storage.policy.xml)]

## Next steps

Learn more about APIM policies:

+ [Transformation policies](../api-management-transformation-policies.md)
+ [Policy samples](../policy-reference.md)
---
title: Message Translator pattern
titleSuffix: Cloud Design Patterns
description: Describes how data can be translated from one format to another.
author: maruma
ms.date: 03/30/2021
ms.topic: conceptual
ms.service: architecture-center
ms.subservice: design-pattern
products:
  - azure-functions
  - azure-logic-apps
  - azure-blob-storage
  - azure-storage-queues
ms.custom:
  - design-pattern
keywords:
  - design pattern
---

# Message Translator Pattern

> How can systems using different data formats communicate with each other using messaging?

The Message Translator pattern describes how data can be translated from one format to another. Transformation can happen at different levels:

* Data structure: related to entity hierarchies, relationships, cardinality, etc.
* Data types: related to cross-references, domains, constraints, data types, field names, etc.
* Data representation: deals with the format, e.g. binary, JSON, XML, CSVs, key-value pairs; industry standards like EDIFACT, X12; vendor-specific formats, character sets, encryption, compression, digital signatures, etc.
* Transport: deals with communication protocols such as HTTP, JMS, AMQP, gRPC, SOAP, etc.

This pattern was originally [described][enterprise-integration-patterns] in the book *Enterprise Integration Patterns*, by Gregor Hohpe and Bobby Woolf.

## Context and problem

## Solution

## Issues and considerations

## When to use this pattern

## Examples

## Related patterns and guidance

- The examples described above are available on [GitHub][sample-code].

<!-- links -->
[enterprise-integration-patterns]: https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageTranslator.html
[sample-code]: https://github.com/mspnp/cloud-design-patterns/tree/master/message-translator

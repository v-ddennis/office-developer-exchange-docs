---
title: "SubscriptionId (GetEvents)"
 
 
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- SubscriptionId
api_type:
- schema
ms.assetid: 77c0abab-69e8-428e-8c20-22258e4ef71b
description: "The SubscriptionId element represents the identifier for a subscription."
---

# SubscriptionId (GetEvents)

The **SubscriptionId** element represents the identifier for a subscription. 
  
```xml
<SubscriptionId/>
```

 **SubscriptionIdType**
## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
### Attributes

None.
  
### Child elements

None.
  
### Parent elements

|**Element**|**Description**|
|:-----|:-----|
|[GetEvents](getevents.md) <br/> |Represents the operation used by pull clients to request notifications from the server.  <br/> |
|[Notification](notification-ex15websvcsotherref.md) <br/> |Contains information about the subscription and the events that have occurred since the last notification.  <br/> |
|[SubscribeResponseMessage](subscriberesponsemessage.md) <br/> |Contains the status and result of a Subscribe request.  <br/> |
|[Unsubscribe](unsubscribe.md) <br/> |Contains the properties used to unsubscribe from a subscription.  <br/> |
   
## Text value

A text value is required. The text value is a GUID.
  
## Remarks

The GUID that represents the subscription identifier is generated by the Client Access server when the subscription is created.
  
The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.
  
## Element information

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|Schema name  <br/> |messages schema  <br/> |
|Validation file  <br/> |messages.xsd  <br/> |
|Can be empty  <br/> |False  <br/> |
   
## See also



[Subscribe operation](subscribe-operation.md)
  
[GetEvents operation](getevents-operation.md)
  
[Unsubscribe operation](unsubscribe-operation.md)


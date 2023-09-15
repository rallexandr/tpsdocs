# 13. AML

## AML Callback

```json
{
  "ValidationParameters": [
    {
      "Code": "receiver_idn",
      "Value": ""
    },
    {
      "Code": "receiver_last_name",
      "Value": "Doe"
    },
    {
      "Code": "operation_amount_mdl",
      "Value": "50000"
    },
    {
      "Code": "sender_country_code",
      "Value": "MDA"
    },
    {
      "Code": "sender_region_code",
      "Value": null
    },
    {
      "Code": "operation_type_code",
      "Value": "TRANSFER_TO_CARD"
    },
    {
      "Code": "receiver_type",
      "Value": "INDIVIDUAL"
    },
    {
      "Code": "sender_account_values",
      "Value": null
    },
    {
      "Code": "receiver_account_type_codes",
      "Value": "CARD_MASK"
    },
    {
      "Code": "sender_address",
      "Value": "Alexander Pushkin St 15"
    },
    {
      "Code": "provider",
      "Value": "Ukrcard"
    },
    {
      "Code": "sender_type",
      "Value": "INDIVIDUAL"
    },
    {
      "Code": "receiver_region_code",
      "Value": null
    },
    {
      "Code": "executor",
      "Value": "PaySend"
    },
    {
      "Code": "receiver_account_values",
      "Value": "510218******9559"
    },
    {
      "Code": "sender_location",
      "Value": "Chisinau"
    },
    {
      "Code": "comment",
      "Value": "Monthly rent payment"
    },
    {
      "Code": "receiver_country_code",
      "Value": "MDA"
    },
    {
      "Code": "operation_date",
      "Value": "2023-09-12T17:37:18"
    },
    {
      "Code": "sender_account_type_codes",
      "Value": null
    },
    {
      "Code": "receiver_location",
      "Value": null
    },
    {
      "Code": "receiver_address",
      "Value": null
    },
    {
      "Code": "operation_currency_code",
      "Value": "MDL"
    },
    {
      "Code": "service",
      "Value": "Mastercard transfer to Moldovan card"
    },
    {
      "Code": "sender_first_name",
      "Value": "Alice"
    },
    {
      "Code": "receiver_first_name",
      "Value": "John"
    },
    {
      "Code": "system_code",
      "Value": "TPS"
    },
    {
      "Code": "operation_amount_currency",
      "Value": null
    },
    {
      "Code": "sender_last_name",
      "Value": "Smith"
    },
    {
      "Code": "sender_idn",
      "Value": null
    }
  ],
    "EventId": 379,
    "SecretKey": null,
    "Email": null,
    "URL": "https://tps-api-test.paynet.md/api/Callback",
    "CaseId": 1093,
    "EventDate": "2023-09-13T09:06:55.647",
    "EventTypeCode": "IDENTIFICATION_REQUEST_CHECK",
    "EventTypeName": null,
    "Id": 379,
    "SystemCode": null,
    "CaseStatus": "CANCELED",
    "OperationReference": "100720",
    "OperationType": "OperationScreeningRequest",
    "RequestStatus": "ACCEPTED",
    "RequestId": 3670
}
```

CaseStatus -  Текущий статус кейса (выявленного риска).

**Возможные варианты:**    
CANCELED - риск не подтвержден. Разрешено продожлить работу с клиентом / по операции.  
CONFIRMED - риск подтвержден.Продолжать работу по клиенту/ операции запрещено.  




# POST /payments

## Описание метода
Оплата товара.

## Тело запроса
```json
{
  "payment date": "25-04-2024",
  "payment amount": "1584.11", 
  "id_client": "95874"
}
 ```

## Тело ответа
```json
{
  "id_payment": 6584
}
 ```

## Описание ошибок:
201: Create (id_product)                            
404: Not found

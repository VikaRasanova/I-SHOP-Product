# POST /orders

## Описание метода
Добавить товар в корзину.

## Тело запроса
```json
{
  "order date": "25-04-2024", 
  "id_client": "12587458",
  "id_product": "985895"
}
 ```

## Тело ответа
```json
{
  "id_order": 458
}   
 ```

## Описание ошибок:
201: Create (id_product)                   
404: Not found


# PATCH /orders/order_id

## Описание метода
Оформить заказ.

## Тело запроса
```json
{
  "id_order": "958458", 
  "order status": "Создан"
}
 ```

## Тело ответа
```json
{
  "id_order": 958458, 
  "order status": "Создан"
}   
 ```

## Описание ошибок:
201: Create (id_product)                   
404: Not found

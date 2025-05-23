# GET /products

## Описание метода
Посмотреть товар в каталоге.

## Тело запроса
Нет тела запроса.

## Тело ответа
```json
[
  {
    "id_product": 5874458,
    "product_name": "Молоко",
    "product category": "Молочные продукты" ,
    "price": 2.58
  },
  {
   "id_product": 152458,
    "product_name": "Макароны рожки",
    "product category": "Бакалея" ,
    "price": 5.10
  }
]
 ```

## Описание ошибок:
200: OK                          
404: Not found                  
500: Internal Server Error


# POST /products

## Описание метода
Добавление товара в каталоге. Доступно только для администратора.

## Тело запроса
```json
{
  "product category": " Хлебобулочные изделия ",
  "product name": "Батон",
  "price quantity": "3.52"
}
 ```

## Тело ответа
```json
{
  "id_product": 1587458
}
 ```

## Описание ошибок:
201: Create (id_product)            
401: Unauthorized                                  
403: Forbidden                   
404: Not found


# PUT /products

## Описание метода
Изменение информации о товаре в каталоге. Доступно только для администратора.

## Тело запроса
```json
{
  "id_product": "25845",
  "product category": "Соки",
  "product Name": "Сок вишневый",
  "price": "5.80",
  "quantity": "1568"
}
 ```

## Тело ответа
```json
{
  "id_product": 985895
}
 ```

## Описание ошибок:
201: Create (id_product)            
401: Unauthorized                                  
403: Forbidden                   
404: Not found

# DELETE /products/products_id

## Описание метода
Удаление товара из каталога. Доступно только для администратора.

## Тело запроса
```json
{
  "id_product": "985895"
}
 ```

## Тело ответа
```json
{
  "id_product": 985895
}
 ```

## Описание ошибок:
201: Create (id_product)            
401: Unauthorized                                  
403: Forbidden                   
404: Not found

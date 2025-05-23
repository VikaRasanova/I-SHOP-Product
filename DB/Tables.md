# Таблица Clients
| Атрибут             | Тип             | Описание                                  |
|---------------------|-----------------|-------------------------------------------|
| id_client           | int             | Идентификатор клиента           |
| full_name           | char            | Полное имя                                |
| telephone_number    | int             | Номер телефона                            |
| email               | char            | Адрес электронной почты                   |
| promotional_status  | char            | Акционный статус                          |
| total_amount_ransom | decimal         | Общая сумма выкупа                        |
| created_at          | datetime        | Дата и время создания                     |
| updated_at          | datetime        | Дата и время изменения                    |

# Таблица Products
| Атрибут             | Тип             | Описание                                  |
|---------------------|-----------------|-------------------------------------------|
| id_product          | int             | Идентификатор товара                      |
| product_category    | char            | Категория товара                          |
| product_name        | char            | Наименование товара                       |
| price               | decimal         | Цена товара                               |
| quantity            | int             | Количество                                |
| created_at          | datetime        | Дата и время создания                     |
| updated_at          | datetime        | Дата и время изменения                    |

# Таблица Orders
| Атрибут             | Тип             | Описание                                  |
|---------------------|-----------------|-------------------------------------------|
| id_order            | int             | Идентификатор заказа                      |
| order_number        | int             | Номер заказа                              |
| order_status        | char            | Статус заказа                             |
| order_date          | date            | Дата заказа                               |
| id_client           | int             | Идентификатор клиента                     |
| id_product          | int             | Идентификатор товара                      |
| sum_amount_order    | decimal         | Сумма заказа                              |
| created_at          | datetime        | Дата и время создания                     |
| updated_at          | datetime        | Дата и время изменения                    |

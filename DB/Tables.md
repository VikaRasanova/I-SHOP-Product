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

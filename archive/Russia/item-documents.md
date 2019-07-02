# Товарные документы

Business Central включает несколько документов, которые можно использовать для управления складом, например, отчеты, которые необходимо предоставлять официальным органам, такие как ТОРГ-29, акт приемки товаров ТОРГ-1 и расхождение при приемке ТОРГ-2.

Следующие типы документов полезны при управлении складом:

- Акт приемки товаров без счета поставщика — применяется для учета прихода товаров на основе качества, количества и стоимости.
- Акт списания товаров — применяется для регистрации повреждений по таким причинам, как утрата качества товаров, которые не подлежат дальнейшей продаже.
- Перемещение товара — применяется при приеме и поставке отгрузок для перемещения товаров в рамках организации.

## Настройка нумерации складских документов

В следующей процедуре показан порядок нумерации складских документов.

1. Выберите значок ![Поиск страницы или отчета](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/1.png), введите **Настройка модуля "Запасы"**, а затем выберите связанную ссылку.
2. На экспресс-вкладке **Нумерация** укажите в следующих полях серии номеров документов.
   - **Акт Оприход. Товаров Номера**
   - **Учт. Акты Оприходования Номера**
   - **Акт Списания Номера**
   - **Учт. Акт Списания Номера**

## Создание акта оприходования товаров без поставщика

В следующей процедуре показан порядок создания акта оприходования товаров без поставщика.

1. Выберите значок ![Поиск страницы или отчета](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/1.png), введите **Акты оприходования товаров**, а затем выберите связанную ссылку.

2. В заголовке окна **Акт Оприходования Товаров** введите поля, описанные в следующей таблице.

   | Поле                               | Описанием                                                    |
   | ---------------------------------- | ------------------------------------------------------------ |
   | **Номер**                          | Определяет номер заголовка складского документа.             |
   | **Описание Учета**                 | Определяет описание учета.                                   |
   | **Код Склада**                     | Указывает значение кода, которое заполняется из списка складов. |
   | **Общая бизнес-группа**            | Определяет код общей бизнес-группы.                          |
   | **Дата учета**  **Дата Документа** | Указывает рабочую дату, которая заполняется по умолчанию.    |
   | **Номер внешнего документа**       | Введите номер первичного документа.                          |
   | **Код менеджера**                  | Указывает значение кода, которое выбирается из списка продавцов или менеджеров. |
   | **Корректировка**                  | Определяет операцию как исправление.                         |
   | **Статус**                         | Указывает состояние документа: "Открыт" или "Выпущен".       |

3. В строках документа окна **Акт Оприходования Товаров** заполните поля, описанные в следующей таблице.

   | Поле                          | Описанием                                                    |
   | ----------------------------- | ------------------------------------------------------------ |
   | **Код товара**                | Указывает номер товара из таблицы "Товар Список".            |
   | **Описание**                  | Определяет описание товара.                                  |
   | **Количество**                | Определяет количество единиц товара.                         |
   | **Зарезерв. входящее кол-во** | Указывает количество товара, зарезервированное на складе получателя. |
   | **Цена Единицы**              | Определяет цену единицы товара.                              |
   | **Косв. себест. %**           | Определяет процент косвенных затрат.                         |
   | **Себестоимость единицы**     | Определяет себестоимость единицы товара в строке прихода отгрузки. |
   | **Сумма**                     | Определяет сумму транзакции.                                 |
   | **Код единицы измерения**     | Определяет код единицы измерения полученных товаров.         |

4. В окне **Акт оприходования товаров** выберите действие **Подписи сотрудников**, чтобы указать подпись ответственного лица.

5. Введите значения в поля, описанные в следующей таблице.

   | Поле                | Описанием                                                    |
   | ------------------- | ------------------------------------------------------------ |
   | **Сотрудник Тип**   | Определяет тип сотрудника.                                   |
   | **Сотрудник Номер** | Задает номер сотрудника, который должен поставить свою подпись. |
   | **Сотрудник Имя**   | Задает значения, которые извлекаются из стандартных полей выбранной карточки **Карточка сотрудника**. |

6. Следующие функции доступны в окне **Акт оприходования товара**.

| Функция                        | Описанием                                                    |
| ------------------------------ | ------------------------------------------------------------ |
| Изменение статуса документа    | Документы можно открыть или выпустить для следующего этапа обработки. Выберите действие **Выпустить** или **Открыть повторно**. |
| Резервирование строк документа | Товары можно зарезервировать из строки документа. Выберите действие **Резервировать**. |
| Расчет коррекции склада        | Относится только к коррекции количества товаров в складских ячейках. Эта функция доступна только тогда, когда на складке используется расширенная комплектация и размещение. |
| Учет документа                 | Выберите действие **Учесть**, чтобы выполнить следующее:   -   **Учет** Учет акта оприходования товара. Создается учтенный акт оприходования товара. -   **Учет и печать** Учет акта оприходования и печать тестового отчета. |

## Анализ учтенного документа оприходования товара без поставщика

В следующей процедуре показан порядок анализа учтенного документа оприходования товаров без поставщика.

1. Выберите значок ![Поиск страницы или отчета](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/1.png), введите **Учт. акты оприходования товаров**, затем выберите связанную ссылку.

    Примечание

   В учтенном акте оприходования товаров отображается вся информация из приходной накладной.

2. Выберите действие **Сортировка**, чтобы отсортировать список выбранных для печати документов по возрастанию или по убыванию.

3. Нажмите кнопку **Печать**.

## Создание акта списания товаров

В следующей процедуре показан порядок создания акта списания товаров.

1. Выберите значок ![Поиск страницы или отчета](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/1.png), введите **Акты списания товаров**, а затем выберите связанную ссылку.

2. В заголовке окна **Акт Списания Товаров** заполните поля. Эти поля идентичны полям окна **Акт Оприходования Товаров**.

3. В строках документа окна **Акт Списания Товаров** заполните поля. Эти поля идентичны полям окна **Акт Оприходования Товаров**, за исключением следующего.

   - Поле **Косвен. Себест.** доступно только в окне **Акт Оприходования Товаров**.
   - Поля, описанные в следующей таблице, доступны только в окне **Акт Списания Товаров**.

   | Поле                      | Описанием                                                    |
   | ------------------------- | ------------------------------------------------------------ |
   | **ОС Номер**              | Указывает основное средство для списания товаров и материалов. |
   | **Код Книги Амортизации** | Указывает книгу амортизации основных средств, в которую будет добавлена дополнительная себестоимость. |

4. В окне **Акт списания товаров** выберите действие **Подписи сотрудников**, чтобы указать подпись ответственного лица.

5. Введите значения в поля, описанные в следующей таблице.

   | Поле                | Описанием                                                    |
   | ------------------- | ------------------------------------------------------------ |
   | **Сотрудник Тип**   | Определяет тип сотрудника.                                   |
   | **Сотрудник Номер** | Задает номер сотрудника, который должен поставить свою подпись. |
   | **Сотрудник Имя**   | Задает значения, которые извлекаются из стандартных полей выбранной карточки **Карточка сотрудника**. |

6. Выберите действие **Печать**.

Функции, доступные в окне **Акт списания товаров**, совпадают с функциями, доступными в окне **Акт оприходования товаров**.

## Анализ учтенного документа списания товара

В следующей процедуре показан порядок анализа учтенного акта списания товаров.

1. Выберите значок ![Поиск страницы или отчета](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/1.png), введите **Учт. акты списания товаров**, затем выберите связанную ссылку.

    Примечание

   В учтенном акте списания товаров отображается вся информация из расходной накладной.

2. Выберите действие **Сортировка**, чтобы отсортировать список выбранных для печати документов по возрастанию или по убыванию.

3. Выберите действие **Печать**.

## Отчет по заказу на перемещение ТОРГ-13 на основании неучтенного документа перемещения

В следующей процедуре описывается порядок создания отчета по заказу на перемещение ТОРГ-13 на основании документов на перемещение, которые не были учтены.

1. Выберите значок ![Поиск страницы или отчета](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/1.png), введите **Заказы на перемещение**, а затем выберите связанную ссылку.

   Выберите действие **Печать**.

## Отчет по заказу на перемещение ТОРГ-13 на основании учтенного документа перемещения - "Перемещение Прих. Накл."

В следующей процедуре описан порядок создания отчета на основе учтенного документа перемещения, называемого приходной накладной перемещения.

1. Выберите значок ![Поиск страницы или отчета](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/1.png), введите **Учт. прих. накладная на перемещение**, затем выберите связанную ссылку.
2. Выберите действие **Печать**.

## Отчет по заказу на перемещение ТОРГ-13 на основании учтенного документа перемещения - "Перемещение Расх. Накл."

В следующей процедуре описан порядок создания отчета на основе учтенного документа перемещения, называемого расходной накладной перемещения.

1. Выберите значок ![Поиск страницы или отчета](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/1.png), введите **Учтенные расходные накладные на перемещение**, затем выберите связанную ссылку.

   Выберите действие **Печать**.

## См. также

[Настройка товаров](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/inventory-setup.md)

[Акты обязательств по товару](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/item-obligatory-acts.md)

[Финансовый оборот для товара](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/item-general-ledger-turnover.md)
### Project_delivery_app 

Команда внедрила в приложение доставки умную систему рекомендации товаров – предполагается, что такая система поможет пользователям эффективнее работать с приложением и лучше находить необходимые товары.
Чтобы проверить эффективность системы рекомендаций, был проведен АБ-тест. В группе 1 оказались пользователи с новой системой рекомендаций, в группе 0 пользователи со старой версией приложения, где нет рекомендации товаров.

> - моя задача – оценить, смогла ли новая система рекомендаций принести пользу бизнесу и пользователям приложения.
> - нужно выбрать метрики, которые отвечают за качество сервиса, и статистически сравнить эти метрики в двух группах.
> - аналитическое заключение с ответом на вопрос, стоит ли включать новую систему рекомендаций на всех пользователей.

Данные для анализа:
- ab_users_data – история заказов пользователей, в этой таблице есть информация о том, какие заказы создавали и отменяли пользователи
- ab_orders – подробная информация о составе заказа, тут для каждого заказа есть список id тех продуктов, которые были включены в заказ
- ab_products – подробная информация о продуктах, их название и стоимость

> Провела анализ новой системы рекомендаций в приложении доставки: проанализировала данные, определила нужные метрики для анализа, провела А/В тестирование метрик с помощью метода Т-теста Стьюдента и проверила гипотезы на отличия, визуализировала полученные данные.
> 
> Результат анализа: однозначно стоит включать новую систему рекомендаций для всех пользователей сайта, она поможет пользователям эффективнее работать с приложением и быстрее находить необходимые товары, а бизнесу увеличит оборот товаров и колоссальное увеличение выручки.

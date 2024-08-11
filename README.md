### Project_delivery_app 
⚒️ `Стек: python, pandas, numpy, seaborn, matplotlib, scipy, pingouin, statsmodels, Jupyter Notebook`

Команда внедрила в приложение доставки умную систему рекомендации товаров – предполагается, что такая система поможет пользователям эффективнее работать с приложением и лучше находить необходимые товары. Чтобы проверить эффективность системы рекомендаций, был проведен АБ-тест. В группе 1 оказались пользователи с новой системой рекомендаций, в группе 0 пользователи со старой версией приложения, где нет рекомендации товаров.

Данные для анализа:
- ab_users_data – история заказов пользователей, в этой таблице есть информация о том, какие заказы создавали и отменяли пользователи
- ab_orders – подробная информация о составе заказа, тут для каждого заказа есть список id тех продуктов, которые были включены в заказ
- ab_products – подробная информация о продуктах, их название и стоимость
### Цель:
1. моя задача – оценить, смогла ли новая система рекомендаций принести пользу бизнесу и пользователям приложения.
2. нужно выбрать метрики, которые отвечают за качество сервиса, и статистически сравнить эти метрики в двух группах.
3. аналитическое заключение с ответом на вопрос, стоит ли включать новую систему рекомендаций на всех пользователей.

### Этапы работы:
1. проанализировала данные,
2. определила нужные метрики для анализа,
3. провела А/В тестирование метрик с помощью метода Т-теста Стьюдента и проверила гипотезы на отличия,
4. визуализировала полученные данные.
 
### Результат анализа:
однозначно стоит включать новую систему рекомендаций для всех пользователей сайта, она поможет пользователям эффективнее работать с приложением и быстрее находить необходимые товары, а бизнесу увеличит оборот товаров и колоссальное увеличение выручки.

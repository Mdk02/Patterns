# Patterns
Наименование проекта "название"

Проект предствавляет собой проделанную работу по "n" сессии

"вставить отчет"

Проект сделан в jupyter notebook с использованием языка python 3
 
В процессе проекта столкнулся с такими-то проблемами

Последнее обновление "дата"

Создатель Хисамутдинов Булат


--------------------------------------------

#pd.plotting.scatter_matrix(df, figsize=(14,8))

df2[df2.columns].hist(figsize=(16,8));

for x in ['windspeed']:
    q75,q25 = np.percentile(BIKE.loc[:,x],[75,25])
    intr_qr = q75-q25

    max = q75+(1.5*intr_qr)
    min = q25-(1.5*intr_qr)

    BIKE.loc[BIKE[x] < min,x] = np.nan
    BIKE.loc[BIKE[x] > max,x] = np.nan




# ZhanerkeSabitovnaInstagramReach.github.io
Instagram Reach Analysis exploration

Instagram генерирует много данных каждый день. Когда создатели контента размещают посты в Instagram, они действительно оценивают свою вовлеченность и охват, чтобы найти категорию постов, которые им следует публиковать чаще. Вот данные Instagram, которые мы собрали из аккаунта основателя 1Diaa.y. Ниже приведены все функции, содержащиеся в данных:

Показы: Количество показов поста (охват)
Из дома: Добраться из дома
По хэштегам: Охват по хэштегам
Из исследования: Достичь из исследования
Из других: Доступ из других источников
Сохранения: Количество сохранений
Комментарии: Количество комментариев
Акции: Количество акций
Лайки: Количество лайков
Посещения профиля: Количество посещений профиля с помощью сообщения
Подписчики: Количество подписчиков

import pandas as pd
import plotly.graph_objs as go
import plotly.express as px
import plotly.io as pio
pio.templates.default = "plotly_white"

data = pd.read_csv("https://docs.google.com/spreadsheets/d/e/2PACX-1vTeWBHEZcdrfPTwC8drmZBWbWjhbpvpIAs61ouUwmiUsVBKnAI6uGMAdMYeBVdiPClc-hcurwfg4gRa/pub?gid=2074512117&single=true&output=csv", encoding = 'latin-1')
print(data.head())

  Date  Instagram reach
0  2022-04-01 0:00:00              762
1  2022-04-02 0:00:00              890
2  2022-04-03 0:00:00             1018
3  2022-04-04 0:00:00             1146
4  2022-04-05 0:00:00             1274

# DataBasesTEKKR2


## ШАГ 1. Создание таблицы «Районы»

<img width="476" height="118" alt="Снимок экрана 2025-12-18 в 09 55 59" src="https://github.com/user-attachments/assets/ccd60c25-4a23-47de-9e12-7f935708ace8" />


## ШАГ 2. Создание таблицы «Объект недвижимости»

<img width="444" height="363" alt="Снимок экрана 2025-12-18 в 09 56 30" src="https://github.com/user-attachments/assets/4ece5e0e-3fcd-4f73-bd18-ee742aeaef36" />


## ШАГ 3. Создание таблицы «ОПИСАНИЕ ОБЪЕКТА»

<img width="540" height="193" alt="Снимок экрана 2025-12-18 в 09 57 12" src="https://github.com/user-attachments/assets/458c937d-e782-4bfe-89ff-9b68d5ed3e30" />
## ШАГ 4. Заполнение таблицы «Районы»

<img width="401" height="142" alt="Снимок экрана 2025-12-18 в 10 22 07" src="https://github.com/user-attachments/assets/4abdc786-19ca-41a4-863b-1a680ab2e002" />
## ШАГ 5. Заполнение таблицы «Объект недвижимости»

<img width="2200" height="386" alt="image" src="https://github.com/user-attachments/assets/28b03632-d202-4ef1-8081-2098e059e8f5" />

## ШАГ 6. Заполнение таблицы «ОПИСАНИЕ ОБЪЕКТА» одной командой INSERT
<img width="700" height="522" alt="Снимок экрана 2025-12-18 в 10 25 00" src="https://github.com/user-attachments/assets/dff9ea4b-6f5f-48c5-8475-022be2fc1054" />


## ШАГ 7. Указание жилой площади (обновление JSON)

Допустим:
```
жилая площадь = 70% от общей
```
<img width="624" height="207" alt="Снимок экрана 2025-12-18 в 10 26 28" src="https://github.com/user-attachments/assets/d73d6e01-18e3-4df8-a01c-3e2a5d8b65c8" />

Теперь массив "Площадь" выглядит так:
```
"Площадь": [60, 42]
```

## 5.1. Адреса двухкомнатных объектов недвижимости в указанном районе

<img width="849" height="314" alt="Снимок экрана 2025-12-18 в 10 28 10" src="https://github.com/user-attachments/assets/a35647c3-96cf-4d5b-915c-ffa04dc418b2" />

## 5.2. Разница в процентах между общей и жилой площадью

<img width="605" height="488" alt="Снимок экрана 2025-12-18 в 10 28 35" src="https://github.com/user-attachments/assets/cbfa3926-d2d5-498c-ab20-6509660a89eb" />


Формула:
```
(Общая - Жилая) / Общая * 100
```

## 5.3. Стоимость 1 м² на указанном этаже

<img width="685" height="416" alt="Снимок экрана 2025-12-18 в 10 29 41" src="https://github.com/user-attachments/assets/6b2ddf91-faab-4320-9d0a-9381c1892fb8" />

## 5.4. Количество объектов по городу, городу и району, всего

<img width="725" height="554" alt="Снимок экрана 2025-12-18 в 10 30 10" src="https://github.com/user-attachments/assets/026d22bc-eea1-4ab4-9cc8-4ccb0ad33a8d" />

GROUPING SETS позволяет получить:
```
город + район

город

общее количество

```
## 5.5. Средняя площадь по городу и району

<img width="838" height="463" alt="Снимок экрана 2025-12-18 в 10 30 48" src="https://github.com/user-attachments/assets/6a4ffc4b-2c74-4a2f-a887-006b19e14c69" />


## 5.6. Максимальная и минимальная стоимость по области, области и району

<img width="781" height="489" alt="Снимок экрана 2025-12-18 в 10 31 19" src="https://github.com/user-attachments/assets/24db42c9-fa4a-4d3b-bd20-71fb89442381" />


## 5.7. Отклонение от средней стоимости по району

<img width="607" height="489" alt="Снимок экрана 2025-12-18 в 10 31 36" src="https://github.com/user-attachments/assets/98ffc9fc-3ad2-4eb2-bc8f-083c055aefcf" />


## 5.8. Полный адрес объектов, выставленных в текущем году
<img width="902" height="483" alt="Снимок экрана 2025-12-18 в 10 31 58" src="https://github.com/user-attachments/assets/61ff5c9c-94f5-4f9a-8c31-af272f811c51" />


# tableau_visualization_task3

## folders: 
```
├───res
│   ├─── Task_1.png
│   ├─── Task_2.png
│   └─── Task_3.png
└───tableau_project
    ├─── HW3.twb
    └───Data
        └───0u33a381qzsw7v1dsp8l507fse1j
            └─── res.csv
```
## comments:
### Task 1
- В яких країнах світу населення у 2100 році буде більшим, ніж було у 2000 році, а в яких меншим?
![res/Task_1.png](/res/Task_1.png?raw=true)
**Посилання на інтерактивну візуалізацію [Task_1](https://public.tableau.com/views/HW3Task1/Task1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)**  
Дана візуалізація є досить простою. Нам потрібно показати тільки бінарне значення (ріст чи зниження), тому поставимо у відповідник одному - один колір, другому - інший.     
Важливо щоб кольори не збивали читача. У мене спершу (автоматично) ріст позначався - синім кольором, зниження - оранжевим. Проте це трішки суперечило уявленню щодо кольорів (синій - спокійніший) і я зміни їх місцями.   

- На скільки відсотків збільшиться або зменшиться населення кожної країни у 2100 році у порівнянні з 2000 роком?
![res/Task_2.png](/res/Task_2.png?raw=true)
**Посилання на інтерактивну візуалізацію [Task_2](https://public.tableau.com/views/HW3Task2/Task2?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)**  
Знову ж таки, як і в попередньому прикладі кодуємо відсотковий ріст чи зниження кольором (синій-оранжевий).  
Варто пам'ятати про розмірність величин. Особисто я здивувався прогнозу для України у -50% населення.  

- Яким буде населення країн світу у 2100 році?
![res/Task_3.png](/res/Task_3.png?raw=true)
**Посилання на інтерактивну візуалізацію [Task_3](https://public.tableau.com/views/HW3Task2/Task2?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)**  
У цій візуалізації нам потрібно показати числове значення на карті. До того ж воно є у великих межах і ще й росте не лінійно.  
Якщо скористатися просто кольором, то така візуалізація майже нічого не дасть. Нам важко оцінити число тільки за кольором.  
Я спробував відобразити кількість людей розміром. Розмір ми сприймаємо і порівнюємо значно краще, проте порівняти два круги які є на великій відстані все ще досить важко.  
Тому я об'єднав два вищезгадані параметри. За допомогою розміру ми можемо припустити в скільки разів одна кілька більша за іншу і "відчути цю різницю". За допомогою кольору ми ж можемо поріняти просто оцінити яка з двох країн матиме більше населення. Для зручності і наглядності - кольорова шкала (яка відповідає тільки за порівняння, тобто є бінарним показником) є логарифмічною.  
За допомогою поєднання цих двох параметрів спостерігач може як і порівняти населення у двох країнах з приблизно однаковою кількістю населення, так і припустити наскільки населення однієї країни більше за іншу порівнюючи розміри кругів.  

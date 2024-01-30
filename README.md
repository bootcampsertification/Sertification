# Sertification
**Загальний опис проекта:** інформаційна система, яка дозволяє керувати процесом сертифікації ІТ-дисциплін в вишах Харкова, за рахунок обліку поточного стану сібусів освітніх курсів в вишах в Харкові, а також можливості оцінювати, узагальнювати існуючі матеріали та спрямовано залучати викладачів до процесу сертифікації дисциплін та подальшого їх покращення.

## Технології, що використовуються
### FrontEnd
HTML+CSS (Bootstrap), JS (отримання даних).

### BackEnd
PHP (стабільна робота, немає потреби компілювати мікросервіси), MySQL.

## Технічне завдання
### MockUps.
* **Перелік університетів**  
<img src = "img/uni.png">  

* **Перелік освітніх програм**  
<img src = "img/uni.png">  

* **Перелік курсів**  
<img src = "img/uni.png">  

* **Інші таблиці**   
<img src = "img/tables.png">  

### Endpoints
/universities:  
  
/programs:specialty_id|university_id|level|  
  
/courses:type_id|program_id|teacher_id
  
/teachers  
  
/specialty  
  
/schools  
  
/programs_levels  
  
/course_types:  
  
/course_types:type_id  
  
/course_statuses  
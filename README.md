# SQL-ODEV-4
film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.
ÇÖZÜM:SELECT DISTINCT(replacement_cost) FROM film

![666](https://user-images.githubusercontent.com/128131203/226311379-4e666855-fe38-436d-bacf-a3e19df16982.PNG)

film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?
ÇÖZÜM:SELECT COUNT(DISTINCT replacement_cost) FROM film

![7](https://user-images.githubusercontent.com/128131203/226312900-5b0b2b41-cbf5-4d8e-b17e-ab8d7fe95f0d.PNG)

film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?
ÇÖZÜM:SELECT COUNT (title) FROM film
WHERE title LIKE 'T&' AND rating= 'G'

![123](https://user-images.githubusercontent.com/128131203/226315260-39fc2c24-9e6e-4653-80e2-f513d45278a1.PNG)

country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?
ÇÖZÜM:SELECT COUNT (DISTINCT country) FROM country
WHERE country LIKE '_____'

![13](https://user-images.githubusercontent.com/128131203/226317094-80b1a75d-fb15-4311-b461-ee29cd9dc6b6.PNG)

city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?
ÇÖZÜM:SELECT COUNT (DISTINCT city)FROM city
WHERE city ILIKE '%R'

![SON](https://user-images.githubusercontent.com/128131203/226317757-7a2911ab-38ab-48a4-9097-7a5b29769dcc.PNG)

# Soru 1

### **film**  tablosunda bulunan **title** ve **description** sütunlarındaki verileri sıralayınız.

## Cevap :
```sql
SELECT title, description FROM film;
```

# Soru 2
### **film** tablosunda bulunan tüm sütunlardaki verileri film uzunluğu (length) 60 dan büyük VE 75 ten küçük olma koşullarıyla sıralayınız.

## Cevap :
```sql
SELECT * FROM film
WHERE length > 60 AND length < 75;
```

# Soru 3
### **film** tablosunda bulunan tüm sütunlardaki verileri **rental_rate 0.99** VE **replacement_cost 12.99** VEYA **28.99** olma koşullarıyla sıralayınız.

## Cevap :
```sql
SELECT * FROM film
WHERE rental_rate = 0.99 AND replacement_cost = 12.99 
OR replacement_cost = 28.99;
```

# Soru 4
### **customer** tablosunda bulunan **first_name** sütunundaki değeri 'Mary' olan müşterinin last_name sütunundaki değeri nedir?

## Cevap :

## SORGU :
```sql
SELECT last_name FROM customer
WHERE first_name = 'Mary';
```
## ÇIKTI :

| id | last_name |
| ----------- | ----------- |
| 1 | Smith |



# Soru 5
### **film** tablosunda bulunan tüm sütunlardaki verileri **rental_rate 0.99** VE **replacement_cost 12.99** VEYA **28.99** olma koşullarıyla sıralayınız.

## Cevap :
```sql
SELECT * FROM film
WHERE rental_rate = 0.99 AND replacement_cost = 12.99 
OR replacement_cost = 28.99
ORDER BY rental_rate, replacement_cost;
```

# Soru 1

### **film** tablosunda bulunan **rental_rate** sütunundaki değerlerin ortalaması nedir?

## Cevap :
```sql
SELECT AVG(rental_rate) FROM film;
```

# Soru 2

### **film** tablosunda bulunan filmlerden kaç tanesi '**C**' karakteri ile başlar?

## Cevap :
```sql
SELECT COUNT(*) FROM film
WHERE title LIKE 'C%';
```

# Soru 3

### **film** tablosunda bulunan filmlerden **rental_rate** değeri **0.99** a eşit olan en uzun (**length**) film kaç dakikadır?

## Cevap :
```sql
SELECT MAX(length) FROM film
WHERE rental_rate = 0.99;
```


# Soru 4

### **film** tablosunda bulunan filmlerin uzunluğu **150** dakikadan büyük olanlarına ait kaç farklı **replacement_cost** değeri vardır?

## Cevap :
```sql
SELECT COUNT(DISTINCT(replacement_cost)) FROM film
WHERE length > 150;
```
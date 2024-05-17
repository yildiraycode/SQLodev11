# SQLodev11
## sql sorguları patika odev 11 <br/>
**Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.**<br/>
1.actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.<br/><br/>
SELECT first_name<br/>
FROM actor<br/>
UNION<br/>
SELECT first_name<br/>
FROM customer;<br/><br/><br/>
2.actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım..<br/><br/>
SELECT first_name<br/>
FROM actor<br/>
INTERSECT<br/>
SELECT first_name<br/>
FROM customer;<br/><br/><br/>
3.actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.br/><br/>
SELECT first_name<br/>
FROM actor<br/>
EXCEPT<br/>
SELECT first_name<br/>
FROM customer;<br/><br/>

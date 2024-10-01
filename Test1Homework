1.select * from suppliers s 
where supplier_id between 1 and 5;

2.select * from suppliers s 
where supplier_id in (1,2,4,5);

3.select * from products
where product_name = 'Chang' or product_name = 'Aniseed Syrup';

4.select * from products p
where supplier_id = 3 or unit_price > 10;

5.select product_name as ÜrünAdı , unit_price as ÜrünFiyatı from products p ;

6.select * from products p 
where upper(product_name) like '%C%' ;

7.select * from products p 
where product_name like 'N%' and product_name not like '%n%n%';

8.select * from  order_details od  
where quantity > 50;

9.select * from products p 
where unit_price = (select min(unit_price) from products p2);
select * from products p 
where unit_price = (select max(unit_price) from products p2);

11.select * from products p
where product_name like '%Spice%';

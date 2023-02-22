# Online Eyewear Shop Website has XSS vulnerability

## XSS vulnerability

BUG_Author: Murasaki

URL：http://localhost/oews/admin/?page=orders/view_order&id=

Link:https://www.sourcecodester.com/php/16089/online-eyewear-shop-website-using-php-and-mysql-free-download.html

There is a stored XSS vulnerability in the order submission,attackers can use XSS injection to steal the identity authentication of administrative users, and perform some background operations as administrators to achieve CSRF attacks. Attackers can also hang horses on websites, so that visitors' browsers can be controlled by attackers.


![](https://github.com/1MurasaKi/Eyewear_Shop_XSS/blob/main/CartList.png?raw=true)

![](https://github.com/1MurasaKi/Eyewear_Shop_XSS/blob/main/alert.png?raw=true)

![](https://github.com/1MurasaKi/Eyewear_Shop_XSS/blob/main/orderDetails.png?raw=true)

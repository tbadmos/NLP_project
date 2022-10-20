<img src="https://retailinasia.com/wp-content/uploads/2020/02/Mercari-770x478.png">

Mercari, Japan's biggest community-powered shopping app provides a marketplace for seller to sell a wide variety of products. Mercari would like to offer a pricing suggesition to its sellers. This is a tough task considering the huge amout of products solds online. Also items such as clothings have seasonal pricing trends and are higly influenced by brand names, while prices of electronics are influenced by spec of the product among other factors.

The task is to build an algorithm that automatically suggests the right product prices based on provided details such as  product descriptions, product category, brand name, and product condition.

### Dataset

The data consist of a list of product listings:-
- train_id or test_id - the id of the listing
- name - the title of the listing. 
- item_condition_id - the condition of the items provided by the seller
- category_name - category of the listing
- brand_name
- price - the price that the item was sold for. This is the target variable that you will predict. The unit is USD. 
- shipping - 1 if shipping fee is paid by seller and 0 if paid by the buyer
- item_description - the full description of the item. 

**Source:** https://www.kaggle.com/c/mercari-price-suggestion-challenge
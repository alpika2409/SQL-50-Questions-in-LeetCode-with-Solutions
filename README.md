# Easy

### SQL Schema  
#### Table: Products  

| Column Name | Type  |
|------------|-------|
| product_id | int   |
| low_fats   | enum  |
| recyclable | enum  |

- `product_id` is the **primary key** (unique identifier).  
- `low_fats` is an **ENUM** (`'Y'`, `'N'`), where `'Y'` means the product is low fat.  
- `recyclable` is an **ENUM** (`'Y'`, `'N'`), where `'Y'` means the product is recyclable.  


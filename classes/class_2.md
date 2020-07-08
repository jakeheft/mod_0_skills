## class: Customer

### attributes:
- `favorite_dish` (string)
- `avg_dollar_spend` (float)
- `current_satisfaction` (integer)
- `makes_reservations` (boolean)
- `gets_dessert` (boolean)

### methods:
- `introduce_special` : changes `favorite_dish`
- `offer_dessert_promo` : increases `avg_dollar_spend` **&** changes `gets_dessert = true`
- `deliver_meal` : brings meal to guest, increases `current_satisfaction`
- `initiate_text_res` : implement easy text reservation system, changes `makes_reservations = true`

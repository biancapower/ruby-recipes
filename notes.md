# Data Model

* ingredient
  - belongs_to_many recipes
* item
  - on shopping_list
  - has_many tags
  - may or may not be an ingredient
    - for ingredients, selected based on combination of ingredients within meal plan items added to shopping list
    - includes other shopping items that aren't ingredients
* recipe
  - has_many ingredients
  - belongs_to_many meals
* meal (one or more recipes)
  - has_one_or_many recipes
  - is on (a) meal_plan(s)
* shopping_list
  - has_many items
  - is added to from meal_plans
* meal_plan
  - has_many meals

** Quantities?
  - item: 50ml
  - buy: 1 x 300ml carton
  - ingredients vs items...?
    - [ingredient: 50ml cream] + [ingredient: 120ml cream] -> [item: 300ml carton of cream]

** One or more shopping lists?
  - or is it really just a filtered view of items (based on tags)?

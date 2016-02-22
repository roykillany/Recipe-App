# Tables
### USER
	* username
	* email
	* password_digest
	* admin
	* has_one profile
	* has_many recipes
	* has_many blogs
	* has_many favorite_recipes

### PROFILE
	* favorite_cuisine
	* favorite_meal
	* favorite_ingredient

### FAVORITES (recipes)
	* user_id
	* recipe_id

### RECIPE
	* user_id
	* title
	* description
	* has_many recipe_categories
	* has_many recipe_pictures
	* has_many recipe_steps
	* has_many recipe_ingredients
	* has_many recipe_comments

### INGREDIENTS
	* name

### CATEGORIES
	* name

### COMMENTS
	* type

### RECIPE_INGREDIENTS
	* recipe_id
	* ingredient_id

### RECIPE_CATEGORIES

### RECIPE_PICTURES

### RECIPE_STEPS
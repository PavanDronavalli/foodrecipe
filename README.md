Open Kitchen: Recipe-Sharing Platform 
1. Introduction
   
Open Kitchen is a thriving online community where food lovers unite to explore, share, and create culinary masterpieces. It provides a user-friendly platform for discovering new recipes, connecting with fellow cooks, and showcasing culinary talents. 
 
Discover new recipes from our ever-growing database, curated by food lovers worldwide. Open Kitchen is more than just a recipe site it's a collective archive of culinary delights, where each contribution enriches our cooking experience.

2. Features 
User Accounts: 
•Signup & Login: Users can create accounts using email or login into their existing accounts. 
Recipe Creation & Management: 
•Intuitive Recipe Creating Process: A user-friendly interface for crafting and sharing recipes, including:  o Dish Name o Preparation Time o Ingredients List o Step-by-Step Instructions o Photos for visual appeal 
•Editing & Deleting: Authors maintain full control over their recipes, they will be able to edit or delete their own recipes. 
Recipe Discovery & Interaction: 
•Personalized Feed: A curated stream of recipes from all the users and trending dishes. 
•Powerful Search: Find recipes by dish name, ingredients, or keywords. 
•Recipe Pages: In-depth views with print/save options. 
•Likes/Favorites: Bookmark recipes for future reference.

3.Technology Stack 
•Frontend: React (for dynamic UI), Tailwind CSS (for styling). 
•Backend: Node.js (with Express.js), MongoDB(for database storage). 
•APIs: RESTful API for frontend-backend communication, Cloudinary for image/video storage. 
•Search: Elasticsearch for efficient recipe search. 


4.Database Schema 
•Users: id, email, password_hash, name
•Recipes: id, author_id, dish_name, time_to_prepare, ingredients, steps, photos, created_at
•Likes: user_id, recipe_id 

5.Security & Performance 
Open Kitchen prioritizes the security of user data and employs best practices to protect against vulnerabilities. The platform is optimized for speed and responsiveness, ensuring a smooth user experience. 

6.Future Enhancements 
•User Groups: Create communities around specific interests. 
•Gamification: Introduce badges and challenges to boost engagement. 
•Premium Features: Offer advanced features like personalized meal plans and exclusive recipes. 

7.Conclusion 
Open Kitchen is more than just a recipe platform; it's a thriving community where food enthusiasts can connect, learn, and share their passion for cooking. With its user-friendly interface, robust features, and focus on security and performance, Open Kitchen is poised to become a leading destination for culinary inspiration. 



APP MODEL IMAGES:
<img width="872" height="491" alt="image" src="https://github.com/user-attachments/assets/d48d8134-d5d2-4d2a-a6bb-45f4210532b8" />
All users can see the recipes created by other users in the app without logging in. They are free to browse the recipes and click on them to know more about the recipe, there is also a like button available if they wish to appreciate the other users recipe.


 	 
<img width="872" height="491" alt="image" src="https://github.com/user-attachments/assets/0a81f097-156e-4128-ac5b-16a24b35f9db" />
If the user wants to create a recipe, then the user has to login. Directly clicking on create button without login/signup will redirect to login page.



<img width="872" height="491" alt="image" src="https://github.com/user-attachments/assets/6ecca3f7-d77b-41ed-b794-c532a63a410a" />
After creating a recipe it gets published in the home page of the app and there is edit and delete button visible for the user who has created that recipe. 


<img width="872" height="491" alt="image" src="https://github.com/user-attachments/assets/399b11cc-9783-4abd-b2bf-838797b06ce3" />
Users can use our search feature to search for the particular recipes without logging in.


<img width="872" height="491" alt="image" src="https://github.com/user-attachments/assets/a7a0d06e-30e6-447c-a7bf-c407cd9c365e" />
Clicking on the recipe available on the home page will open a recipe card as shown, this contains information regarding the recipe.


<img width="872" height="491" alt="image" src="https://github.com/user-attachments/assets/1cc85e7a-6415-45e3-8373-a2798272cc53" />
Users are allowed to like their favourite recipes by using our LIKE button feature.


<img width="872" height="295" alt="image" src="https://github.com/user-attachments/assets/5dab6bd7-c444-4af5-85e2-b37002f1c04e" />
This database shows us the users who have logged in and this shows us their email-id along with username and the date when they have logged in.


<img width="872" height="264" alt="image" src="https://github.com/user-attachments/assets/3434906e-bd0d-496a-9379-52a3fe88e4b3" />
This database shows us the recipes created and this shows us the dish name, time-to-prepare, ingredients, steps and the author-id  along with likes, image of the recipe and the time when they created the recipes.




API’s Used:

(1.) => Before deployment
(2.)=> After deployment
create API call:
1.localhost:8000/api/recipe
2.https://recipe-server-red.vercel.app/api/recipe

retrieve API  call
1.localhost:8000/api/recipe
2.https://recipe-server-red.vercel.app/api/


Retrieve by id API call
1.localhost:8000/api/recipe/:id
2.https://recipe-server-red.vercel.app/api/recipe/:id


update API call (patch)
1.localhost:8000/api/recipe/:id
2.https://recipe-server-red.vercel.app/api/recipe/:recipeId

delete API call
1.localhost:8000/api/recipe/:id
2.https://recipe-server-red.vercel.app/api/recipe/${recipeId}

register API call
1.localhost:8000/api/register
2.https://recipe-server-red.vercel.app/api/register

login API call
1.localhost:8000/api/recipe/login
2.https://recipe-server-red.vercel.app/api/login









    THE END

 
 
 

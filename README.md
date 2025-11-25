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


<img width="872" height="491" alt="image" src="https://github.com/user-attachments/assets/d48d8134-d5d2-4d2a-a6bb-45f4210532b8" />

 	 




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

 
 
 

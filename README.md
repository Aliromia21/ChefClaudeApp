🍳 ChefClaude – AI-Powered Recipe Generator

ChefClaude is a fun React application that helps you discover recipes based on the ingredients you have at home.
It integrates with Hugging Face Inference API (Mistral/Mixtral) to generate recipes in real-time, formatted in Markdown for easy display.

🚀 Features

Add ingredients dynamically via a simple input form

View a live-updated list of ingredients

Generate creative recipes with AI (Mixtral model via Hugging Face)

Recipes are returned in Markdown, making them clean and well-structured

Modular components:

IngredientsList – displays your chosen ingredients

ClaudeRecipe – renders the AI-generated recipe

Main – orchestrates the app

📂 Project Structure
 ```bash
 ├── src
 │   ├── components
 │   │   ├── IngredientsList.jsx
 │   │   └── ClaudeRecipe.jsx
 │   ├── ai.js
 │   └── Main.jsx
 ├── package.json
 └── README.md
   ```

⚙️ Setup & Installation

1. Clone the repository

 ```bash 
   git clone https://github.com/yourusername/ChefClaude.git
   cd ChefClaude
 ```
2. Install dependencies :
```bash 
   npm install
```

3.Add environment variables
   ```bash 

   Create a .env file in the root directory:

   HF_ACCESS_TOKEN=your_huggingface_token_here

   ```
4. Run the app :
```bash 
   
   npm run dev
  ```

💡 How It Works :

Enter ingredients in the input field.

Ingredients appear in a dynamic list.

Click Get Recipe → The app sends your ingredients to Hugging Face’s Mixtral model.

The model generates a creative recipe (Markdown formatted).

The recipe is displayed beautifully in the UI.




🛠️ Tech Stack :

Frontend: React ( Vite )

AI Model: Hugging Face Inference API (Mixtral-8x7B-Instruct)

Language: JavaScript / JSX

Styling: CSS
   

---
title: VideTonFrigo
publishDate: 2024-06-17 00:00:00
img: /assets/vide-ton-frigo.jpg
img_alt: An app interface showing a recipe generated from listed ingredients.
description: |
  VideTonFrigo is an innovative application that generates recipes based on listed ingredients or described cravings. Utilizing ChatGPT-3.5 and a custom layer, it creates JSON outputs from prompts.
tags:
  - Dev
  - FullStack
  - AI
---

## Project Overview

VideTonFrigo is an application designed to generate recipes based on ingredients you have or your described cravings. By leveraging ChatGPT-3.5 and a custom layer developed by us, the application produces JSON outputs from prompts instead of simple text.

The API is accessible on [GitHub](https://github.com/yourusername/VideTonFrigoAPI) with an online demo available [here](https://demo.herisson.dev/vide-ton-frigo).

## Features

### HomeActivity

- **Prompt Input**: The main screen where users enter their prompt.
- **Intent Launch**: Once the prompt is validated, an intent launches the RecipeActivity.

### RecipeActivity

- **API Interaction**: Queries our API at [https://recipe.herisson.dev/api/recipes/generate](https://recipe.herisson.dev/api/recipes/generate) with the user's prompt.
- **Recipe Display**: Shows the generated recipe, including ingredients and steps.
- **Timer**: A timer can be activated for each step within the app, alerting the user upon completion.

### HistoriqueActivity

- **Prompt History**: Displays the user's prompt history, allowing them to review previous requests.

## Technical Stack

- **ChatGPT-3.5**: Utilized for generating recipe content based on user prompts.
- **Custom Layer**: Developed to convert prompts into JSON format for more structured data handling.
- **API**: Accessible on GitHub with a demo for real-time interaction.

## How It Works

1. **HomeActivity**: Users enter their ingredient list or describe their cravings.
2. **RecipeActivity**: The app sends this input to our API, which generates a recipe in JSON format. This recipe is then displayed, complete with ingredients and step-by-step instructions. A built-in timer helps manage cooking steps.
3. **HistoriqueActivity**: Users can access their prompt history to revisit or reuse previous queries.

## Conclusion

VideTonFrigo offers a unique and practical solution for home cooks looking to make the most of their ingredients. By combining AI with a custom API, it provides a seamless and interactive recipe generation experience. The integration of features like step timers and prompt history enhances usability and user satisfaction.

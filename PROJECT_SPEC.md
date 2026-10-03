# Smart Grocery US — Build Specification

## Audience
United States only. All user-facing copy must be English (en-US). Currency is USD. Prefer US customary food measurements.

## Visual system
Black background, dark cards, fluorescent/neon green primary accents, rounded corners, modern icons, restrained animations, mobile-first responsive UI.

## Main navigation
Dashboard, What to Eat Today, Recipes, Shop, Settings. Use bottom navigation on mobile.

## Dashboard
Show Meals Prepared, Workouts Completed, Active Days, Favorites and Weekly Progress. Planned meals must not count as completed until marked prepared. Workouts count only after completion.

## What to Eat Today
Two areas: My Planning (available to free users) and My Day Pro (Pro-gated). Planning groups meals by date and shows recipe image/name/time/servings/calories/protein/carbs with prepared/not prepared/remove actions.

## My Day Pro
Profile: weight, height, goal (lose weight/maintain/gain muscle), activity level, workout location (gym/home), training level. Show estimated daily calories, protein/carbohydrate targets, suggested meals and workout suggestion. Include a non-medical informational disclaimer.

## Recipes
Each recipe needs a real food photo, name, category, prep time, servings, calories, protein, carbs, ingredients, detailed unique steps and allergens. Start with 12 free recipes. Locked paid recipes may show teaser information but must not reveal full ingredients or preparation.

Paid recipes cost $2.00 each. Pro must never automatically unlock paid recipes and paid recipe cards must not use a Pro badge.

Filters: All Recipes, Favorites, Unlocked; Breakfast, Lunch, Afternoon Snack, Dinner; Fitness Breads, Healthy Cakes, Salads, Healthy Pasta, Healthy Desserts, Smoothies & Shakes.

Include Banana Oat Cake, Apple Cinnamon Oat Cake, Cocoa Banana Cake, Carrot Oat Cake, Yogurt Lemon Cake, Whole Wheat Sandwich Bread, Oat Banana Breakfast Bread, Whole Wheat Herb Rolls, Sweet Potato Bread and Skillet Oat Bread.

## Shop
Offers: 1 recipe $2.00; 3 recipes $5.50; 5 recipes $8.50; 10 recipes $15.00; 20 recipes $27.00. Packs grant recipe credits and each premium recipe unlock consumes one credit.

Pro: $7.99/month. Pro unlocks My Day Pro, personalized meal suggestions/targets, workout planning and advanced progress features. It does not unlock paid recipes.

## Persistence
Persist favorites, purchased recipes, recipe credits, meal planning, prepared meals, workout history, Pro profile and user preferences. Local persistence is acceptable initially, but keep architecture ready for authentication/database integration.

## Checkout
Do not implement real payments in the initial build. Keep payment buttons/architecture ready for a future payment provider. Never expose secrets in frontend code.

## Development constraint
Prioritize a stable Lovable-compatible architecture. Do not add Vercel-specific configuration. Keep features modular and avoid unnecessary build/framework changes.

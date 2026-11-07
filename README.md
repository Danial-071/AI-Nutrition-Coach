# AI Nutrition Coach

AI Nutrition Coach is an AI-based multimodal RAG (Retrieval-Augmented Generation) application that analyzes a user-uploaded food image and answers nutrition-related questions about that meal.

## What this project does

- Accepts a food image uploaded by the user
- Extracts visual context from the image
- Retrieves relevant nutrition knowledge
- Generates context-aware answers to user questions (for example: calories, macros, ingredients, and healthier alternatives)

## High-level workflow

1. **Image upload** – user submits a food photo
2. **Multimodal understanding** – the model interprets food items from the image
3. **Retrieval step** – relevant nutrition data is fetched from the knowledge base
4. **RAG response generation** – the system answers the user question using retrieved context

## Example use cases

- “How many calories are in this meal?”
- “Is this meal high in protein?”
- “Suggest a healthier version of this dish.”
- “Can this fit into a weight-loss diet?”

## Goal

Provide practical, contextual, and easy-to-understand nutrition guidance based on what users are actually eating.

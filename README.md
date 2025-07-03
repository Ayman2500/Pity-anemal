git init
git add .
git commit -m "Initial commit - PetTalk AI Vite React app"
git branch -M main
git remote add origin https://github.com/AYMAN2500 /pet-talk-ai.git
git push -u origin main
#!/bin/bash

echo "Please enter your GitHub username:"
read USERNAME

echo "Initializing git repository..."
git init

echo "Adding files..."
git add .

echo "Committing changes..."
git commit -m "Initial commit - PetTalk AI Vite React app"

echo "Setting branch to main..."
git branch -M main

echo "Adding remote origin..."
git remote add origin https://github.com/$USERNAME/pet-talk-ai.git

echo "Pushing to GitHub..."
git push -u origin main

echo "Done! Check your GitHub repository now."

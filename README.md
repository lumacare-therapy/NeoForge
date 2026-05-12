# Create folder
mkdir neoforge-ai
cd neoforge-ai

# Create files
echo "your html code here" > index.html
echo "# NeoForge AI" > README.md

# Upload to GitHub
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/neoforge-ai.git
git push -u origin main

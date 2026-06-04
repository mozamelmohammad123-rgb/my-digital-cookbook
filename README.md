mkdir my-digital-cookbook
cd my-digital-cookbook
# Create your first recipe file
echo "# My Digital Cookbook" > README.md
echo "## Spaghetti Carbonara" > carbonara.md
echo "**Prep Time:** 15 minutes" >> carbonara.md
echo "**Ingredients:** pasta, eggs, bacon, parmesan cheese" >> carbonara.md

# Check status
git status

# Add files to staging
git add .

# Commit with message
git commit -m "Initial commit: Add README and carbonara recipe"

# View your commit history
git log --oneline


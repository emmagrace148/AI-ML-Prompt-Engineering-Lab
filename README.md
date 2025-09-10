# AI-ML-Prompt-Engineering-Lab
# create local folder and init a repo with main branch
mkdir AI-ML-Prompt-Engineering-Lab
cd AI-ML-Prompt-Engineering-Lab
git init -b main

# create README.md (this will write the README content shown below)
cat > README.md << 'EOF'
# (PASTE README CONTENT FROM BLOCK BELOW HERE)
EOF

git add README.md
git commit -m "Initial commit: Add README for AI-ML-Prompt-Engineering-Lab"

# Create empty repo on GitHub (do this via web UI OR create via gh CLI below)
# Then add remote & push (replace USERNAME)
git remote add origin https://github.com/USERNAME/AI-ML-Prompt-Engineering-Lab.git
git push -u origin main

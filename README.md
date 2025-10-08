# configure git (if not done)
git config --global user.name "Sahil"
git config --global user.email "youremail@example.com"

mkdir sahil-profile
cd sahil-profile
echo "# Hi, I'm Sahil" > README.md
git init
git add README.md
git commit -m "initial profile README"
# Create repo on GitHub via web or gh CLI, then push

pkg install git curl -y
git clone https://github.com/your-username/your-repo.git
cd your-repo
curl -s https://www.contributor-covenant.org/version/2/1/code_of_conduct.md -o CODE_OF_CONDUCT.md
git add CODE_OF_CONDUCT.md
git commit -m "Add CODE_OF_CONDUCT"
git push

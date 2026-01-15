# github-repository
github-repository
cd /opt/
sudo dnf update -y
sudo dnf install git nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx
ls -ld /var/www/html
mkdir -p /var/www/html
git clone https://github.com/shivangishakya78-web/github-repository.git
dir
cd github-repository/
git status
mkdir shivangi
chmod 655 shivangi
cd shivangi/
vi index.html
<h1>CI CD Working Successfully</h1>
ls
git add index.html
git status
git commit -m "change by shivangi"
git branch
git push
ssh-keygen -t rsa -b 4096
ll
cat ~/.ssh/id_rsa.pub
sudo dnf install nodejs -y
node -v
npm -v
npm init -y
vi .gitignore
-------------
node_modules
.env
---------------
git branch
git status
git add .gitignore
git commit -m "shivangi"
git branch
git remote add origin https://github.com/shivangishakya78-web/github-repository.git
git remote -v
git config --global pull.rebase false
git pull origin main --allow-unrelated-histories
git push -u origin main

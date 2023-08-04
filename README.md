# metaboliteMath
Use to count pathways and reactions for metabolites

steps to set up the SSH key:

in Git Bash (local computer)

ssh-keygen -t rsa -C "klongnecker@whoi.edu"
cat ~/.ssh/id_rsa.pub | clip

Test the key: ssh -T git@github.com (that is the right email address)
git remote set-url origin git@github.com:KujawinskiLaboratory/metaboliteMath.git

git add -A\
git commit -am "Update README.md"\
git push

$Add the key to the ssh-agent

ssh-add ~/.ssh/id_rsa

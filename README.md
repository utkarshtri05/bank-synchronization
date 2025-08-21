# 1) create a local folder and move files into it
mkdir bank-synchronization-demo
cd bank-synchronization-demo
# move your file here:
cp ../bank-synchronization.html ./

# 2) initialize git
git init
git add .
git commit -m "Add Bank Synchronization Demo — Race Condition vs Lock"

# 3) connect with GitHub repo
git branch -M main
git remote add origin https://github.com/USERNAME/bank-synchronization-demo.git
git push -u origin main

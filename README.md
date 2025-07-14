# ci_cd_practice
CI/CD practice repository
#once we know the code is working, this is how you deply or CD

via terminal:
git pull #latest code
git checkout #mainbranch of github
npm install
npm run build 

#deploy code into server with a cmd
#next ssh
ssh #into server and restart no node.js process if running js
pm2 restart 0


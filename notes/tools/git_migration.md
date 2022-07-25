Git Rep Migration:

git clone --mirror <URL to my OLD repo location>
cd <New directory where your OLD repo was cloned>
git remote set-url origin <URL to my NEW repo location>
git push --mirror origin

Source: https://stackoverflow.com/questions/1484648/how-to-migrate-git-repository-from-one-server-to-a-new-one

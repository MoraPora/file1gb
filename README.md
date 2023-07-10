# file1gb

Add 2nd run - PKI - FL.00,01

<<<<<<< HEAD
=======
## LOCAL
git filter-branch --force --index-filter \
  "git rm --cached --ignore-unmatch .env" \
  --prune-empty --tag-name-filter cat

git filter-branch --force --index-filter \
  "git rm --cached --ignore-unmatch git-credentials.txt" \
  --prune-empty --tag-name-filter cat

git filter-branch --force --index-filter \
  "git rm --cached --ignore-unmatch git-credentials.txt~" \
  --prune-empty --tag-name-filter cat

git filter-branch --force --index-filter \
  "git rm --cached --ignore-unmatch file1gb.tar.gz" \
  --prune-empty --tag-name-filter cat

git push origin --force --all

## REMOTE
git pull --rebase
>>>>>>> c3932860bc46b69ae11756912f0dec79f3315fa8

# Note

- blog link: [Github](https://shakilahmedatik.blogspot.com/) , [Zoom](https://asif-102.blogspot.com/)
- common issues:
  - failed to push ref error (after editing on GitHub):
    - `git push -u origin main -f`
    - `git pull` + `git push` (best solution)
  - git clone unable to access error (cloned with .git file):
    - delete .git file from file manager
    - delete .git on terminal: `git rm -rf .git`
  - unable to access repo error (permission denied - publickey):
    - change origin "SSH" to "HTTP" (delete .git & set again)
  - fatal error (multiple GitHub account/requested url returned error):
    - Credential Manager → Windows Credential → remove github

# Screenshot

### Problem 1

![](/screenshot/28.png)

### Problem 2

![](/screenshot/29.png)

### Problem 3

![](/screenshot/30.png)

### Problem 4

![](/screenshot/31.png)

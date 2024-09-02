# FoodFiesta
FoodFiesta is a fictional food delivery platform designed to provide users with a seamless experience to order food from their favorite restaurants. The platform aims to offer a variety of cuisines, easy payment options, and quick delivery services.

## Team Members
- Alice Anderson
- Bob Brown
- Charlie Clark
- Dana Davis


## Bash Command Work
Dell@DESKTOP-JC58O94 MINGW64 ~ (main)
$ git clone https://github.com/Praveen-kush/FoodFiesta.git
fatal: destination path 'FoodFiesta' already exists and is not an empty directory.

Dell@DESKTOP-JC58O94 MINGW64 ~ (main)
$ cd FoodFiesta

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (main)
$ touch .gitignore

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (main)
$ git add .gitignore

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (main)
$ git commit -m "Added .gitignore to ignore node_modules, .env, and other non-essential files"
[main 2525f9e] Added .gitignore to ignore node_modules, .env, and other non-essential files
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 .gitignore

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (main)
$ git push origin main
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Praveen-kush/FoodFiesta.git/'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (main)
$ git checkout -b feature-user-authentication
Switched to a new branch 'feature-user-authentication'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-user-authentication)
$ git checkout -b feature-order-tracking
Switched to a new branch 'feature-order-tracking'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-order-tracking)
$ git checkout -b feature-payment-system
Switched to a new branch 'feature-payment-system'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ echo "// User Authentication Feature Code" > backend/authentication.js
bash: backend/authentication.js: No such file or directory

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git add .

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git commit -m "Developed User Authentication feature"
On branch feature-payment-system
nothing to commit, working tree clean

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git checkout feature-order-tracking
Switched to branch 'feature-order-tracking'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-order-tracking)
$ echo "// Order Tracking Feature Code" > backend/order-tracking.js
bash: backend/order-tracking.js: No such file or directory

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-order-tracking)
$ git checkout feature-order-tracking
Already on 'feature-order-tracking'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-order-tracking)
$ echo "// Order Tracking Feature Code" > backend/order-tracking.js
bash: backend/order-tracking.js: No such file or directory

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-order-tracking)
$ git add .

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-order-tracking)
$ git commit -m "Developed Order Tracking feature"
On branch feature-order-tracking
nothing to commit, working tree clean

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-order-tracking)
$ git checkout feature-payment-system
Switched to branch 'feature-payment-system'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ echo "// Payment System Feature Code" > backend/payment-system.js
bash: backend/payment-system.js: No such file or directory

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git add .

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git commit -m "Developed Payment System feature"
On branch feature-payment-system
nothing to commit, working tree clean

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git push origin feature-user-authentication
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Praveen-kush/FoodFiesta.git/'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git push origin feature-order-tracking
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Praveen-kush/FoodFiesta.git/'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git push origin feature-payment-system
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Praveen-kush/FoodFiesta.git/'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git checkout feature-user-authentication
Switched to branch 'feature-user-authentication'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-user-authentication)
$ git pull origin main
From https://github.com/Praveen-kush/FoodFiesta
 * branch            main       -> FETCH_HEAD
Already up to date.

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-user-authentication)
$ git checkout feature-order-tracking
Switched to branch 'feature-order-tracking'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-order-tracking)
$ git pull origin main
From https://github.com/Praveen-kush/FoodFiesta
 * branch            main       -> FETCH_HEAD
Already up to date.

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-order-tracking)
$ git checkout feature-payment-system
Switched to branch 'feature-payment-system'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git pull origin main
From https://github.com/Praveen-kush/FoodFiesta
 * branch            main       -> FETCH_HEAD
Already up to date.

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git push origin feature-user-authentication
error: unable to read askpass response from 'C:/Program Files/Git/mingw64/bin/git-askpass.exe'
Username for 'https://github.com': Praveen-kush
error: unable to read askpass response from 'C:/Program Files/Git/mingw64/bin/git-askpass.exe'
Password for 'https://Praveen-kush@github.com':
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Praveen-kush/FoodFiesta.git/'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git push origin feature-user-authentication
error: unable to read askpass response from 'C:/Program Files/Git/mingw64/bin/git-askpass.exe'
Username for 'https://github.com': Praveen-kush
error: unable to read askpass response from 'C:/Program Files/Git/mingw64/bin/git-askpass.exe'
Password for 'https://Praveen-kush@github.com':
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Praveen-kush/FoodFiesta.git/'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git push origin feature-order-tracking
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Praveen-kush/FoodFiesta.git/'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git push origin feature-payment-system
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Praveen-kush/FoodFiesta.git/'

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git log
commit 2525f9e80f5cfab17807ab58aa4cb0c8edf6cfea (HEAD -> feature-payment-system, main, feature-user-authentication, feature-order-tracking)
Author: Praveen-kush <praveenkushwaha0468@gmail.com>
Date:   Mon Sep 2 19:56:37 2024 +0530

    Added .gitignore to ignore node_modules, .env, and other non-essential files

commit 9ce16ae59e33296e5dadeee85a4e9ad3ffa19621 (origin/main, origin/HEAD)
Author: Praveen Maurya <99396223+Praveen-kush@users.noreply.github.com>
Date:   Mon Sep 2 19:32:09 2024 +0530

    Update README.md

commit 84f0d669f79f77701f8a26f35d7541f33748f051
Author: Praveen Maurya <99396223+Praveen-kush@users.noreply.github.com>
Date:   Mon Sep 2 19:30:41 2024 +0530

    Initial commit

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git log --oneline --graph --all
* 2525f9e (HEAD -> feature-payment-system, main, feature-user-authentication, feature-order-tracking) Added .gitignore to ignore node_modules, .env, and other non-essential files
* 9ce16ae (origin/main, origin/HEAD) Update README.md
* 84f0d66 Initial commit

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git status
On branch feature-payment-system
nothing to commit, working tree clean

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git pull origin main
From https://github.com/Praveen-kush/FoodFiesta
 * branch            main       -> FETCH_HEAD
Already up to date.

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git log --oneline --graph --all
* 2525f9e (HEAD -> feature-payment-system, main, feature-user-authentication, feature-order-tracking) Added .gitignore to ignore node_modules, .env, and other non-essential files
* 9ce16ae (origin/main, origin/HEAD) Update README.md
* 84f0d66 Initial commit

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$ git status
On branch feature-payment-system
nothing to commit, working tree clean

Dell@DESKTOP-JC58O94 MINGW64 ~/FoodFiesta (feature-payment-system)
$

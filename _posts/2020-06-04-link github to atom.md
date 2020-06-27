---
title: How to Link and Manage Github Project in Atom
---
Obviously, we need a Github account and project to get start with.

## Setup


#### *If Project Not in Local*

Assuming the project is not in local yet, click `Github` on the right corner and choose `Clone an existing Github repository`.

<img src = "https://i.imgur.com/09xzVh8.png" width = "65%" height = "65%" />

There'll be a popup window.

`Clone from`: get Git link from Github page and paste here

`To directory`: it is the folder where you want to the project to be cloned into.

![Screen Shot 2020-06-27 at 1.27.04 AM](https://i.imgur.com/Ss0gZFt.png)

After that, it will ask you to click a link to generate a token for authentication. Get the token and paste it, then you should be able to Login.

![Screen Shot 2020-06-27 at 1.23.58 AM](https://i.imgur.com/BxPzhNH.png)

<br>

#### *If Project already in Local*

It's super easy. Simply go to menu `File` - `Add Project Folder` and choose the parent folder which contains `.git`.

Click `Github` on the right corner, it will ask for authentication token just as above. Once it's verified, Atom will recognize it.

## How to Push Request from Local to Github

`Push Request` is a term to describe the changes will be uploaded from local to Github.

After setup, the Git/Github panel will look like below. Any changes we made, the changed files will show under `Unstaged Changes` on the right.

![](https://i.imgur.com/g7Mt3zJ.png)

Once we clicked `Stage All`, all files will move to `Staged Changes`.

Now put some comments under `Commit message` and click `Commit to Master`(or <kbd>Cmd ⌘</kbd> <kbd>Enter ↵</kbd>) to confirm. This step is equal to `git commit -m "message"`

![](https://i.imgur.com/4G6n4SX.png)

The comments and `Push` request will be updated. Click `Push x` to push the change to Github. It is equal to `git push origin master`.

![](https://i.imgur.com/o8A8ues.png)

## How to Pull Request from Github to Local

In contrary to `Push Request`, `Pull Request` means the changes will be downloaded from Github to local folder. To do this, click `Fetch` button on the right corner.

![](https://i.imgur.com/Q2mHYjY.png)

If there's any change available, it will show `Pull x`. Click it to execute `Pull Request`.

![Screen Shot 2020-06-27 at 2.06.52 AM](https://i.imgur.com/yUFaOQB.png)
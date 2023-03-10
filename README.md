# 𝟏𝟎 𝐌𝐮𝐬𝐭-𝐊𝐧𝐨𝐰 𝐆𝐢𝐭 𝐂𝐨𝐦𝐦𝐚𝐧𝐝𝐬 𝐓𝐡𝐚𝐭 𝐚𝐫𝐞 𝐤𝐧𝐨𝐰𝐧 𝐛𝐲 𝐟𝐞𝐰𝐞𝐫 𝐩𝐞𝐨𝐩𝐥𝐞 (newbie).


𝟏. 𝐀𝐝𝐝/𝐂𝐨𝐦𝐦𝐢𝐭 𝐀𝐥𝐥
```
Standard way: git add .
git commit -m "Message"
Another way: git commit -a -m "Message"
```

𝟐. 𝐀𝐥𝐢𝐚𝐬𝐞𝐬
```
With aliases, you can write your own Git commands that do anything you want.
Eg: git config --global alias.ac '!git add -A && git commit -m'
(alias called ac, git add -A && git commit -m will do the full add and commit)
```

𝟑. 𝐑𝐞𝐯𝐞𝐫𝐭
```
The revert command simply allows us to undo any commit on the current branch.
Eg: git revert 486bdb2
Another way: git revert HEAD (for recent commits)
```

𝟒. 𝐑𝐞𝐟𝐥𝐨𝐠
```
This command lets you easily see the recent commits, pulls, resets, pushes, etc on your local machine.
Eg: git reflog
```

𝟓. 𝐏𝐫𝐞𝐭𝐭𝐲 𝐋𝐨𝐠𝐬
Gives you the ability to print out a pretty log of your commits/branches.
Eg: git log --graph --decorate --oneline

𝟔. 𝐒𝐞𝐚𝐫𝐜𝐡𝐢𝐧𝐠 𝐋𝐨𝐠𝐬
```
One can also use the log command to search for specific changes in the code.
Eg: git log -S "A promise in JavaScript is very similar"
```

𝟕. 𝐒𝐭𝐚𝐬𝐡
```
This command will stash (store them locally) all your code changes but does not actually commit them.
Eg: git stash
```

𝟖. 𝐑𝐞𝐦𝐨𝐯𝐞 𝐃𝐞𝐚𝐝 𝐁𝐫𝐚𝐧𝐜𝐡𝐞𝐬
```
This command will delete all the tracking information for branches that are on your local machine that are not in the remote repository, but it does not delete your local branches.
Eg: git remote update --prune
```

𝟗. 𝐁𝐢𝐬𝐞𝐜𝐭
```
For finding which commits caused certain bugs
Eg: git bisect start
git bisect bad
git bisect good 48c86d6
```

𝟏𝟎. 𝐃𝐞𝐬𝐭𝐫𝐨𝐲 𝐋𝐨𝐜𝐚𝐥 𝐂𝐡𝐚𝐧𝐠𝐞𝐬
```
One can wipe out all changes on your local branch to exactly what is in the remote branch.
Eg: git reset --hard origin/main
```

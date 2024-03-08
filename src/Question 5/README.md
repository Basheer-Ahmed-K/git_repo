Question 5

Step 1: Step 1: Create a feature branch.

Step 2: Switch to the new branch.

		open the file and make some changes to it. (change 1 done)

		Add and commit the changes to the new branch. 

		open the same file and make some changes to it. (change 2 done)

		Add and commit the changes to the new branch.

		open the same file and make some changes to it. (change 3 done)

		Add and commit the changes to the new branch.

Step 3: Use the "git log" command to view the commit history and identify the commit to which you want to reset.

Step 4: Use the "git reset" command followed by the desired reset type and the commit hash

Step 5: Verify that the reset was successful by using the "git log" command again. 

Step 6: Use the "git log" command to view the commit history and identify the commit that you want to reverse.

Step 7: Use the "git revert" command followed by the commit hash or reference to which you want to revert. (Hint: git revert <commit hash>)

Step 8: Verify that the revert was successful by using the "git log" command again.

Note: Identify the difference between git log after git reset and git r evert.


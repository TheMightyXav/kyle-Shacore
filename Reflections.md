Answer each in 2–5 sentences. Specifics from your own session (exact commands,
error messages, commit messages) count for more than general definitions.

1. **Where does your code live?** Describe (or sketch and include an image of)
   where your changes exist after each step: after you save the file, after
   `git add`, after `git commit`, after `git push`, and after your partner runs
   `git pull`. At which point can your partner see your work?

   The code that I have written exists only on my local machine until it is sent to github. The command 'git add' takes the code and prepares it to be sent out, placing the files that I want to send out into the Staging Area. from there, I can enter the command 'git commit' to verify that these are the files that I want to send out and that I will not be editing them further. Following that, I enter 'git push' to finally send these files to the Github Repository of my choosing. If I want to access these files from a different device or have a teammate download them, either I, on my new device, or my teammate would have to enter the command 'git pull' after cloning that repository so that all updates to the code in question are properly downloaded.

2. **Your predictions vs. reality.** In Round 1, step 5, you each predicted
   what would happen when Partner B pushed. What did each of you predict, and
   what actually happened? Using what you know now, explain *why* git rejected
   the push. Then explain what `git pull` did that the push couldn't.

   So in that scenario, having already uploaded my own modified files, anything that Self was trying to also upload was rejected. This was because the changes that I made to the online repository were not automatically translated into his local repo. Github could not accept push commands until Self had run the 'git pull' command, which updated his local repo to match the version that had my modified code in it as well.

3. **Resolving a conflict.** Pick one of the two conflicts you resolved
   (Round 1 or Round 2). How did you and your partner decide what to keep?
   How did you confirm the resolution was correct before pushing?
 
 One problem we had while doing the assignment was getting the git pull to show on the other partner's github repository. Which lead us to be confuse for a little while we took a break and came back to the problem with a new mind intact we ask for help from our fellow classmates which allow us to see our errors and rectify the problem and find the solution. One of us ran git push to send the file which allow the other one to finally run git pull so they can save and download the information. 


4. **Getting unstuck.** Describe one moment when something didn't work or
   didn't match what you expected, in the warm-up or while writing the story.
   What was the exact message or result? What did you check first (for
   example `git status` or `git remote -v`), and what fixed it?

There was an instance where we were having difficulty getting our shared repository set up. Despite having our local clones of the repository, we were having difficulty setting up the upload and download of our respective versions. We verified that the connections to Github were correct, before turning our attention to the repository itself. The answers came to us through our peers, who informed us that we were already setting it up right, and informed us that running the 'git pull command' allowed us to download the new files.


5. **Commit messages for a team.** Look at your commit history on GitHub. Pick
   the most useful commit message and the least useful one, and rewrite the
   weak one here (you don't need to change the message on GitHub). Then
   explain: if five people were working in this repo instead of two, why would
   clear commit messages and pulling before you start matter even more?


   
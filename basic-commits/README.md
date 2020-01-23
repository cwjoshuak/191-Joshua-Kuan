# Git Kata: Basic Commits

## The task

1. Use `git status` to see which branch you are on.
![Answer to Q1](images/Q1,png)

2. What does `git log` look like?
![Answer to Q2](images/Q2.png)

3. Create a file
` $ touch test.txt`

4. What does the output from `git status` look like now?
![Answer to Q4](images/Q4.png)

5. `add` the file to the staging area
` $ git add test.txt`

6. How does `git status` look now?
![Answer to Q6](images/Q6.png)

7. `commit` the file to the repository
![Answer to Q7](images/Q7.png)

8. How does `git status` look now?
![Answer to Q8](images/Q8.png)

9. Change the content of the file you created earlier
` $ echo "STUFF" >>test.txt `

10. What does `git status` look like now?
![Answer to Q10](images/Q10.png)

11. `add` the file change
` $ git add test.txt`

12. What does `git status` look like now?
![Answer to Q12](images/Q12.png)

13. Change the file again
` $ echo "more STUFF" >>test.txt`

14. Make a `commit`
` $ git commit -m "added more stuff to test.txt"`
15. What does the `status` look like now? The `log`?
![Answer to Q14 - git status](images/Q14-1.png)
![Answer to Q14 - git log](images/Q14-2.png)

16. Commit the newest change
``` 
$ git add test.txt
$ git commit -m "added more stuff to test.txt"
```

# Git Workshop Practice Repository

This repository was created to practice and improve my Git skills. It includes tasks that cover  Git commands.

---

<img src="https://github.com/user-attachments/assets/9c245cef-41c0-40a2-a288-55a88001f8da"
alt="Git Workshop Image" style="width: 100%; height: 100%;" />

---

## What This Repository Covers ?


1. **Creating Repositories**  
   - Start with a local repository.
     
   - Link it to a remote repository on GitHub.
     
-- 

2. **Adding and Pushing Files**  
   - Add files like:  
     - `demo.py` (to practice pushing Python files).  
     - `mena.txt` (to practice pushing text files).
       
   - Learn how to reset, restore, and re-add files with `new.txt`.
   - Push a **folder** called `Test` to practice working with folders in Git.
     
-- 

3. **Working with Branches**  
   - Create a new branch called `new-branch`.  
   - Add a file (`new branch.txt`) in this branch.  
   - Merge it back into the main branch.
     
   - **Difference Between Merging vs. rebasing :**
     - To incorporate new commits into your branch, you have two options: `merging` or `rebasing`.
       
       ![image](https://github.com/user-attachments/assets/b59faa63-08e1-4387-878c-a0b07676b059)

     - `merge`:<br>
       This creates a new “merge commit” in the feature branch that ties together the histories of both branches, giving you 
       a branch structure that looks like this:
       
       ![image](https://github.com/user-attachments/assets/73c2d742-6aef-4b12-8eb4-70bc43e54de1)
     - `rebase`:<br>
       This moves the entire feature branch to begin on the tip of the main branch, effectively incorporating all of the new 
       commits in main. But, instead of using a merge commit, rebasing re-writes the project history by creating brand new 
       commits for each commit in the original branch like this:
       
       ![image](https://github.com/user-attachments/assets/f4086d8c-3364-4755-b4e3-fe3bd2dd48ab)

       

      - For more information : [Atlassian article on Merging vs. rebasing](https://www.atlassian.com/git/tutorials/merging-vs-rebasing))
        

--

4. **Using Tags**  
   - Create a lightweight tag (`v1.0`).  
   - Create an annotated tag (`v2.0`).
     
   - **Difference Between Lightweight and Annotated Tags :**
     - `Lightweight Tags`: These types of tags are just pointers to a commit without any other additional metadata. They are super quick and uncomplicated to create but they do not keep any extra details.
     - `Annotated Tags`: They are full objects within the Git database that save information such as the tagger’s name, email address, date of creation and a tagging message. These tags contain more information and are often used for public-release versions.
     - For more information : [GeeksforGeeks article on Git Tags](https://www.geeksforgeeks.org/git-tags/)
    


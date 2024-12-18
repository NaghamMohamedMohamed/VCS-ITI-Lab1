# Lab 2 : Tell Me Commands Part

1. To remove a branch ( dev , test ) locally and remotely :

   **- Locally :**   git branch -d dev  , git branch -d test

   ( If they are not fully-merged on main and still want to delete them then write the same command by changing **d** into **D** )

   **- Remotely :**   git push origin :dev  ,  git push origin :test
   
   
3. To checkout another branch without commit changes :  git checkout -b dev 
   
4. To list tags :   git tag
   
5. To remove a tag ( v7.0 ) locally and remotely :

   **- Locally :**   git tag -d v7.0

   **- Remotely :**   git push origin --delete v7.0

     ![removal ai _f7739bb2-e45b-44e7-838d-f29c3f591639-f170d1f1b3568e847bb26fadcb45f520](https://github.com/user-attachments/assets/022e6321-b3c0-4606-a843-079d4bb5128d)



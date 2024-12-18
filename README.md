**Lab 2 : Commands**

1. To remove a branch ( dev , test ) locally and remotely :

   **- Locally :**   git branch -d dev  , git branch -d test   ( If they are not fully-merged on main and still want to delete them then write the same command by changing **d** into **D** )

   **- Remotely :**   git push origin :dev  ,  git push origin :test
   
   
3. To checkout another branch without commit changes :  git checkout -b dev 
   
4. To list tags :   git tag
   
5. To remove a tag ( v7.0 ) locally and remotely :

   **- Locally :**   git tag -d v7.0

   **- Remotely :**   git push origin --delete v7.0

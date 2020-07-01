# Github

[Como fazer um merge](https://www.youtube.com/watch?v=NR9jc5ODvuM)

## Merge

1. Criar uma branch para uma nova feature. 
~~~
git checkout -b branchName
~~~ 

2. Fazer as alterações no código. 

3. Fazer o push para a branch nova. 
~~~
git add .
git commit -m "Commit details"
git push origin branchName
~~~

4. Ir para a branch master
`git checkout master` 

5. Fazer o merge. Essas alterações só serão válidas localmente.
`git merge branchName`

6. Fazer o push para a branch Master. 
~~~
git add . 
git commit -m "Merge concluído". 
git push origin master
~~~ 

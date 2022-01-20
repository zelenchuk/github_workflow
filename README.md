# About GitHub workflow



## Read this

https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token


## Practice

1. Try clone repo. And edit files.
2. Generate token by link upper and try to add, commit and push updates.
3. Example

- GitHub ask for entering token
- We need paste our token and thats all!
- If we edit file one's more, next push'ing must be without token entering.
- Enjoy


## Change repo 



### 1. Read this

https://stackoverflow.com/questions/22844806/how-to-change-my-git-username-in-terminal



### 2. Try 

`git remote set-url origin https://{new url with username replaced}`



### 3. Example for me

`
git remote set-url origin https://github.com/zelenchuk/github_workflow
`


## Change git user on PC

READ THIS

https://medium.com/@devesu/how-to-logout-from-git-in-windows-e17c66fe9ca8


### 1. Delete all auth on DESCTOP (PC):

Панель управления\Все элементы панели управления\Диспетчер учетных данных


### 2. Git unset 


`git config user.name --unset`

`git config user.email --unset`

`git config user.name "new_username"`

`git config user.email "new@email.com"`


### 3. Checking

- Try to commit. 

- GitHub or Bitbucket ask you to login again!

- Check who been the author of this sending. If that you? Thats works!


### 4. Enjoy


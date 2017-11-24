# from-server-to-bitbucket
A small guide to help you set up version control on our server and push to bitbucket.



## Connect to Server
<small>(See KonsolH for our ssh/ftp credentials)</small>

```
ssh *username*@apps.clockworkmedia.co.za
```

## Change Directory
```
cd public_html/your-project
```

## Setup Git/ Add files/ Commit and Push

```

git init

git add .

git commit -m "First Commit"

git remote add origin https://bitbucket.com/your-project-url.git

git push

```

*Remember to create the project on Bitbucket first

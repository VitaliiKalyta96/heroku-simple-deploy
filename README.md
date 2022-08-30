### Instruction 


Enter in site heroku https://www.heroku.com and input your login and password.

2 ways to deploy a project on heroku

1 option

Then perform next command in your terminal:

```
git clone "path_project"

sudo snap install --classic heroku

heroku login

heroku create "heroku_app_name"

git init

heroku git:remote -a a1sd3ff

git add .

git commit -am "1"

git push heroku master


```

** If app not run then perform next 2 additional command:

```
heroku container:push web --app "heroku_app_name"
heroku container:release web --app "heroku_app_name"
```

After run project in terminal:

```
Ctrl+C

heroku logout
```

2 option

Directly in your heroku account

```
Create new app "heroku_app_name";

Deployment method - connect to GitHub;

Search for a repository to connect "name_repository" and connect;

Deploy a GitHub branch .

```
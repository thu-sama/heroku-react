# heroku-github
Example React app on Heroku deploy from Github.

### Demo
[https://heroku-react-deploy.herokuapp.com/](https://heroku-react-deploy.herokuapp.com/)

#### Create React project and host it on heroku

Create React project : [https://github.com/mars/create-react-app-buildpack#quick-start](https://github.com/mars/create-react-app-buildpack#quick-start) 

#### Push to Github
    git remote add origin https://github.com/acc/heroku-react.git
    git push origin master
>Replace `https://github.com/acc/heroku-react.git` with the git repository you want.

>You can also create a Github repository first and clone it.

#### Set Deployment method
In your newly created heroku app dashboard, go to 
* Deploy
* Choose `Github` in `Deployment method`
* Type in repository name : in this case `heroku-react`
* Click Search and click Connect

>![Screen Shot](https://raw.githubusercontent.com/thu-sama/heroku-github/master/resources/img/heroku%20github%20deploy%20%C2%B7%20GitHub%20%20%20Heroku.png)

* Choose Enable Automatic Deploys if you want. `This will set heroku to deploy everytime you push a commit to github`
* Click DeployBranch and done

>![Screen Shot](https://raw.githubusercontent.com/thu-sama/heroku-github/master/resources/img/heroku%20github%20deploy%20%C2%B7%20GitHub%20%20%20Heroku%20(1).png)
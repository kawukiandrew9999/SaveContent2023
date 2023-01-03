apt install ffmpeg git python3-pip
git clone your_repo_link
cd saverestrictedcontentbot 
pip3 install -r requirements.txt
python3 -m main
```

- if you want bot to be running in background then enter `screen -S srcb` before `python3 -m main` 
- after `python3 -m main`, click ctrl+A, ctrl+D
- if you want to stop bot, then enter `screen -r srcb` and click ctrl+A then press K and enter Y.

Deploy your bot on `Render`

Tutorial - [Click here](https://telegra.ph/SRCB-on-Render-05-17)

Deploy your bot on `heroku`

» Method - 1:
- Star the repo, and fork it in desktop mode
- Go to settings of your forked repo
- Rename your repo by any other name
- Click on  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
 
» Method - 2:
- Star the repo, and fork it in desktop mode
- create app in heroku
- go to settings of app›› config vars›› add all variables
- add buildpacks
- connect to github and deploy
- turn on dynos
  
Buildpacks for manual deploy:

- `heroku/python`
- `https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git`

Deploy your bot on `Okteto` [Useless]
  
Tutorial for okteto - [click here](https://telegra.ph/Okteto-Deploy-04-01)

[![Develop on Okteto](https://okteto.com/develop-okteto.svg)](https://cloud.okteto.com)

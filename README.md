# docker run -it -p 4000:4000 -p 4205:4205 -v $(pwd):/home/app -w /home/app <image> /bin/bash
# To improve this scripts .............:::::::::
# ng --version
# ng new my-project --skip-install
# cd new-project
# npm install
# export CHROME_BIN=/usr/bin/chromium-browser
# RUN THE SERVER OUTSIDE CONTAINER VIA 4000 port
# ng serve --host 0.0.0.0 --port 4000
# docker exec -ti <container_name_runnin> bash
# cd new-project
# ng test --port 4205
# steps to heroku:
# heroku login
# heroku container:login
# heroku apps
# >>>herokuappname :radiant-journey-22301
# heroku container:push --app radiant-journey-22301
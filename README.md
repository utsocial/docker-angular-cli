# docker-angular-cli
Docker angular cli stable

docker run -it -p 4200:4200 -p 4205:4205 -v $(pwd):/usr/src -w /usr/src hoatle/teracy-angular-cli /bin/bash
# ng --version
# ng new my-project --skip-install
# cd new-project
# npm install
# export CHROME_BIN=/usr/bin/chromium-browser
# RUN THE SERVER OUTSIDE VIA 4200 port
# ng serve --host 0.0.0.0 --port 4200
# NEW TERM ....:
# docker exec -ti <container runnin> bash
# cd new-project
# ng test --port 4205

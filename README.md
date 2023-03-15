# Sara - the Rasa Demo Bot, commands for building and running docker containers
This is a dockernized rasa demo, which shows how does rasa work, Just simply run below docker-compose command.

Clone the project and train a model
```
git clone git@github.com:GuoqiangJia/rasa-demo-dockernized.git
pip install -r requirements.txt
rasa train
```

Build a docker image for Actions, and start up action server & rasa server 
```
docker-compose up -d
```

## :gift: License
Licensed under the GNU General Public License v3. Copyright 2018 Rasa Technologies
GmbH. [Copy of the license](https://github.com/RasaHQ/rasa-demo/blob/main/LICENSE).
Licensees may convey the work under this license. There is no warranty for the work.
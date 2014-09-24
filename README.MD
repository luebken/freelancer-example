- An example how to use https://registry.hub.docker.com/u/luebken/freelancer/

- Clone this repo `$ git clone git@github.com:luebken/freelancer-example.git`

- Edit as you like
  - _config.yml
  - _posts/*markdown
  - img/

- Build and run
  - `$ docker build -t mypage .`
  - `$ docker run -i -t -p 8080:4000 mypage`
  - `$ `
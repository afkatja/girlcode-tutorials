# Hosting

- Heroku app via Bolster / Maarten as girl-code (auto deploys from master)
  - env variables:
    - MONGO_URL:
    - ROOT_URL: http://girl-code.herokuapp.com
- Heroku Buildpack: https://github.com/AdmitHub/meteor-buildpack-horse.git
- DNSimple service for domain registration and redirect
  - name servers changed on vimexx.nl
- database via compose.io (otherwise via MongoLab)

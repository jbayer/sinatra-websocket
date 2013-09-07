sinatra-websocket
=================

simple web socket sinatra app that deploys to Cloud Foundry instances such as run.pivotal.io

## deploy to cloud foundry

- git clone THISREPO
- cd sinatra-websocket
- edit manifest.yml for any values to customize
- cf push
- visit the app on a port that supports web socket - on run.pivotal.io that is currently port 4443, so you would use https://wstest-f5169.cfapps.io:4443/ where the f5169 would vary for your app based on the value of ${random-word} chosen by the manifest.

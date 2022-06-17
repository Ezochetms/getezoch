# getezoch
Bienvenus sur EZOCH maison des jetons créé par l'équipe des collaborateurs de chetms 

# name: Deployment

on:
  push:
    branches:
      - main

jobs:
  deployment:
    runs-on: ubuntu-latest
    environment: 
      name: getezoch 
      url: https://getezoch.com
    steps:
      - name: deploy
        # ...deployment-specific steps

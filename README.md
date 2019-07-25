# Debug Build Configs

## Fix: 
Removed the "-" from my s3 bucket name
Had issues with code pipeline running "npm run build". Fixed that by manually running npm init and recreating another package.json file

## Config Three
- Having issues connecting to GH
![File Three](./assets/aws3-error.png)

- Build errors after fixing GH issues

![File Build](./assets/aws3-initial-build-error.png)

Had issues with code pipeline running "npm run build". Fixed that by manually moving my package.json and packagelock.json a folder up from where they were before

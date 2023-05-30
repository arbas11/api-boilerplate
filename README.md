# api-boilerplate
api boilerplate

with typescript
- express server
- kubernetes
- skaffold

change your-api directory with project name

open skaffold.yaml file and configure all the file name using the same name of api project name you just changed

open infra/k8s
change the file yaml file name with your project name followed by -depl.yaml

open yaml file and configure all the file name using the same name of api project name you just changed

if building without kubernetes and skaffold
work only on api directory
and do npm install to install all the dependencies

run using
 npm run serve for developmenr
 npm start for production

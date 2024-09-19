### DEPLOYING A NODEJS APP ON NETLIFY USING JENKINS

The Pipeline is running on docker agent

- CHECKOUT SCM

- BUILD STAGE
     - npm ci
     - npm run build

- TEST STAGE (UNIT TEST)
     - npm test

- DEPLOY STAGE
     - login to netlify (login credentials added as secrets text)
     - Install netlify cli
     - deploy to production

- RESULT
- Website URL:       https://sprightly-clafoutis-0f8648.netlify.app

<img width="496" alt="image" src="https://github.com/user-attachments/assets/c2a7451c-3fad-4ea2-a4eb-3ca9ce788f4f">













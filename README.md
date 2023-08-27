# gregemyers-api

This repo holds the headless CMS, a Strapi application, which powers  [greg-e-myers](https://github.com/tkgnm/greg-e-myers). Admins can log in [here](https://gregemyers-api-fly.fly.dev/admin) and add new posts/pages etc. 

### Develop

In order to make changes to the data model you'll need to start up a local server and then push to production. Please note you won't be able to actually access the production database when  running locally.

```
npm run develop
# or
yarn develop
```

## Deploy

This headless CMS is deployed on [fly.io](https://fly.io/), which comes with a postgres database to store all data on. The images are uploaded via the apps Media Library, which are then stored on S3.

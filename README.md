# Shop Angular Cloudfront

Angular version: ~12.

Manual deploy

- [Link to S3 website](http://angular-cloudfront.s3-website-eu-west-1.amazonaws.com/)

- [Link to S3 manual deploy website](http://angular-cloudfront-manual.s3-website-eu-west-1.amazonaws.com/)
- [Link to cloudfront manual deploy website](https://d3p5dnchj4qmtk.cloudfront.net/)

Auto deploy

- [Link to S3 auto deploy website](http://angular-cloudfront-auto-deploy.s3-website-eu-west-1.amazonaws.com/)
- [Link to cloudfront auto deploy website](https://d3pqms05kkm99n.cloudfront.net/)

Repo maintainers:

- [Sergey Gultyayev](https://github.com/gultyaev)

## The purpose

The repository was created to have an Angular version of e-shop for EPAM NodeJS AWS course. At the same time we strive to make this repository follows best practices so it may be used as a starter for new projects with all the necessary toolings already set up.

## NodeJS AWS course integration

All the necessary API endpoints are in the environments files `environment.ts` (for dev builds). Also it contains feature flags to enable/disable endpoints invocations from within the app so to ensure that you don't get errors for not implemented API endpoints.

## Contribution

Create an issue with the detailed description of the improvement/issue.

If you would like to help implementing some feature, you should ask the maintainers for approval so to ensure that the feature is desired in the repository and no efforts go wasted.

## Get up and running

Prerequisites: NodeJS v14

Follow the steps:

- git clone
- npm i
- ng serve

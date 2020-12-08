# Sample App Contribution Guide
Follow these directions when contributing new Sample apps.

## Quick Start
1) Create a new repository from this project using the `Use Template` button.
2) Delete the template specific files and folders: `SAMPLE_APP_CONTRIBUTING.md`, `screenshots`.
3) Fill out the `README.md` and `INSTRUCTIONS.md` files while following the directions (in comments) within.
4) Fill out the `astra.json` file with the pertinent values from your `README.md`
5) Ping the #sample-apps team to review your app and go through the publishing process.

When your app is complete, it will be forked into the `DataStax-Examples` organization and distributed across our web properties.

## Sample App Requirements
- Hosted on Github
- Created as a repository template from the [Sample App Template](https://github.com/DataStax-Examples/sample-app-template)
- Tracking enabled (UTM/Github stats)
- Focus on Astra/SG integration
- Focus on the problem solved
- Don't recapitulate 3rd party readme's
- Astra usage is required
- CI/CD
  - At minimum - Astra/SG Integration tests
  - Tests run via Github Actions
  - Tests run against DataStax Example's Astra DB and a docker image of SG's latest
  - SG latest tests run nightly
  - SG nightly failures are piped to #stargate-cicd
- Deployment
  - Local Development enumerated
  - Deployable to a 3rd party OOTB (Netlify, Vercel, Heroku, Gitpod, etc)
- Code Quality
  - Literative
  - Minimal
  - High value comments
  - Idiomatic
  - Consistent formatting
  - Configuration/Data driven
  - Piggyback on Ecosystem Frameworks 

## Reference Examples
  - https://github.com/DataStax-Examples/astra-next.js-starter

# Facebook Messenger Bot Skeleton
Skeleten Application to handle the authentication and webhook requests sent via facebook for new messenger bots.

This project is developed to work with Heroku with no coding changes required. It implements the standard echo function that is provided by Facebook to provide visual feedback it is working.

This project is written in Node.js and Express to stay in line with the official Facebook docs and make it easier to use their provided examples.

It has a default Verify Token of `TEST` however this can be changed be setting an environmental variable in heroku of `VERIFY_TOKEN`

There is also a requirement for a `PAGE_ACCESS_TOKEN` which is provided during the Facebook setup below. If you use the Heroku Button it will ask you for this during setup.

To see full instructions on how to enable in Facebook. [Follow the official guide](https://developers.facebook.com/docs/messenger-platform/quickstart)

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

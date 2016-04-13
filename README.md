# Facebook Messenger Bot Skeleton
Skeleten Application to handle the authentication and webhook requests sent via facebook for new messenger bots.

This project is developed to work with Heroku with no coding changes required. Obviously the Bot won't do anything unless you add some of your own logic.

This project is written in Node.js and Express to stay in line with the official Facebook docs and make it easier to use their provided examples.

It has a default Verify Token of `TEST` however this can be changed be setting an environmental variable in heroku of `VERIFY_TOKEN`

To see full instructions on how to enable in Facebook. [Follow the official guide](https://developers.facebook.com/docs/messenger-platform/quickstart)

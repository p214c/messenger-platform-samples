# Respbot ChatBot for FB Messenger Platform Sample -- node.js

This project is a ChatBot server for Messenger Platform built in Node.js. With this app, you can send it messages and it will respond based on matches found in the responses.txt file.

It contains the following functionality:

* Webhook (specifically for Messenger Platform events)
* Send API
* Web Plugins
* Messenger Platform v1.1 features

Follow the [walk-through](https://developers.facebook.com/docs/messenger-platform/quickstart) to learn about this project in more detail.

## Setup

Set the following environment variables before running the app:
MESSENGER_APP_SECRET=<app secret>
MESSENGER_VALIDATION_TOKEN=<user defined token>
MESSENGER_PAGE_ACCESS_TOKEN=<FB page access token>
SERVER_URL=<hosting URL>
Alternatively, you can set the corresponding environment variables as defined in `app.js`.

## Run

## Webhook

All webhook code is in `app.js`. It is routed to `/webhook`. This project handles callbacks for authentication, messages, delivery confirmation and postbacks. More details are available at the [reference docs](https://developers.facebook.com/docs/messenger-platform/webhook-reference).

## License

See the LICENSE file in the root directory of this source tree. Feel free to use and modify the code.

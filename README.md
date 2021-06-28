# Challenges microsite

This is a one page application that shows the challenges for a hackathon event using the remote API of [dribdat](https://github.com/dribdat/dribat).

## Usage

Deploy this application with any service that supports Vue.js.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fnext.js%2Ftree%2Fcanary%2Fexamples%2Fhello-world)

Configure with the following environment variables:

- `VUE_APP_DRIBDAT_EVENT` - id of your event (e.g. 1)
- `VUE_APP_DRIBDAT_URL` - link to the home page of your dribdat server, including `https://` and no trailing slash
- `VUE_APP_GOOGLE_FORM_URL` (optional) - if you are using a Google Form to collect votes or feedback, include it here

## Development

To run locally, install Node.js and Yarn, then to start a development server:

```
yarn serve
```

Created using Vue.js and CodeSandbox.

![](https://upload.wikimedia.org/wikipedia/commons/9/9a/Zh_Basketball_backboard_and_basket_bitmap_1940.svg)

_Players typically aim for the box in the backboard when making a shot in basketball._

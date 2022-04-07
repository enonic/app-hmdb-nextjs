# Back-end for "nextjs-enonic-demo"

This is used for the TLDR; version of the Next.xp tutorial https://developer.enonic.com/docs/next.xp

As this app only represents the back-end, you will also need to run the Next.js project "nextjs-enonic-demo" to get the front-end.
Next.js must be configured to access this application, in order to have a back-end.
This app must then be configured with the location of the Next.js preview server, for preview and live page editing to work in Content studio.

## Usage

* Sign up to Enonic and create a solution based on the Next.js demo template
* Sign up and create a project in Vercel based on "nextjs-enonic-demo"
* Configure Vercel app to access the "Drafts API" - Remember to append /_graphql to the URL
* Configure preview in Enonic by configuring the URL to the Vercel app
* Finally, create another Vercel project from the same project and branch, but this time reference the "Live API" instead.

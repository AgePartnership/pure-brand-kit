# Pure Brand Kit

This package contains Sass allowing for consistent distribution of Pure Retirement branding, such as hex colour values.

This package is distributed through npm.

## Install using npm

Before you can use npm, you need to [install Node](https://nodejs.org/en/download/).

Once you've done that, in the root of your project directory, run:

<pre>
    <code>
        npm install pure-brand-kit
    </code>
</pre>

This will install the starter pack in the 'node_modules' directory located in the root of your project.

## Importing the Sass into your project

### Include all the things!

If you want to include everything in this repo, there's a handy single file you need to import into your main project Sass file:

`@import 'node_modules/pure-brand-kit/all';`

### Pick 'n' Mix

You can include files individually allowing you to customise what is available to your project. For example, to include just the colour variables, you would drop the following into your main project Sass file:

`@import 'node_modules/pure-brand-kit/config.colour';`

That's pretty much it. Now, go make a brew.

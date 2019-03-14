# NodeJS Template

This template assumes you're using nvs, but you could equally be using nvm.

# Getting going

This template uses node 8.10 (via `.node-version`) as that's what I usually use in AWS Lambda. I also grab the latest version of npm.

    $ nvs use
    $ npm install -g npm@latest
    $ npm install

# Update all dependencies

    $ npm run-script update-dependencies

# Run tests and check coverage

    $ npm test

You'll get a coverage report logged to the console and you can also open `coverage/index.html` for detailed test coverage.

# Running

    $ npm start

...although this doesn't really do anything in this template. You need to fill that in.

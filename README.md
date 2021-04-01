# npm-link
Understanding npm link

## About
https://docs.npmjs.com/cli/v7/commands/npm-link

## Steps
cd ~/projects/node-redis    # go into the package directory
npm link                    # creates global link
cd ~/projects/node-bloggy   # go into some other package directory.
npm link redis              # link-install the package
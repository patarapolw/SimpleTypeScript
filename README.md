# SimpleTypeScript

My approach to TypeScript from knowing client-side JavaScript.

For Part One, of Node.js, see <https://github.com/patarapolw/SimpleNodeJS>

## Additional installations

```commandline
# Locally in your project
npm install -D ts-node
npm install -D typescript

# Or globally (not recommended)
npm install -g ts-node
npm install -g typescript
```

Now, it also works for TypeScript!

## Running scripts

```commandline
# Execute a script as `node` + `tsc`.
ts-node script.ts

# Starts a TypeScript REPL.
ts-node

# Execute code with TypeScript.
ts-node -e 'console.log("Hello, world!")'

# Execute, and print, code with TypeScript.
ts-node -p '"Hello, world!"'

# Pipe scripts to execute with TypeScript.
echo "console.log('Hello, world!')" | ts-node
```

## Converting scripts to JavaScript

```commandline
tsc script.ts
```

## TypeScript REPL

You will also need to install [TypeScript REPL](https://github.com/HerringtonDarkholme/typescript-repl)

```commandline
npm install -g tsun
tsun
```

## A new environment: Yarn

Learning from <https://exercism.io/my/tracks>. It seems to use Yarn for TypeScript, but NPM for JavasScript...

You can get Yarn here <https://yarnpkg.com/en/>.

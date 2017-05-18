# prettier-eslint-cli-repro

If you have an issue with `prettier-eslint-cli` then you can use this repository to reproduce that issue.

## Setup

First fork the repository and clone your fork. Then, in your cloned directory:

```
npm install
npm test
```

The test script should work and will just log out the resulting formatted output. Now update
the project as little as possible to reproduce the issue.

You'll notice that there are a few scripts you can use to try things out. There's also an
ESLint config that you can use. Give all of those things a try.

Good luck! 💪

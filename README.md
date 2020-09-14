# ultimate-node-env
using docker dev environment and some other tricks we can create a reproducible dev environment with all the tools for a modern node.js service

- [LTS NodeJS (12)](https://nodejs.org/)
  - A JavaScript runtime built on Chrome's V8 JavaScript engine.
- [Typescript](https://www.typescriptlang.org/)
  - Typed JavaScript at Any Scale.
  - [source-map-support](https://www.npmjs.com/package/source-map-support)
    - Provides source map support for stack traces
- [ts-node](https://github.com/TypeStrong/ts-node) with [nodemon](https://nodemon.io/)
  - TypeScript execution and REPL for node.js, with source map support.
  - Monitor for any changes in your source and automatically restart
- [Jest](https://jestjs.io/)
  - A delightful JavaScript Testing Framework with a focus on simplicity.
- [ESLint](https://eslint.org/)
  - Find and fix problems in your Javascript (or Typescript) code
- [Yarn](https://yarnpkg.com/) or [NPM](http://npmjs.com/)

- Intergrated Terminal
  - [ZSH](https://www.zsh.org/)
    - A shell designed for interactive use
  - [oh-my-zsh](https://ohmyz.sh/)
    - A delightful, open source, community-driven framework for managing your Zsh configuration.
  - [Powerline10k](https://github.com/romkatv/powerlevel10k)
    - A theme for Zsh. It emphasizes speed, flexibility and out-of-the-box experience.
      <details>
        <summary>Install MesloLGS NF font if you havent already</summary>

        - [MesloLGS NF Regular.ttf](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Regular.ttf)
        - [MesloLGS NF Bold.ttf](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold.ttf)
        - [MesloLGS NF Italic.ttf](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Italic.ttf)
        - [MesloLGS NF Bold Italic.ttf](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold%20Italic.ttf)
      </details>
- [Docker](https://www.docker.com/)
  - Helps developers and development teams build and ship apps.
  - [Dev environment](https://code.visualstudio.com/docs/remote/containers)
  - build container
- [Github actions](https://github.com/features/actions)
  - Makes it easy to automate all your software workflows
  - run tests
  - publish container

## Nomad Code Check Example

This is an example app repository for showcasing how nomad-codecheck is used. For nomad-codecheck, visit it's repository: https://ship.nomadinteractive.co/nomad-interactive/nomad-codecheck

To install

```npm install```

To Run

```npm run check```

To test local nomad-codecheck working copy as dependency, update package.json with ```file:../nomad-codecheck``` dependency url instead of ```git+ssh://git@ship.nomadinteractive.co:nomad-interactive/nomad-codecheck.git``` and npm install:

```"nomad-codecheck": "file:../nomad-codecheck"```
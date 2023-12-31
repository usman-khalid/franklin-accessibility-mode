# Franklin Accessibility Mode Sidekick Plugin

![Alt Text](docs/a11y-mode-demo.gif)

A sidekick extension that integrates with [Sa11y](https://sa11y.netlify.app/) to check the page from an accessibility perspective, and provides suggestions on things that can be improved. 

### Custom Checks
Custom checks can added based on the project and/or block requirements. These can be useful to promote correct usage of blocks or adhere to style guidelines.

This repo contains [an example](https://github.com/usman-khalid/franklin-accessibility-mode/blob/main/tools/sidekick/plugins/accessibility-mode/custom-checks/custom-checks.js#L12) of a custom check which reports if there is more than one _Alert_ block on a page.


## Environments
- Preview: https://main--franklin-accessibility-mode--usman-khalid.hlx.page/
- Live: https://main--franklin-accessibility-mode--usman-khalid.hlx.live/

## Installation

```sh
npm i
```

## Linting

```sh
npm run lint
```

## Local development

1. Start AEM Proxy: `aem up` (opens your browser at `http://localhost:3000`)
1. Open the `franklin-accessibility-mode` directory in your favorite IDE and start coding :)

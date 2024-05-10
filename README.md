# US Bank Edge Delivery Document-Based Authoring Demo...
Mockup of US Bank landing page and article page to showcase how efficient development in Edge Delivery Services is.

Landing Page:
https://www.usbank.com/financialiq/manage-your-household.html
Article:
https://www.usbank.com/financialiq/manage-your-household/establish-credit/how-to-maximize-your-credit-card-rewards.html 

## Environments
- Preview: https://main--usbank--AdobeDevXSC.hlx.page/
- Live: https://main--usbank--AdobeDevXSC.hlx.live/

## Installation

```sh
npm i
```

## Linting

```sh
npm run lint
```

## Local development

1. Create a new repository based on the `aem-boilerplate` template and add a mountpoint in the `fstab.yaml`
1. Add the [AEM Code Sync GitHub App](https://github.com/apps/aem-code-sync) to the repository
1. Install the [AEM CLI](https://github.com/adobe/helix-cli): `npm install -g @adobe/aem-cli`
1. Start AEM Proxy: `aem up` (opens your browser at `http://localhost:3000`)
1. Open the `usbank` directory in your favorite IDE and start coding :)

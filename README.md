![Node.js CI](https://github.com/nmrs-nigeria/openmrs-esm-nmrs/workflows/Node.js%20CI/badge.svg)

# NMRS ESM

Nigeria Medical Records System based of OpenMRS 3.x

## Running this code

```sh
yarn  # to install dependencies
yarn start  # to run the dev server
```

Once it is running, a browser window
should open with the OpenMRS 3 application. Log in and then navigate to
`/openmrs/spa/hello`.

## Adapting the code

1. Start by finding and replacing all instances of "template" with the name
  of your microfrontend.
1. Update `index.ts` as appropriate, at least changing the feature name and
  the page name and route.
1. Rename the `hello.*` family of files to have the name of your first page.
1. Delete the contents of the objects in `config-schema`. Start filling them
  back in once you have a clear idea what will need to be configured.
1. Delete the `greeter` and `patient-getter` directories, and the contents of
  `hello.tsx`.
1. Delete the contents of `translations/en.json`.
1. Open up `.github/workflows` and adapt it to your needs. If you're writing
  a microfrontend that will be managed by the community, you might be able to
  just replace all instances of `template` with your microfrontend's name.
  However, if you're writing a microfrontend for a specific organization or
  implementation, you will probably need to configure GitHub Actions differently.
1. Delete the contents of this README and write a short explanation of what
  you intend to build. Links to planning or design documents can be very helpful.



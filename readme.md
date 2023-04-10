# Architect 10.12 + Rust

## Check it out

Compiled handlers in Architect! Let's go:

1. `npm i`
2. Make sure you have Rust + [cargo-lambda](https://www.cargo-lambda.info/guide/installation.html) installed
3. Run `npx arc create` to create your root Rust handler
4. Run `npm run start` and visit `http://localhost:3333` to see it running in Sandbox
5. Run `npx arc deploy` (and possibly edit `app.arc` with your profile + region) to ship it to AWS!

# frozenjsono

## Issue reproduction

In the `Component.ts` file, a model is initialized with a simple array.

In the `Main.view.xml` a simple `sap.m.List` is bound to this array.

Running this repo with `npm i`/`npm start` demonstrates the working binding.

Switch between model with frozen prop and model with nonfrozen prop by (un)commenting the model init step in the `Component.ts`

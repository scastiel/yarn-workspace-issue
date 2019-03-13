To reproduce the issue:

- `cd my-package`
- `yarn add lower-case`
- Check that the folder _node_modules/lower-case_ exists
- `yarn add lower-case`
- Observe that it doesn’t exist anymore 🙁

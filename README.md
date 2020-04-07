# npm workspaces progress tracker

Setting up a bunch of repos using Lerna or Yarn/Pnpm workspaces and trying out arborist on it.

### Status indication
- :white_check_mark: Works as expected
- :ballot_box_with_check: Works partially
- :x: Not working / blocked

### Current

|   Name                |   type        |   install                     |   test                |   tweaks  |
|-----------------------|---------------|-------------------------------|-----------------------|-----------|
| **Inquirer.js**       | Lerna + Yarn  | :white_check_mark:            | :white_check_mark:        |           |
| **babel**             | Lerna + Yarn  | :ballot_box_with_check:       | :x:                       | [changes](https://github.com/ruyadorno/babel/commit/27d036f8414328d9bc8a7f6d295463f7bad96b34)   |
| **create-react-app**  | Lerna + Yarn  | :white_check_mark:            | :ballot_box_with_check:   | [changes](https://github.com/ruyadorno/create-react-app/commit/ce58c221b668cb036a515a1dd6da62f21cb829e7)   |
| **reakit**            | Lerna + Yarn  | :ballot_box_with_check:       | :white_check_mark:        | [changes](https://github.com/ruyadorno/reakit/commit/3257e49f1a83b89d87f0176a9ebabd19d7bd529a)   |

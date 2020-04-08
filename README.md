# npm workspaces progress tracker

Setting up a bunch of repos using Lerna or Yarn/Pnpm workspaces and trying out arborist on it.

### Status indication
- :white_check_mark: Works as expected
- :ballot_box_with_check: Works partially
- :x: Not working / blocked

### Current

|   Name                |   type        |   install                     |   test                |   tweaks  |
|-----------------------|---------------|-------------------------------|-----------------------|-----------|
| **babel**             | Lerna + Yarn  | :ballot_box_with_check:       | :x:                       | [changes](https://github.com/ruyadorno/babel/commit/27d036f8414328d9bc8a7f6d295463f7bad96b34)   |
| **create-react-app**  | Lerna + Yarn  | :white_check_mark:            | :ballot_box_with_check:   | [changes](https://github.com/ruyadorno/create-react-app/commit/ce58c221b668cb036a515a1dd6da62f21cb829e7)   |
| **enzyme**            | Lerna         | :x:                           | :x:                       | [notes](https://github.com/ruyadorno/enzyme/commit/7c413a01133f228fa8fe17338ea2674c90934410)   |
| **Inquirer.js**       | Lerna + Yarn  | :white_check_mark:            | :white_check_mark:        |           |
| **reakit**            | Lerna + Yarn  | :ballot_box_with_check:       | :white_check_mark:        | [changes](https://github.com/facebook/create-react-app/commit/ce58c221b668cb036a515a1dd6da62f21cb829e7)   |

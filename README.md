# npm workspaces progress tracker

Setting up a bunch of repos using Lerna or Yarn/Pnpm workspaces and trying out arborist on it.

### Status indication
- :white_check_mark: Works as expected
- :ballot_box_with_check: Works partially
- :x: Not working / blocked

### Current

|   Name                |   type                        |   install                     | install --legacy              |   test                    |   tweaks  |
|-----------------------|-------------------------------|-------------------------------|-------------------------------|---------------------------|-----------|
| **airbnb/javascript** | Custom scripts-based setup    | :white_check_mark:            |                               | :white_check_mark:        | [changes](https://github.com/ruyadorno/javascript/commit/712b597b81cdd5b25e8557bba20ef850996378a5)     |
| **babel**             | Lerna + Yarn                  | :white_check_mark:            |                               | :x:                       | [changes](https://github.com/ruyadorno/babel/commit/53aa8d315cc7bdf284d656fd206db3f7c0bc4beb)     |
| **create-react-app**  | Lerna + Yarn --use-workspaces | :white_check_mark:            |                               | :ballot_box_with_check:   | [changes](https://github.com/ruyadorno/create-react-app/commit/2cfcaf1b0cdc6a1119abce18bcbe7812e7d35005)   |
| **enzyme**            | Lerna                         | :x:                           | :white_check_mark:            | :white_check_mark:        | [notes](https://github.com/ruyadorno/enzyme/commit/7b5a0696717d511957a0d32fc83abdbc636642b1)      |
| **Inquirer.js**       | Lerna + Yarn --use-workspaces | :white_check_mark:            |                               | :white_check_mark:        |           |
| **opencensus-node**   | Lerna                         | :white_check_mark:            |                               | :white_check_mark:        | [changes](https://github.com/ruyadorno/opencensus-node/commit/bb237277657010e969f35a7f29108fa32162eedf)  |
| **reakit**            | Lerna + Yarn --use-workspaces | :x:                           | :white_check_mark:            | :white_check_mark:        | [changes](https://github.com/ruyadorno/reakit/commit/cbc82a44210f22e3fbb2f00c697d9c43cdc9773b)    |
| **webpack-cli**       | Lerna + Yarn --use-workspaces | :white_check_mark:            |                               | :ballot_box_with_check:   | [changes](https://github.com/ruyadorno/webpack-cli/commit/140bd24f46673dad9e222652ad61499ed616f003)   |

## TODO

- https://github.com/open-telemetry/opentelemetry-js
- https://github.com/istanbuljs/istanbuljs
- https://github.com/ibm/report-toolkit
- https://github.com/lerna/lerna

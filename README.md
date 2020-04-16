# npm workspaces progress tracker

Setting up a bunch of repos using Lerna or Yarn/Pnpm workspaces and trying out arborist on it.

### Status indication
- :white_check_mark: Works as expected
- :ballot_box_with_check: Works partially
- :x: Not working / blocked

### Current

|   Name                |   type                        |   install                     | install --legacy              |   test                    |   tweaks  |
|-----------------------|-------------------------------|-------------------------------|-------------------------------|---------------------------|-----------|
| **babel**             | Lerna + Yarn                  | :white_check_mark:            |                               | :x:                       | [changes](https://github.com/ruyadorno/babel/commit/53aa8d315cc7bdf284d656fd206db3f7c0bc4beb)   |
| **create-react-app**  | Lerna + Yarn --use-workspaces | :white_check_mark:            |                               | :ballot_box_with_check:   | [changes](https://github.com/ruyadorno/create-react-app/commit/2cfcaf1b0cdc6a1119abce18bcbe7812e7d35005)   |
| **enzyme**            | Lerna                         | :x:                           | :white_check_mark:            | :white_check_mark:        | [notes](https://github.com/ruyadorno/enzyme/commit/7b5a0696717d511957a0d32fc83abdbc636642b1)   |
| **Inquirer.js**       | Lerna + Yarn                  | :white_check_mark:            |                               | :white_check_mark:        |           |
| **opencensus-node**   | Lerna                         | :x:                           |                               | :x:                       | [notes](https://github.com/ruyadorno/opencensus-node/commit/79125038e049ea5fe02d36f1280f3cb6f13aca3c)  |
| **reakit**            | Lerna + Yarn                  | :ballot_box_with_check:       |                               | :white_check_mark:        | [changes](https://github.com/ruyadorno/reakit/commit/3257e49f1a83b89d87f0176a9ebabd19d7bd529a)   |

## TODO

- https://github.com/airbnb/javascript
- https://github.com/webpack/webpack-cli
- https://github.com/open-telemetry/opentelemetry-js

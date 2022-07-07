# yarn-circular-root

This repository has a single dependency: `@webassemblyjs/helper-code-frame`.

That depends on different packages and one of those depends on
`@webassemblyjs/helper-code-frame`, which creates a circular dependency and
doesn't give us a clear "root".


Here is the `yarn.lock` file visualized with [this tool](https://observablehq.com/@mbostock/yarn-lock-visualizer):

![screenshot_2022-07-07_13 40 19@2x](https://user-images.githubusercontent.com/1185253/177765096-e0933972-55ef-48d1-95c5-0c00ec2551b7.png)

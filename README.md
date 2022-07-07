# yarn-circular-root

This repository has a single dependency: `@webassemblyjs/helper-code-frame`.

That depends on different packages and one of those depends on
`@webassemblyjs/helper-code-frame`, which creates a circular dependency and
doesn't give us a clear "root".

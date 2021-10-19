# Description
Utility package for common functions within Tracer's Perpetual Pools ecosystem. Useful for clients who wish to interact with Tracer's Perpetual Pools Protocol.
# Usage
```
npm install @tracer-protocol/tracer-pools-utils
```

To use any of the packages, simply import the function from the package you wish to use, directly from the tracer-utils library.
```
import { calcLossMultiplier } from "@tracer-protocol/tracer-pools-utils`
calcLossMultiplier(...)
```
# Development
## Contributing
When creating a new package follow the structure of

```
-- src
    -- NewUtilsSpace
        -- index.ts // export or main
        -- source.ts
        -- extra source files or folders
```
# Switch - A functional EVM programming language
Switch is a (work in progress) functional EVM programming language built off of the functional programming principles of purity and statelessness.

In traditional Solidity smart contracts, statefulness is offered through state variables that are stored onchain thanks to SSTORE. With Switch, this design is completely rejected and instead Switch will only allow for you to make use of MSTORE (memory) and TSTORE (transient) for storage, eliminating any state that remains at the end of the call. With this design, the only means of being able to use persistent storage is through.

## Why?
Not even I know
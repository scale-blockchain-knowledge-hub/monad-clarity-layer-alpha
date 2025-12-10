# Migration Checklist (EVM → Monad)

This checklist ensures your contract is Monad-ready.

### Compatibility
- [ ] Contract is written in Solidity  
- [ ] No chain-specific precompiles  
- [ ] External dependencies easily portable  

### Architecture
- [ ] Users operate on mostly independent state paths  
- [ ] No unavoidable shared bottleneck  
- [ ] Conflicts are minimal or infrequent  

### Testing
- [ ] All tests pass with Hardhat / Foundry  
- [ ] Basic load testing is done  

### Documentation
- [ ] Simple explanation of why your app benefits from Monad  
- [ ] Notes on expected parallelism gains  

### Next Step
Explore: *Micro Project Starters*

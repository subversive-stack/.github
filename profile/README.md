
## Subversive: Stack

The opinionated blockchain stack not pumping any token/coin.

### Opinions

1. Blockchain end users are front and centre.  The following are _not_ those end users: block validators/miners, validator/miner stakers, and the like.
2. Permissioned blockchains can be a way to guarantee user data is secure. Hence, permissioned blockchains are, **currently** the only intended use case.
3. Permissionless configurations, and the artifacts supporting them, will only be added when there is public proof, and a working demonstration, the proposed configuration protects end user data when faced with the shutdown-breakdown vulnerabilities.

#### Shutdown-Breakdown Vulnerabilities

The following should by considered a work-in-progress. 
If you would like to contribute to improving the security of end user data, please help refine these definitions.
To do so, you can open an issue in the [Gateway repository](https://github.com/subversive-stack/gateway).

A shutdown is when all miners, validators, producers, etc. cease activity. 
All code and resources that were available to the public, remain available to the public. Private/secured resources are assumed to be destroyed.
A blockchain is vulnerable if user data can be altered by one or more actors after the shutdown.

A breakdown is when the token price declines to "near zero".
All code and resources that were available to the public, remain available to the public. Private/secured resources are assumed to be destroyed.
A blockchain is vulnerable if user data can be altered by one or more actors after the token price declines to "near zero" or lower.
A critical issue for proving invulnerability to breakdown is the definition of "near zero", or the breakdown boundary (stopping time).
The amount of resources required by a 51% attack, etc. at this boundary/stopping time is immaterial.
User data must be secure at all points beyond such a breakdown boundary.

If you have a proof of invulnerability, a working demonstration, and you would like to make the configuration or supporting artifacts available to Subversive developers.
Please open an issue in the [Gateway repository](https://github.com/subversive-stack/gateway), linking to the proof and detailing how to reproduce your demonstration results.

### Resources

Please use the "Issues" for each repository to report reproducible behavior. 
Please provide the code, or a repository, for a minimal reproducible example.

Until the [Subversive Stack](https://github.com/subversive-stack) deviates from the upstream project, the upstream project resources are the best source of information.
Consequently, currently there is no forum dedicated to blockchains building on the [Subversive Stack](https://github.com/subversive-stack).
Your best channel for help specific to Subversive is StackOverflow. However I don't promise I'll check there.

### Contribution guidelines

If you want to influence the direction of Subversive, please do so via the [Gateway repository](https://github.com/subversive-stack/gateway). 
Please bear in mind Subversive is a blockchain stack that is not pumping any token/coin, and never will.  
There are no full time anyone available.
This is an old-school open source effort aimed at putting the blockchain end user front and centre. 
So it has the weaknesses and limitations of that approach to open source. 
It also has the strengths of that approach.  
These strengths and weaknesses have been described elsewhere, so there is no additional value in rehearsing that detail here.


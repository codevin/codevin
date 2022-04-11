I am @codevin, interested in better digital life for humanity. 

Some of the things I am interested in, and request your feedback.

## Feature driven development environment 

Primarily, we must be able to answer why a particular line of code exists. That can only be done by mapping it to the feature (or any other requirement) that drove that change. 

At best, the developer will implement the requirement and add git commit logs to reflect the implementation - perhaps with some idea of what is (and what is not) implemented. 

We need a totally different approach, which I have documented in the pdf: [FeatureManagementUsingMarkups.pdf](https://github.com/codevin/codevin/files/8439808/FeatureManagementUsingMarkups.pdf)

## Verified Source Computing

Trust is biggest problem in our society today. One of the element of trust is to trust the computing ecosystem. If I can be sure that the remove server is running a verified code (either opensource or audited publically), that is a better way of trust than blind trust in big brands.

Essentially this means that the deployment of verified code has to be trustworthy. The deployment process should happen using established paths where each transfer is verifiable on a blockchain. The cpu nodes are configured to only receive code from blockchain and not by any direct means.  This approach is already taken by modern routers. The code can be auditably deployed.

Such a node can't have usual login based OS. It would have to minimize the number of software components. Most likely, this new ecosystem will be pure hardware nodes to run bare programs, and not operating systems. Unikernel ecosystem is very relevant: https://unzip.dev/0x005-unikernels/

There are many implications that will result:
* The nodes are now quite passive, so brand of datacenter shouldn't matter. Instead of capital intensive clouds by biggies, we can have thousands of smaller datacenters. The reliability should come from distributed system, and not by centralization. 
* Much higher security since hackers can't login and change the system.
* A mechanism for governments to enact laws that will ensure that the public infrastrucure will run verified code. So the very policies by companies will then be driven by public. 

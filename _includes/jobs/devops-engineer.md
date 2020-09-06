
We are looking for a DevOps engineer to help us implement and deploy [PolkaBTC](https://medium.com/interlay/bitcoin-on-polkadot-proof-of-concept-for-trustless-bridge-shipped-6fb8e549bef0). 

The PolkaBTC bridge connects Bitcoin with the Polkadot ecosystem in a trustless and decentralized manner and will serve as the main gateway for bringing BTC liquidity into Polkadot’s DeFi ecosystem. The design is based on [top tier academic research](https://eprint.iacr.org/2018/643) and the implementation follows our [detailed specification](https://interlay.gitlab.io/polkabtc-spec/index.html). The project is funded by a [Web3 Foundation grant](https://web3.foundation/).

Your task will be to improve our automated testing and deployment of the PolkaBTC bridge via our CI/CD pipelines. Additionally, you will develop a setup to automatically deploy and update our alpha and beta testnets that are scheduled to be released in November/December this year. This includes setting up logging and monitoring strategies across our cloud-hosted tech stack.

Our PolkaBTC bridge is implemented in Rust. Clients that interact with the bridge are implemented in Rust (CLI-based) and TypeScript/React (web-based). Additionally, we interface directly with Bitcoin’s core software written in C++. Our current CI setup is based on GitLab’s CI features. We are hosting our clients on Kubernetes/DigitalOcean. We currently do not have a common logging and monitoring solution in place and it will be your task to suggest a suitable solution and implement it. All our infrastructure should be described by code and any task should be automated using scripts. Experience with DevOps in blockchain-based environments and/or distributed systems is strongly encouraged, as you will need a basic understanding of the underlying technology to ensure the security of the system in a decentralized and open environment.

*Full-time and preferably based in the UK (remote)*


**What you will do**

-Automation of testnet deployments and upgrades for our PolkaBTC bridge
- Integration of test and deployment strategies for our various software products (PolkaBTC bridge, clients, UI …)
- Collaboration with our software engineering team to resolve issues before/during/after deployment
- Implementation and testing of a logging and monitoring solution for our various software products
- Creating metrics and graphs to display on a dashboard to monitor the status and health of our services
- Maintenance of our Kubernetes/DigitalOcean infrastructure

**What you bring**

- Expertise in Linux administration and very comfortable with a command-line interface
- Expertise in at least one programming language such as JS/TS/Python/Rust/Go/…
- Experience with Kubernetes/Docker
- Passion for automation of the entire DevOps toolchain
- Prior experience with CI/CD and monitoring of distributed applications
- Prior experience with open-source projects
- Desire to learn and work with bleeding-edge technology
- BSc/MSc degree in Computer Science or a related field, or equivalent experience
- Proficiency in English

**“Nice to have”**

- Experience with Rust/TypeScript projects
- Experience with blockchain-based projects

**Benefits and Perks**
* Stock options
* Remote working
* Flexible working hours
* Yearly retreat
* Open-source software
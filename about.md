#### About Bitcoin:
- Bitcoin is sound money because of it's deterministic issuance and fixed supply without any single point of failure(third-parties)
- Other cryptocurrencies are often centralized and hardly those nodes run in a p2p manner, the harder better money always drives out other easier monies
- It can be easily taken in your own posession using self-custody i.e. securely saving the private keys
- The private keys can be always kept offline and transactions be signed without connecting to the internet (psbt)
- Transactions must be broadcasted using a Bitcoin node, since transactions only contain signature(not private keys) it is possible to use wallets that use third-party nodes to broadcast txs but not recommended since it brings third-parties into the equation
- Running Bitcoin nodes has some challenges: it requires compute resources, disk space and the initial download of entire history takes long time
- Additionally, Bitcoin has probabilistic settlement guarantee(more blocks past a tx, make it more immutable) so this does take sometime(6 confirmations/6 blocks past a tx make it near impossible for a tx to get reversed).


#### Things that are important for Bitcoin to succeed:
- Education: people need to understand how to store(securing private keys) and transact Bitcoin(using nodes/wallets) in addition to learning about it's importance from economic stand point
- Technical improvements: Bitcoin core is an open-source project that anyone can contribute to if they've improvements(implementation or proposals)


#### What are some worthy technical problems to solve:
- Making it easy for people to run Bitcoin nodes 
- Making the UX of custody of Bitcoin easier and secure (ex. techniques like multi-sig, psbt etc.)
- Enabling merchants to easily start accepting payments in the most secure and censorship resistant way
- Making it more secure and private
- Making it harder to attack from network security perspective
- Advancement of off-chain protocols like lightning network to enable instant payments

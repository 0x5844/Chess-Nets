# Chess-Nets ♟️
"Chess Nets" is a collection of AI / Machine Learning experimental research on Chess and Neural Networks. It consists of notebooks, networks, weights, results, methodologies, data and code conducted by this research.

Powered by [Paperspace](https://www.paperspace.com/), both bots are running on 1 x A100 80GB GPU, 12 vCPU, 90 GB RAM.

## Bots

### cheeseNet 🧀
[cheeseNet 🧀](https://www.lichess.org/@/cheeseNet) is  an avant-garde approach powered by [Lc0](https://lczero.org/) engine. This setup has a *Hybrid Convolutional Neural Network (HCNN)* that learns gradually by utilizing *Reinforced Self-Training (ReST)* and *human-feedback*. This setup runs with the speed of *~1M nps*. Plays Bullet, Blitz, and Rapid in Standard and Chess960 variants (rated/casual) [min:0 , max: 15M, inc:1, 2, 3] up to **3** concurrent games.

### buffFishNet 🐟
[buffFishNet 🐟](https://www.lichess.org/@/buffFishNet) yet another avant-garde approach powered by [Stockfish](https://stockfishchess.org/) engine. This setup has a *Hybrid Efficiently Updatable Neural Network (HNNUE)* that learns gradually by utilizing *Reinforced Self-Training (ReST)*. This setup runs with the speed of *~5M nps*. Plays Bullet, Blitz, and Rapid in Standard, Chess960, Atomic, Antichess, and Crazyhouse variants (rated/casual) [min:0 , max: 15M, inc:1, 2, 3] up to **3** concurrent games.

## Methodology

Networks crafting methodology is inspired by [Reinforced Self-Training (ReST) for Language Modeling paper](https://arxiv.org/abs/2308.08998).

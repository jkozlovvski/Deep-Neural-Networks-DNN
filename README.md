# Deep-Neural-Networks-DNN

| Project | Description |
| ----------- | ----------- |
| Backpropagation with checkpointing | Backpropagation algorithm with a little tweak - not saving every node in forward pass. Instead computing some nodes for the second time when backpropagating. Such variation of backpropagation is used with big neural nets when space complexity is limitation. Detailed explanation can be found here: https://arxiv.org/abs/1604.06174. |
| FCOS | Implementation of https://arxiv.org/abs/1904.01355 for toy example of MNIST numbers put in the random places on canvas. |
| Decoder only transformer | Implementation of decoder-only transfomer model based on sequences generated in a random manner detailed by a Markov chain. Based on https://arxiv.org/abs/1706.03762.|
| Almost rainbow dqn | Implementation of multiple variations of dqn algorithms (ddqn, n-step dqn, duelling dqn, noisy dqn, prioritized buffer dqn) and combining all of these to create (almost) rainbow buffer. Expreminets are done on Lunar Lander environemnt from https://gymnasium.farama.org.

Feel free to contact me if you see come bugs or you're curious about the code/idea behind it.




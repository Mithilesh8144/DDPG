# HalfCheetahBulletEnv-v0

The repository involves experiments conducted on the HalfCheetahBulletenv-v0 from pybullet_envs

The results are documented in the notebooks.

The final experiment conducted which yielded optimal results involves the use of hyperparameters such as:
- std_dev = 0.15

- critic_lr = 0.0003

- actor_lr = 0.0003

- total_episodes = 500

- gamma = 0.99

- tau = 0.05

- buffer size - (100000, 128)
The results are documented in the Final_experiment notebook.

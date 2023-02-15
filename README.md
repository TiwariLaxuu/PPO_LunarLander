# PPO_LunarLander
In this tutorial, we’re going to train our agent, a Lunar Lander, to land correctly on the moon. To do that, the agent needs tolearn to adapt its speed and position(horizontal, vertical, and angular) to land correctly.

We see with Observation Space Shape (8,) that the observation is a vector of size 8, where each value contains different information about the lander:

Horizontal pad coordinate (x)
Vertical pad coordinate (y)
Horizontal speed (x)
Vertical speed (y)
Angle
Angular speed

If the left leg has contact point touched the land
If the right leg has contact point touched the land
1M training and its last training values 
| rollout/                |             |
|    ep_len_mean          | 338         |
|    ep_rew_mean          | 254         |
| time/                   |             |
|    fps                  | 869         |
|    iterations           | 62          |
|    time_elapsed         | 1167        |
|    total_timesteps      | 1015808     |
| train/                  |             |
|    approx_kl            | 0.005054847 |
|    clip_fraction        | 0.0444      |
|    clip_range           | 0.2         |
|    entropy_loss         | -0.792      |
|    explained_variance   | 0.922       |
|    learning_rate        | 0.0003      |
|    loss                 | 34.7        |
|    n_updates            | 244         |
|    policy_gradient_loss | -9.89e-05   |
|    value_loss           | 124         |

Rollout/  | \|
------------- | -------------
ep_len_mean  | 338
ep_rew_mean  | 254 

# Reward
Mean Reward =256.25 +/- 20.06130326723367

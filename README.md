## Risk Averse Reinforcement Learning for Mixed Multi-Agent Environments
#### Public repo containing supplementary material for the work submitted to IJCAI-19
#

![Framework](https://github.com/constraint-solvers/riskaverse-marl/blob/master/method.png)

*Figure 1 : Overview of our risk constrained multi-agent de-centralized actor, centralized critic system.*   

---
    
![Framework](https://github.com/constraint-solvers/riskaverse-marl/blob/master/envs.png)

*Figure 2 :  Illustration of multi-agent environments for the mixed cooperative-competitive tasks we consider namely a)KeepAway 2)Physical Deception 3)Predator Prey.*

---
    
![Framework](https://github.com/constraint-solvers/riskaverse-marl/blob/master/scenarios.png)

*Figure 3 : ###Sequences of events for the two settings 1)Unconstrained 2)Risk Constrained for the keep away task for 4 continuous time steps.###Time steps t=0-2 are common to both the settings which shows the observation by agents and movement towards landmark. The good agents movements are rewarded based on its close distance to the target Landmark 1. The adversary learns the target Landmark based on the movements of agents and is rewarded based on its minimal distance to the target landmark 1 and its distance to the other agents. At time step t=3, the first row shows the high variance in policy of the agent near the landmark. This is understandable by the giant leap by the agent to move away from the adversary towards the other landmark to fool the adversary. But this is a risky move, since it might take longer sequence of bad rewards before reaching the target. The second row shows the constrained setting wherein the agent near the landmark is restricted to shorter movements leading to smaller variance even when the adversary is near by thereby, reduces the risk of bad rewards.*

---

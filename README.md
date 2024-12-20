#### **Overview**  
This project implements the **Cart Pole Balancing Problem** using the **REINFORCE Policy Gradient Algorithm**. The goal is to balance a pole on a cart through reinforcement learning, comparing standard REINFORCE and REINFORCE with a baseline.

---

#### **Files**  
- **`Cart_Pole_REINFORCE.ipynb`**: Jupyter Notebook containing:  
  - Gradient derivation in LaTeX.  
  - Implementation of REINFORCE and REINFORCE with baseline.  
  - Training and testing performance comparison.

---

#### **Key Features**  
1. Linear policy with softmax: \( \pi(a|s, \theta) = \text{softmax}(\theta \cdot s) \).  
2. Baseline: \( \hat{v}(s, w) = \mathbf{w}^\top \mathbf{s} \) to reduce gradient variance.  
3. Performance plots for training rewards and algorithm comparison.

---

#### **How to Run**  
1. Install dependencies: NumPy, Matplotlib, Jupyter, OpenAI Gym.  
2. Run the notebook:  
   ```bash
   jupyter notebook Cart_Pole_REINFORCE.ipynb
   ```

---

#### **Results**  
- **Training**: REINFORCE with baseline converges faster and is more stable.  
- **Testing**: Evaluated over 5 episodes, demonstrating effective learning.  

---

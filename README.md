# 📄 Paper Reading

### Paper 1
**Title:** Practical Recommendations for Gradient-Based Training of Deep Architectures      
**Authors:** ```Yoshua Bengio & Xavier Glorot```               
**Year:** 2012  
**Link:** https://arxiv.org/abs/1206.5533  

**Notes:**  
- This paper presents many **practical recommendations** for training deep neural networks, including initialization, optimization, activation functions, and regularization strategies.

- Also discusses and recommends **Xavier (Glorot) Initialization**, which is well-suited for **sigmoid and tanh** activation functions while training DNNs.    
- It is a practical weight initialization strategy using a **uniform or normal distribution** designed to keep the variance of activations and gradients stable across layers helping to prevent vanishing or exploding gradients.


---

### Paper 2
**Title:** Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification         
**Authors:** ```Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun```      
**Link:** https://arxiv.org/abs/1502.01852  

**Notes:**  
- Kaiming He is the researcher behind **He (Kaiming) Initialization**, a weight initialization method (*modified from Xavier Initilization*) that significantly improves training stability and convergence in deep networks using ReLU activations.

---

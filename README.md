# 📄 Paper Reading


### Paper 0
**Title:** Adam: A Method for Stochastic Optimization     
**Authors:** ```Diederik P. Kingma, Jimmy Ba```               
**Year:** 2014      
**Link:** https://arxiv.org/abs/1412.6980         

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

### Paper 3
**Title:** Empirical Evaluation of Rectified Activations in Convolutional Network    
**Authors:** ```Bing Xu, Naiyan Wang, Tianqi Chen, Mu Li```        
**Link:** https://arxiv.org/abs/1505.00853  

**Notes:**
- Present the variants of ReLU and how they evaluate

---

### Paper 4
**Title:** Self-Normalizing Neural Networks        
**Authors:** ```Günter Klambauer, Thomas Unterthiner, Andreas Mayr, Sepp Hochreiter```        
**Link:** https://arxiv.org/abs/1706.02515    

**Notes:**
- Addresses a key problem: standard feed-forward neural networks (FNNs) usually do not work well when they are deep, unlike CNNs and RNNs. This is mainly due to unstable activations and gradients.
- Highlights SNNs (Self-normalizing Neural Networks)
- SNNs use a special activation function called SELU (Scaled Exponential Linear Unit) that makes neuron activations automatically converge to zero mean and unit variance, without needing Batch Normalization.


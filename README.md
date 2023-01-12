# Regularization :-
  Any modification we make to a learning algorithm that is intended to reduce its generalization error but not its training error, are called as Regularization. Regularization not allows the weights to go too much higher or lower, to avoid overfitting. As a result, it reduces the complexicity of the learning algorithm, rather then try to fit the  data and also make it simpler, so that the trained algorithm can work on low-end device (i.e, Mobile phone, Digital camera etc.)

![simpler](https://user-images.githubusercontent.com/68110323/212059129-d5b31442-1945-4fd9-8386-8210b22cd61b.png)

As we can see in the image, initially the model was overfited. But as the regularization method implemented on the model, complexicity of the model get reduced and the model become simpler with the same dataset.

# L2-Regularization :- 
 This regularization strategy drives the weights closer to the origin1by adding a regularization term "Ω(θ) = $\^1/_2\||w\||_2^2$" to the objective function. L2-Regularization is "Parameter Norm Penalties", which is based on limiting the capacity of models by adding a parameter norm penalty "Ω(θ)" to the objective function "J". We denote the regularizedobjective function by "˜J":
 
                                                       ˜J(θ; X, y) = J(θ; X, y) + α.Ω(θ),
                                                       
Where α ∈ [0, ∞) is a hyperparameter, θ denotes all parameters. Assume no bias parameters (i.e, 0 = w): $\^α/_2w^Tw$

                                                       ˜J(w; X, y) = $\^α/_2w^Tw$ + J(w; X, y),
                                                       
                                                       
                                                       
                                                       
                                                       
hgjhggdfdfdgfdgfdgfdgfdgfd
                                                        
                                                         $\^α/_2w^Tw$ 

                                                        

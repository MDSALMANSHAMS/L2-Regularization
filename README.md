# Regularization :-
  Any modification we make to a learning algorithm that is intended to reduce its generalization error but not its training error, are called as Regularization. Regularization not allows the weights to go too much higher or lower, to avoid overfitting. As a result, it reduces the complexicity of the learning algorithm, rather then try to fit the  data and also make it simpler, so that the trained algorithm can work on low-end device (i.e, Mobile phone, Digital camera etc.)

![simpler](https://user-images.githubusercontent.com/68110323/212059129-d5b31442-1945-4fd9-8386-8210b22cd61b.png)

As we can see in the image, initially the model was overfited. But as the regularization method implemented on the model, complexicity of the model get reduced and the model become simpler with the same dataset.

# L2-Regularization :- 
 This regularization strategy drives the weights closer to the origin1by adding a regularization term "Ω(θ) = $\^1/_2\||W\||_2^2$" to the objective function. L2-Regularization is "Parameter Norm Penalties", which is based on limiting the capacity of models by adding a parameter norm penalty "Ω(θ)" to the objective function "J". We denote the regularizedobjective function by "˜J":
 
                                       ˜J(θ; X, y) = J(θ; X, y) + α.Ω(θ),
                                                       
Where α ∈ [0, ∞) is a hyperparameter, 

θ denotes all parameters, assume no bias parameters : ˜J(W; X, y) =  J(W; X, y) + $\^α/_2W^TW$,     (i.e, 0 = w)

with the corresponding parameter gradient:               

                                       ∇w˜J(W; X, y) = α.W + ∇w.J(W; X, y),

To take a single gradient step to update the weights, we perform this update:   

                                         W* ← W − ∈(α.W + ∇w.J(W; X, y),
                                                         
We can see that the addition of the "weight decay" term has modiﬁed the learning rule to multiplicatively shrink the weight vector (W*) by a constant factor on each step,just before performing the usual gradient update. And this is why "L2-Parameter Norm Penalties" is also known as "weight decay".

# Result:- 

<img width="407" alt="model summry" src="https://user-images.githubusercontent.com/68110323/212091478-00ccc017-1f63-4c5f-a629-fe1b6e881507.png">

In the model summary, as we can see that the parameters are reduced from "401920" to "1290", which is huge difference. Also made our learning algorithm way simpler/lighter. And "Testing_loss = 0.1382555216550827" & "Testing_accuracy = 0.979200005531311" are also optimised  as shown in the given figure below.

<img width="284" alt="test loss" src="https://user-images.githubusercontent.com/68110323/212093971-8e9dc1fd-9aff-4b49-a8ae-38243230b0df.png">

                                                       
                                                       




                                                        

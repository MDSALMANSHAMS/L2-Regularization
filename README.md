# Regularization :-
  Any modification we make to a learning algorithm that is intended to reduce its generalization error but not its training error, are called as Regularization. Regularization not allows the weights to go too much higher or lower, to avoid overfitting. As a result, it reduces the complexicity of the learning algorithm, rather then try to fit the  data and also make it simpler, so that the trained algorithm can work on low-end device (i.e, Mobile phone, Digital camera etc.)

![simpler](https://user-images.githubusercontent.com/68110323/212059129-d5b31442-1945-4fd9-8386-8210b22cd61b.png)

As we can see in the image, initially the model was overfited. But as the regularization method implemented on the model, complexicity of the model get reduced and the model become simpler with the same dataset.

# L2-Regularization :- 
 This regularization strategy drives the weights closer to the origin1by adding a regularization term Ω(θ) = $\^1/_2\||w\||_2^2$ to the objective function. $\^1/_2$

# varients-Gradient-Decent
One of the main issues with Gradient Descent is that it takes a lot of time to navigate regions with gentle slopes, because the gradient is very small in these regions. An intuitive solution would be that if the algorithm is repeatedly being asked to go in the same direction, then it should probably gain some confidence and start taking bigger steps in that direction.
Momentum based Gradient Descent Update Rule
a. υt = γ * υt−1 + η∇ωt

b. ωt+1 = ωt − υt

c. ωt+1 = ωt − γ * υt−1 − η∇ωt

Intuition behind nesterov accelerated gradient descent
Can we do something to reduce the oscillation in Momentum based GD

a. υt = γ * υt−1 + η∇ωt

b. ωt+1 = ωt − υt

c. ωt+1 = ωt − γ * υt−1 − η∇ωt

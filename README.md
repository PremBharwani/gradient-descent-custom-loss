# Implementing Linear and Polynomial regression with custom loss metrics.

Linear regression had to be implemented with the loss functions :
```
a) |x -  x̂|³
b) |x -  x̂| 
```

Polynomial regression(Degree=2) had to be implemented with the loss functions :
```
a) |x -  x̂|⁴
b) |x -  x̂|⁷
```

The higher power loss functions were a bit difficult to work with, becuase they were exploding too quickly. The gradients and the loss both had to be controlled so that they don't overflow the limits.




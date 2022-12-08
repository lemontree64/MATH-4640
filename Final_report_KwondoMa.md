```
---
Name: Kwondo Ma
Topic: [12]
Title: Why do we learn eigenvalue problem in math class?
----
```

# Eigenvalue Problem

The eigenvalue problem is determination of non-trivial solutions of $Ax = λx$ for vector $x$ and scalar value $λ$ [1]. Here, the matrix $A$ has to be a square matrix, vector $x$ can not be a zero vector, and scalar $λ$ has to be a real number. The solution vector $x$ is defined as an eigenvector and the corresponding scalar value $λ$ is defined as an eigenvalue.

Let's look into how to solve this eigenvalue problem. Assume that the matrix $A$ is $n \times n$ matrix. Then, the equation can be written as $(A-λI)x = 0$ where $I$ is represented an identity matrix with a size of $n \times n$. For deriving non-trivial solutions, determinant of $A-λI$ part has to be zero as, $det(A-λI)=0$. As long as we have full knowledge of matrix $A$, this is an equation with one unknown variable $λ$ and the order of this equation $n$. Therefore, we can compute the values of $λ$ from this equation (sometimes some of them are not real numbers and in this case, we dont have eigenvalue-eigenvector pairs).

Once we compute the $n$ number of eigenvalues $λ$, we can derive the corresponding eigenvector $x$ by substituting $λ$ into equation $(A-λI)x = 0$. Here, eigenvector $x$ has $n$ unknown variable and we have $n$ number of equation out of initial equation $(A-λI)x = 0$. Therefore, we can specify each eigenvector $x$ from corresponding eigenvalue $λ$.

In conclusion, equation $Ax = λx$ is solved by computing a determinant of matrix $A-λI$ for eigenvalues first, and then derive the corresponding eigenvectors later.

## What are these (eigenvalue, eigenvector) pairs used for?















# Reference

[1] Wilkinson, James Hardy. The algebraic eigenvalue problem, volume 662. Oxford Clarendon, 1965.

**1. Linear Algebra and Calculus refresher**

&#10230; Hoja de referencia de Álgebra lineal y cálculo

<br> 

**2. General notations**

&#10230; Notaciones Generales

<br> 

**3. Definitions**

&#10230; Definiciones

<br> 

**4. Vector ― We note x∈Rn a vector with n entries, where xi∈R is the ith entry:**

&#10230; Vector ― Sea x∈Rn un vector con n entradas, donde xi∈R es la n-ésima entrada:

<br> 

**5. Matrix ― We note A∈Rm×n a matrix with m rows and n columns, where Ai,j∈R is the entry located in the ith row and jth column:**

&#10230; Matriz ― Sea A∈Rm×n una matriz con m filas y n columnas; donde Ai,j∈R es el valor ubicado en la i-ésima fila y la j-ésima columna:

<br>

**6. Remark: the vector x defined above can be viewed as a n×1 matrix and is more particularly called a column-vector.**

&#10230; Observación: el vector x definido arriba puede ser visto como una matriz n×1 y es particularmente llamado vector-columna.

<br>

**7. Main matrices**

&#10230; Matrices principales

<br>

**8. Identity matrix ― The identity matrix I∈Rn×n is a square matrix with ones in its diagonal and zero everywhere else:**

&#10230; Matriz identidad - La matriz identidad I∈Rn×n es una matriz cuadrada con valores 1 en su diagonal y ceros en el resto:

<br>

**9. Remark: for all matrices A∈Rn×n, we have A×I=I×A=A.**

&#10230; Observación: para todas las matrices A∈Rn×n, se cumple que A×I=I×A=A.

<br>

**10. Diagonal matrix ― A diagonal matrix D∈Rn×n is a square matrix with nonzero values in its diagonal and zero everywhere else:**

&#10230; Matriz diagonal ― Una matriz diagonal D∈Rn×n es una matriz cuadrada con valores diferentes de zero en su diagonal y cero en el resto:

<br>

**11. Remark: we also note D as diag(d1,...,dn).**

&#10230; Observación: también se denota D como diag(d1,...,dn).

<br>

**12. Matrix operations**

&#10230; Operaciones de matrices

<br>

**13. Multiplication**

&#10230; Multiplicación

<br>

**14. Vector-vector ― There are two types of vector-vector products:**

&#10230; Vector-vector ― Hay dos tipos de multiplicaciones vector-vector:

<br>

**15. inner product: for x,y∈Rn, we have:**

&#10230; producto interno: para x,y∈Rn, se tiene que:

<br>

**16. outer product: for x∈Rm,y∈Rn, we have:**

&#10230; producto diádico: para x∈Rm,y∈Rn, se tiene que:

<br>

**17. Matrix-vector ― The product of matrix A∈Rm×n and vector x∈Rn is a vector of size Rn, such that**

&#10230; Matriz-vector ― El producto de la matriz A∈Rm×n y el vector x∈Rn, es un vector de tamaño Rn; tal que:

<br>

**18. where aTr,i are the vector rows and ac,j are the vector columns of A, and xi are the entries of x.**

&#10230; donde aTr,i son los vectores fila y ac,j son los vectores columna de A, y xi son las entradas de x.

<br>

**19. Matrix-matrix ― The product of matrices A∈Rm×n and B∈Rn×p is a matrix of size Rn×p, such that:**

&#10230; Matriz-matriz ― El producto de las matrices A∈Rm×n y B∈Rn×p es una matriz de tamaño Rn×p, tal que:

<br>

**20. where aTr,i,bTr,i are the vector rows and ac,j,bc,j are the vector columns of A and B respectively**

&#10230; donde aTr,i,bTr,i son los vectores fila y ac,j,bc,j son los vectores columna de A y B respectivamente

<br>

**21. Other operations**

&#10230; Otras operaciones

<br>

**22. Transpose ― The transpose of a matrix A∈Rm×n, noted AT, is such that its entries are flipped:**

&#10230; Transpuesta ― La transpuesta de una matriz A∈Rm×n, denotada AT, es tal que sus entradas se intercambian de la siguiente forma:

<br>

**23. Remark: for matrices A,B, we have (AB)T=BTAT**

&#10230; Observación: dadas las matrices A,B, se cumple que (AB)T=BTAT

<br>

**24. Inverse ― The inverse of an invertible square matrix A is noted A−1 and is the only matrix such that:**

&#10230; Inversa ― La inversa de una matriz cuadrada invertible A es denotada como A−1 y es la única matriz tal que:

<br>

**25. Observación: not all square matrices are invertible. Also, for matrices A,B, we have (AB)−1=B−1A−1**

&#10230; Nota: no todas las matrices cuadradas son invertibles. Además, para las matrices A,B, se cumple que (AB)−1=B−1A−1

<br>

**26. Trace ― The trace of a square matrix A, noted tr(A), is the sum of its diagonal entries:**

&#10230; Traza ― La traza de una matriz cuadrada A, denotada tr(A), es la suma de los elementos en su diagonal:

<br>

**27. Remark: for matrices A,B, we have tr(AT)=tr(A) and tr(AB)=tr(BA)**

&#10230; Observación: dadas las matrices A,B, se cumple que tr(AT)=tr(A) y tr(AB)=tr(BA)

<br>

**28. Determinant ― The determinant of a square matrix A∈Rn×n, noted |A| or det(A) is expressed recursively in terms of A∖i,∖j, which is the matrix A without its ith row and jth column, as follows:**

&#10230; Determinante ― El determinante de una matriz cuadrada A∈Rn×n, denotado |A| o det(A), es expresado recursivamente en términos de A∖i,∖j, que es la matriz A sin su i-ésima fila ni su j-ésima columna, de la siguiente forma:

<br>

**29. Remark: A is invertible if and only if |A|≠0. Also, |AB|=|A||B| and |AT|=|A|.**

&#10230; Observación: A es invertible si y solo si |A|≠0. Además, |AB|=|A||B| y |AT|=|A|.

<br>

**30. Matrix properties**

&#10230; Propiedades de matrices

<br>

**31. Definitions**

&#10230; Definiciones

<br>

**32. Symmetric decomposition ― A given matrix A can be expressed in terms of its symmetric and antisymmetric parts as follows:**

&#10230; Descomposición simétrica ― Una matriz dada A puede ser expresada en términos de sus partes simétricas y antisimétricas de la siguiente forma:

<br>

**33. [Symmetric, Antisymmetric]**

&#10230; [Simétrica, Antisimétricas]

<br>

**34. Norm ― A norm is a function N:V⟶[0,+∞[ where V is a vector space, and such that for all x,y∈V, we have:**

&#10230; Norma ― Una norma (o módulo) es una función N:V⟶[0,+∞[ donde V es un vector espacial tal que para todo x,y∈V, se cumple que:

<br>

**35. N(ax)=|a|N(x) for a scalar**

&#10230; N(ax)=|a|N(x) siendo a un escalar

<br>

**36. if N(x)=0, then x=0**

&#10230; si N(x)=0, entonces x=0

<br>

**37. For x∈V, the most commonly used norms are summed up in the table below:**

&#10230; Para x∈V, las normas comúnmente utilizadas se resumen en la siguiente tabla:

<br>

**38. [Norm, Notation, Definition, Use case]**

&#10230; [Norma, Notación, Definición, Caso de uso]

<br>

**39. Linearly dependence ― A set of vectors is said to be linearly dependent if one of the vectors in the set can be defined as a linear combination of the others.**

&#10230; Dependencia lineal ― Un conjunto de vectores se dice que es linealmente dependiente si uno de los vectores del conjunto puede ser definido como una combinación lineal de los restantes.

<br>

**40. Remark: if no vector can be written this way, then the vectors are said to be linearly independent**

&#10230; Observación: si ningún vector puede ser escrito de esta forma, entonces se dice que los vectores son linealmente independientes

<br>

**41. Matrix rank ― The rank of a given matrix A is noted rank(A) and is the dimension of the vector space generated by its columns. This is equivalent to the maximum number of linearly independent columns of A.**

&#10230; Rango matricial ― El rango de una matriz dada A es denotado rank(A) y es la dimensión del espacio vectorial generado por sus columnas. Esto es equivalente al máximo número de columnas linealmente independientes de A.
 
<br>

**42. Positive semi-definite matrix ― A matrix A∈Rn×n is positive semi-definite (PSD) and is noted A⪰0 if we have:**

&#10230; Matriz semi-definida positiva ― Una matriz A∈Rn×n es semi-defininda positiva (PSD), lo cual se denota como A⪰0, si se cumple que:

<br>

**43. Remark: similarly, a matrix A is said to be positive definite, and is noted A≻0, if it is a PSD matrix which satisfies for all non-zero vector x, xTAx>0.**

&#10230; Observación: de igual forma, una matriz A se dice definida positiva, lo cual se denota con A≻0, si es una matriz PSD que satisface para todos los vectores x diferentes de cero, xTAx>0.

<br>

**44. Eigenvalue, eigenvector ― Given a matrix A∈Rn×n, λ is said to be an eigenvalue of A if there exists a vector z∈Rn∖{0}, called eigenvector, such that we have:**

&#10230; Valor propio, vector propio ― Dada una matriz A∈Rn×n, λ se dice que es un valor propio (eigenvalue, en inglés) de A si existe un vector z∈Rn∖{0}, llamado vector propio (eigenvector, en inglés), tal que:

<br>

**45. Spectral theorem ― Let A∈Rn×n. If A is symmetric, then A is diagonalizable by a real orthogonal matrix U∈Rn×n. By noting Λ=diag(λ1,...,λn), we have:**

&#10230; Teorema espectral ― Sea A∈Rn×n. Si A es simétrica, entonces A es diagonalizable a través de una matriz real ortogonal U∈Rn×n. Denotando Λ=diag(λ1,...,λn), se tiene que:

<br>

**46. diagonal**

&#10230; diagonal

<br>

**47. Singular-value decomposition ― For a given matrix A of dimensions m×n, the singular-value decomposition (SVD) is a factorization technique that guarantees the existence of U m×m unitary, Σ m×n diagonal and V n×n unitary matrices, such that:**

&#10230; Descomposición en valores singulares ― Para una matriz dada A de dimensiones m×n, la descomposición en valores singulares (SVD, por sus siglas en inglés de _Singular-Value Decomposition_) es una técnica de factorización que garantiza la existencia de las matrices U m×m unitaria, Σ m×n diagonal y V n×n unitaria, tal que:

<br>

**48. Matrix calculus**
 
&#10230; Cálculo de matrices

<br>

**49. Gradient ― Let f:Rm×n→R be a function and A∈Rm×n be a matrix. The gradient of f with respect to A is a m×n matrix, noted ∇Af(A), such that:**

&#10230; Gradiente ― Sea f:Rm×n→R una función y A∈Rm×n una matriz. El gradiente de f con respecto a A es una matriz de m×n, denotada por ∇Af(A), tal que:

<br>

**50. Remark: the gradient of f is only defined when f is a function that returns a scalar.**

&#10230; Observación: el gradiente de f se define únicamente cuando f es una función que retorna un escalar.

<br>

**51. Hessian ― Let f:Rn→R be a function and x∈Rn be a vector. The hessian of f with respect to x is a n×n symmetric matrix, noted ∇2xf(x), such that:**

&#10230; Hessiana ― Sea f:Rn→R una función y x∈Rn un vector. La hessiana de f con recpecto a x es una matriz simétrica n×n, denotada ∇2xf(x), tal que:

<br>

**52. Remark: the hessian of f is only defined when f is a function that returns a scalar**

&#10230; Observación: la matriz hessiana de f se define únicamente cuando f es una función que devuelve un escalar

<br>

**53. Gradient operations ― For matrices A,B,C, the following gradient properties are worth having in mind:**

&#10230; Operaciones de gradiente ― Dadas las matrices A,B,C, las siguientes propiedades de gradiente merecen ser tenidas en cuenta:

<br>

**54. [General notations, Definitions, Main matrices]**

&#10230; [Notaciones generales, Definiciones, Matrices principales]

<br>

**55. [Matrix operations, Multiplication, Other operations]**

&#10230; [Operaciones matriciales, Multiplicación, Otras operaciones]

<br>

**56. [Matrix properties, Norm, Eigenvalue/Eigenvector, Singular-value decomposition]**

&#10230; [Propiedades de matrices, Norma, Valor propio/Vector propio, Descomposición en valores singulares]

<br>

**57. [Matrix calculus, Gradient, Hessian, Operations]**

&#10230; [Cálculo de matrices, Gradiente, Hessiana, Operaciones]

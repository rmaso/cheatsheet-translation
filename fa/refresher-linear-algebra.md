**1. Linear Algebra and Calculus refresher**
<div dir="rtl">
یادآوری جبر خطی و حسابان
</div>
<br>

**2. General notations**
<div dir="rtl">
نمادها
</div>
<br>

**3. Definitions**
<div dir="rtl">
تعاریف
</div>
<br>

**4. Vector ― We note x∈Rn a vector with n entries, where xi∈R is the ith entry:**
<div dir="rtl">
بردار - $x \in \mathbb{R}^n$ یک بردار با $n$ درایه است، که $x_i \in \mathbb{R}$ درایه‌ی $i$ام می‌باشد:
</div>
<br>

**5. Matrix ― We note A∈Rm×n a matrix with m rows and n columns, where Ai,j∈R is the entry located in the ith row and jth column:**
<div dir="rtl">
ماتریس - $A \in \mathbb{R} ^ {m \times n}$ یک بردار با $n$ سطر و $m$ ستون است، که در آن $A_{i, j} \in \mathbb{R}$ درایه‌ای است که در سطر $i$ام و ستون $j$ام قرار دارد:
</div>
<br>

**6. Remark: the vector x defined above can be viewed as a n×1 matrix and is more particularly called a column-vector.**
<div dir="rtl">
نکته: بردار $x$ که در بالا تعریف شد را می‌توان به صورت یک ماتریس $n \times 1$ در نظر گرفت که به طور خاص به آن بردار ستونی گویند.
</div>
<br>

**7. Main matrices**
<div dir="rtl">
ماتریس‌های اصلی:
</div>
<br>

**8. Identity matrix ― The identity matrix I∈Rn×n is a square matrix with ones in its diagonal and zero everywhere else:**
<div dir="rtl">
ماتریس همانی - ماتریس همانی $I \in \mathbb{R}^{n \times n}$ یک ماتریس مربعی است که درایه‌های قطری آن همه مقدار ۱ و بقیه‌ی درایه‌ها مقدار ۰ دارند:
</div>
<br>

**9. Remark: for all matrices A∈Rn×n, we have A×I=I×A=A.**
<div dir="rtl">
نکته: برای همه‌ی ماتریس‌های $A \in \mathbb{R}^{n \times n}$ داریم $A \times I = I \times A = A$.
</div>
<br>

**10. Diagonal matrix ― A diagonal matrix D∈Rn×n is a square matrix with nonzero values in its diagonal and zero everywhere else:**
<div dir="rtl">
ماتریس قطری - ماتریس $D \in \mathbb{R} ^ {n \times n}$ یک ماتریس مربعی است که درایه‌های قطری آن مقادیر غیرصفر دارند و بقیه‌ی درایه‌ها صفر هستند:
</div>
<br>

**11. Remark: we also note D as diag(d1,...,dn).**
<div dir="rtl">
نکته:‌$D$ همچنین به صورت $\text{diag}(d_1, \dots, d_n)$ هم نمایش داده می‌شود.
</div>
<br>

**12. Matrix operations**
<div dir="rtl">
عملیات ماتریسی
</div>
<br>

**13. Multiplication**
<div dir="rtl">
ضرب
</div>
<br>

**14. Vector-vector ― There are two types of vector-vector products:**
<div dir="rtl">
بردار با بردار - دو نوع عملیات ضرب بردار با بردار وجود دارد:
</div>
<br>

**15. inner product: for x,y∈Rn, we have:**
<div dir="rtl">
ضرب داخلی: برای هر $x, y \in \mathbb{R}^n$ داریم:
</div>
<br>

**16. outer product: for x∈Rm,y∈Rn, we have:**
<div dir="rtl">
ضرب خارجی: برای هر $x \in \mathbb{R}^m$ و $y \in \mathbb{R}^n$ داریم:
</div>
<br>

**17. Matrix-vector ― The product of matrix A∈Rm×n and vector x∈Rn is a vector of size Rn, such that:**
<div dir="rtl">
ماتریس با بردار - ضرب ماتریس $A \in \mathbb{R}^{m \times n}$ و بردار $x \in \mathbb{R}^n$ برداری با اندازه‌ی $m$ است به طوری که:
</div>
<br>

**18. where aTr,i are the vector rows and ac,j are the vector columns of A, and xi are the entries of x.**
<div dir="rtl">
که $a^T_{r, i} بردارهای سطری و $a_{c, j}$ بردارهای ستونی $A$، و $x_i$ درایه‌های $x$ هستند.
</div>
<br>

**19. Matrix-matrix ― The product of matrices A∈Rm×n and B∈Rn×p is a matrix of size Rn×p, such that:**
<div dir="rtl">
ماتریس با ماتریس - ضرب ماتریس‌های $A \in \mathbb{R}^{n \times m}$ و $B \in \mathbb{R}^{n \times p}$ ماتریسی با اندازه‌ی $n \times p$ است که:
</div>
<br>

**20. where aTr,i,bTr,i are the vector rows and ac,j,bc,j are the vector columns of A and B respectively**
<div dir="rtl">
که $a^T_{r, i}$ و $b^T_{r, i}$ بردارهای سطری و $a_{c, j}$ و b_{c, j}$ بردارهای ستونی $A$ و $B$ هستند.
</div>
<br>

**21. Other operations**
<div dir="rtl">
دیگر عملیات
</div>
<br>

**22. Transpose ― The transpose of a matrix A∈Rm×n, noted AT, is such that its entries are flipped:**
<div dir="rtl">
ترانهاده - ترانهاده‌ی ماتریس $A \in \mathbb{R}^{m \times n}$ که با $A^T$ نمایش داده می‌شود، ماتریسی است که مکان درایه‌های آن نسبت به قطر ماتریس برعکس شده‌اند:
</div>
<br>

**23. Remark: for matrices A,B, we have (AB)T=BTAT**
<div dir="rtl">
نکته: برای ماتریس‌های $A$ و $B$، داریم $(AB)^T = B^T A^T$.
</div>
<br>

**24. Inverse ― The inverse of an invertible square matrix A is noted A−1 and is the only matrix such that:**
<div dir="rtl">
معکوس - معکوس یک ماتریس مربعی معکوس‌پذیر $A$ که با $A^{-1}$ نمایش داده می‌شود، تنها ماتریسی است که:
</div>
<br>

**25. Remark: not all square matrices are invertible. Also, for matrices A,B, we have (AB)−1=B−1A−1**
<div dir="rtl">
نکته: همه‌ی ماتریس‌های مربعی معکوس‌پذیر نیستند. همچنین، برای ماتریس‌های مربعی معکوس‌پذیر $A$ و $B$ داریم $(AB)^{-1} = B^{-1} A^{-1}$.
</div>
<br>

**26. Trace ― The trace of a square matrix A, noted tr(A), is the sum of its diagonal entries:**
<div dir="rtl">
اثر - اثر ماتریس مربعی $A$ که با $tr(A)$ نمایش داده می‌شود، مجموع همه‌ی درایه‌های قطری ماتریس است.
</div>
<br>

**27. Remark: for matrices A,B, we have tr(AT)=tr(A) and tr(AB)=tr(BA)**
<div dir="rtl">
نکته: برای ماتریس‌های $A$ و $B$ داریم $tr(A^T) = tr(A)$ و $tr(AB) = tr(BA)$.
</div>
<br>

**28. Determinant ― The determinant of a square matrix A∈Rn×n, noted |A| or det(A) is expressed recursively in terms of A∖i,∖j, which is the matrix A without its ith row and jth column, as follows:**
<div dir="rtl">
دترمینان - دترمینان یک ماتریس مربعی $A \in \mathbb{R}^{n \times n}$ که با $|A|$ یا $\det(A)$ نمایش داده می‌شود، به صورت یک عبارت بازگشتی بر روی $A_{\\i, \\j}$، که ماتریس $A$ بدون سطر $i$-ام و ستون $j$-ام است، به صورت زیر تعریف می‌شود:
</div>
<br>

**29. Remark: A is invertible if and only if |A|≠0. Also, |AB|=|A||B| and |AT|=|A|.**
<div dir="rtl">
نکته: $A$ معکوس‌پذیر است اگر و فقط اگر $|A| \neq 0$. همچنین $|A B| = |A| |B|$ و $|A^T| = |A|$.
</div>
<br>

**30. Matrix properties**
<div dir="rtl">
ویژگی‌های ماتریس‌ها
</div>
<br>

**31. Definitions**
<div dir="rtl">
تعاریف
</div>
<br>

**32. Symmetric decomposition ― A given matrix A can be expressed in terms of its symmetric and antisymmetric parts as follows:**
<div dir="rtl">
تجزیه‌ی متقارن - یک ماتریس دلخواه $A$ را می‌توان با استفاده از اجزای متقارن و غیرمتقارن آن به صورت زیر نشان داد:
</div>
<br>

**33. [Symmetric, Antisymmetric]**
<div dir="rtl">
[متقارن، غیرمتقارن]
</div>
<br>

**34. Norm ― A norm is a function N:V⟶[0,+∞[ where V is a vector space, and such that for all x,y∈V, we have:**
<div dir="rtl">
نرم - نرم تابع $N: \mathbb{V} \rightarrow [0, +\infty[$ است که $V$ یک فضای برداری است، و به گونه‌ای است که برای هر $x, y \in \mathbb{V}$ داریم:
</div>
<br>

**35. N(ax)=|a|N(x) for a scalar**
<div dir="rtl">
$N(a x) = |a| N(x)$ برای عدد اسکالر
</div>
<br>

**36. if N(x)=0, then x=0**
<div dir="rtl">
اگر $N(x) = $ باشد در این صورت $x = 0$
</div>
<br>

**37. For x∈V, the most commonly used norms are summed up in the table below:**
<div dir="rtl">
برای $x \in \mathbb{V}$، نرم‌هایی که بیشتر استفاده می‌شوند در جدول زیر آمده‌اند:
</div>
<br>

**38. [Norm, Notation, Definition, Use case]**
<div dir="rtl">
[نُرم، نماد، تعریف، کاربرد]
</div>
<br>

**39. Linearly dependence ― A set of vectors is said to be linearly dependent if one of the vectors in the set can be defined as a linear combination of the others.**
<div dir="rtl">
وابستگی خطی - مجموعه‌ای از بردارها وابستگی خطی دارند اگر یکی از بردارهای مجموعه را بتوان به صورت ترکیب خطی دیگر بردارها تعریف کرد.
</div>
<br>

**40. Remark: if no vector can be written this way, then the vectors are said to be linearly independent**
<div dir="rtl">
نکته: اگر نتوان هیچ برداری را به این شکل تعریف کرد، در این صورت بردارها استقلال خطی دارند.
</div>
<br>

**41. Matrix rank ― The rank of a given matrix A is noted rank(A) and is the dimension of the vector space generated by its columns. This is equivalent to the maximum number of linearly independent columns of A.**
<div dir="rtl">
رتبه ماتریس - رتبه‌ی یک ماتریس $A$ که با $\text{rank}(A)$ نمایش داده می‌شود، تعداد ابعاد فضایی است که توسط ستون‌های آن ایجاد می‌شود. این مقدار برابر است با حداکثر تعداد ستون‌های $A$ که استقلال خطی داشته باشند.
</div>
<br>

**42. Positive semi-definite matrix ― A matrix A∈Rn×n is positive semi-definite (PSD) and is noted A⪰0 if we have:**
<div dir="rtl">
ماتریس مثبت نیمه‌معین - ماتریس $A \in \mathbb{R}^{n \times n}$ یک ماتریس مثبت نیمه‌معین است که با $A \succeq 0$ نمایش داده می‌شود اگر داشته باشیم:
</div>
<br>

**43. Remark: similarly, a matrix A is said to be positive definite, and is noted A≻0, if it is a PSD matrix which satisfies for all non-zero vector x, xTAx>0.**
<div dir="rtl">
نکته: به طور مشابه، یک ماتریس $A$ مثبت معین است ($A \succ 0$)، اگر یک ماتریس مثبت نیمه‌معین باشد که برای هر بردار غیرصفر $x$ داشته باشیم $x^T A > 0$.
</div>
<br>

**44. Eigenvalue, eigenvector ― Given a matrix A∈Rn×n, λ is said to be an eigenvalue of A if there exists a vector z∈Rn∖{0}, called eigenvector, such that we have:**
<div dir="rtl">
مقدار ویژه، بردار ویژه - برای یک ماتریس $A \in \mathbb{R}^{n \times n}$، گوییم $\lambda$ یک مقدار ویژه ماتریس $A$ است اگر وجود داشته باشد بردار $z \in \mathbb{R}^n \\ \{0\}$، که یک بردار ویژه نام دارد، به طوری که:
</div>
<br>

**45. Spectral theorem ― Let A∈Rn×n. If A is symmetric, then A is diagonalizable by a real orthogonal matrix U∈Rn×n. By noting Λ=diag(λ1,...,λn), we have:**
<div dir="rtl">
قضیه‌ی طیفی - فرض کنید $A \in \mathbb{R}^{n \times n}$ باشد. اگر $A$ متقارن باشد، در این صورت $A$ توسط یک ماتریس حقیقی متعامد $U \in \mathbb{R} ^{n \times n}$ قطری‌پذیر است. با نمایش $\Lambda = \diag(\lambda_1, \dots, \lambda_n)$ داریم:
</div>
<br>

**46. diagonal**
<div dir="rtl">
قطری
</div>
<br>

**47. Singular-value decomposition ― For a given matrix A of dimensions m×n, the singular-value decomposition (SVD) is a factorization technique that guarantees the existence of U m×m unitary, Σ m×n diagonal and V n×n unitary matrices, such that:**
<div dir="rtl">
تجزیه‌ی مقدار منفرد - برای یک ماتریس $A$ با ابعاد $m \times n$، تجزیه‌ی مقدار منفرد یک تکنیک تقسیم‌بندی است که تضمین می‌کند یک ماتریس یکانی $U \in \mathbb{R}^{n \times n}$، یک ماتریس قطری $\Sigma \in \mathbb{R}^{m \times n}$، و یک ماتریس یکانی $V \in \mathbb{R}^{n \times n}$ وجود دارند، به طوری که:
</div>
<br>

**48. Matrix calculus**
<div dir="rtl">
حسابان ماتریسی
</div>
<br>

**49. Gradient ― Let f:Rm×n→R be a function and A∈Rm×n be a matrix. The gradient of f with respect to A is a m×n matrix, noted ∇Af(A), such that:**
<div dir="rtl">
گرادیان - فرض کنید $f: \mathbb{R}^{m \times n} \rightarrow \mathbb{R}$ یک تابع و $A \in \mathbb{R}^{m \times n}$ یک ماتریس باشد. گرادیان $f$ نسبت به $A$ یک ماتریس با ابعاد $m \times n$ است و با $\nabla_A f(A)$ نمایش داده می‌شود، به طوری که:
</div>
<br>

**50. Remark: the gradient of f is only defined when f is a function that returns a scalar.**
<div dir="rtl">
نکته: گرادیان $f$ تنها زمانی تعریف شده است که $f$ تابعی باشد که یک عدد اسکالر خروجی دهد.
</div>
<br>

**51. Hessian ― Let f:Rn→R be a function and x∈Rn be a vector. The hessian of f with respect to x is a n×n symmetric matrix, noted ∇2xf(x), such that:**
<div dir="rtl">
هشین - فرض کنید $f: \mathbb{R}^n \rightarrow \mathbb{R}$ یک تابع و $x \in \mathbb{R}^n$ یک بردار باشد. هشین $f$ نسبت به $x$ یک ماتریس متقارن با ابعاد $n \times n$ است و با $\nabla^2_x f(x)$ نمایش داده می‌شود، به طوری که:
</div>
<br>

**52. Remark: the hessian of f is only defined when f is a function that returns a scalar**
<div dir="rtl">
نکته: هشین تابع $f$ تنها زمانی تعریف شده است که $f$ تابعی با خروجی اسکالر باشد.
</div>
<br>

**53. Gradient operations ― For matrices A,B,C, the following gradient properties are worth having in mind:**
<div dir="rtl">
عملیات گرادیانی - برای ماتریس‌های $A$، $B$، و $C$، ویژگی‌های زیر را به خاطر داشته باشید:
</div>
<br>

**54. [General notations, Definitions, Main matrices]**
<div dir="rtl">
[نمادها، تعاریف، ماتریس‌های اصلی]
</div>
<br>

**55. [Matrix operations, Multiplication, Other operations]**
<div dir="rtl">
[عملیات ماتریسی، ضرب، بقیه‌ی عملیات]
</div>
<br>

**56. [Matrix properties, Norm, Eigenvalue/Eigenvector, Singular-value decomposition]**
<div dir="rtl">
[ویژگی‌های ماتریس، نُرم، مقدار ویژه/بردار ویژه، تجزیه‌ی مقدار منفرد]
</div>
<br>

**57. [Matrix calculus, Gradient, Hessian, Operations]**
<div dir="rtl">
[حسابان ماتریسی، گرادیان، هشین، عملیات]
</div>

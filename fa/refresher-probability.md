**1. Probabilities and Statistics refresher**
<div dir="rtl">
یادآوری آمار و احتمالات
</div>
<br>

**2. Introduction to Probability and Combinatorics**
<div dir="rtl">
مقدمه‌ای بر احتمالات و ترکیبیات
</div>
<br>

**3. Sample space ― The set of all possible outcomes of an experiment is known as the sample space of the experiment and is denoted by S.**
<div dir="rtl">
فضای نمونه - مجموعه‌ی همه‌ی پیشامدهای یک آزمایش را فضای نمونه‌ی آن آزمایش گویند که با $S$ نمایش داده می‌شود.
</div>
<br>

**4. Event ― Any subset E of the sample space is known as an event. That is, an event is a set consisting of possible outcomes of the experiment. If the outcome of the experiment is contained in E, then we say that E has occurred.**
<div dir="rtl">
رخداد - هر زیرمجموعه‌ی $E$از فضای نمونه یک رخداد در نظر گرفته می‌شود.
به عبارت دیگر، یک رخداد مجموعه‌ای از پیشامدهای یک آزمایش است.
اگر پیشامد یک آزمایش عضوی از مجموعه‌ی $E$ باشد، در این حالت می‌گوییم که رخداد $E$ اتفاق افتاده است.
</div>
<br>

**5. Axioms of probability For each event E, we denote P(E) as the probability of event E occuring.**
<div dir="rtl">
اصول موضوعه‌ی احتمالات.
برای هر رخداد $E$، $P(E)$ احتمال اتفاق افتادن رخداد $E$ می‌باشد.
</div>
<br>

**6. Axiom 1 ― Every probability is between 0 and 1 included, i.e:**
<div dir="rtl">
اصل ۱ - احتمال عددی بین ۰ و ۱ است.
</div>
<br>

**7. Axiom 2 ― The probability that at least one of the elementary events in the entire sample space will occur is 1, i.e:**
<div dir="rtl">
اصل ۲ - احتمال اینکه حداقل یکی از رخدادهای موجود در فضای نمونه اتفاق بیافتد، ۱ است.
</div>
<br>

**8. Axiom 3 ― For any sequence of mutually exclusive events E1,...,En, we have:**
<div dir="rtl">
اصل ۳ - برای هر دنباله از رخدادهایی که دو به دو اشتراک نداشته باشند، داریم:
</div>
<br>

**9. Permutation ― A permutation is an arrangement of r objects from a pool of n objects, in a given order. The number of such arrangements is given by P(n,r), defined as:**
<div dir="rtl">
جایگشت - یک جایگشت چیدمانی از $r$ شی از $n$ شی با یک ترتیب خاص است. تعداد این چنین جایگشت‌ها $P(n, r)$ است که به صورت زیر تعریف می‌شود:
</div>
<br>

**10. Combination ― A combination is an arrangement of r objects from a pool of n objects, where the order does not matter. The number of such arrangements is given by C(n,r), defined as:**
<div dir="rtl">
ترکیب - یک ترکیب چیدمانی از $r$ شی از $n$ شی است، به طوری که ترتیب اهمیتی نداشته باشد. تعداد این چنین ترکیب‌ها $C(n, r)$ است که به صورت زیر تعریف می‌شود:
</div>
<br>

**11. Remark: we note that for 0⩽r⩽n, we have P(n,r)⩾C(n,r)**
<div dir="rtl">
نکته: برای $0 \leq r \leq n$، داریم $P(n, r) \geq C(n, r)$
</div>
<br>

**12. Conditional Probability**
<div dir="rtl">
احتمال شرطی
</div>
<br>

**13. Bayes' rule ― For events A and B such that P(B)>0, we have:**
<div dir="rtl">
قضیه‌ی بیز - برای رخدادهای $A$ و $B$ به طوری که $P(B) > 0$ داریم:
</div>
<br>

**14. Remark: we have P(A∩B)=P(A)P(B|A)=P(A|B)P(B)**
<div dir="rtl">
نکته:‌داریم $P(A \cap B) = P(A) P(B | A) = P(A | B) P(B)$
</div>
<br>

**15. Partition ― Let {Ai,i∈[[1,n]]} be such that for all i, Ai≠∅. We say that {Ai} is a partition if we have:**
<div dir="rtl">
افراز - فرض می‌کنیم برای $\{A_i, i \in [1, n] \}$ به ازای هر $i$ داشته باشیم $A_i \neq \mathbf{0}$. در این صورت می‌گوییم $\{A_i\}$ یک افراز است اگر:
</div>
<br>

**16. Remark: for any event B in the sample space, we have P(B)=n∑i=1P(B|Ai)P(Ai).**
<div dir="rtl">
نکته: برای هر رخداد $B$ در فضای نمونه داریم $P(B) = \sum_{i=1}^n P(B | A_i) P(A_i)$.
</div>
<br>

**17. Extended form of Bayes' rule ― Let {Ai,i∈[[1,n]]} be a partition of the sample space. We have:**
<div dir="rtl">
تعمیم قضیه‌ی بیز - فرض می‌کنیم $\{A_i, i \in [1, n]\}$ یک افراز از فضای نمونه باشید. در این صورت داریم:
</div>
<br>

**18. Independence ― Two events A and B are independent if and only if we have:**
<div dir="rtl">
استقلال - دو رخداد $A$ و $B$ مستقل هستند اگر و فقط اگر داشته باشیم:
</div>
<br>

**19. Random Variables**
<div dir="rtl">
متغیرهای تصادفی
</div>
<br>

**20. Definitions**
<div dir="rtl">
تعاریف
</div>
<br>

**21. Random variable ― A random variable, often noted X, is a function that maps every element in a sample space to a real line.**
<div dir="rtl">
متغیر تصادفی - یک متغیر تصادفی، که معمولاً با $X$ نمایش داده می‌شود، یک تابع است که هر عضو فضای نمونه را به اعداد حقیقی نگاشت می‌کند.
</div>
<br>

**22. Cumulative distribution function (CDF) ― The cumulative distribution function F, which is monotonically non-decreasing and is such that limx→−∞F(x)=0 and limx→+∞F(x)=1, is defined as:**
<div dir="rtl">
تابع توزیع تجمعی - تابع توزیع تجمعی $F$، که تابعی یکنوا و اکیدا غیرنزولی است و برای آن $\lim_{x \rightarrow -\infty} F(x) = 0$ و $\lim_{x \rightarrow +\infty} F(x) = 1$ صدق می‌کنید، به صورت زیر تعریف می‌شود:
</div>
<br>

**23. Remark: we have P(a<X⩽B)=F(b)−F(a).**
<div dir="rtl">
نکته: داریم $P(a < X \leq b) = F(b) - F(a)$.
</div>
<br>

**24. Probability density function (PDF) ― The probability density function f is the probability that X takes on values between two adjacent realizations of the random variable.**
<div dir="rtl">
تابع چگالی احتمال (PDF) - تابع چگالی احتمال $f$ احتمال آن است که متغیر تصادفی $X$ مقداری بین دو تحقق همجوار این متغیر تصادفی را بگیرد.
</div>
<br>

**25. Relationships involving the PDF and CDF ― Here are the important properties to know in the discrete (D) and the continuous (C) cases.**
<div dir="rtl">
ارتباط بین PDF و CDF - موارد زیر ویژگی‌های مهمی هستند که باید در مورد حالت گسسته و حالت پیوسته در نظر گرفت.
</div>
<br>

**26. [Case, CDF F, PDF f, Properties of PDF]**
<div dir="rtl">
[[CDF F, PDF f, ویژگی‌های PDF]]
</div>
<br>

**27. Expectation and Moments of the Distribution ― Here are the expressions of the expected value E[X], generalized expected value E[g(X)], kth moment E[Xk] and characteristic function ψ(ω) for the discrete and continuous cases:**
<div dir="rtl">
امید ریاضی و گشتاورهای یک توزیع - عبارت‌های مربوط به امید ریاضی $E[X]$، امید ریاضی تعمیم یافته $E[g(X)]$، $k$-مین گشتاور $E[X^k]$، و تابع ویژگی $\psi(\omega)$ برای حالات پیوسته و گسسته به صورت زیر هستند:
</div>
<br>

**28. Variance ― The variance of a random variable, often noted Var(X) or σ2, is a measure of the spread of its distribution function. It is determined as follows:**
<div dir="rtl">
واریانس - واریانس یک متغیر تصادفی، که معمولاً با $Var(X)$ یا $\sigma^2$ نمایش داده می‌شود، میزانی از پراکندگی یک تابع توزیع است. مقدار واریانس به صورت زیر به دست می‌آید:
</div>
<br>

**29. Standard deviation ― The standard deviation of a random variable, often noted σ, is a measure of the spread of its distribution function which is compatible with the units of the actual random variable. It is determined as follows:**
<div dir="rtl">
انحراف معیار - انحراف معیار یک متغیر تصادفی، که با $\sigma$ نمایش داده می‌شود، میزانی از پراکندگی یک تابع توزیع است که با متغیر تصادفی هم‌واحد است. مقدار آن به صورت زیر به دست می‌آید:
</div>
<br>

**30. Transformation of random variables ― Let the variables X and Y be linked by some function. By noting fX and fY the distribution function of X and Y respectively, we have:**
<div dir="rtl">
تبدیلات متغیرهای تصادفی - فرض کنید متغیرهای تصادفی $X$ و $Y$ توسط تابعی به هم مرتبط هستند. با نمایش تابع توزیع متغیرهای تصادفی $X$ و $Y$ با $f_X$ و $f_Y$ داریم:
</div>
<br>

**31. Leibniz integral rule ― Let g be a function of x and potentially c, and a,b boundaries that may depend on c. We have:**
<div dir="rtl">
قضیه‌ی انتگرال لایبنیتس - فرض کنید $g$ تابعی از $x$ و $c$ باشد، و $a$ و $b$ کران‌هایی باشند که مقدار آن‌ها وابسته به مقدار $c$ باشد. داریم:
</div>
<br>

**32. Probability Distributions**
<div dir="rtl">
توزیع‌های احتمالی
</div>
<br>

**33. Chebyshev's inequality ― Let X be a random variable with expected value μ. For k,σ>0, we have the following inequality:**
<div dir="rtl">
نابرابری چبیشف - فرض کنید $X$ متغیری تصادفی با امید ریاضی $\mu$ باشد. برای هر $k$ و $\sigma > 0$ نابرابری زیر را داریم:
</div>
<br>

**34. Main distributions ― Here are the main distributions to have in mind:**
<div dir="rtl">
توزیع‌های احتمالی اصلی - توزیع‌های زیر توزیع‌های احتمالی اصلی هستند که بهتر است به خاطر بسپارید:
</div>
<br>

**35. [Type, Distribution]**
<div dir="rtl">
[نوع، توزیع]
</div>
<br>

**36. Jointly Distributed Random Variables**
<div dir="rtl">
متغیرهای تصادفی با توزیع مشترک
</div>
<br>

**37. Marginal density and cumulative distribution ― From the joint density probability function fXY , we have**
<div dir="rtl">
چگالی حاشیه‌ای و توزیع تجمعی - از تابع چگالی احتمالی مشترک $f_{XY}$ داریم
</div>
<br>

**38. [Case, Marginal density, Cumulative function]**
<div dir="rtl">
[حالت، چگالی حاشیه‌ای، تابع تجمعی]
</div>
<br>

**39. Conditional density ― The conditional density of X with respect to Y, often noted fX|Y, is defined as follows:**
<div dir="rtl">
چگالی شرطی - چگالی شرطی $X$ نسبت به $Y، که معمولاً با $f_{X | Y}$ نمایش داده می‌شود، به صورت زیر تعریف می‌شود:
</div>
<br>

**40. Independence ― Two random variables X and Y are said to be independent if we have:**
<div dir="rtl">
استقلال - دو متغیر تصادفی $X$ و $Y$ مستقل هستند اگر داشته باشیم:
</div>
<br>

**41. Covariance ― We define the covariance of two random variables X and Y, that we note σ2XY or more commonly Cov(X,Y), as follows:**
<div dir="rtl">
کوواریانس - کوواریانس دو متغیر تصادفی $X$ و $Y$ که با $\sigma_{XY}$ یا به صورت معمول‌تر با $Cov{X,Y}$ نمایش داده می‌شود، به صورت زیر است:
</div>
<br>

**42. Correlation ― By noting σX,σY the standard deviations of X and Y, we define the correlation between the random variables X and Y, noted ρXY, as follows:**
<div dir="rtl">
همبستگی - با نمایش انحراف معیار $X$ و $Y$ به صورت $\sigma_X$ و $\sigma_Y$، همبستگی مابین دو متغیر تصادفی $X$ و $Y$ که با $\rho_{XY}$ نمایش داده می‌شود به صورت زیر تعریف می‌شود:
</div>
<br>

**43. Remark 1: we note that for any random variables X,Y, we have ρXY∈[−1,1].**
<div dir="rtl">
نکته‌ی ۱: برای هر دو متغیر تصادفی دلخواه $X$ و $Y$، داریم $\rho_{XY} \in [-1, 1]$.
</div>
<br>

**44. Remark 2: If X and Y are independent, then ρXY=0.**
<div dir="rtl">
نکته‌ی ۲: اگر $X$ و $Y$ مستقل باشند، داریم $\rho_{XY}=0$.
</div>
<br>

**45. Parameter estimation**
<div dir="rtl">
تخمین پارامتر
</div>
<br>

**46. Definitions**
<div dir="rtl">
تعاریف
</div>
<br>

**47. Random sample ― A random sample is a collection of n random variables X1,...,Xn that are independent and identically distributed with X.**
<div dir="rtl">
نمونه‌ی تصادفی - یک نمونه‌ی تصادفی مجموعه‌ای از $n$ متغیر تصادفی $\{X_1, \dots, X_n\}$ است که از هم مستقل هستند و توزیع یکسانی با $X$ دارند.
</div>
<br>

**48. Estimator ― An estimator is a function of the data that is used to infer the value of an unknown parameter in a statistical model.**
<div dir="rtl">
تخمین‌گر - یک تخمین‌گر تابعی از داده‌ها است که برای به‌دست‌آوردن مقدار نامشخص یک پارامتر در یک مدل آماری به کار می‌رود.
</div>
<br>

**49. Bias ― The bias of an estimator ^θ is defined as being the difference between the expected value of the distribution of ^θ and the true value, i.e.:**
<div dir="rtl">
پیش‌قدر - پیش‌قدر یک تخمین‌گر $\hat{\theta}$ به عنوان اختلاف بین امید ریاضی توزیع $\hat{\theta}$ و مقدار واقعی تعریف می‌شود. یعنی:
</div>
<br>

**50. Remark: an estimator is said to be unbiased when we have E[^θ]=θ.**
<div dir="rtl">
نکته: یک تخمین‌گر بدون پیش‌قدر است اگر داشته باشیم $E[\hat{\theta}] = \theta$.
</div>
<br>

**51. Estimating the mean**
<div dir="rtl">
تخمین میانگین
</div>
<br>

**52. Sample mean ― The sample mean of a random sample is used to estimate the true mean μ of a distribution, is often noted ¯¯¯¯¯X and is defined as follows:**
<div dir="rtl">
میانگین نمونه - میانگین نمونه‌ی یک نمونه‌ی تصادفی که برای تخمین مقدار واقعی میانگین $\mu$ یک توزیع به کار می‌رود، معمولاً با $\bar{X}$ نمایش داده می‌شود و به صورت زیر تعریف می‌شود:
</div>
<br>

**53. Remark: the sample mean is unbiased, i.e E[¯¯¯¯¯X]=μ.**
<div dir="rtl">
نکته: میانگین نمونه بدون پیش‌قدر است، یعنی $E[\bar{X}] = \mu$.
</div>
<br>

**54. Central Limit Theorem ― Let us have a random sample X1,...,Xn following a given distribution with mean μ and variance σ2, then we have:**
<div dir="rtl">
قضیه‌ی حد مرکزی - یک نمونه‌ی تصادفی $\{X_1, \dots, X_n \}$ که از یک توزیع با میانگین $\mu$ و واریانس $\sigma^2$ به دست آمده‌اند را در نظر بگیرید؛ داریم:
</div>
<br>

**55. Estimating the variance**
<div dir="rtl">
تخمین واریانس
</div>
<br>

**56. Sample variance ― The sample variance of a random sample is used to estimate the true variance σ2 of a distribution, is often noted s2 or ^σ2 and is defined as follows:**
<div dir="rtl">
واریانس نمونه - واریانس نمونه‌ی یک نمونه‌ی تصادفی که برای تخمین مقدار واقعی واریانس $\sigma^2$ یک توزیع به کار می‌رود، معمولاً با $\s^2$ یا $\hat{\sigma}^2$ نمایش داده می‌شود و به صورت زیر تعریف می‌شود:
</div>
<br>

**57. Remark: the sample variance is unbiased, i.e E[s2]=σ2.**
<div dir="rtl">
نکته: واریانس نمونه بدون پیش‌قدر است، یعنی $E[s^2] = \sigma^2$.
</div>
<br>

**58. Chi-Squared relation with sample variance ― Let s2 be the sample variance of a random sample. We have:**
<div dir="rtl">
رابطه‌ی $\chi^2$ با واریانس نمونه - فرض کنید $s^2$ واریانس نمونه‌ی یک نمونه‌ی تصادفی باشد. داریم:
</div>
<br>

**59. [Introduction, Sample space, Event, Permutation]**
<div dir="rtl">
[معرفی، فضای نمونه، رخداد، جایگشت]
</div>
<br>

**60. [Conditional probability, Bayes' rule, Independence]**
<div dir="rtl">
[احتمال شرطی، قضیه‌ی بیز، استقلال]
</div>
<br>

**61. [Random variables, Definitions, Expectation, Variance]**
<div dir="rtl">
[متغیرهای تصادفی، تعاریف، امید ریاضی، واریانس]
</div>
<br>

**62. [Probability distributions, Chebyshev's inequality, Main distributions]**
<div dir="rtl">
[توزیع‌های احتمالی، نابرابری چبیشف، توزیع‌های اصلی]
</div>
<br>

**63. [Jointly distributed random variables, Density, Covariance, Correlation]**
<div dir="rtl">
[متغیرهای تصادفی با توزیع مشترک، چگالی، کواریانس، هم‌بستگی]
</div>
<br>

**64. [Parameter estimation, Mean, Variance]**
<div dir="rtl">
[تخمین عامل، میانگین، واریانس]
</div>

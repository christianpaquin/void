Copy-pasted:
* 𝑎 ∈ 𝐴 Indicates that element 𝑎 is in set 𝐴. If 𝑎 is a list, then all its elements are in 𝐴.
* 𝐴 ⊆ 𝐵 Indicates that the set 𝐴 is a subset of or equal to set 𝐵.
* 𝐴 ∪ 𝐵 The union of the sets 𝐴 and 𝐵.
* 𝐴 − 𝐵 When 𝐴 and 𝐵 are sets, this represents the set of elements present in 𝐴 but not in 𝐵.
* {0,1}∗ The set of all octet strings with a minimum length of 0 (the empty string) up to a maximum length of 2^32 − 1.
* {0, 1, … , 𝑛,𝑡} A set of index values from 0 to 𝑛, plus a special last value labeled 𝑡. The number 𝑛 could be 0, in which case the set is equal to {0,𝑡}. In an implementation, it is safe to assume that 𝑡 = 𝑛 + 1.
* ℤ𝑞 The set of integers modulo 𝑞, i.e., {0, 1, … , 𝑞 − 1}. In this document, 𝑞 is always a large prime number.
* ℤ𝑞∗ The multiplicative subgroup of ℤ𝑞. For a prime number 𝑞 this is {1, … , 𝑞 − 1}.
* 𝐺𝑞 An algebraic group of prime order 𝑞. This document defines two group constructions: one based on a subgroup of a finite field and one based on 
elliptic curves over a prime field, see Section 2.1. For uniformity, the multiplicative notation of the subgroup construction is used throughout; as such, 
when using the elliptic curve construction it should be understood that 𝑎𝑏 represents the group addition of points 𝑎 and 𝑏, and that 𝑎𝑏 represents the  scalar multiplication of point 𝑎 by the integer 𝑏.
* Ø The null value, a zero-length octet string.
* 0x Prefix of a hexadecimal value. For example, 0x39c3 represents the two octet values 39 and c3 in sequence.
* 𝑎𝑏 Group operation of elements 𝑎 and 𝑏.
* 𝑎^−𝑏 If 𝑏 = 1, then this represents the group inverse of element 𝑎. If 𝑏 > 1, this is equivalent to (𝑎𝑏)−1. In this document, this operation is always performed in 𝐺𝑞 or in ℤ𝑞.
* 𝑎 ∶= 𝑏 Assign value 𝑏 to element 𝑎.
* 𝑎||𝑏 The binary concatenation of 𝑎 and 𝑏.
* ℋ(… ) Hash the input data represented by the ellipsis in a fixed order, see Section 2.2 for hash input formatting.
* ℋ(… ) → ℤ𝑞 Transform the outcome of a hash operation into an element of ℤ𝑞, see Section 2.2.
* ∏𝑖∈𝐼 𝑎𝑖 Multiply all the values 𝑎𝑖 for which 𝑖 ∈ 𝐼.

LaTeX:
* $a \in A$ Indicates that element $a$ is in set $A$. If $a$ is a list, then all its elements are in $A$.
* $A \subseteq B$ Indicates that the set $A$ is a subset of or equal to set $B$.
* $A \cup B$ The union of the sets $A$ and $B$.
* $𝐴 − 𝐵$ When $A$ and $B$ are sets, this represents the set of elements present in $A$ but not in $B$.
* $\{0,1\}^∗$ The set of all octet strings with a minimum length of 0 (the empty string) up to a maximum length of $2^32 − 1$.
* $\{0, 1, ..., n,t\}$ A set of index values from 0 to $n$, plus a special last value labeled $t$. The number $n$ could be 0, in which case the set is equal to $\{0,t\}$. In an implementation, it is safe to assume that $t = n + 1$.
* $\Z_q$ The set of integers modulo 𝑞, i.e., $\{0, 1, ... , q − 1\}$. In this document, $q$ is always a large prime number.
* $\Z_q^*$ The multiplicative subgroup of $\Z_q$. For a prime number $q$ this is $\{1, ..., q − 1\}$.
* $𝐺_𝑞$ An algebraic group of prime order $q$. This document defines two group constructions: one based on a subgroup of a finite field and one based on 
elliptic curves over a prime field, see Section 2.1. For uniformity, the multiplicative notation of the subgroup construction is used throughout; as such, 
when using the elliptic curve construction it should be understood that $ab$ represents the group addition of points $a$ and $b$, and that $ab$ represents the  scalar multiplication of point $a$ by the integer $b$.
* $\emptyset$ The null value, a zero-length octet string.
* $\texttt{0x}$ Prefix of a hexadecimal value. For example, 0x39c3 represents the two octet values 39 and c3 in sequence.
* $ab$ Group operation of elements $a$ and $b$. 
* $a^−b$ If $b=1$, then this represents the group inverse of element $a$. If $b>1$, this is equivalent to $(ab)^-1$. In this document, this operation is always performed in $𝐺_𝑞$ or in $\Z_q$.
* $a := b$ Assign value $b$ to element $a$.
* $a||b$ The binary concatenation of $a$ and $b$.
* $\mathcal{H}(...)$ Hash the input data represented by the ellipsis in a fixed order, see Section 2.2 for hash input formatting.
* $\mathcal{H}(...) \rightarrow \Z_q$ Transform the outcome of a hash operation into an element of $Z_q$, see Section 2.2.
* $\prod_{i \in I}a_i$ Multiply all the values $a_i$ for which $i \in I$.


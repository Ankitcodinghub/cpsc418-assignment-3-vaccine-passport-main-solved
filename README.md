# cpsc418-assignment-3-vaccine-passport-main-solved
**TO GET THIS SOLUTION VISIT:** [CPSC418 Assignment 3-Vaccine_Passport-main Solved](https://www.ankitcodinghub.com/product/cpsc418-assignment-3-vaccine_passport-main-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92291&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CPSC418 Assignment 3-Vaccine_Passport-main Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Problem 1 — A modified variant of the Diffie-Hellman protocol

Consider the following modification of the Diffie-Hellman protocol.

Set-up:

<ul>
<li>􏰈 &nbsp;All participants agree on a public prime p and a primitive root of p.</li>
<li>􏰈 &nbsp;Each participant generates their own random exponent ui with 1 &lt; ui &lt; p − 1 and computes
Ui ≡ gui (mod p).

The public parameters g,p as well as the numbers Ui are stored in a public database. Each

participant keeps their exponent ui secret.

Suppose Alice and Bob wish to establish on a shared cryptographic key. Denote Alice’s database

entry by X ≡ gx (mod p) and Bob’s database entry by Y ≡ gy (mod p). They proceed as follows: Key Agreement Protocol
</li>
</ul>
<ol>
<li>1) &nbsp;Alice generates a secret exponent a with 1 &lt; a &lt; p − 1, computes A ≡ ga (mod p) and sends A to Bob.
Bob generates a secret exponent b with 1 &lt; b &lt; p−1, computes B ≡ gb (mod p) and sends B

to Alice.
</li>
<li>2) &nbsp;Alice looks up Bob’s public database entry Y and computes K ≡ BxY a (mod p).
Bob looks up Alice’s public database entry X and computes K ≡ AyXb (mod p).
</li>
</ol>
The key shared between Alice and Bob is K. The man-in-the-middle attack on ordinary Diffie- Hellman discussed in class no longer works here as long as the database is tamper-proof (of course any attacker with the ability to hack into the database can simply replace Bob’s database entry by her own and impersonate Bob).

<ol>
<li>(2 marks) Formally prove that Alice and Bob compute the same quantity K in step 2.</li>
<li>(4 marks) Recall the Diffie-Hellman problem whose solution breaks the original Diffie-Hellman
protocol:

Givenp,g,A≡ga (modp)andB≡gb (modp),computegab (modp).

Suppose Eve is able to solve the Diffie-Hellman problem efficiently for any inputs p, g, A and B. Explain how she can use this capability when eavesdropping on Alice and Bob to find any key generated by Alice and Bob using the modified Diffie-Hellman protocol described above.1
</li>
</ol>
1You may not assume here that Eve has the capability of extracting discrete logarithms; this is a stronger assumption. Remember that an algorithm for solving the discrete logarithm problem solves the Diffie-Hellman problem, and it is easy to see that it also makes finding keys for this variant very simple. But the reverse direction is unknown; that is, it is unknown whether anyone with the capability of discovering Diffie-Hellman keys or keys for this modified variant can use this ability to compute discrete logarithms.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Problem 2 — Properties of cryptographic hash functions

Recall the two properties of collision resistance and pre-image resistance that a cryptographic hash function needs to satisfy. In class, we asserted that these properties do not imply each other. This problem introduces two hash functions that confirm this fact; one is pre-image resistant but not collision resistant, the other is collision resistant but not pre-image resistant.

a. Let h : {0, 1}∗ → {0, 1}n be a pre-image resistant hash function. Define a new hash function H : {0, 1}∗ → {0, 1}n via

H(M) = h(M′) ,

where M ′ ∈ {0, 1}∗ is the bit string obtained by replacing the last bit of M by 0. That is, if thelastbitofM is0,thenM′ =M,whereasifthelastbitofM is1,thenM′ agreeswithM except for the last but which is changed from 1 in M to 0 in M′.

<ol>
<li>(i) &nbsp;(4 marks) Formally prove that H is pre-image resistant.

Hint: Proof by contradiction works nicely here. Specifically, prove that if you can find a pre-image of some x ∈ {0, 1}n under H , then you can also find a pre-image of x ∈ {0, 1}n under h, contradicting the pre-image resistance of h. Also, don’t overthink this; this is a really easy problem.</li>
<li>(ii) &nbsp;(2 marks) Prove that H is not collision resistant by exhibiting an explicit example of a collision for H. Explain your example.</li>
</ol>
b. Let h : {0, 1}∗ → {0, 1}n be a collision resistant hash function. Define a new hash function H : {0, 1}∗ → {0, 1}n+1 via

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰇1∥0n

begins with a 1, followed by n 0’s.

<ol>
<li>(i) &nbsp;(4 marks) Formally prove that H is collision resistant. Hint: Go with proof by contra- diction again. Specifically, prove that if you can find a collision for H, then you can also a collision for h, contradicting the collision resistance of h.</li>
<li>(ii) &nbsp;(2 marks) Prove that H is not pre-image resistant by exhibiting an explicit example of a string x ∈ {0,1}n+1 for which it is easy to find a pre-image under H. Explain your example.</li>
</ol>
Problem 3 — CFB-MAC

Consider a block cipher whose plaintexts and ciphertexts are bit strings of length n ∈ N, where encryption using a key K is denoted by EK. Recall the the message authentication code CBC- MAC, where the MAC of a message M is the last ciphertext block when encrypting M using CBC mode:

CBC-MAC

1) Pad M with zeros so the length of the padded string is a multiple of the block length n. 2) Split the padded string into L blocks M1, M2, . . . , ML where each block Mi has length n.

</div>
</div>
<div class="layoutArea">
<div class="column">
if M = 0,

,

otherwise,

where, as usual, “∥” denotes string concatenation and 1∥0n is the string of length n + 1 that

</div>
</div>
<div class="layoutArea">
<div class="column">
H(M) =

0∥h(M )

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
3) Put C0 = 0n (the string of n zeros).

4) For 1 ≤ i ≤ L, compute Ci = EK(Mi ⊕ Ci−1). 5) CBC-MAC(M) = CL.

Similarly, define a message authentication code CFB-MAC based on using the same block cipher in CFB mode:2

CFB-MAC

1) Pad M with zeros so the length of the padded string is a multiple of the block length n. 2) Split the padded string into L blocks M1, M2, . . . , ML where each block Mi has length n. 3) Put C0′ = M1 (the first message block)

4) For 1 ≤ i ≤ L − 1, compute Ci′ = Mi+1 ⊕ EK(Ci′−1).

5) CFB-MAC(M) = EK(CL′ −1).

Now Let M be any message, K a key, Ci (1 ≤ i ≤ L) the sequence of ciphertext blocks obtained when computing CBC-MAC(M ) and Ci′ (1 ≤ i ≤ L − 1) the sequence of ciphertext blocks obtained when computing CFB-MAC(M).

a. (4marks)UseinductiononitoprovethatCi =Ci′⊕Mi+1 for0≤i≤L−1. b. (2 marks) Prove that CBC-MAC(M) =CFB-MAC(M).

Problem 4 — A variant of RSA (10 marks)

Let a, b be integers that are not both zero. The least common multiple of a, b, denoted lcm(a, b), is the unique positive integer satisfying the following properties:

(A) a divides lcm(a, b) and b divides lcm(a, b).

(B) If L is an integer such that a divides L and b divides L, then lcm(a, b) divides L.

You may use without proof the fact that the integer lcm(a, b) is unique for any a, b and satisfies gcd(a, b) · lcm(a, b) = ab .

Now consider the following variant of RSA in which the quantity φ(n) = (p − 1)(q − 1) in the key generation procedure is replaced by lcm(p − 1, q − 1).

Set-up: In order to generate their public/private key pair, each user does the following.

1) Generates two large distinct primes p, q.

2) Computesn=pqandl=lcm(p−1,q−1).

3) Selects an element e ∈ Z∗l .

4) Solves the congruence ed ≡ 1 (mod l) for d ∈ Z∗l .

The user’s public and private keys are (e, n) and d, respectively.

Encryption and decryption proceed exactly as in ordinary RSA. That is, plaintexts and ciphertexts are elements in Z∗n, the encryption of a plaintext M ∈ Z∗n is C ≡ Me (mod n), and the decryption ofaciphertextC∈Z∗n isM≡Cd (modn).

2CFB-MAC can be defined more generally with any intitial value C0′ , in which case it differs from CBC-MAC. But for this problem, we specifically pick C0′ = M1.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
<ol>
<li>(6 marks) Formally prove that this variant of RSA works. Specifically, prove that (Me)d ≡ M (mod n)
for all M ∈ Z∗n.
</li>
<li>(4marks)Supposepandqaresafeprimes,sop=2p′+1andq=2q′+1withprimesp′,q′. Formally prove how an attacker who knows n and l = lcm(p − 1, q − 1) can find factor n, i.e. find p and q.</li>
</ol>
Problem 5 — A probabilistic encryption scheme (28 marks)

In this problem, you will investigate a homomorphic probabilistic public key cryptosystem. Set-up: In order to generate their public/private key pair, each user does the following.

<ol>
<li>1) &nbsp;Generates two large distinct primes p, q such that p does not divide q − 1 and q does not divide p − 1;</li>
<li>2) &nbsp;Computesn=pqandφ(n)=(p−1)(q−1).</li>
</ol>
The user’s public and private keys are n and φ(n), respectively. The user also precomputes the

modular inverse of φ(n) modulo n, i.e. the element f ∈ Z∗n such that fφ(n) ≡ 1 (mod n) .

Plaintexts are elements in Zn and ciphertexts are elements in the set

Zn∗2 ={a∈Z|0≤a&lt;n2 and gcd(a,n2)=1}.

Encryption: To encrypt a plaintext M ∈ Zn, the sender does the following. 1) Generates a random element r ∈ Z∗n2 .

2) Computes and sends the ciphertext C ≡ (n + 1)M rn (mod n2). Decryption: To decrypt a ciphertext C ∈ Z∗n2 , the receiver does the following.

<ol>
<li>1) &nbsp;Computes a ≡ Cφ(n) (mod n2).</li>
<li>2) &nbsp;Computes the integer b = (a − 1)/n.</li>
<li>3) &nbsp;Computes the plaintext M ≡ bf (mod n).</li>
</ol>
a. In this part, you will prove some mathematical preliminaries that are required for the proof that this cryptosystem works.

<ol>
<li>(i) &nbsp;(2 marks) Using the properties of Euler’s phi function covered in class, prove that φ(n2) = nφ(n).</li>
<li>(ii) &nbsp;(3 marks) Prove that gcd(n, φ(n)) = 1. This establishes that φ(n) has an inverse modulo n, so the quantity f defined above exists.</li>
<li>(iii) &nbsp;(2 marks) Prove that the number b in step 2 of the decryption procedure is an integer.</li>
<li>(iv) &nbsp;(3 marks) Prove that (n + 1)k ≡ kn + 1 (mod n2) for all positive integers k.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
b. (6 marks) Prove correctness of this cryptosystem. Specifically, prove that if C is the encryption of any plaintext M ∈ Zn, obtained via the encryption procedure above, then applying the decryption procedure above to C yields M.

c. (3 marks) For any plaintext M ∈ Zn, denote by E(M, r) the encryption of M under public key n using the random number r for encryption. Prove that for any two plaintexts M1, M2 ∈ Zn, any elements r1, r2 ∈ Z∗n, and any positive integer k, we have

E(M1, r1) · E(M2, r2) = E(M1 + M2, r1r2) and E(M1, r1)k = E(kM1, r1k) .

In other words, if we apply decryption to the above identities, we see that decrypting a product of two encryptions yields the sum of the plaintexts, and decrypting a power of an encryption yields the corresponding multiple of the plaintext.3

<ol start="4">
<li>Consider the following chosen ciphertext attack on the above system where an attacker wishes to obtain the decryption M of a ciphertext C and proceeds as follows.
<ol>
<li>1) &nbsp;Generates r ∈ Z∗n2 with rn ̸≡ 1 (mod n2).</li>
<li>2) &nbsp;Computes C′ ≡ Crn (mod n2) (this is the chosen ciphertext).</li>
<li>3) &nbsp;Obtains the decrytion M′ of C′.</li>
</ol>
<ol>
<li>(i) &nbsp;(2 marks) Prove that C′ ̸= C, so C′ is a valid choice of ciphertext to get decrypted in step 3.</li>
<li>(ii) &nbsp;(3 marks) Prove that M′ = M. In other words, the decryption obtained in step 3 of the CCA is precisely the plaintext that the attacker is after, and thus the attack is successful.</li>
</ol>
</li>
<li>(4 marks) An element z ∈ Z∗n2 is an n-th power residue modulo n2 if and only if there exists an element x ∈ Zn2 such that xn ≡ z (mod n2). Prove that a ciphertext C is the encryption of the plaintext M = 0 if and only if C is an n-th power residue modulo n2. So decryption for this cryptosystem can be thought of as an “n-th power residue modulo n2 detector”.4</li>
</ol>
Written Problem for MATH 318 only

Problem 6 — An RSA-like public key cryptosystem (38 marks)

In this problem, you will investigate a public key cryptosystem that is similar to RSA but has the advantage that an adversary is able to break the system if and only if she is able to factor the modulus. The price to pay for this potential added security is the restriction on the format of plaintexts: they must have Jacobi symbol 1 with respect to n. In addition, the system is extremely vulnerable to a simple chosen ciphertext attack that does not work for RSA.

3Cryptosytems satisfying these two properties are called linearly homomorphic. The first property in particular makes this system very suitable for electronic voting, especially for yes/no elections. Every user encrypts their vote, which is 1 for “yes” and 0 for “no”, using the election administrator’s public key n. The administrator multiplies all the encrypted votes together and decrypts the product. By the first property, this decryption is the sum of all the votes, which is just the number of “yes” votes (note that the administrator need not know the random numbers used by the voters to encrypt their votes). This voting procedure preserves secrecy of individual votes and anonymity of voters. Moreover, the election administrator only needs to compute a modular product and perform one decryption, which is much more efficient than decrypting each vote individually.

4Detecting n-th power residues modulo n2 is generally believed to be computationally intractable when n is the product of two distinct large primes.

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
In part(c), we will extend the plaintext space to be all of Z∗n (like RSA), but at the additional cost of more complicated encryption and decryrption procedures as well as reduced efficiency: in addition to a modular exponentiation (like in RSA), encryption in the extended scheme requires the evaluation of a Jacobi symbol.

Set-up: In order to generate their public/private key pair, each user does the following.

1) Generatestwolargeprimespandqwithp≡3(mod4)andq≡3(mod4). 2) Computes n = pq and f = φ(n)/4.

3) Selectse∈Zwith1&lt;e&lt;f andgcd(2e,f)=1

4) Solvesthecongruence2ed≡1 modf ford∈Z,1≤d&lt;f.

The user’s public and private keys are (e, n) and d, respectively. Here, as always, φ() denotes the Euler phi function.

∗ 􏰅M􏰆

The plaintext space is the set of all M ∈ Zn such than n = 1. Encryption of such a plaintext

M with public key (e, n) is given by

C≡M2e (modn). Decryption of a ciphertext C is given as

M ≡ Cd (mod n) .

Unfortunately, the 2 in the encryption exponent introduces the same abiguity as squaring of or- dinary integers. Specifically, it makes it impossible to distinguish M from n − M (which is just −M (mod n)) after decryption. Now that one way to distinguish these two numbers is by their parity: one of them is odd and the other is even (since n is odd). So the encrypter simply needs to send the parity bit distinguishing M from n−M, along with the ciphertext. Specifically, encryption and decryption proceed as follows:

Encryption: To encrypt a plaintext M ∈ Z∗ with 􏰃M􏰄 = 1, the sender does the following. nn

1) IfM iseven,putb=0,elseputb=1. 2) Compute C ≡ M2e (mod n).

3) Send (C, b).

Decryption: To decrypt a pair (C, b) , the receiver does the following. 1) Compute M′ ≡ Cd (mod n).

2) IfM′ isevenandb=0orM′ isoddandb=1,putM=M′,elseputM=n−M′. Remark: The restrictions 􏰃M􏰄 = 1 and p ≡ q ≡ 3 (mod 4) ensure the condition

n

􏰅M 􏰆(q−1)/2 􏰅M 􏰆(p−1)/2

p =q (1)

for all M ∈ Z∗n which is crucial for this cryptosystem to work; you will use this in part (a) (iii). a. (Correctness, 14 marks)

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
<ol>
<li>(i) &nbsp;(2 marks) Prove that (p − 1)/2 and (q − 1)/2 are odd.</li>
<li>(ii) &nbsp;(3 marks) Prove that 􏰃M􏰄 = 􏰃M􏰄 for all M ∈ Z∗. Then use part (a) (i) to conclude that</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
pqn

</div>
</div>
<div class="layoutArea">
<div class="column">
property (1) above holds.

(iii) (4marks)ProvethatMf ≡±1(modn)forallM∈Z∗ with􏰃M􏰄=1.

</div>
</div>
<div class="layoutArea">
<div class="column">
Hint: Specifically, prove M f ≡ e (mod n) where e = 􏰃M 􏰄(q−1)/2 = 􏰃M 􏰄(p−1)/2 pq

</div>
</div>
<div class="layoutArea">
<div class="column">
is the (iv) (5 marks) Use part (a) (iii) to prove correctness of this cryptosystem. Specifically, prove

</div>
</div>
<div class="layoutArea">
<div class="column">
quantity in (1).

that if C is the encryption of any plaintext M ∈ Zn∗ with 􏰃M􏰄 = 1, obtained via the

</div>
</div>
<div class="layoutArea">
<div class="column">
n

encryption procedure above, then applying the decryption procedure above to C yields M.

b. (Security, 12 marks)

Just as for RSA, it is evident that if an attacker can factor n, i.e. find the primes p and q, she can proceed as the designer and compute f and the private key d, thereby breaking the scheme. In this part, you will prove the “converse”: if an attacker can break the scheme via a successful chosen ciphertext attack, she can factor n.

Consider the following chosen ciphertext attack on the above system where an attacker at- tempts to factor n.

∗ 􏰅y􏰆

<ol>
<li>1) &nbsp;Choosesanyy∈Zn suchthat n =−1.</li>
<li>2) &nbsp;Computes C ≡ y2 (mod n) (this is the chosen ciphertext).</li>
<li>3) &nbsp;Obtains the decryption M of C.</li>
<li>4) &nbsp;Computes x ≡ Me (mod n).</li>
<li>5) &nbsp;Computes gcd(x − y, n).
􏰅−1􏰆
</li>
</ol>
<ol>
<li>(i) &nbsp;(2 marks) Prove that n = 1.
􏰅M􏰆
</li>
<li>(ii) &nbsp;(2marks)Provethat n =1andhence n =1,withM asgiveninstep3andx
as in step 4 of the CCA.
</li>
<li>(iii) &nbsp;(2 marks) Prove that x2 ≡ y2 (mod n).</li>
<li>(iv) &nbsp;(3 marks) Use parts (b) (i)-(ii) to prove that x ̸≡ y (mod n) and x ̸≡ −y (mod n).</li>
</ol>
􏰅x􏰆 􏰅y􏰆 􏰅−y􏰆

Hint: Compare n with n and n .

(v) (3 marks) Finally, the grand finale: use parts (b) (ii)-(iv) to prove that gcd(x − y, n) = p

or q, so the attack above factors n.

c. (Expanding the plaintext space to all of Z∗n, 12 marks)

The idea behind this part is to choose the primes p and q such that for any M ∈ Z∗n, if 􏰃M􏰄 = −1 (so M is not a valid plaintext) then 􏰃2M􏰄 = 1 (so 2M (mod n) is a valid plaintext).

In addition to sending along a parity bit, the encrypter then also needs to send another bit indicating whether 􏰃M􏰄 = −1 (in which case 2M is encrypted instead of M). You will prove

n

in part (c) (ii) that an appropriate choice is

p ≡ 3 (mod 8) , q ≡ 7 (mod 8) ,

</div>
</div>
<div class="layoutArea">
<div class="column">
nn

</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰅x􏰆

</div>
</div>
<div class="layoutArea">
<div class="column">
nn

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
so we assume these congruence conditions from here on.

Consider the following modified encryption procedure, where the plaintext space is now all

of Z∗n:

Encryption: to encrypt a plaintext M ∈ Z∗n, proceed as follows.

1) Compute 􏰃M􏰄. n

2) If􏰃M􏰄=1,putM0 =M andb0 =0,elseputM0 ≡2M (modn)andb0 =1. n

</div>
</div>
<div class="layoutArea">
<div class="column">
3) IfM0 iseven,putb1 =0,elseputb1 =1. 2) Compute C ≡ M2e (mod n).

</div>
</div>
<div class="layoutArea">
<div class="column">
0 3) Send(C,b0,b1).

</div>
</div>
<div class="layoutArea">
<div class="column">
Decryption: to decrypt a triple (C, b0, b1), proceed as follows.

1) Compute L ≡ Cd (mod n).

2) IfLisevenandb1 =0orLisoddandb1 =1,putL0 =L,elseputL0 =n−L.

3) If b0 = 0, put M = L0, else put M ≡ n+1L0 (mod n) 2

Note that the quantity (n + 1)/2 in step 3 of decryption is simply the inverse of 2 modulo n as 1 ≤ (n + 1)/2 &lt; n and 2 · (n + 1)/2 = n + 1 ≡ 1 (mod n).

􏰅2􏰆

<ol>
<li>(i) &nbsp;(3 marks) Prove that n = −1.
Remark: This shows that y = 2 is a valid choice in step 1 of the CCA above.
</li>
<li>(ii) &nbsp;(2 marks) Prove that 􏰃M0􏰄 = 1, with M0 as in step 2 of the modified encryption proce-
n

dure.
</li>
<li>(iii) &nbsp;(4 marks) Prove that L0 = M0, with L as in step 2 of decryption and M0 as in step 2 of decryption.</li>
<li>(iv) &nbsp;(3 marks) Use part (c) (iii) to prove correctness of this modified version of this cryptosys- tem. Specifically, prove that if C is the encryption of any plaintext M ∈ Zn∗, obtained via the modified encryption procedure above, then applying the modified decryption procedure above to C yields M.</li>
</ol>
The scheme in thus problem is known as the Rabin-Williams cryptosystem, after its inventors. In 1979, Michael Rabin introduced the idea of squaring in the context of a signature scheme, which an adversary can break, i.e. forge signatures via a chosen message attack, if and only if she can factor the modulus. In 1980, Hugh C. Williams, who is a former math professor at U Calgary (and long retired by now) proposed the public key cryptosystem above which merges Rabin’s squaring approach with RSA.

Programming Problem for CPSC 418 only Problem 7 — Vaccine Passports (38 marks)

Don’t be daunted by the long description of this problem! Most of it is very clear specifications, including those for the autograder, to make your life easier.

</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
Overview. It’s currently August 15th, 2006. More than three years ago, SARS managed to escape from Scarborough Grace Hospital in Ontario, mutate to become more virulent, and establish widespread community spread across the globe. Governments have engaged in a rollercoaster of lockdowns and “opening up” ever since, with tens of millions of deaths. They’ve also thrown as much funding as they can at developing a vaccine, and the resulting flurry of development created one in just less than three years, a new record. As of June 11th, 2006, Ontario residents could get a SARS-COV-1 vaccine shot and 80% of the province has done so. So it was a bit of a shock when Ontario Health told your team the province was heading into a new health crisis. Politicians and the media have over-hyped the vaccine as a silver bullet, ignoring that it has only a 70% effective rate after two weeks and that the latest research suggests that effectiveness rapidly dwindles after a year. That’s not enough to achieve herd immunity. Worse, the public has no appetite to return to the lockdown rollercoaster, and there is increasing levels of violence at anti-vaccine protests. Add in the oncoming Fall semester of school, and there’s potential for the health system to be completely overrun.

They and other civil servants have come up with a compromise: vaccine passports. Society will be split in two, with the vaccinated enjoying more freedom to move thanks to their immunity while those who refuse to vaccinate are isolated to prevent more mass casualties. The length of time since the last shot needs to be tracked, to deal with the issue of waneing immunity. Naturally, these passports need to be both tamper-resistent and convenient to use.

Your team has come up with a suitable system, based around a cutting-edge technology from Japan called a “QR code”. Encryption will be used to obfuscate the details stored in these codes, a MAC guards against data corruption, and a combination of a digital signature and keyed MAC provide authenticity. Your job is to create the first implementation of this system, with code that will be used in web browsers, portable hand scanners, and a web server.5

Passport Format. Like the first assignment, the data portion can be divided into three segments: the plaintext, the nonce, and a tag.

The plaintext is 96 bytes long. The upper four bits of the first byte contain the number of vaccines this person has had. Values greater than 15 are capped at 15. The lower four bits of the first byte are the upper portion of a 12 bit number, the lower eight bytes being contained in the second byte of the cyphertext. This value represents the week the person had their last vaccine shot, measured in weeks since June 11th, 2006.6 Any value greater than 4,095 is capped at 4,095. If the person hasn’t had a vaccine shot, this value is set to 4,095.

The next two bytes represent the birthdate of the person, measured in days since January 1st, 1880. This is in big endian format, and capped to 65,535 days.

The next 92 bytes represent the given name and surname, stored in that order. For maximum flexibility, both of them are contained in the same field, so that short names can make room for longer ones. To specify where the surname starts, the first byte of the text section (or the fifth byte of the overall plaintext) contains the byte index to its location, relative to the start of the text portion (not the plaintext, and excluding the index byte; see the diagram). The characters are encoded in UTF-8. If the combined length of both names is less than 91 bytes after encoding, the encoder picks a random but valid index for the surname and pads any excess space with zero byte characters. If the combined length is greater than 91 then characters are iteratively removed from the longest of the two names until their combined UTF-8 encoded size is 91 bytes or less; in

5This is a greatly simplified variation of the system currently used by many Canadian provinces. 6For instance, six days after that epoch is zero weeks while eight is one.

</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
the event of a tie, remove a character from the surname.

vax date (upper)

</div>
</div>
<div class="layoutArea">
<div class="column">
vax date birth date surname given name offset 0 1 2 3 4 5 6

</div>
</div>
<div class="layoutArea">
<div class="column">
surname index

</div>
<div class="column">
0 1

</div>
<div class="column">
surname index

</div>
<div class="column">
+1 +2

</div>
</div>
<div class="layoutArea">
<div class="column">
# of

vaccines (lower) index …

</div>
<div class="column">
surname

…

</div>
<div class="column">
95 90

</div>
</div>
<div class="layoutArea">
<div class="column">
The nonce is 16 bytes long. It has the same role as the initialization vector from the first assignment, though it is used quite differently. The tag is 16 bytes long, and is defined as

H (P (”OH SARS SECOND VERIFY”)||P (hash key)||nonce||plaintext||0x10), where H () is SHAKE256 with a digest size of 16 bytes and P() appends zero bytes to the input until the resulting output is

a multiple of 136 bytes (or appending nothing if it already is a multiple).7

Encryption is done slightly differently than Assignment 1. All three segments of the data are divided into eight blocks. The first tag block is appended to the first plaintext block, and the combination appended to the nonce block. This is repeated, resulting in eight blocks that each consist of a mix of nonce, plaintext, and tag. Each block is encrypted with AES-256 using enc key.8

After encryption, H(nonce||plaintext||tag) is calculated and appended to the cyphertext, result- ing in a 159 byte9 sequence.10

</div>
</div>
<div class="layoutArea">
<div class="column">
block 0 1 7 8-9

</div>
</div>
<div class="layoutArea">
<div class="column">
nonce

2,3

</div>
<div class="column">
plaintext

</div>
<div class="column">
tag

</div>
<div class="column">
… nonce 14,15

AES

</div>
<div class="column">
plaintext tag

</div>
</div>
<div class="layoutArea">
<div class="column">
nonce plaintext

byte index 0,1 0-11 (per section)

AES

output

Signature. The passport itself contains little sensitive data. It is meant to be presented to someone with a scanner along with a piece of government-issued ID; the person scans the QR code, decrypts it, and verifies the name and birthdate match those of the ID. Rather than protect data from unauthorized viewing, this system is primarily designed to be extremely difficult to forge.

Symmetric encryption can only provide this via a trusted third party, which cannot be guaranteed when anyone can hold a scanner that may not have cellular access (let alone internet access). Instead, the 159 byte sequence is signed with an RSA keypair (NRSA,d) that is kept private, resulting in the 319 bytes contained within the QR code. The public keypair (NRSA,e) is shared to anyone who requests it, and embedded within each scanner. This allows anyone to verify the passport was almost certainly generated by an approved device and is therefore authentic.

Communication. There is an additional security concern. To request your vaccine passport in as convenient a form as possible, people will be allowed to request one via a web form by supplying their Ontario Health Number, birthdate, and when they had their last vaccine shot. This opens up

7This algorithm is based on KMAC, which implies the ”0x10” portion is the length of the digest encoded as a single byte. It is worth thinking about how KMAC relates to HMAC.

8Aside: we’ve discouraged the use of ECB encoding in class, yet invoked it here. Try to figure out why we’re not hypocritical about this.

9This is not a typo, the just-mentioned SHAKE256 tag is 31 bytes long instead of 32.

10This approach is considered inferior to what was done in Assignment 1, incidentally. See Bellare (2008).

</div>
</div>
<div class="layoutArea">
<div class="column">
tag

0,1

</div>
<div class="column">
12-23 2,3

AES

</div>
<div class="column">
84-95

AES

</div>
<div class="column">
14,15

</div>
</div>
<div class="layoutArea">
<div class="column">
MAC

</div>
</div>
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
two attack vectors, the most obvious of which is a person-in-the-middle attack to link a person’s name, birthdate, and OHN for identity theft.

A more subtle one involves brute force. An OHN consists of ten digits, and yet the population of Ontario is approximately 12,200,000. As a result, the odds of guessing a valid OHN are no lower than one in a thousand. As everyone rushed to get a vaccine once it was available, guessing the date someone received a vaccine shot is easier than it otherwise would be. The demographics of Ontario are well known. In sum, an attacker can simply flood the passport website with requests in the hope that they guess correctly, at which point they have a name, birthdate, and OHN.

To combat those attacks, you’ll use the security protocol introduced in Assignment 2. It is a toy version of Transport Layer Security (TLS), used to negotiate a shared secret to protect against person-in-the-middle attacks. A proof-of-work system was added to discourage request flooding.

Implementation. There are three main components to this system: the QR code server, which issues and fully verifies said codes; the scanner, which partially verifies QR codes; and the web client, which can request a QR code from the server or ask that it be verified.11 On startup, the QR code server does the following:

􏰈 Generates two RSA primes p and q of size 640-bits and computes NRSA = pq, ensuring the result is 1280 bits in size.

􏰈 Generates its own RSA key-pair (NRSA, e) and (NRSA, d).12

􏰈 Generates a 512-bit safe prime NDH as well as a primitive root g of said safe prime.

The scanner already has access to (NRSA,e), and the web client can retrieve those values from the QR code server.

Registration. The registration portion of A2 is carried forward, though some parameters have been adapted. username is now uuid, and password is now secret; both of these are now computer- generated and fixed at 32 bytes in length, but otherwise have the same behaviour.13

Protocol. Initiate the protocol from Assignment 2, but with the following modifications:

􏰈 Instead of the Client sending A as plaintext, they will send Enc(A), the RSA encryption of A under the Server’s public key.14

<ul>
<li>􏰈 &nbsp;Upon receiving Enc(A) the server must decrypt to obtain A.</li>
<li>􏰈 &nbsp;In case you did not implement the following check in Assignment 2: the server should ensure
that the value A is not congruent to 0 under the SRP modulus and abort otherwise (it may

be fun to think about why).
</li>
<li>􏰈 &nbsp;The remainder of the protocol proceeds as in Assignment 2 (derive the shared key and verify).</li>
<li>􏰈 &nbsp;With the shared key derived, the web client appends the OHN as a five byte number, three
zero bytes, birthdate (days since January 1st, 1880, as two bytes), four zero bytes, and a date

11As hash key is stored exclusively on the server, the scanner cannot verify the tag. This is by design.

12In a real implementation, these values would be loaded from read-only storage instead of recalculated, as otherwise vaccine passwords would become invalid after a server reset.

13This does make the single byte representing the length of the username redundant. Rather than force you to rewrite the registration functions with this byte removed, we’ll instead keep the byte so no alterations are required.

14This is not the ideal way to do this, for instance consider the case where a client sends a vaccine passport signature instead of Enc(A). Using separate keys for encryption and signing would add significant runtime without teaching you anything new, however, and the TAs can’t come up with an exploit that depends on RSA key reuse.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
12

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
of vaccination (days since June 11th, 2006, as two bytes) in that order.15 The client encrypts that via AES-256 and uses the following 32 byte value as the key.

H(P(”OH SARS KEYEXTEND 1”)||P(NRSA||e)||Kclient||0x20) (2)

where H() is SHAKE256 with a 32 byte digest and P() is the padding function defined earlier.

<ul>
<li>􏰈 &nbsp;The server decrypts that value, converts it to a byte sequence, and splits that sequence back into its three components. It looks up those values in a database, and if they match an
existing entry the server generates the QR code value outlined above.
</li>
<li>􏰈 &nbsp;The server takes the first 32-bytes of the shared key as the encryption key, and the next 32 bytes as the key for MAC. It uses a modified version of the encryption algorithm from Assignment 1 to encrypt the QR code. It returns the length of the encrypted QR code to the
client, encoded as four big-endian bytes, then returns the actual QR code.
</li>
<li>􏰈 &nbsp;The web client decrypts the QR code and verifies it was transmitted successfully.
The Assignment 1 encryption algorithm is modified in the following way. Instead of allowing an arbitrary hash function to be used for encryption, AES-256 is invoked instead. Instead of allowing an arbitrary block ID generator, it always starts at 0 and counts upwards. The MAC is now calculated as H(P(”OH SARS QR MAC”)||P(MAC key)||IV||cyphertext||0x20) where H() is SHAKE256 with a 32 byte digest.

Problem Your task is to complete the template program vaccine passport.py

which will become your group’s proof of concept for Ontario Health. With approval, a team of programmers will take your template and use it to develop a web interface, scanner software, and the QR code server. You may pair up with one other student to write your code, if you wish, but be sure to mention your partner’s name in the README! As with Assignment 2, all messages over the socket should be echoed to standard output by both the sending and receiving party. All prior permitted and forbidden functions carry forward. For AES-256, use the implementation in the pycryptodome library.16 You are expected to implement your own versions of the RSA related functions. You may not use functions related to RSA from another library for this exercise. See the course notes for the specifics of the RSA encryption and signature schemes.

Specifications. Fill in the empty functions in the template program vaccine passport.py. Since this is built on top of previous assignments, you are permitted to import any and all functions from the reference code for the prior two. The template even explicitly imports the relevant ones for you. Once complete, you should be able to perform the full TLS handshake between the web client and the QR code server by running something like

python3 vaccine passport.py –request QR python3 vaccine passport.py –QR server python3 vaccine passport.py –quit server

You may also combine these actions with one invocation of vaccine passport.py, as with Assign- ment 2. In addition, you will be able to simulate the function of the scanner by running

15Yes, you will have to check this; otherwise, how would you know the value was correctly decoded?

16Other implementations are out there, but they either aren’t a core Python module or are not installed on the auto-grader.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
13

</div>
</div>
</div>
<div class="page" title="Page 14">
<div class="layoutArea">
<div class="column">
python3 vaccine passport.py –verify QR –hash key “” –code [HEX STRING]

where [HEX STRING] is the hexadecimal output generated by –request QR. As usual, there are additional command-line options to change key parameters from the defaults and control which actions are taken. In detail, the new functions you’ll need to fill in fall into the following categories:

a. Low-level Functions:

<ol>
<li>(i) &nbsp;RSA.modulus(. . . ), which generates p and q for the specified bit length.</li>
<li>(ii) &nbsp;RSA.keypair(. . . ), which generates e and d.</li>
<li>(iii) &nbsp;RSA.sign(. . . ) and RSA.verify(. . . ), which respectively sign a value and verify a sig- nature.</li>
<li>(iv) &nbsp;RSA.encrypt(…) and RSA.decrypt(…), which respectively encrypt and decrypt a value.</li>
<li>(v) &nbsp;encode name(…), which converts a given name and surname into a byte sequence as outlined prior.</li>
<li>(vi) &nbsp;gen plaintext(. . . ), which uses encode name(. . . ) to generate the plaintext as outlined above.</li>
<li>(vii) &nbsp;pseudoKMAC(…), a helper function which carries out the modified KMAC algorithm outlined above.</li>
<li>(viii) &nbsp;interleave data(. . . ), which interleaves the nonce, plaintext, and tag as described above.</li>
<li>(ix) &nbsp;encrypt data(. . . ) and decrypt data(. . . ), which perform the modified version of As- signment 1’s encryption algorithm as outlined above.</li>
</ol>
b. High-level Functions:

<ol>
<li>(i) &nbsp;create passport(…), which combines all of the above functions to generate a QR code.</li>
<li>(ii) &nbsp;verify passport(. . . ), which verifies the given passport and returns the decoded data.</li>
<li>(iii) &nbsp;request passport(…), which duplicates the actions the web client makes when re-
questing a passport.
</li>
<li>(iv) &nbsp;retrieve passport(. . . ), which duplicates the actions the QR code server makes when generating a QR code for the web client.</li>
</ol>
As per Assignment 2, some of your functions will need to translate between integers and byte object parameters. All numbers are again converted to bytes via network byte order. Additional details and documentation of these functions can be found in the template program found on the Piazza resources page.

Submission Submit a completed version of the template program with filename vaccine passport.py

</div>
</div>
<div class="layoutArea">
<div class="column">
14

</div>
</div>
</div>
<div class="page" title="Page 15">
<div class="layoutArea">
<div class="column">
If you’ve spread your code across multiple source files, submit all of them. The auto-grader will have copies of the reference code for A1 and A2 with the same file name, so there is no need to submit those files. Provide a description of your implementation in a separate README file in text format. Do not include the written portion of the programming problem in the PDF file containing your solutions to the written problems. Your description should include the following:

<ol>
<li>A list of files submitted that pertain to the problem and a short description of each file.</li>
<li>A list of what is implemented in the event that you are submitting a partial solution or a
statement that the problem is fully solved.
</li>
<li>A list of what is not implemented in the event that you are submitting a partial solution.</li>
<li>A list of known bugs or a statement that there are no known bugs.</li>
<li>If you worked with a partner on your answer, include their name and a one-sentence statement
that you worked with them.
</li>
</ol>
You may use the solution files from Assignments 1 and 2.

</div>
</div>
<div class="layoutArea">
<div class="column">
15

</div>
</div>
</div>

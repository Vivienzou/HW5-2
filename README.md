HW5-2
=====
Set n = 46542522303931112269894498267410070064860780094508610950702224
3989832434235392755390925153223240785026564207986842591632881027341648
1567992145162141358151, where n is an odd number. 

"Fermat's little theorem states that if p is a prime number, then for any integer a, 
the number a^p − a is an integer multiple of p. " from Wiki

Prove by contradiction, meaning assumed n is a prime number so it is not composite. Let a = 2. 
2^n = n (mod n)
2^n = nm + 2, where m is any integer
2^n will always be even number as soon as n > 0 and n is a integer. However, when m is an odd number,
nm is also an odd number, then nm + 2 is odd.
odd number doesn't equal to even number, so 2^n = nm + 2 does not exist in all situations.
contradict with the assumption, then n is not a prime number, so it is composite. 

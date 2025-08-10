# number_theory_spectral
spectral approximation of known arithmetic functions
 
 In the von_mangoldt_approx.m program, the spectral approximation of the Von-Mangoldt function Λ(n) is visualized, according to Landau's paper. Here, rho are the values of the first 50 zeros of the zeta function, Lamda_k is the Von-Mangoldt function approximated. The interval is taken between [2,50].

 In the mobfunapprox.m program, the spectral approximation of the Möbius function μ(n) is visualized, according to thε paper. Here also, rho are the values of the first 50 zeros of the zeta function, zeta_prime_rho are the values of ζ'(ρ) for the given zeros and mu_k is the Möbius function approximated. The interval is also taken between [2,50].

In the phiapprox.m program, the spectral approximation of the Euler's totient function φ(n) is visualized, according to this paper. Here also, rho are the values of the first 50 zeros of the zeta function, zeta_prime_rho are the values of ζ'(ρ) for the given zeros ρ, alpha are the values of ζ(ρ-1) for the given zeros and phi_k is the Euler's totient function approximated. The interval is also taken between [2,50].

In the lamlog.m program, the spectral approximation of the prime power indicator function Λ(n)/log(n) is visualized, according to the paper. Again, rho are the values of the first 50 zeros of the zeta function and lamlog_k is the prime power indicator function approximated. The interval is also taken between [2,50].

 In the chipapprox.m program, the spectral approximation of the prime characteristic function χ_P(n) is visualized, according to the paper. Again, rho are the values of the first 50 zeros of the zeta function , mu_k are the first five values of the Möbius function μ(n), chi_k is the prime characteristic function approximated. The interval is also taken between [2,50]. Due to computational reasons, the first five roots are being taken, in order to maximize the interval to [2,b] for \(b>50\) the logarithm log_{2}(b) must be taken as the maximal root of the interval.

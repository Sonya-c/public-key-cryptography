# Criptografía de llave pública

En los cifradores simetricos, tanto el que cifra como el que decifra usa la misma llave. Ahora, en los cifradores asimetricos las llaves son diferentes. Para ello, primero hay que establecer confianza, pues la primera comunicación no es confiable. Por eso, es necesario hacer un intercambio de llaves.  

Propiedades

- La llave pública $P_k$ sea diferente a la privada $S_k$.
- $(S_k, P_k)$ son generador con el que quiere recibir información.
- Se debe verificar la autenticidad de la llave publica.
    $$
    c, P_k \xrightarrow{x} m \\
    m = D(S_k, c)
    $$

## Temas  

- [ ] RSA
  - [x] Esquema Trapdoor RSA.  
  - [ ] Esquema de cifrado de llava pública (RSA OAEP).  
- [ ] Diffie-Hellman.  
  - [x] Protocolo de intercambio de llaves
  - [ ] Problema del logaritmo discreto.  
    - [x] Búsqeda exhaustiva.
    - [x] Paso de bebe, paso de gigante.
    - [ ] Pollard's Rho.  
    <!-- - [ ] Pohlig-Hellman.   -->
  <!-- - [ ] Problema Diffie-Hellaman Computacional.   -->
  - [x] Esquema ElGamal.  
- [x] Curvas Elípticas.  
  - [x] Sobre $\mathbf{F}_p$.  
  - [x] Curva $P256$.
  - [x] Diffi-Hellman Sobre $P256$.  
  - [x] ElGamal con curvas.

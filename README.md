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

- [ ] Esquema Trapdoor.  
  - [x] Esquema Trapdoor RSA.  
- [ ] Esquema de cifrado de llava pública (RSA OAEP).  
- [ ] Protocolo de intercambio de llaves Diffie-Hellman.  
  - [ ] Problema del logaritmo discreto.  
    - [x] Búsqeda exhaustiva.
    - [x] Paso de bebe, paso de gigante.
    - [ ] Pllard's Rho.  
    - [ ] Pohlig-Hellman.  
  - [ ] Problema Diffie-Hellaman Computacional.  
- [ ] Esquema ElGamal.  
- [ ] Curvas Elípticas.  
  - [ ] Sobre $\mathbf{R}$.  
  - [ ] Sobre $\mathbf{F}_p$.  
  - [ ] Curva $P256$.
  - [ ] Diffi-Hellman Sobre $P256$.  

## Historia  

Nace como una idea a mitada de los 70s. En 1978, Diffie.Hellaman crear el protocolo de intercambio de llaves y con el nacenel problema de logratimos discreto y diffie-hellamn computacional sobre un grupo $F^n_q$.  

```none
Ya me dio flojera pasar el resto de notas. En resumen: mucha genete loca, creando criptosistemas y esquemas locos y problemas matematicos aun mas locos. 
```

================================================================================
TEMPLATE COMPLETO — TODAS AS VARIAÇÕES DE NOTAÇÃO CIENTÍFICA NO OBSIDIAN
================================================================================

## 1. FORMA PADRÃO (matemática pura)

Inline: $a \times 10^{n}$
Bloco:

$$
a \times 10^{n}
$$

Regra: $1 \le |a| < 10$, $n$ é inteiro [web:34][web:36]

---

## 2. EXPOENTE POSITIVO (números grandes)

$3 \times 10^{8}$

$6{,}02 \times 10^{23}$

$1{,}5 \times 10^{11}$

$9{,}11 \times 10^{31}$

---

## 3. EXPOENTE NEGATIVO (números pequenos)

$1{,}6 \times 10^{-19}$

$9{,}11 \times 10^{-31}$

$6{,}67 \times 10^{-11}$

$1{,}38 \times 10^{-23}$

---

## 4. EXPOENTE ZERO

$7 \times 10^{0}$

$5 \times 10^{0} = 5$

---

## 5. VARIAÇÕES DO SÍMBOLO DE MULTIPLICAÇÃO

| Símbolo  | Código LaTeX | Exemplo                                                    |
| -------- | ------------ | ---------------------------------------------------------- |
| `\times` | `\times`     | `$3 \times 10^{8}$` → \(3 \times 10^{8}\) [web:29][web:35] |
| `\cdot`  | `\cdot`      | `$3 \cdot 10^{8}$` → \(3 \cdot 10^{8}\) [web:29]           |
| Espaço   | (nenhum)     | `$3(10^{8})$` → \(3(10^{8})\) [web:29]                     |
| `*`      | `*`          | `$3 * 10^{8}$` → \(3 * 10^{8}\) [web:29]                   |

---

## 6. FORMATO DE PROGRAMADOR (E-notation)

Inline em texto: `3E8` ou `3e8`

Em MathJax:

$3 \text{e} 8$

$3 \text{E} 8$

Usado em: programação, calculadoras, logs [web:29][web:35]

---

## 7. COM UNIDADES (física/química)

### Unidades básicas

$3 \times 10^{8}\ \mathrm{m/s}$

$1{,}6 \times 10^{-19}\ \mathrm{C}$

$6{,}626 \times 10^{-34}\ \mathrm{J \cdot s}$

### Unidades compostas

$6{,}67 \times 10^{-11}\ \mathrm{N \cdot m^2 / kg^2}$

$1{,}38 \times 10^{-23}\ \mathrm{J/K}$

$8{,}314 \times 10^{0}\ \mathrm{J/(mol \cdot K)}$

### Usando `\mathrm{}` para unidades

Sem `\mathrm{}` (errado): $3 \times 10^{8}\ m/s$

Com `\mathrm{}` (certo): $3 \times 10^{8}\ \mathrm{m/s}$ [web:25]

---

## 8. COM DECIMAIS (vírgula vs ponto)

### Padrão brasileiro (vírgula)

$3{,}14 \times 10^{2}$

$1{,}6 \times 10^{-19}$

$6{,}02 \times 10^{23}$

### Padrão americano (ponto)

$3.14 \times 10^{2}$

$1.6 \times 10^{-19}$ [web:35]

---

## 9. CONVERSÃO PARA/DE FORMA DECIMAL

### Grande → científica

$450000 = 4{,}5 \times 10^{5}$

$602000000000000000000000 = 6{,}02 \times 10^{23}$

### Pequeno → científica

$0{,}00032 = 3{,}2 \times 10^{-4}$

$0{,}00000000000000000016 = 1{,}6 \times 10^{-19}$

### Científica → decimal

$4{,}5 \times 10^{5} = 450000$

$3{,}2 \times 10^{-4} = 0{,}00032$ [web:34][web:35]

---

## 10. BLOCO COM ALINHAMENTO (equações múltiplas)

$$
\begin{aligned}
450000 &= 4{,}5 \times 10^{5} \\
0{,}00032 &= 3{,}2 \times 10^{-4} \\
602000000000000000000000 &= 6{,}02 \times 10^{23}
\end{aligned}
$$

$$
\begin{aligned}
v &= 3 \times 10^{8}\ \mathrm{m/s} \\
c &= 2{,}99792458 \times 10^{8}\ \mathrm{m/s} \\
\lambda &= 5{,}5 \times 10^{-7}\ \mathrm{m}
\end{aligned}
$$

---

## 11. OPERAÇÕES COM NOTAÇÃO CIENTÍFICA

### Multiplicação

$$
(2 \times 10^{3})(4 \times 10^{2}) = 8 \times 10^{5}
$$

$$
(3 \times 10^{4})(5 \times 10^{2}) = 15 \times 10^{6} = 1{,}5 \times 10^{7}
$$

### Divisão

$$
\frac{6 \times 10^{8}}{2 \times 10^{2}} = 3 \times 10^{6}
$$

$$
\frac{9 \times 10^{-5}}{3 \times 10^{-2}} = 3 \times 10^{-3}
$$

### Adição/Subtração (mesmo expoente)

$$
(3 \times 10^{4}) + (2 \times 10^{4}) = 5 \times 10^{4}
$$

$$
(7 \times 10^{-3}) - (4 \times 10^{-3}) = 3 \times 10^{-3}
$$

### Adição (expoentes diferentes)

$$
(3 \times 10^{4}) + (2 \times 10^{3}) = 3 \times 10^{4}) + (0{,}2 \times 10^{4}) = 3{,}2 \times 10^{4}
$$

---

## 12. POTÊNCIAS E RAÍZES

### Potência de potência

$$
(10^{3})^{2} = 10^{6}
$$

$$
(2 \times 10^{3})^{2} = 4 \times 10^{6}
$$

### Raiz quadrada

$$
\sqrt{4 \times 10^{6}} = 2 \times 10^{3}
$$

$$
\sqrt{9 \times 10^{-4}} = 3 \times 10^{-2}
$$

---

## 13. FÍSICA — CONSTANTES FUNDINAIS

### Velocidade da luz

$$
c = 3 \times 10^{8}\ \mathrm{m/s}
$$

### Carga do elétron

$$
e = 1{,}6 \times 10^{-19}\ \mathrm{C}
$$

### Massa do elétron

$$
m_e = 9{,}11 \times 10^{-31}\ \mathrm{kg}
$$

### Massa do próton

$$
m_p = 1{,}67 \times 10^{-27}\ \mathrm{kg}
$$

### Constante de Planck

$$
h = 6{,}626 \times 10^{-34}\ \mathrm{J \cdot s}
$$

### Constante gravitacional

$$
G = 6{,}67 \times 10^{-11}\ \mathrm{N \cdot m^2 / kg^2}
$$

### Constante de Boltzmann

$$
k_B = 1{,}38 \times 10^{-23}\ \mathrm{J/K}
$$

---

## 14. QUÍMICA — CONSTANTES FUNDINAIS

### Número de Avogadro

$$
N_A = 6{,}02 \times 10^{23}\ \mathrm{mol^{-1}}
$$

### Constante dos gases

$$
R = 8{,}314 \times 10^{0}\ \mathrm{J/(mol \cdot K)}
$$

$$
R = 0{,}0821 \times 10^{0}\ \mathrm{atm \cdot L/(mol \cdot K)}
$$

---

## 15. PREFIXOS DO SI (conversão com notação)

| Prefixo | Símbolo | Fator | Notação |
|---------|---------|-------|---------|
| quilo | k | $10^{3}$ | $1\ \mathrm{km} = 10^{3}\ \mathrm{m}$ |
| mega | M | $10^{6}$ | $1\ \mathrm{MW} = 10^{6}\ \mathrm{W}$ |
| giga | G | $10^{9}$ | $1\ \mathrm{GHz} = 10^{9}\ \mathrm{Hz}$ |
| mili | m | $10^{-3}$ | $1\ \mathrm{mm} = 10^{-3}\ \mathrm{m}$ |
| micro | μ | $10^{-6}$ | $1\ \mathrm{μm} = 10^{-6}\ \mathrm{m}$ |
| nano | n | $10^{-9}$ | $1\ \mathrm{nm} = 10^{-9}\ \mathrm{m}$ |
| pico | p | $10^{-12}$ | $1\ \mathrm{pF} = 10^{-12}\ \mathrm{F}$ |

---

## 16. TABELA DE EXEMPLOS PRÁTICOS

| Grandeza                        | Valor em decimal                        | Valor em notação científica                   |
| ------------------------------- | --------------------------------------- | --------------------------------------------- |
| Velocidade da luz               | 300000000                               | $3 \times 10^{8}\ \mathrm{m/s}$               |
| Carga do elétron                | 0,00000000000000000016                  | $1{,}6 \times 10^{-19}\ \mathrm{C}$           |
| Massa do elétron                | 0,000000000000000000000000000000911     | $9{,}11 \times 10^{-31}\ \mathrm{kg}$         |
| Número de Avogadro              | 602000000000000000000000                | $6{,}02 \times 10^{23}\ \mathrm{mol^{-1}}$    |
| Constante de Planck             | 0,0000000000000000000000000000000006626 | $6{,}626 \times 10^{-34}\ \mathrm{J \cdot s}$ |
| Comprimento de onda (luz verde) | 0,00000055                              | $5{,}5 \times 10^{-7}\ \mathrm{m}$            |
| 1 ano-luz                       | 9460000000000000                        | $9{,}46 \times 10^{15}\ \mathrm{m}$           |

---

## 17. ERROS COMUNS (evite isso)

| Errado                  | Certo                             | Problema                        |
| ----------------------- | --------------------------------- | ------------------------------- |
| `$3x10^8$`              | `$3 \times 10^{8}$`               | Falta espaço e `\times`         |
| `$3*10^8$`              | `$3 \times 10^{8}$`               | `*` não é padrão matemático     |
| `$10^-3$`               | `$10^{-3}$`                       | Expoente precisa de chaves      |
| `$3.2 \times 10^4$`     | `$3{,}2 \times 10^{4}$`           | Ponto ≠ vírgula (PT-BR)         |
| `$3 \times 10^8 m/s$`   | `$3 \times 10^{8}\ \mathrm{m/s}$` | Unidade em itálico (errado)     |
| `$0{,}5 \times 10^{3}$` | `$5 \times 10^{2}$`               | Coeficiente < 1 (não é padrão)  |
| `$15 \times 10^{6}$`    | `$1{,}5 \times 10^{7}$`           | Coeficiente ≥ 10 (não é padrão) |

---

## 18. SNIPPETS RÁPIDOS PARA COPIAR

### Básico
```markdown
$a \times 10^{n}$
```

### Com expoente negativo
```markdown
$a \times 10^{-n}$
```

### Com unidade
```markdown
$a \times 10^{n}\ \mathrm{unidade}$
```

### Bloco alinhado
```markdown
$$
\begin{aligned}
\text{eq1} &= \text{valor1} \\
\text{eq2} &= \text{valor2}
\end{aligned}
$$
```

### Multiplicação de duas notações
```markdown
$(a \times 10^{m})(b \times 10^{n}) = (a \cdot b) \times 10^{m+n}$
```

---

## 19. MODELO PARA RESOLUÇÃO DE EXERCÍCIOS

**Problema:** Converter $0{,}00045$ para notação científica.

**Solução:**

$$
\begin{aligned}
0{,}00045 &= 4{,}5 \times 10^{-4} \\
\text{(mova a vírgula 4 casas para a direita)} \\
\text{(expoente negativo porque o número é < 1)}
\end{aligned}
$$

---

**Problema:** Calcular $(2 \times 10^{3})(4 \times 10^{2})$

**Solução:**

$$
\begin{aligned}
(2 \times 10^{3})(4 \times 10^{2}) &= (2 \cdot 4) \times 10^{3+2} \\
&= 8 \times 10^{5}
\end{aligned}
$$

---

## 20. ATALHO DE MEMORY PARA ESTUDO

Use sempre este molde na prova:

**\(a \times 10^{n}\)** onde:
- \(1 \le |a| < 10\)
- \(n\) é inteiro
- Unidade em `\mathrm{}` se existir

Isso é o que aparece em 100% das questões de física/química do EsPCEx/ESA. [web:34]

================================================================================
FIM DO TEMPLATE — Salve nas suas notas do Obsidian e use como referência
================================================================================
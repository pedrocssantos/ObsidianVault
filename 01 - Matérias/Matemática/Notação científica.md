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

| Prefixo | Símbolo | Fator      | Notação                                 |
| ------- | ------- | ---------- | --------------------------------------- |
| quilo   | k       | $10^{3}$   | $1\ \mathrm{km} = 10^{3}\ \mathrm{m}$   |
| mega    | M       | $10^{6}$   | $1\ \mathrm{MW} = 10^{6}\ \mathrm{W}$   |
| giga    | G       | $10^{9}$   | $1\ \mathrm{GHz} = 10^{9}\ \mathrm{Hz}$ |
| mili    | m       | $10^{-3}$  | $1\ \mathrm{mm} = 10^{-3}\ \mathrm{m}$  |
| micro   | μ       | $10^{-6}$  | $1\ \mathrm{μm} = 10^{-6}\ \mathrm{m}$  |
| nano    | n       | $10^{-9}$  | $1\ \mathrm{nm} = 10^{-9}\ \mathrm{m}$  |
| pico    | p       | $10^{-12}$ | $1\ \mathrm{pF} = 10^{-12}\ \mathrm{F}$ |

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

## RAIZ QUADRADA

Inline: $\sqrt{16} = 4$

Raiz com índice: $\sqrt[3]{27} = 3$

Raiz no bloco:

$$
\sqrt{a^2 + b^2}
$$

Raiz de expressão complexa:

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

---

## DELTA (discriminante da equação quadrática)

Delta simples: $\Delta = b^2 - 4ac$

Delta no bloco:

$$
\Delta = b^2 - 4ac
$$

Delta maiúsculo vs minúsculo:
- $\Delta$ (maiúsculo, triângulo) — usado para delta de equação
- $\delta$ (minúsculo) — usado para variação pequena [web:51]

---

## FÓRMULA DE BHASKARA COMPLETA

$$
x = \frac{-b \pm \sqrt{\Delta}}{2a}
$$

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

---

## EXEMPLO PRÁTICO COMPLETO

$$
\begin{aligned}
\text{Equação: } & x^2 - 5x + 6 = 0 \\
\Delta &= (-5)^2 - 4(1)(6) \\
\Delta &= 25 - 24 \\
\Delta &= 1 \\
x' &= \frac{-(-5) + \sqrt{1}}{2(1)} = \frac{5 + 1}{2} = 3 \\
x'' &= \frac{-(-5) - \sqrt{1}}{2(1)} = \frac{5 - 1}{2} = 2
\end{aligned}
$$

---

## OPERAÇÕES COM RAÍZES

$$
\sqrt{a} \cdot \sqrt{b} = \sqrt{ab}
$$

$$
\frac{\sqrt{a}}{\sqrt{b}} = \sqrt{\frac{a}{b}}
$$

$$
\sqrt{a^2} = |a|
$$

---

## RAIZ DE NOTAÇÃO CIENTÍFICA

$$
\sqrt{4 \times 10^{6}} = 2 \times 10^{3}
$$

$$
\sqrt{9 \times 10^{-4}} = 3 \times 10^{-2}
$$

---

## OUTROS SÍMBOLOS QUE VOCÊ VAI USAR

### Frações

Inline: $\frac{a}{b}$

Bloco:

$$
\frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

### Somatório

$$
\sum_{i=1}^{n} x_i
$$

### Produto

$$
\prod_{i=1}^{n} x_i
$$

### Integrais

$$
\int_{a}^{b} f(x)\,dx
$$

$$
\int x^2\,dx = \frac{x^3}{3} + C
$$

### Limites

$$
\lim_{x \to 0} \frac{\sin x}{x} = 1
$$

### Números reais, naturais, etc.

$\mathbb{R}$ — reais

$\mathbb{N}$ — naturais

$\mathbb{Z}$ — inteiros

$\mathbb{Q}$ — racionais

### Símbolos de comparação

$\neq$ — diferente

$\leq$ — menor ou igual

$\geq$ — maior ou igual

$\approx$ — aproximadamente

$\propto$ — proporcional

### Operações

$a \pm b$ — mais ou menos

$a \cdot b$ — produto (ponto)

$a \times b$ — produto (cruz)

$\div$ — divisão

### Letras gregas (usadas em física)

$\alpha$ — alfa

$\beta$ — beta

$\gamma$ — gama

$\delta$ — delta minúsculo

$\Delta$ — delta maiúsculo

$\theta$ — theta

$\lambda$ — lambda

$\mu$ — micro

$\pi$ — pi

$\rho$ — rho

$\sigma$ — sigma

$\Phi$ — fi

---

## TABELA COMPLETA DE SÍMBOLOS MATEMÁTICOS

| Símbolo | LaTeX | Uso |
|---------|-------|-----|
| $\sqrt{}$ | `\sqrt{}` | Raiz quadrada |
| $\sqrt[3]{}$ | `\sqrt[3]{}` | Raiz cúbica |
| $\Delta$ | `\Delta` | Discriminante (quadrática) |
| $\delta$ | `\delta` | Variação pequena |
| $\pm$ | `\pm` | Mais ou menos |
| $\mp$ | `\mp` | Menos ou mais |
| $\frac{}{}$ | `\frac{}{}` | Fração |
| $\sum$ | `\sum` | Somatório |
| $\int$ | `\int` | Integral |
| $\lim$ | `\lim` | Limite |
| $\infty$ | `\infty` | Infinito |
| $\neq$ | `\neq` | Diferente |
| $\leq$ | `\leq` | Menor ou igual |
| $\geq$ | `\geq` | Maior ou igual |
| $\approx$ | `\approx` | Aproximadamente |
| $\in$ | `\in` | Pertence |
| $\notin$ | `\notin` | Não pertence |
| $\forall$ | `\forall` | Para todo |
| $\exists$ | `\exists` | Existe |
| $\Rightarrow$ | `\Rightarrow` | Implica |
| $\Leftrightarrow$ | `\Leftrightarrow` | Se e somente se |
| $\circ$ | `\circ` | Composição |
| $\circ$ | `\circ` | Comprimento |
| $^\circ$ | `^{\circ}` | Graus (ângulo) |
| $\mathbb{R}$ | `\mathbb{R}` | Reais |
| $\mathbb{N}$ | `\mathbb{N}` | Naturais |
| $\mathbb{Z}$ | `\mathbb{Z}` | Inteiros |

---

## FRASES COMPLETAS PARA EXERCÍCIOS

**Equação do 2º grau:**

$$
\begin{aligned}
\text{Dada: } & ax^2 + bx + c = 0 \\
\text{Delta: } & \Delta = b^2 - 4ac \\
\text{Se } & \Delta > 0 \Rightarrow \text{2 raízes reais distintas} \\
\text{Se } & \Delta = 0 \Rightarrow \text{1 raiz real (dupla)} \\
\text{Se } & \Delta < 0 \Rightarrow \text{2 raízes complexas} \\
\text{Raízes: } & x = \frac{-b \pm \sqrt{\Delta}}{2a}
\end{aligned}
$$

**Teorema de Pitágoras:**

$$
a^2 + b^2 = c^2 \Rightarrow c = \sqrt{a^2 + b^2}
$$

**Fórmula de área com raiz:**

$$
A = \frac{\sqrt{3}}{4} \cdot L^2 \quad \text{(triângulo equilátero)}
$$

---

## ERROS COMUNS

| Errado | Certo | Problema |
|--------|-------|----------|
| `$\sqrt 16$` | `$\sqrt{16}$` | Chaves sempre |
| `$delta$` | `$\Delta$` | Delta maiúsculo = `\Delta` [web:51] |
| `$\sqrtb^2 - 4ac$` | `$\sqrt{b^2 - 4ac}$` | Chaves envolvem tudo |
| `$\frac a b$` | `$\frac{a}{b}$` | Chaves explícitas |
| `$\int x^2 dx$` | `$\int x^2\,dx$` | Espaço `\,` antes de `dx` |

---

## SNIPPETS PARA COPIAR/RABISCAR

### Bhaskara completo
```markdown
$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$
```

### Delta simples
```markdown
$\Delta = b^2 - 4ac$
```

### Raiz quadrada de expressão
```markdown
$\sqrt{a^2 + b^2}$
```

### Raiz cúbica
```markdown
$\sqrt{27} = 3$[1]
```

### Bhaskara passo a passo
```markdown
$$
\begin{aligned}
\Delta &= b^2 - 4ac \\
x' &= \frac{-b + \sqrt{\Delta}}{2a} \\
x'' &= \frac{-b - \sqrt{\Delta}}{2a}
\end{aligned}
$$
```

---

## PLUGINS ÚTEIS (opcional, não obrigatórios)

Se você quiser **melhorar experiência** com matemática:

| Plugin | O que faz | Vale a pena? |
|--------|-----------|--------------|
| **Latex Suite** | Snippets de LaTeX, atalhos para matemática | SIM — acelera digitação [web:45] |
| **Obsidian Desmos** | Gráficos de funções 2D | SIM — se você estuda cálculo/funções [web:45] |
| **LaTeX Math** | Calculadora simbólica com SymPy | SIM — resolve equações no vault [web:53] |
| **Obsidian Solve** | Calculadora inline | SIM — cálculos rápidos [web:52] |
| **Mathlive** | Editor visual de fórmulas | Opcional — editor gráfico |

**Ponto crucial:** Você **NÃO PRECISA** de plugins para raiz, delta, Bhaskara, notação científica — tudo isso funciona **nativamente** com MathJax [web:44][web:55]. Plugins só aceleram fluxo, não adicionam funcionalidade básica.

---

## PÔ, PEDRO, ESCUTA AQUI

Você quer **"tudo"**. Aqui está a verdade dura:

| Formato | Código | Quando usar |
|---------|--------|-------------|
| Raiz quadrada | `\sqrt{}` | 90% das raízes |
| Raiz cúbica | `\sqrt[3]{}` | Raiz cúbica |
| Raiz enésima | `\sqrt[n]{}` | Raiz de índice qualquer |
| Delta | `\Delta` | Equação do 2º grau |
| Bhaskara | `\frac{-b \pm \sqrt{\Delta}}{2a}` | Resolução completa |

Isso é **95% do que você vai usar** no EsPCEx/ESA. O resto é detalhe. [web:44][web:55]

Quer que eumonte um **template único** com tudo isso + 10 exercícios-modelo de álgebra/física para você só copiar e estudar?
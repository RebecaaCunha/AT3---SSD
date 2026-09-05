# AT3---SSD
Maximização
[README(1).md](https://github.com/user-attachments/files/31868004/README.1.md)
# 📊 Demandas Marshallianas

Este projeto apresenta a resolução de um problema de **maximização da utilidade do consumidor**, utilizando uma função de utilidade do tipo **Cobb-Douglas**.

## 📌 Objetivo

Calcular as **demandas Marshallianas** dos bens X e Y a partir da maximização da utilidade, considerando uma restrição orçamentária.

### Função de utilidade

$$
u(x,y) = Ax^\alpha y^\beta
$$

### Restrição orçamentária

$$
P_xx + P_yy \leq R
$$

### Demandas Marshallianas

$$
x^* = \frac{\alpha}{\alpha+\beta}\frac{R}{P_x}
$$

$$
y^* = \frac{\beta}{\alpha+\beta}\frac{R}{P_y}
$$

## 🛠️ Tecnologias utilizadas

- Python
- Google Colab
- SymPy

## 📂 Conteúdo

O código realiza:

- Definição da função de utilidade;
- Definição da restrição orçamentária;
- Construção da Lagrangiana;
- Cálculo das derivadas parciais;
- Resolução do sistema de equações;
- Cálculo das demandas Marshallianas;
- Cálculo da utilidade máxima;
- Exemplo numérico;
- Verificação da restrição orçamentária.

## ▶️ Como executar

1. Abra o arquivo no **Google Colab**.
2. Execute as células do código.
3. Altere os valores de `A`, `alpha`, `beta`, `Px`, `Py` e `R` para testar diferentes cenários.

## 👩‍💻 Autora

**Rebeca Alves**  
Engenharia de Produção — Universidade de Brasília (UnB)

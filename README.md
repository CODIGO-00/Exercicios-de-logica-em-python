### 🐍[Lógica de Programação em Python](#logica-de-programacao-em-python)

Exercícios de lógica de programação em Python.

---

## 🗒 [Sobre o Repositório:](#sobre_o_repositorio)
 
Repositório criado para armazenar meus exercícios de lógica de programação utilizando Python.

---

## ⚙ [Ambientes e Ferramentas:] (#ambientes_e_ferramentas)

- dispositivo: Smartphone Android;
- editor: Pydroid.3
- sistema: Android 10
- biblioteca: GitHub
- controle de versão: Git;

---

## 🔧 [Conteúdos:](#conteudos)

- entrada-e-saida;
- operadores;
- estruturas condicionais;
- laços de repetição;
- funções;

---

## 📂[Estrutura do Repositório](#-estrutura_do_repositorio)

```

#logica-python:
 | 
 |---entrada-e-saida/ 
 |   |
 |   |___01_ola_mundo.py
 |   | 
 |   |___02_informações_do_usuario.py
 |   |
 |   |___
 |   
 |---operadores/
 |   |
 |   |___01_calculo_com_operador.py
 |   |
 |   |___02_calculo_de_media.py
 |   |
 |   |___03_calculo_aritmetico.py
 |   |
 |   |___04_tabuada.py
 |   |
 |   |___
 |
 |---estruturas-condicionais/
 |   |
 |   |___01_programa_de_comparacao.py
 |   |
 |   |___02_identificacao_de_numeros.py
 |   |
 |   |___03_verificacao_de_idade.py
 |   |
 |   |___
 |
 |
 |---lacos-de-repeticao/
 |    |
 |    |___01_par_ou_impar_com_lacos.py
 |
```

## Sobre os programas:

---
# [Entrada_e_saida:](#entrada_e_saida:)

**01_ola_mundo.py**
  
Criação do primeiro programa que imprime na tela "Olá Mundo". 

**Objetivo**

É aprender como funciona saida de dados
utilizando 'print()' para imprimir na tela.

**Script**

```Python
print(f"Olá mundo! Estou aprendendo python.")
```
---

**02_informações_do_usuario.py**

Programa que pede ao usuário o nome e a idade e no final imprime o resultado.

**Objetivo**

 Como usar variáveis,int,input em um script que pede ao usuário sua idade e nome.

**Script**

```Python
idade=int(input("Digite sua idade:"))

nome=input("Digite seu nome:")

print(f"Olá{nome},voce tem{idade}anos.")
```
---

 # [Operadores:](#operadores)

**01_calculo_com_operador.py**

 Comando que calcula o dobro do valor e a exponenciação.

**Objetivo**

 Entender a funcionalidade do operador aritmético, '*'(multiplicação) em um Script que calcula valores que o usuário digita.

**Script**

```Python
numero=int(input("Digite um número:"))

print("o Dobro é ", numero * 2)
print("o Resultado ao quadrado é",numero ** 2)
```
---

**02_calculo_de_media.py**

 Programa que descobre a média dos valores falados pelo o usuário.

**Objetivo**

 Como calcular a média de um valor com a utilização de operadores(/ e +), e avançar mais ainda com as variáveis.

**Script**

```Python
numero_1=int(input("Digite o primeiro número:"))
numero_2=int(input("Digite o segundo número:"))
numero_3=int(input("Digite o terceiro número:"))

media=(numero_3 + numero_2 + numero_1) / 3

print(f"A média é {media}")
```
---

**03_calculo_aritmetico.py**

 Script que resolve problemas  matemáticos básicos, como soma, subtração, multiplicação e o resto da divisão.

**Objetivo**

 Utilizar todos os operadores dentro de um Script.

**Script**

```Python
primeiro=int(input("Digite um número:"))
segundo=int(input("Digite outro número:"))

print(f"Resultado da soma é {primeiro + segundo}")

print(f"Resultado da subtração é {primeiro - segundo}")

print(f"Resultado da multiplicação é {primeiro * segundo}")

print(f"Resultado do resto da divisão é {primeiro % primeiro}")
```
___

**04_tabuada.py**
 
 Programa que resolve valores de multiplicação do 1 até o 10.

**Objetivo**

Evoluir no cálculo mental da multiplicação com a com o uso do Script de forma lógica e intuitiva.

**Script**

```Python
#entrada 
numero=int(input("Digite um número:"))

#Tabela de multiplicação:
print (numero * 1)
print (numero * 2)
print (numero * 3)
print (numero * 4)
print (numero * 5)
print (numero * 6)
print (numero * 7)
print (numero * 8)
print (numero * 9)
print (numero * 10)
```

---

# [Estruturas_condicionais](#estruturas_condicionais)

**01_programa_de_comparacao.py**

 Script que imprime na tela qual o maior valor utilizando if e else para a comparação desses valores.

**objetivo:**

 Aprender como usar if e else em um programa de comparação.

**script**

```Python
primeiro=int(input("Digite o primeiro número:"))
segundo=int(input("Digite o segundo número:"))

if primeiro >= segundo:
    print(f"O {primeiro} número maior que o {segundo}.")
else:
    print(f"O {primeiro} número é menor que o {segundo}.")
```

---

**02_indentificacao_de_numeros.py**

 Programa que verifica números positivos, negativos e nulos,com o valor que o usuário escreve na entrada do script.

**objetivo:**

 Como identificar números positivos e negativos entre o número zero, com uso de if, else e o elif para colocar mais condições.

**script**

```Python
numero=int(input("Digite um número:"))
if numero >=1:
    print("É positivo.")
elif numero == 0:
    print("É zero.")
else:
    print("É negativo.")
```
---

**03_verificacao_de_idade.py**

 Script que varifica se a pessoa é maior de idade.

**objetivo:**

Criar um programa para informar se o usuário é maior de idade ou não. Para fixar o aprendizado de Estruturas-Condicionais.

**script**

```Python
idade= int(input("Digite sua idade:"))
if idade >=18:
    print("É maior de idade.")
else:
    print("É menor de idade.")
```

---

# [Laços de repetição:](#lacos_de_repeticao:)
 
 Script para descobrir se o número é ímpar ou par.

**objetivo**

Desenvolver o raciocínio com while e true em laços de repetição.

**script**
```Python
while True:
numero=int(input("Digite um número"))
if n % 2==0:
    print("é par")
else:
    print("É impar")
print("O resultado é",numero)
```

## ↗️[Meta:](#meta:)

 Desenvolver o raciocínio computacional com a prática de exercícios na lógica de programação em Python🐍.Criando resoluções criativas para ter uma melhor aprendizagem e desenvolvimento técnico,com o intuito de atingir um melhor desempenho em lógica.
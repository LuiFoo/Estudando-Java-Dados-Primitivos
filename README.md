# Tipos de Dados em Java

## 1. Números Inteiros

Utilizados para representar números **sem casa decimal**.

| Tipo  | Tamanho | Intervalo |
|------|--------|-----------|
| byte | 8 bits | -128 até 127 |
| short | 16 bits | -32.768 até 32.767 |
| int | 32 bits | -2.147.483.648 até 2.147.483.647 |
| long | 64 bits | -9.223.372.036.854.775.808 até 9.223.372.036.854.775.807 |

**Exemplos:**

```
100
255
120
1
234345
```

---

## 2. Números Decimais

Usados para representar números com **casas decimais**.

| Tipo | Tamanho | Precisão |
|-----|--------|----------|
| float | 32 bits | precisão simples |
| double | 64 bits | precisão dupla |

**Exemplos:**

```
1.2
3.4
5.6
7.8
9.0
5.50
```

---

## 3. String (Texto)

Utilizado para representar **palavras ou frases**.

```java
String nome = "Fernanda";
```

---

## 4. Char (Caractere)

Representa **apenas um único caractere**.

✔ Exemplo correto:

```java
char letra = 'a';
```

❌ Exemplo incorreto:

```java
char letra = "Fernanda"; // char aceita apenas um caractere
```

---

## 5. Boolean (Valor Lógico)

Representa **valores verdadeiros ou falsos**.

Valores possíveis:

```
true
false
```

### **Brinquedos Mágicos Database 🪄**

#### 1. **Criar uma Nova Lista de Brinquedos**

Primeiro, precisamos de um lugar para armazenar nossos brinquedos. Vamos criar uma "mágica" caixa chamada `Brinquedos`.

```sql
CREATE DATABASE BrinquedosMagicos;
USE BrinquedosMagicos;
```

#### 2. **Criar uma Tabela para os Brinquedos**

Dentro da caixa `Brinquedos`, vamos criar uma tabela chamada `MeusBrinquedos` para manter informações sobre cada brinquedo.

```sql
CREATE TABLE MeusBrinquedos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    categoria VARCHAR(255),
    idade_recomendada INT
);
```

#### 3. **Adicionar um Novo Brinquedo à Coleção**

Agora, podemos adicionar um novo brinquedo à nossa coleção. Vamos chamar isso de "Feitiço Mágico de Adição".

```sql
-- Nome do Brinquedo: Varinha Mágica
-- Categoria: Brinquedo Mágico
-- Idade Recomendada: 6
INSERT INTO MeusBrinquedos (nome, categoria, idade_recomendada) VALUES ('Varinha Mágica', 'Brinquedo Mágico', 6);
```

#### 4. **Descobrir Quais Brinquedos Temos**

Quando quisermos ver todos os nossos brinquedos, podemos usar o "Encantamento de Listagem".

```sql
SELECT * FROM MeusBrinquedos;
```

#### 5. **Atualizar Informações sobre um Brinquedo**

Se decidirmos que a idade recomendada para a Varinha Mágica deveria ser 7, podemos usar o "Feitiço de Atualização".

```sql
UPDATE MeusBrinquedos SET idade_recomendada = 7 WHERE nome = 'Varinha Mágica';
```

#### 6. **Remover um Brinquedo da Coleção**

Se decidirmos que não queremos mais a Varinha Mágica, podemos usar o "Feitiço de Remoção".

```sql
DELETE FROM MeusBrinquedos WHERE nome = 'Varinha Mágica';
```

E assim, usando esses feitiços mágicos SQL, podemos criar, ler, atualizar e deletar brinquedos na nossa coleção mágica! 🌟Claro, vou tentar simplificar para que seja compreensível por crianças. Usaremos uma linguagem fictícia para tornar as explicações mais simples.

### **Brinquedos Mágicos Database 🪄**

#### 1. **Criar uma Nova Lista de Brinquedos**

Primeiro, precisamos de um lugar para armazenar nossos brinquedos. Vamos criar uma "mágica" caixa chamada `Brinquedos`.

```sql
CREATE DATABASE BrinquedosMagicos;
USE BrinquedosMagicos;
```

#### 2. **Criar uma Tabela para os Brinquedos**

Dentro da caixa `Brinquedos`, vamos criar uma tabela chamada `MeusBrinquedos` para manter informações sobre cada brinquedo.

```sql
CREATE TABLE MeusBrinquedos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    categoria VARCHAR(255),
    idade_recomendada INT
);
```

#### 3. **Adicionar um Novo Brinquedo à Coleção**

Agora, podemos adicionar um novo brinquedo à nossa coleção. Vamos chamar isso de "Feitiço Mágico de Adição".

```sql
-- Nome do Brinquedo: Varinha Mágica
-- Categoria: Brinquedo Mágico
-- Idade Recomendada: 6
INSERT INTO MeusBrinquedos (nome, categoria, idade_recomendada) VALUES ('Varinha Mágica', 'Brinquedo Mágico', 6);
```

#### 4. **Descobrir Quais Brinquedos Temos**

Quando quisermos ver todos os nossos brinquedos, podemos usar o "Encantamento de Listagem".

```sql
SELECT * FROM MeusBrinquedos;
```

#### 5. **Atualizar Informações sobre um Brinquedo**

Se decidirmos que a idade recomendada para a Varinha Mágica deveria ser 7, podemos usar o "Feitiço de Atualização".

```sql
UPDATE MeusBrinquedos SET idade_recomendada = 7 WHERE nome = 'Varinha Mágica';
```

#### 6. **Remover um Brinquedo da Coleção**

Se decidirmos que não queremos mais a Varinha Mágica, podemos usar o "Feitiço de Remoção".

```sql
DELETE FROM MeusBrinquedos WHERE nome = 'Varinha Mágica';
```

E assim, usando esses feitiços mágicos SQL, podemos criar, ler, atualizar e deletar brinquedos na nossa coleção mágica! 🌟
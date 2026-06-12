# ChargeGrid Intelligence

### Transformando cada recarga em inteligência acionável

Projeto desenvolvido para o EV Challenge 2026 – Sprint 2, em parceria com a FIAP e a GoodWe.

---

# Integrantes

**Equipe 3**

Bruno — RM: 572648
Marcos — RM: 573857
Bernardo — RM: 568808
Gabriel — RM: 571735
Guilherme — RM: 571951
Matheus — RM: 574166

---

# Sobre o Projeto

O ChargeGrid Intelligence é uma solução de gerenciamento energético para eletropostos de veículos elétricos.

O projeto busca aumentar a eficiência energética das estações de recarga através do monitoramento do consumo, controle inteligente da demanda e utilização de energia solar.

Nesta Sprint 2 foi desenvolvida uma prova de conceito funcional capaz de simular o gerenciamento da potência disponível entre veículos conectados a um eletroposto.

---

# Problema Identificado

Com o crescimento da mobilidade elétrica, diversos veículos podem realizar recargas simultaneamente.

Sem um sistema de gerenciamento adequado podem ocorrer:

* Sobrecarga da rede elétrica;
* Queda na eficiência energética;
* Desperdício de energia disponível;
* Aumento dos custos operacionais;
* Baixo aproveitamento da energia solar.

---

# Solução Proposta

A prova de conceito desenvolvida simula um sistema de controle inteligente de demanda.

O sistema recebe informações sobre:

* Quantidade de veículos conectados;
* Energia solar disponível.

A partir desses dados, realiza a distribuição da potência disponível entre os veículos e identifica situações em que seria necessário ativar mecanismos de controle para evitar sobrecarga.

---

# Funcionalidades Demonstradas

## Controle Inteligente de Demanda

O sistema verifica a quantidade de veículos conectados e distribui a potência disponível entre eles.

Benefícios:

* Evita sobrecargas;
* Melhora a eficiência da infraestrutura elétrica;
* Permite o atendimento simultâneo de múltiplos veículos.

## Prioridade para Energia Solar

O sistema considera a disponibilidade de energia solar durante a operação.

Benefícios:

* Redução do consumo da rede elétrica;
* Maior aproveitamento da geração fotovoltaica;
* Incentivo ao uso de energia renovável.

---

# Arquitetura da Solução

```text
Usuário
   |
   v
Sistema ChargeGrid Intelligence
   |
   +---- Controle de Demanda
   |
   +---- Monitoramento Energético
   |
   +---- Gestão de Energia Solar
   |
   v
Resultados e Alertas
```

---

# Tecnologias Utilizadas

* Linguagem C
* Dev-C++ / CodeBlocks / GCC
* Lógica de Programação
* Conceitos de Eficiência Energética
* Conceitos de Energias Renováveis

---

# Sustentabilidade e Energias Renováveis

A sustentabilidade é um dos pilares do projeto.

A solução busca:

* Maximizar o uso de energia solar;
* Reduzir desperdícios energéticos;
* Melhorar a eficiência da infraestrutura de recarga;
* Contribuir para a expansão sustentável da mobilidade elétrica.

O aproveitamento da energia fotovoltaica reduz a dependência da rede elétrica convencional e favorece o uso de fontes renováveis.

---

# Como Executar

1. Compilar o arquivo fonte em linguagem C.
2. Executar o programa.
3. Informar:

   * Quantidade de veículos conectados;
   * Energia solar disponível.
4. Visualizar a análise realizada pelo sistema.

---

# Demonstração

Durante a execução, o sistema:

* Recebe dados do usuário;
* Analisa a quantidade de veículos conectados;
* Distribui a potência disponível;
* Identifica possíveis situações de sobrecarga;
* Considera a utilização de energia solar.

---

# Vídeo de Apresentação

Link do vídeo:

(Adicionar link do YouTube não listado)

---

# Repositório

Link do GitHub:

(Adicionar link do repositório)

---

# Conclusão

O protótipo desenvolvido demonstra a viabilidade técnica do conceito proposto pelo ChargeGrid Intelligence.

A solução evidencia como técnicas simples de monitoramento e gerenciamento energético podem contribuir para a eficiência operacional dos eletropostos e para a utilização mais inteligente de energias renováveis, preparando a infraestrutura para o crescimento da mobilidade elétrica.

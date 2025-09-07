## 🔍 Matriz de Criticidade - Continuação

```mermaid
graph TD
    subgraph Matriz de Impacto - Parte 2

    PC["9. Perda de conexão em call importante (D50)"]:::laranja
    MP["10. Máquina de pagamento fora do ar (D20)"]:::amarelo
    SC["11. Sistema de controle de tráfego falhou (V100)"]:::vermelho
    CE["12. Cadastro de estudantes indisponível (E50)"]:::laranja
    FI["13. Falha em irrigação agrícola (E20)"]:::amarelo
    VC["14. Vazamento químico em fábrica (V100)"]:::vermelho
    SI["15. Site institucional fora do ar (C8)"]:::branco
    ER["16. Erro em relatório financeiro (D50)"]:::laranja

    end

classDef branco fill:#fff,stroke:#000,color:#000;
classDef amarelo fill:#FFD84D,stroke:#000,color:#000;
classDef laranja fill:#FFA233,stroke:#000,color:#000;
classDef vermelho fill:#E64C3C,stroke:#000,color:#000;



<!-- 🧾 Tabela de Classificação e Justificativas – Método Crystal
Nº	Cenário	Criticidade	Intensidade	Justificativa
1	Ar-condicionado parou	C	20	Impacta conforto, mas não compromete segurança ou operação crítica
2	Sistema bancário fora do ar	D	100	Afeta diretamente transações financeiras e confiança do cliente
3	Hospital sem energia	E	100	Risco à vida e funcionamento de equipamentos vitais
4	App de transporte com erro de tarifa	D	20	Prejuízo financeiro leve, sem risco à vida
5	Bairro sem luz por 6h	E	50	Impacta segurança e bem-estar, mas não é letal
6	Vazamento de dados e-commerce	D	50	Afeta privacidade e reputação, com impacto financeiro moderado
7	Elevador parou com pessoas dentro	V	100	Risco direto à vida e segurança física
8	Iluminação pública apagada	E	20	Reduz segurança urbana, mas sem impacto imediato à vida
9	Perda de conexão em call importante	D	50	Pode gerar prejuízo comercial e perda de oportunidades
10	Máquina de pagamento fora do ar	D	20	Afeta vendas pontuais, mas há alternativas de pagamento
11	Sistema de controle de tráfego falhou	V	100	Risco de acidentes e vidas em perigo
12	Cadastro de estudantes indisponível	E	50	Impacta processos educacionais, mas não é crítico à vida
13	Falha em irrigação agrícola	E	20	Prejuízo potencial à produção, mas não imediato
14	Vazamento químico em fábrica	V	100	Alto risco à vida e ao meio ambiente
15	Site institucional fora do ar	C	8	Impacto mínimo, sem prejuízo direto
16	Erro em relatório financeiro	D	50	Pode gerar decisões equivocadas e prejuízo financeiro -->

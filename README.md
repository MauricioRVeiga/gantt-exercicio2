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

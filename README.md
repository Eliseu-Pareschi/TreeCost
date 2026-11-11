# 🌳 TreeCost - Sistema de Gestão de Fórmulas (BOM)

Sistema integrado desenvolvido para modelagem e gestão de Listas de Materiais (BOM) utilizando árvores genéricas, permitindo cálculos de explosão, implosão de custos e persistência local.

## 🚀 Sobre o Projeto
Esta ferramenta faz a ponte entre a lógica de árvores genéricas em Java e uma interface gráfica desktop interativa. Os dados de componentes são estruturados, processados e armazenados com segurança em base de dados SQLite, contando também com um relatório visual em HTML para documentação e apresentação.

## 🛠️ Tecnologias Utilizadas
- **Java & Java Swing:** Lógica de negócio de árvores genéricas e interface gráfica desktop.
- **SQLite (`sqlite-jdbc`):** Armazenamento relacional leve para persistência dos itens e estrutura hierárquica.
- **HTML5 / CSS3:** Relatório visual estático para representação da árvore de materiais.
- **Git & GitHub:** Versionamento e gestão do código-fonte académico.

## ⚙️ Funcionalidades Principais
- **Árvore Genérica BOM:** Modelação hierárquica flexível de produtos, conjuntos e subcomponentes (ex: Computador e respetivas peças).
- **Explosão de Fórmulas:** Cálculo automatizado das quantidades necessárias de cada componente por lote de produção.
- **Implosão (Custos):** Recálculo dinâmico do custo total acumulado do produto baseando-se nos preços unitários.
- **Persistência de Dados:** Sincronização automática entre os modelos em memória e a base de dados SQLite.

## 📸 Demonstração do Sistema
1. **Interface Gráfica (Java Swing)**
2. **Relatório Visual (HTML)**
3. **Execução e Testes via Consola (Explosão e Implosão)**

## 🔒 Organização e Boas Práticas
O repositório está estruturado em pacotes coesos (`model`, `service`, `view`) seguindo os princípios de orientação a objetos, garantindo um código limpo, modular e de fácil manutenção para o ambiente académico.

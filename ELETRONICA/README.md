# ⚡ Subsistema de Eletrônica e Hardware

Este diretório contém os arquivos de projeto, esquemáticos, layouts de circuito impresso e especificações de hardware desenvolvidos para viabilizar a **Interface de Controle de Tanques à Distância**.

A engenharia eletrônica atua como a ponte entre o sistema de automação e a estrutura física (sensores e atuadores das bancadas).

---

## 📦 Escopo de Desenvolvimento

A atuação desta frente está estruturada nos seguintes pilares fundamentais:

* 📐 **Design de PCB:** Criação do layout da placa de circuito impresso (esquemático e roteamento de trilhas) para condicionamento de sinais e acionamento de potência.
* 📋 **Listagem de Componentes (BOM):** Catálogo detalhado com part numbers, especificações elétricas, encapsulamentos e fornecedores de todos os componentes eletrônicos utilizados.
* 🔌 **Diagrama de Conexões Elétricas:** Esquema de pinagem, fiação interna, alimentação do sistema e proteção elétrica geral.
* 🌐 **Ligação entre Sistemas e Subsistemas:** Arquitetura de interface para integrar o hardware local à unidade de processamento, aos sensores/atuadores mecânicos e ao sistema de controle remoto.

---

## 🛠️ Ferramentas Recomendadas

Para visualizar e editar os projetos de hardware contidos nesta pasta, recomenda-se a utilização de:
* **Altium Designer** / **KiCad** / **EasyEDA** *(Altere aqui para o software principal do seu time)*

---

## 🚀 Como Contribuir nesta Pasta

1. **Versionamento de Hardware:** Sempre exporte os arquivos de fabricação (Gerbers, Pick and Place, e furos de broca) para a pasta `/fabricacao` ao finalizar uma versão estável.
2. **Esquemáticos em PDF:** Sempre disponibilize uma versão em PDF do diagrama de conexões elétricas para facilitar a leitura rápida de outros membros do time.
3. **Padrão de Organização:**
   * `/esquematicos` — Arquivos fonte do circuito.
   * `/bom` — Tabelas de listagem de componentes (formatos `.csv` ou `.xlsx`).
   * `/diagramas` — Desenhos de interconexão entre os subsistemas.

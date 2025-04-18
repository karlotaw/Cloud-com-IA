# ☁️ Resumo: Conceitos e Benefícios da Nuvem - AZ-900

Este resumo reúne os principais **conceitos fundamentais** e **benefícios da computação em nuvem**, com foco na certificação **Microsoft Azure Fundamentals (AZ-900)**.

---

## 📘 Conceitos de Nuvem

A **computação em nuvem** é o fornecimento de serviços como armazenamento, processamento e rede por meio da internet, promovendo **inovação mais rápida**, **recursos flexíveis** e **economia com base no uso**.

### 🔹 Modelos de Nuvem

- **Nuvem Pública:** Recursos fornecidos por provedores e acessados pela internet; ideal para cargas dinâmicas e com menor preocupação com segurança.
- **Nuvem Privada:** Infraestrutura exclusiva da organização, oferecendo **controle total**, segurança e customização.
- **Nuvem Híbrida:** Combina os dois modelos, trazendo **flexibilidade** e adequação a requisitos legais ou de conformidade.

### 🔹 Comparação dos Modelos

| Modelo        | Vantagens Principais                                      |
|---------------|-----------------------------------------------------------|
| Pública       | Sem investimento inicial (CapEx), escalável e sob demanda |
| Privada       | Maior controle e segurança                                |
| Híbrida       | Flexibilidade + controle de conformidade                  |

---

## 💸 CapEx vs OpEx

- **CapEx (Capital Expenditure):** Investimento antecipado em infraestrutura, com depreciação.
- **OpEx (Operational Expenditure):** Pagamento sob demanda, sem investimento inicial — ideal na nuvem.

### 🔹 Modelo Baseado no Consumo

No modelo baseado em consumo, você paga **somente pelos recursos utilizados**, o que **melhora o planejamento financeiro** e evita gastos desnecessários.

---

## 🔧 Casos de Uso

- Use **nuvem pública** para desenvolvimento rápido e escalável.
- Use **nuvem privada** para cargas com requisitos de segurança e conformidade.
- Use **nuvem híbrida** para integrar sistemas locais com a nuvem, de forma segura e flexível.

---

### 📊 SLA (Service Level Agreement)

Um **SLA (Acordo de Nível de Serviço)** é o compromisso formal assumido por um provedor de nuvem, como o Azure, garantindo um **nível mínimo de disponibilidade** dos seus serviços.

- **Exemplo:** Um SLA de 99,9% significa que o serviço estará disponível por no mínimo 99,9% do tempo em um determinado período (geralmente mensal).

#### 🔹 Importância do SLA:
- Define expectativas claras sobre a **disponibilidade** do serviço.
- Ajuda a escolher **serviços confiáveis** de acordo com a necessidade do negócio.
- Pode influenciar decisões de **redundância e alta disponibilidade**.

#### 🔹 Tipos comuns de SLA:
| SLA (%)  | Tempo de Inatividade por mês |
|----------|------------------------------|
| 99%      | ~7h 18min                    |
| 99,9%    | ~43min                       |
| 99,99%   | ~4min                        |
| 99,999%  | ~26s                         |

> 💡 Dica: Para sistemas críticos, busque serviços com SLA mais alto e avalie estratégias como **regiões redundantes** ou **zonas de disponibilidade**.

## 🌟 Benefícios da Nuvem

### 🔹 Alta Disponibilidade
A nuvem garante o funcionamento dos serviços mesmo com falhas regionais, através de **redundância e contratos de SLA**.

### 🔹 Escalabilidade
Permite **ajustar os recursos com base na demanda**, seja aumentando (escala vertical) ou reduzindo capacidade. Isso **otimiza o custo e desempenho**.

### 🔹 Elasticidade
Recursos podem ser **adicionados ou removidos automaticamente**, com base em picos ou quedas de uso.

### 🔹 Confiabilidade
A infraestrutura da nuvem é **descentralizada** e permite alta tolerância a falhas, garantindo continuidade mesmo em cenários críticos.

### 🔹 Previsibilidade
Com ferramentas de monitoramento e boas práticas como o **Well-Architected Framework**, a nuvem proporciona **previsibilidade de desempenho e custos**.

### 🔹 Segurança
A nuvem fornece **ferramentas robustas de segurança** (criptografia, autenticação, firewall), mas o cliente também tem papel ativo (modelo de responsabilidade compartilhada).

- **IaaS:** mais controle, mais responsabilidade.
- **PaaS/SaaS:** menos controle, mais automação e conveniência.

### 🔹 Governança
Políticas de auditoria e conformidade podem ser aplicadas desde o início para manter a **organização e segurança dos recursos**.

### 🔹 Gerenciabilidade
O gerenciamento pode ser feito via:
- Portal Web
- Azure CLI
- PowerShell
- APIs

Recursos podem ser implantados automaticamente com modelos pré-configurados, ou escalados de forma automática conforme necessário.

---

## 🚀 Conclusão

A nuvem transforma a forma como empresas e desenvolvedores **planejam, constroem e escalam** suas soluções. Dominar os conceitos e benefícios da Azure é o primeiro passo para se destacar na jornada de tecnologia em nuvem e para conquistar a **certificação AZ-900**.

---

> 📘 Estudo baseado no conteúdo oficial Microsoft, apostilas complementares.  
> Repositório mantido por Karla Beatriz — feito com 💙 e curiosidade pela nuvem.

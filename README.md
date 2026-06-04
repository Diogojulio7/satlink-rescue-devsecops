# satlink-rescue-devsecops# SatLink Rescue - DevSecOps

## Integrantes
Diogo Julio - RM553837
Jonata rafael - RM552939
Beatriz Silva - RM553455

## Descrição

O SatLink Rescue é uma plataforma que identifica áreas afetadas por desastres naturais e sugere o posicionamento estratégico de unidades móveis e satélites para restaurar a conectividade de internet em regiões isoladas.

---

## Arquitetura

Desenvolvedor
↓
GitHub
↓
GitHub Actions
↓
Scan de Segurança
↓
Build
↓
Deploy AWS
↓
Monitoramento

---

## Controles Implementados

### Gestão de Segredos

Utilização de GitHub Secrets para armazenar:

- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY
- DATABASE_URL
- JWT_SECRET

### Scan de Vulnerabilidades

Ferramentas utilizadas:

- npm audit
- Trivy

---

## Simulação

Foi simulada a utilização de uma dependência vulnerável.

O pipeline identificou a falha e bloqueou o deploy até que a vulnerabilidade fosse corrigida.

---

## ODS Atendidos

ODS 9 – Indústria, Inovação e Infraestrutura

ODS 11 – Cidades e Comunidades Sustentáveis

ODS 13 – Ação Contra a Mudança Global do Clima

---

## Evidências

As evidências encontram-se na pasta docs/.

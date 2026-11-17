<p align="center">
  <img src="assets/dba-infrastructure-banner.png" alt="Infraestrutura de bancos de dados" width="100%">
</p>

# Patrick Cecílio

**Oracle Database · SQL Server · Backup & Recovery · Linux · Automação**

Profissional de TI com experiência em infraestrutura, segurança e operação de bancos de dados. Na atuação profissional, trabalhei com consultas SQL, validação e correção de dados, conexões, usuários e permissões, acompanhamento de backups e suporte a sistemas integrados em Oracle, SQL Server e PostgreSQL. Este GitHub documenta laboratórios de administração de bancos de dados com escopo, comandos, evidências e critérios de validação explícitos.

## Projetos técnicos

| Projeto | Escopo e evidência |
|---|---|
| [Oracle Database 19c Multitenant](https://github.com/PatrickCecilio/oracle-19c-multitenant-deployment) | Instalação silenciosa no Oracle Linux, criação de CDB/PDB, aplicação de Release Update com OPatch e datapatch e validação no dicionário de dados. |
| [SQL Server: backup e recuperação pontual](https://github.com/PatrickCecilio/sql-server-backup-recovery-lab) | Cadeia full, diferencial e log; incidente simulado; restore em base alternativa com `STOPAT`; conferência do dado recuperado. |
| [Biblioteca Técnica DBA](https://github.com/PatrickCecilio/biblioteca-tecnica-dba) | Referências de Oracle, SQL Server, PostgreSQL e Linux, com [comandos classificados por risco operacional](https://github.com/PatrickCecilio/biblioteca-tecnica-dba/blob/main/COMANDOS-POR-RISCO.md). |

## Método de operação

1. **Preflight:** identificar instância, banco, container, ambiente, versão, privilégios, dependências e espaço disponível.
2. **Proteção:** confirmar backup restaurável, cadeia de logs/archivelogs, ponto de recuperação e RPO/RTO exigidos pelo cenário.
3. **Mudança:** registrar escopo, janela, comandos, responsáveis, critérios de parada e plano de retorno antes da execução.
4. **Validação:** conferir estado dos serviços, consistência dos objetos, dados esperados, logs e evidências após a mudança.

O [índice por risco](https://github.com/PatrickCecilio/biblioteca-tecnica-dba/blob/main/COMANDOS-POR-RISCO.md) separa consultas de alterações reversíveis, ações com indisponibilidade e operações destrutivas. O nível de estudo de um arquivo não indica que seu comando seja seguro para produção.

## Competências demonstradas

- **Bancos de dados:** Oracle Database, SQL Server, PostgreSQL, SQL, usuários e permissões, conexões e rotinas de backup.
- **Laboratórios documentados:** Oracle 19c Multitenant, OPatch/datapatch, RMAN e recuperação point-in-time no SQL Server.
- **Infraestrutura e automação:** Linux, Shell Script, Python, monitoramento e documentação técnica.

- **Formação:** Bacharelado em Sistemas de Informação, em andamento.
- **Localização:** Manaus, Amazonas, Brasil.
- **LinkedIn:** [patrickcecilio](https://www.linkedin.com/in/patrickcecilio/)

<details>
<summary>English summary</summary>

IT professional with hands-on experience in infrastructure, security and database operations. This portfolio documents Oracle 19c and SQL Server administration labs, with explicit scope, recovery procedures, validation steps and operational risk classification.

</details>

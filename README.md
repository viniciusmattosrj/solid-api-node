[![pipeline status](https://github.com/viniciusmattosrj/solid-api-node/badges/releaseCandidate/pipeline.svg)](https://github.com/viniciusmattosrj/solid-api-node/commits/releaseCandidate)

## Requerimentos

- Docker e docker-compose ou NVM
- Node &ge; 12.13.*
- Npm ou Yarn
- Mailtrap

### Tecnologias Utilizadas

* Code style: ESLint
* Typescript
* Rest
* S.O.L.I.D

### Sobre

Esse projeto é base de estudo para melhor compressão na prática dos conceitos de S.O.L.I.D.

Veja `.env.example` as [instruções](docs/installation.md) sobre as variáveis de ambiente.

É possível importar as `.collections` através do [collections](docs/collections.json) que contém querys/mutations/subscriptions.

### Instalação

Para instalação verifique **[installation documentation](docs/installation.md)**.

### Débitos Técnicos / Próximos Desafios

- [ ] Adicionar o dotEnv para que as configs não fiquem fixas no código
- [ ] Alterar a pasta useCases para Application
- [ ] Conectar a database
- [ ] Incluir um docker-compose.example.yml
- [ ] Implementar testes unitários Jest
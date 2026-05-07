# Sistema de Gestão de Rede de Cinemas

Projeto acadêmico para organização e controle de sessões, filmes e público em uma rede de cinemas.

---

## 🎯 Objetivo
Centralizar informações de cinemas, filmes e sessões, garantindo:
- cadastro organizado;
- registro diário de público;
- totalizações por sessão, por filme e por cinema;
- consulta a dados de filmes (elenco, diretor e gênero).

---

## 🧱 Arquitetura
- **Padrão**: MVC + Service + Repository
- **Persistência**: SQLite (`data/cinema.db`)
- **Interface**: CLI (terminal)

---

## ✅ Caso de uso implementado
**Registrar público de uma sessão**, com:
- validação de capacidade do cinema;
- totalizações por sessão, filme e cinema.

---

## 📁 Estrutura do projeto
```
cinema_sistemas/
├─ src/
│  ├─ main.py
│  ├─ models/
│  ├─ controllers/
│  ├─ services/
│  ├─ repositories/
│  └─ views/
├─ docs/
│  ├─ requisitos.md
│  └─ regras_negocio.md
└─ diagrams/
   ├─ diagrama_casosUso.md
   ├─ diagrama_classes.md
   ├─ diagrama_atividades.md
   └─ diagrama_sequencia.md
```

---

## ▶️ Como executar
```bash
python -m src.main
```

---


## 📄 Documentação
- **Requisitos**: `docs/requisitos.md`
- **Regras de negócio**: `docs/regras_negocio.md`

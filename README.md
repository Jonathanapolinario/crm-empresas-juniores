# CRM Empresas Juniores

Sistema completo de CRM para gerenciamento de Empresas Juniores com dois pipelines especializados:

## 🚀 Funcionalidades

- **Pipeline Novas EJs**: Descoberta → Primeiro contato → Reunião agendada → Material enviado → Interesse confirmado → Acompanhamento contínuo → Processo de federação → Federada
- **Pipeline EJs em Risco**: Inativa → Em Risco Crítico → Desfederada → Em Recuperação → Ativação em Transição → Reativada
- Sistema de arrastar e soltar para mudança de estágios
- Dashboard com estatísticas em tempo real
- Cadastro completo com CNPJ, curso, instituição, cidade
- Sistema de interações e histórico

## 🛠 Tecnologias

- **Frontend**: React + TypeScript + Tailwind CSS
- **Backend**: Node.js + Express
- **Banco**: PostgreSQL
- **ORM**: Drizzle
- **UI**: Shadcn/UI + Radix UI

## 📦 Instalação Local

```bash
# Clone o repositório
git clone [seu-repositorio]
cd crm-empresas-juniores

# Instale as dependências
npm install

# Configure as variáveis de ambiente
cp .env.example .env
# Edite o .env com sua DATABASE_URL

# Execute as migrações
npm run db:push

# Inicie o desenvolvimento
npm run dev
```

## 🌐 Deploy Gratuito

### Render (Recomendado)
1. Faça fork deste repositório
2. Conecte sua conta GitHub no Render
3. Selecione este repositório
4. Configure as variáveis de ambiente
5. Deploy automático!

### Vercel + Neon
1. Fork no GitHub
2. Conecte no Vercel
3. Configure banco PostgreSQL no Neon (gratuito)
4. Deploy automático!

## 📋 Variáveis de Ambiente

```
DATABASE_URL=sua_url_postgresql
NODE_ENV=production
```

## 🎯 Como Usar

1. **Dashboard**: Visão geral de todas as EJs e estatísticas
2. **Novas EJs**: Gerencie o pipeline de descoberta até federação
3. **EJs em Risco**: Acompanhe processo de recuperação
4. **Interações**: Registre contatos e acompanhamentos
5. **Relatórios**: Análise de performance e tendências

## 🔧 Scripts Disponíveis

- `npm run dev` - Desenvolvimento
- `npm run build` - Build para produção
- `npm run start` - Executa versão de produção
- `npm run db:push` - Aplica mudanças no schema

## 📄 Licença

MIT - Use livremente para seus projetos!

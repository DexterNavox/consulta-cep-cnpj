# Sistema de Consulta CEP e CNPJ

Este projeto consiste em duas páginas web para consulta de informações de CEP e CNPJ utilizando APIs públicas brasileiras.

## 📋 Descrição

O sistema oferece duas funcionalidades principais:

1. **Consulta de CEP** - Utiliza a API ViaCEP para buscar informações de endereços
2. **Consulta de CNPJ** - Utiliza a API CNPJA (open.cnpja.com) para buscar dados de empresas

## 🚀 Funcionalidades

### Página CEP (`CEP.html`)
- ✅ Validação de CEP (8 dígitos numéricos)
- ✅ Consulta em tempo real via API ViaCEP
- ✅ Exibição completa de dados do endereço
- ✅ Monitoramento de status da API
- ✅ Interface responsiva com Bootstrap
- ✅ Tratamento de erros e loading states

### Página CNPJ (`CNPJ.html`)
- ✅ Validação de CNPJ (14 dígitos numéricos)
- ✅ Consulta via API CNPJA pública
- ✅ Exibição organizada em abas:
  - Dados Básicos da empresa
  - Endereço completo
  - Sócios e Administradores
  - Atividades Econômicas
  - Inscrições Estaduais e SUFRAMA
- ✅ Monitoramento de status da API
- ✅ Interface responsiva com Bootstrap
- ✅ Tratamento de limites de consulta (5/min por IP)

## 🛠 Tecnologias Utilizadas

- **HTML5** - Estrutura das páginas
- **CSS3** - Estilização com Bootstrap 5
- **JavaScript** - Lógica de consulta e interação
- **Bootstrap 5.3.0** - Framework CSS
- **Bootstrap Icons** - Ícones
- **APIs:**
  - ViaCEP (https://viacep.com.br)
  - CNPJA (https://open.cnpja.com)

## 📁 Estrutura de Arquivos

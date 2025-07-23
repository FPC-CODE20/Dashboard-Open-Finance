# Dashboard Financeiro - Itaú

Projeto demonstrativo de análise e visualização de dados financeiros pessoais, pensado para destacar habilidades em tecnologia, análise de dados, UX e inovação no contexto bancário (Open Finance).

## ✨ Funcionalidades

- Upload de extrato bancário (CSV fictício) ou uso de dados de exemplo
- Dashboard com gráficos:
  - Gastos por categoria (Pizza)
  - Evolução do saldo (Linha)
  - Saldo atual destacado
- Recomendações financeiras básicas automáticas
- Visual moderno, responsivo e intuitivo

## 💻 Tecnologias Utilizadas

- [React](https://react.dev/)
- [Chart.js + react-chartjs-2](https://www.chartjs.org/)
- CSS puro

## 🎯 Como executar localmente

1. **Clone o repositório**  
   ```bash
   git clone https://github.com/seu-usuario/seu-repo-itau-dashboard.git
   cd seu-repo-itau-dashboard
   ```

2. **Instale as dependências**  
   ```bash
   npm install
   ```

3. **Execute o projeto**  
   ```bash
   npm start
   ```
   O dashboard abrirá em `http://localhost:3000`.

## 📝 Formato do CSV aceito

O arquivo deve conter as colunas:  
`data,descricao,categoria,valor`

Exemplo:
```csv
data,descricao,categoria,valor
2025-07-01,Salário,Receitas,6000
2025-07-02,Mercado,Alimentação,-500
2025-07-03,Restaurante,Alimentação,-120
2025-07-04,Transporte,Transporte,-70
2025-07-05,Academia,Saúde,-100
2025-07-06,Rendimento,Investimentos,50
```

## 🏦 Sobre

Esse projeto foi desenvolvido com foco em inovação e análise de dados para o setor bancário, inspirado em desafios reais do Open Finance e novas experiências digitais para clientes do Itaú.

---

[Filipe Pitombo](https://github.com/FPC-CODE20)  
 pitombofilipe@gmail.com

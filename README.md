# 🛡️ ChurnGuard | Inteligência Preditiva de Retenção

O ChurnGuard é uma solução de inteligência de dados que utiliza Machine Learning (Regressão Logística) e explicabilidade via SHAP para prever o cancelamento de clientes em bases SaaS.

> 💡 **Nota de Navegação:** Este repositório contém, na raiz, uma Apresentação Executiva Interativa (`index.html`) desenvolvida para demonstrar o valor de negócio e a arquitetura do projeto de forma imersiva.
> 
> 🔗 [Visualizar Apresentação do Projeto (Vercel)](https://churnguard-chi.vercel.app)

[![Stack](https://img.shields.io/badge/Python%20·%20Scikit--Learn%20·%20SHAP%20·%20Telegram%20Bot-5500FF?style=flat-square&labelColor=0a0a0e)](https://github.com/israeloliveiradev/churnguard)

---

## Estrutura

```
churnguard/
│
├── index.html        # Pitch deck interativo (13 slides, hospedado na Vercel)
└── README.md

algorithm/            # branch separada — em breve
├── notebooks/        # EDA e treinamento
├── model/            # Modelo serializado
├── shap/             # Explicabilidade
└── bot/              # Telegram Bot
```

---

## Stack

| Camada | Tecnologia |
|---|---|
| Processamento | Python · Pandas |
| Modelo | Scikit-Learn (Logistic Regression) |
| Explicabilidade | SHAP |
| Interface | Telegram Bot API |
| Deploy | Vercel |

---

## Rodando a apresentação localmente

```bash
git clone https://github.com/israeloliveiradev/churnguard.git
cd churnguard

# Abrir no navegador
open index.html
```

Navegação: `←` `→` · scroll · swipe · `F` para tela cheia.

---

## Algoritmo

O modelo está implementado e validado. O código será publicado na branch `algorithm` em breve.

---

## Autor

**Israel Alexandre de Oliveira**  
[LinkedIn](https://linkedin.com/in/israeloliveiradev) · [GitHub](https://github.com/israeloliveiradev)

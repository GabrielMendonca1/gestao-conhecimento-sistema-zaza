# 👨🏽‍💻 ZAZA

App desktop auto-hospedado para permitir que IA controle seu computador, usando a nova funcionalidade [computer use](https://www.anthropic.com/news/3-5-models-and-computer-use) do Claude. Deixe Claude executar tarefas no seu PC (ou tentar, rs). Feito em Python com PyQt.

## ⚠️ Avisos Importantes

1. **Software experimental** - Dá controle de mouse e teclado para IA. Coisas podem dar errado.
2. **Use com cuidado** - Se apagar seu PC, mandar e-mails estranhos ou pedir 100 pizzas... é sua responsabilidade.

A Anthropic pode ver capturas de tela durante as ações. Oculte informações sensíveis.

## 🎯 Funcionalidades
- Peça para a IA fazer qualquer coisa no computador com mouse e teclado: navegar, codar, etc.

## 💻 Plataformas
- Qualquer sistema que rode Python: MacOS, Windows, Linux, etc.

## 🛠️ Configuração

Obtenha uma chave API da Anthropic [aqui](https://console.anthropic.com/dashboard).

```bash
# Python 3.10+ recomendado
python -m venv venv
source venv/bin/activate  # ou `venv\Scripts\activate` no Windows
pip install -r requirements.txt

# Adicione a chave no .env
echo "ANTHROPIC_API_KEY=sua-chave-aqui" > .env

# Execute
python run.py
```

## 🔑 Atalhos
- `Ctrl + Enter`: Executa a instrução
- `Ctrl + C`: Cancela a ação
- `Ctrl + W`: Minimiza
- `Ctrl + Q`: Fecha o app

## 💡 Dicas
- Claude funciona melhor no Firefox. Instale para melhorar a precisão.
- Seja claro e monitore as ações da IA.

## 🐛 Problemas Conhecidos

- Às vezes, digita no lugar errado. Use `Ctrl + C` para parar e reinicie o agente.

## 🤝 Contribuições

[Gabriel Mendonca](https://github.com/GabrielMendonca1) e [Ravi Azevedo](https://github.com/RaviAzevedo).

## 📄 Licença

[Apache License 2.0](LICENSE)
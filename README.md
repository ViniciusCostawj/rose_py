# rose_py
Assistente virtual por voz em Python, ativada com a palavra "rose", que responde a comandos como previsão do tempo, cotações, notícias e playlists.
🎙️ Rose - Assistente Virtual com Reconhecimento de Voz
Este projeto implementa uma assistente virtual ativada por voz chamada Rose, que responde a comandos falados como previsão do tempo, notícias, cotações de moedas e reprodução de playlists.

🚀 Funcionalidades
Ativação por palavra-chave: Ativada ao ouvir a palavra "rose".

Reconhecimento de voz: Utiliza a API do Google para transcrever comandos falados.

Notícias: Informa as últimas notícias.

Playlists: Toca uma playlist específica.

Previsão do tempo: Informa a temperatura atual ou previsão mínima/máxima.

Cotação de moedas: Informa o valor atual do dólar, euro e bitcoin.

Respostas com áudios: Reproduz respostas em áudio com base nos comandos.

🛠️ Requisitos
Python 3.x

Microfone

Dependências (instale com pip):

bash
Copiar
Editar
pip install SpeechRecognition playsound unidecode
📁 Estrutura do Projeto
arduino
Copiar
Editar
├── comandos/
│   ├── cotacao_moedas.py
│   ├── noticias.py
│   ├── playlists.py
│   └── previsao_tempo.py
├── audios/
│   ├── espera_ai.mp3
│   ├── comando_invalido.mp3
│   └── ... outros áudios
├── cria_audios.py
├── main.py (ou nome do arquivo principal)
└── README.md
▶️ Como Executar
Verifique se os módulos estão instalados.

Certifique-se de que seu microfone está funcionando.

Execute o script:

bash
Copiar
Editar
python main.py
Diga a palavra mágica: rose, seguida de um comando, por exemplo:

“rose, qual o valor do dólar?”

“rose, toca uma playlist”

“rose, qual a temperatura agora?”

🎧 Exemplos de Comandos Reconhecidos
Comando	Ação
"rose, qual o valor do dólar?"	Mostra a cotação do dólar
"rose, qual o valor do bitcoin?"	Mostra a cotação do bitcoin
"rose, toca uma playlist"	Toca a playlist pré-definida
"rose, qual a temperatura agora?"	Informa a temperatura atual
"rose, qual a previsão do tempo?"	Informa a previsão mínima e máxima
"rose, notícias"	Lê as últimas notícias

❗ Observações
A pasta audios/ deve conter os arquivos .mp3 necessários para a resposta da assistente.

O projeto depende da conexão com a internet para o reconhecimento de voz via API do Google.

📌 TODO / Melhorias Futuras
Adicionar interface gráfica (GUI).

Incluir mais comandos (agenda, lembretes, etc.).

Melhorar o tratamento de erros.

Adicionar suporte a múltiplas playlists ou perfis personalizados.


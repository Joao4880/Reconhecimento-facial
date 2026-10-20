# FaceID — Smart Recognition

Protótipo web de reconhecimento facial com cadastro de pessoas e comparação de descritores faciais.

## Recursos
- Acesso à webcam pelo navegador.
- Cadastro de pessoas com nome e observação opcional.
- Captura de múltiplas amostras faciais por pessoa.
- Comparação de um rosto com amostras cadastradas.
- Exportação e importação dos cadastros em JSON.
- Armazenamento local no navegador (`localStorage`).

## Como executar
1. Abra esta pasta no Visual Studio Code.
2. Instale a extensão **Live Server**.
3. Clique com o botão direito em `index.html` e escolha **Open with Live Server**.
4. Permita o acesso à câmera.
5. Aguarde os modelos faciais serem carregados pela internet.

A câmera normalmente exige `localhost` ou HTTPS. Abrir o HTML diretamente pode impedir o acesso à câmera em alguns navegadores.

## Observações importantes
- O sistema é um protótipo: reconhecimento pode falhar, especialmente em perfil extremo, baixa iluminação, rosto parcialmente coberto ou mudanças de aparência.
- Os descritores faciais são armazenados no navegador usado para cadastrar. Não são sincronizados com o GitHub.
- Não envie fotos, descritores faciais, arquivos de exportação JSON ou outros dados biométricos para o repositório.
- Cadastre somente pessoas que consentiram com o uso de seus dados biométricos.
- A biblioteca `face-api.js` e os modelos são carregados de uma CDN; é necessária conexão com a internet para carregá-los.

## Git e GitHub
O código do projeto pode ser versionado com Git e enviado ao GitHub. O GitHub guardará os arquivos de código, não os cadastros salvos no navegador.

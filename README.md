## 🧠 Coleção de Workflows n8n
Este repositório contém uma coleção de workflows do n8n reunidos de várias fontes, incluindo:

Workflows exportados do site n8n.io e do fórum da comunidade

Exemplos compartilhados publicamente encontrados pela web (GitHub, blogs, etc.)

O objetivo é fornecer um recurso útil para inspiração, aprendizado e reutilização em seus próprios projetos com o n8n.

## 📂 Estrutura de Pastas
Cada arquivo .json representa um workflow exportado individualmente.

Os arquivos são nomeados com base no título original ou na fonte de origem.

Você também pode encontrar arquivos .txt que foram convertidos para .json (veja abaixo).

## 🔄 Conversão de TXT para JSON
Alguns workflows foram originalmente salvos como arquivos .txt ou copiados de fontes online. Um script foi utilizado para:

Detectar arquivos .txt

Tentar interpretá-los como JSON ou pares chave-valor estruturados

Convertê-los para o formato .json válido

Se quiser executar a conversão por conta própria, confira o arquivo convert_txt_to_json.py incluído neste repositório.

## 🛠 Instruções de Uso
Para importar um workflow na sua própria instância do n8n:

Abra a sua Interface do Editor do n8n

Clique no menu (☰) no canto superior direito → Importar workflow

Escolha um arquivo .json desta pasta

Clique em "Importar" para carregar o workflow

Certifique-se de revisar e modificar as credenciais ou URLs de webhook conforme necessário antes de executar.

## 🤝 Contribuição
Encontrou um workflow interessante ou criou o seu próprio?
Sinta-se à vontade para contribuir adicionando-o a esta coleção!

Apenas certifique-se de:

Nomear o arquivo de forma descritiva

Incluir um breve comentário no topo com a fonte original, se aplicável

## ⚠️ Aviso
Todos os workflows aqui são compartilhados como estão.
Sempre inspecione e teste em um ambiente seguro antes de usá-los em produção.

# Studio L · Catálogo & Pedido (App Web)

App web simples para exibir o catálogo (link externo) e **receber pedidos por e-mail** sem exibir preços.

## Publicar no GitHub Pages
1. Envie estes arquivos para o repositório (`Add file` → `Upload files`).
2. Em **Settings → Pages**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (pasta `/root`)
3. Salve. O site ficará acessível em: `https://SEU_USUARIO.github.io/NOME_DO_REPO`.

## E-mail de recebimento
Formulário usa **FormSubmit** com destino `Commercial@soustudiol.com.br`.
Você receberá todos os campos + um campo `pedido_json` contendo as linhas do pedido.

## Detecção de país
O campo **País** é preenchido automaticamente via `https://ipapi.co/json/` e pode ser alterado pelo cliente.

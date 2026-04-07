# 📡 Buscador de OLT por Bairro

Ferramenta web simples para consultar qual OLT atende cada bairro da região.

## 🚀 Como usar

Acesse direto pelo GitHub Pages ou abra o arquivo `index.html` no navegador.

### Funcionalidades

- 🔍 Busca em tempo real por bairro ou nome da OLT
- 🏷️ Filtros rápidos por OLT
- 📱 Responsivo para celular e desktop
- 🌙 Suporte a modo escuro automático

## 📂 Estrutura

```
/
└── index.html   # Aplicação completa (HTML + CSS + JS em um único arquivo)
```

## 🌐 Publicar no GitHub Pages

1. Faça o upload dos arquivos no seu repositório GitHub
2. Vá em **Settings → Pages**
3. Em **Source**, selecione a branch `main` e a pasta `/ (root)`
4. Clique em **Save**
5. Aguarde alguns segundos e acesse a URL gerada

## ✏️ Adicionar novos bairros

Abra o `index.html` e localize o array `data` dentro da tag `<script>`. Adicione uma nova linha seguindo o padrão:

```js
{ bairro: "NOME DO BAIRRO", olt: "NOME DA OLT COMPLETO", oltKey: "chave_da_olt" },
```

### Chaves disponíveis (`oltKey`)

| oltKey | OLT |
|--------|-----|
| `idc` | IDC-OLT |
| `esperanca` | OLT Esperança |
| `veneza` | OLT Huawei IDC Veneza |
| `timoteo` | OLT Timoteo Huawei |
| `tplink01` | OLT TPLink 01 - Ipaba |
| `tplink02` | OLT TPLink 02 - Ipaba |
| `tplink03` | OLT TPLink 03 - Ipaba |
| `tplink04` | OLT TPLink 04 - Ipaba |
| `mangueiras` | OLT Mangueiras |
| `paraiso` | OLT Paraíso |

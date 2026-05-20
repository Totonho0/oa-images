# OA Images

Repositório **público** só para mídia do [OA](https://oasisarts.discloud.app).

O app Node (`imagelink`) envia arquivos via GitHub API para `images/{discordUserId}/` (e `banners/` quando for banner).

**Não edite manualmente** a menos que saiba o que está fazendo — uploads e exclusões são feitos pelo servidor.

## Estrutura

```
images/
  {userId}/
    *.png, *.jpg, ...
    banners/
      *.png, ...
```

## CDN

Arquivos públicos são servidos via jsDelivr:

`https://cdn.jsdelivr.net/gh/Totonho0/oa-images@main/images/...`

## Variáveis no app (Discloud)

```
GITHUB_OWNER=Totonho0
GITHUB_REPO=oa-images
GITHUB_TOKEN=<PAT com write neste repo>
```

# RBDS blog

## Como adicionar Posts

Para adicionar posts, basta adicionar `div`'s com a classe `post`, dentro delas siga sempre o seguinte template:

```html
<div class="post">
  <h3 key="post-title">Loading...</h3>
  CONTEUDO (aqui você pode modelar como quiser)
</div>
```

para adicionar os textos com chaves de tradução, basta definir o atributo customizado `key` nas tags que você quer adaptar o conteúdo de texto, a chave que você colocar será buscada no objeto `translations`, lembre de garantir que a chave de tradução que você está adicionando não existe

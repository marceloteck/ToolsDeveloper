# Como usar o código

#### Chamando style

```php
require_once('dir/to/helpers.php');

echo HtmlHelper::htmlResources([
        HtmlHelper::mix_version('/Assets/css/styles.css'),
        ('https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css'),
]);
```

#### Chamando script

```php
require_once('dir/to/helpers.php');

echo HtmlHelper::htmlResources([
        HtmlHelper::mix_version('/assets/js/scripts.js'),
        ('https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js'),
], 'javascript');
// aqui recebe um segundo parametro com o conteudo: javascript
```

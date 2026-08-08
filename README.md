# yunus.gen.tr

Yunus Özen'in kişisel blogu. Bağımlılıksız statik HTML/CSS ile hazırlanır ve
GitHub Pages üzerinden yayınlanır.

## Yerelde çalıştırma

```bash
python3 -m http.server 8000
```

Ardından `http://localhost:8000` adresini açın.

## Yayın

`main` dalına yapılan her push, `.github/workflows/pages.yml` iş akışıyla GitHub
Pages'e dağıtılır. Canlı alan adı `yunus.gen.tr` olarak yapılandırılır.

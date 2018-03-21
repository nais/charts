Helm charts for Nais
====================

> Our Helm repo

## Add a new chart

Add your `.tar.gz` file to the repo, and update `index.yaml` with the following command:

```
helm repo index --url https://nais.github.io/charts .
```

To update `index.html`, you need to run the following command:

```
echo "<html><body><pre>$(cat index.yaml)</pre></body></html>" > index.html
```

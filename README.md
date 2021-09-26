## repo-hunter
repo-hunter es la versión de [repo-check](https://github.com/lliwi/repo-check) como template de nuclei. Nos ayuda a buscar distintos repositorios para posteriormente poder obtener todos los datos con dvcs-ripper.

## Uso
```
$ git clone https://github.com/lliwi/nuclei-repo-hunter.git
$ cd nuclei-repo-hunter
$ nuclei -t repo-hunter.yaml -u https://example.com
```

Para más informacion sobre el uso de nuclei podeis ir a su [github](https://github.com/projectdiscovery/nuclei) oficial.


## Inspiración
Este script está inspirado en el proyecto de kost, [dvcs-ripper](https://github.com/kost/dvcs-ripper). Pretendiendo únicamente localizar con agilidad los repositorios.

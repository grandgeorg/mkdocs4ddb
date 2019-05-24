# mkdocs4ddb
mkdocs Vorlage für DDB Handbücher

## Einrichtung einer neuen Entwicklungsumgebung

### Installieren der Architektur

- Installieren Sie [Python](https://www.python.org/downloads/) (getestet mit Python 3.7.3)
- Installieren Sie mkdocs - [MkDocs](http://www.mkdocs.org/#installation):  
    - ```pip install mkdocs```  
- Installieren Sie markdown extensions:  
    - ```pip install pymdown-extensions```
    - ```pip install pygments```  
    - ```pip install git+git://github.com/grandgeorg/figureAltCaption.git```
- Klonen Sie dieses Repositorium auf ihren Computer und verschieben die Dateien in Ihr Repo.
- Passen Sie die ```mkdocs.yml``` Datei an (insbes. ```nav``` etc.).
- Editieren Sie die md-Dateien ...

:warning: Achten Sie beim Installieren darauf, dass Sie genügend Rechte haben. Unter Windows installieren Sie mit ```pip``` immer in einer als Administrator gestarteten Eingabeaufforderung.

Die von mkdocs erstellte Dokumentation dieser Vorlage finden Sie unter:  
[https://grandgeorg.github.io/mkdocs4ddb/](https://grandgeorg.github.io/mkdocs4ddb/)
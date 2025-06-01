# mkDocs guide

Instruction site: https://squidfunk.github.io/mkdocs-material/

Deze site is gegenereerd met de mkdocs bibliotheek. Deze combineert een 'markdown'-bestand (.md) per pagina tot een wiki-site met inhoudsopgave.

De individuele .md pagina-bestanden worden samengevoegd op basis van de opgegeven structuur in het mkdocs.yml bestand. Door groepen te definiëren wordt de hierarchie gevormd.

Voorbeeld hierarchy-structuur:
```yaml
- Home: index.md
  - About: about.md
  - Controles houtsectie:
    - Buigspanning: controleHoutsectie/buigspanning.md
    - Schuifspanning: controleHoutsectie/schuifspanning.md
  - CW Plugins:
    - Labeling: CWPlugins/labeling.md
  - Tags: tags.md
```

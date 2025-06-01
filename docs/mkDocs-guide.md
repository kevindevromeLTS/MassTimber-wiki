# mkDocs guide

[Instruction site]( https://squidfunk.github.io/mkdocs-material/)  https://squidfunk.github.io/mkdocs-material/

Deze site is gegenereerd met de mkdocs bibliotheek. Deze combineert een 'markdown'-bestand (.md) per pagina tot een wiki-site met inhoudsopgave.

De individuele .md pagina-bestanden worden samengevoegd op basis van de opgegeven structuur in het mkdocs.yml bestand. Door groepen te definiëren wordt de hierarchie gevormd.

Voorbeeld hierarchie-structuur:
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

Oorspronkelijk opgezet via VSCode in venv volgens onderstaande tutorial, waarna deze via git naar github gesynct werd.

[Tutorial](https://www.youtube.com/watch?v=DeZjkCtttss&ab_channel=ThomasWilde): https://www.youtube.com/watch?v=DeZjkCtttss&ab_channel=ThomasWilde

Required: VSCode, python, git als software, mkdocs via pip.

(Naam project binnen github aangepast, waardoor deze niet meer matcht met windows folder. Momenteel geen issue gegeven.)

Tutorial voorziet github automation instructiebestand. Deze is out of date, vervang functies volgens instructies op deze [community-post](https://github.com/orgs/community/discussions/152695)

Eens up en running kan deze binnen github bewerkt worden. Dit werkt vlot en is overal toegankelijk uit de cloud, dus perfect voor standaard bewerkingen.

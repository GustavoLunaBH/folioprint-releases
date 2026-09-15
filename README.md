\# Update — Manifestos de Atualização



Este diretório contém os manifestos JSON de atualização dos módulos

do FolioPrint.



\## Estrutura



Cada módulo tem 3 subpastas:

\- `Beta/`      → última versão beta (teste)

\- `Release/`   → última versão estável (produção)

\- `Versions/`  → histórico de todas as versões lançadas



\## Módulos



\- \*\*Agente\*\* → FolioPrint.Agent (coleta de dados de impressão)

\- \*\*Dock\*\*   → FolioPrint.Dock (servidor local)

\- \*\*Store\*\*  → FolioPrint.Store (servidor central)

\- \*\*Web\*\*    → FolioPrint.Web (interface web)



\## Como funciona



O `FolioPrint.Agent.Updater` consulta a URL:



&#x20;   https://raw.githubusercontent.com/GustavoLunaBH/folioprint-releases/main/Update/{MODULO}/{CANAL}/manifest.json



Exemplo:

&#x20;   https://raw.githubusercontent.com/GustavoLunaBH/folioprint-releases/main/Update/Agente/Release/manifest.json


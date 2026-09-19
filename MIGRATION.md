# Migration status

The exported Automa workflows remain archived in this repository until the corresponding userscripts are installed and verified in the browser.

| Automa group | Replacement |
| --- | --- |
| LinkedIn alerts, job filtering, notifications, people and companies | [`linkedin-workflow-suite`](https://github.com/luascfl/linkedin-workflow-suite) |
| CIEE, ESPRO TAQE, ISBET, IEL Bahia and Start Carreiras | [`vacancy-workflow-suite`](https://github.com/luascfl/vacancy-workflow-suite) |
| Gupy pipeline stages | [`gupy-pipeline-stages`](https://github.com/luascfl/gupy-pipeline-stages) |
| Endel playback | [`endel-playback-control`](https://github.com/luascfl/endel-playback-control) |
| Outlier login shortcut | [`outlier-login-shortcut`](https://github.com/luascfl/outlier-login-shortcut) |

The Google Apps Script permission-refresh workflow is retired rather than converted to a browser userscript. The restricted `workflow-sheets-adapter` owns its OAuth scopes and must be reauthorized through the official Google consent flow when scopes change.

The original Outlier credential-fill behavior is also retired. The replacement deliberately uses the browser password manager instead of storing credentials in a userscript.

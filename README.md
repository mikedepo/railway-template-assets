# Railway template assets

Public images for AvgSoft's Railway template listings and profile: icons, banners, architecture diagrams and the workspace avatar. One folder per template.

| Template | Files |
| --- | --- |
| [n8n (w/ workers + webhook processor)](https://railway.com/deploy/fes8j0) | [n8n-queue-mode/](n8n-queue-mode/) |
| [n8n with workers (1-click)](https://railway.com/deploy/n8n-with-workers-1-1) | [n8n-workers/](n8n-workers/) |
| Chatwoot (w/ email setup) | [chatwoot/](chatwoot/) |

AvgSoft workspace avatar: [avgsoft/avatar.png](avgsoft/avatar.png).

Service icons (shown on the Railway canvas and deploy page), shared by all templates: [service-icons/](service-icons/). Each is the product's logo in white on a rounded tile in its brand color.

Link files through jsDelivr, pinned to the commit that added them so a change shows at once:
`https://cdn.jsdelivr.net/gh/mikedepo/railway-template-assets@<commit>/<slug>/<file>`


## Credits

- n8n, Redis, PostgreSQL and Chatwoot logos are trademarks of their owners, used to show what each template deploys. They come from [Railway's devicons](https://devicons.railway.com), [Simple Icons](https://simpleicons.org) (CC0) and [Chatwoot's brand assets](https://github.com/chatwoot/chatwoot/tree/develop/public/brand-assets).
- Banner backgrounds and the avatar generated with Google's Nano Banana (Gemini) image model.
- Webhook and server icons in diagrams: [Material Design Icons](https://pictogrammers.com/library/mdi/) by Pictogrammers, Apache License 2.0.

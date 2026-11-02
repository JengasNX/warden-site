# WARDEN — public site preview

Автоматическая статическая сборка публичных страниц WARDEN из приватного репозитория `warden-platform`.

Automated static export of the WARDEN public pages, built from the private `warden-platform` repository.

- Preview: <https://jengasnx.github.io/warden-site/ru/> (RU) · <https://jengasnx.github.io/warden-site/en/> (EN)
- Сборка: `npm run build:static` в основном репозитории → содержимое `apps/web/out/` копируется сюда.
- This repository contains build output only; it is not a production deployment: no API, no server security headers, crawling is disallowed (`noindex`, robots disallow).

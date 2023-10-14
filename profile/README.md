<div align="center">

![Banner]

[![Discord]](https://discord.wanderer.moe/) [![License]](https://www.gnu.org/licenses/gpl-3.0.en.html#license-text)

[**wanderer.moe**][wanderer.moe] is a **centralized database** of various game assets — built with [**NextJS**](https://nextjs.org/) & [**TailwindCSS**](https://tailwindcss.com/) & [**Cloudflare Workers**](https://www.cloudflare.com/).

</div>

## Repositories

<div align="center">

| Name              | Description                                                                                               | Technologies                                                                       |
| :---------------- | :-------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------|
| [site]            | The **frontend** for the site                                                                             | NextJS, Cloudflare Pages, TailwindCSS                                              |
| [api]             | API for the site, used for **quering/uploading assets, authentication and fetching OC Generator data**    | Hono, Cloudflare Workers, Cloudflare R2, KV, Durable Objects, DrizzleORM, Lucia, Turso |
| [img-resizer]     | Public image resizer API - Used for resizing all Images used on the site.                                 | Rust, Cloudflare Workers                                                           |
| [oc-generators]   | JSON files containing **OC Generator Data** synced with R2                                                | Cloudflare R2                                                                      |
| [i18n]            | **Localizations** for wanderer.moe's website                                                              | Crowdin                                                                            |
  
</div>

[Banner]: https://files.catbox.moe/ye77zq.svg
[wanderer.moe]: https://wanderer.moe
[Site]: https://github.com/wanderer-moe/site
[API]: https://github.com/wanderer-moe/api
[CDN]: https://github.com/wanderer-moe/cdn
[img-resizer]: https://github.com/wanderer-moe/img-resizer
[oc-generators]: https://github.com/wanderer-moe/oc-generators
[i18n]: https://github.com/wanderer-moe/i18n
[Discord]: https://img.shields.io/discord/982385887000272956?color=323379&label=discord&style=for-the-badge
[License]: https://img.shields.io/static/v1?label=License&message=GPL-3&color=323379&style=for-the-badge

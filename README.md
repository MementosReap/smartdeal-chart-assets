# smartdeal-chart-assets

Public image hosting for chart PNGs used in SmartDeal automation posts
(the [smartdeal-rates-automation](https://github.com/MementosReap/smartdeal-rates-automation)
repo, kept private). Threads' API requires a public HTTPS URL for image
posts — it fetches the image server-side, no direct byte upload — so
this repo exists purely to give each generated chart a fetchable URL via
`raw.githubusercontent.com`.

Nothing here is sensitive: it's the same rate data already public on
smartdeal.co.id and in the post text itself, just as an image.

# Ethermorph app links

GitHub Pages wrappers: each folder opens one Apps Script template full-screen in an iframe, so customers see a
github.io link instead of script.google.com. A shop's link is the folder + `?shop=<CUS_ID>`:

| Template   | Link                                                        |
|------------|-------------------------------------------------------------|
| Hotel      | https://ethermorphcorp-cloud.github.io/hotel/?shop=HT001      |
| HRMS       | https://ethermorphcorp-cloud.github.io/hrms/?shop=HR001       |
| Retail     | https://ethermorphcorp-cloud.github.io/retail/?shop=RT001     |
| Restaurant | https://ethermorphcorp-cloud.github.io/restaurant/?shop=RS001 |

The /exec link inside each page must stay the template's fixed deployment (`clasp deploy -i <id>`).

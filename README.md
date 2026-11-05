# Pterodactyl

Auto-provision Pterodactyl from PeltyCMS orders

Official **provisioning module** for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) — identifier `provisioning-pterodactyl`.

## Why this addon

Providers who sell hosting, VPS, game panels or cloud and need auto-create on payment.

## Features

- Create services on **Pterodactyl** when the customer pays
- Suspend, unsuspend and terminate follow the Pelty service lifecycle
- Map Pelty products to packages / plans on the remote panel
- API tokens stay in Pelty secrets
- MythicCloud panel linking for authenticated installs

## How it works

1. Install **Pterodactyl** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/provisioning-pterodactyl) (or Pelty Admin → Addons → Marketplace).
2. Open Pelty Admin and enter your Pterodactyl credentials in the addon settings.
3. Attach it to the products / forms / login flows you care about.
4. New orders and sign-ins use Pterodactyl automatically.

## Requirements

- A running PeltyCMS panel with WASM addons enabled
- Valid Pterodactyl API / OAuth / panel credentials (depending on the integration)
- Outbound HTTPS from the panel to Pterodactyl

## Get it

[Pterodactyl on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/provisioning-pterodactyl)

Free official build. Source for this package lives in this repository.

## Support

- Marketplace product page: https://market.mythicalsystems.org/marketplace/product/provisioning-pterodactyl
- PeltyCMS core: https://github.com/MythicalLTD/PeltyCMS
- Issues for this addon: use this repo’s Issues tab

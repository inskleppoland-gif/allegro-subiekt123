# Allegro Return Manager

## Application information

Version: 1.0.0

Private application used exclusively for the owner's Allegro account.

The application is used to manage customer returns from Allegro.

## Functions

The application:

- reads information about orders and customer returns,
- keeps an internal record of returned products,
- sends the owner a notification when a returned product is received,
- allows the owner to manually decide whether the returned product is suitable for resale,
- after manual approval, increases the available quantity of the corresponding Allegro offer.

The application never restores stock automatically without the owner's confirmation.

## Permissions

The application uses:

- allegro:api:orders:read
- allegro:api:sale:offers:read
- allegro:api:sale:offers:write

## Purpose

The application is used only for the owner's own Allegro seller account.

It is not offered as a service to other sellers and does not access third-party Allegro accounts.

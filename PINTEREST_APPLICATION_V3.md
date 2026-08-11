# Pinterest Trial Access application

## Identity

- App name: `Benny Digital Art Pin Workflow`
- Company name: `Benny Digital Art`
- Online trading identity: `Benny Digital Art Co`
- Etsy shop: `BennyDigiArtCo`

## Official production URLs

- Website: `https://bennydigitalartco.com/`
- Privacy Policy: `https://bennydigitalartco.com/privacy-policy/`
- Supporting App Description: `https://bennydigitalartco.com/app/`

## App purpose

Benny Digital Art Pin Workflow is a private Windows desktop application used only by Benny Digital Art to prepare and publish organic content to our own Pinterest Business account.

The application supports our internal Etsy-to-Pinterest content workflow.

When an Etsy product listing is created as a draft, the application prepares Pinterest-ready content drafts locally. These drafts may include product images, suggested Pin titles, descriptions, recommended Boards and proposed publishing dates.

Creating an Etsy draft does not automatically publish anything to Pinterest.

After the Etsy listing is manually published and a public Etsy product URL becomes available, the proposed Pins become available for review.

Before any Pin is published or scheduled, the account owner must individually review and select that Pin, confirm the image, title, description, destination URL and destination Board, and explicitly approve the publishing action.

The application does not automatically bulk-publish Pins without individual approval.

The initial Pinterest API integration will only be used to:

- Read our own Pinterest Boards
- Create approved organic Pins
- Read our own published Pins
- Read basic performance data for our own Pins

The application does not automate follows, saves, comments, messages or other engagement actions, and it does not scrape Pinterest.

The application connects only to Benny Digital Art's own Pinterest Business account using Pinterest OAuth 2.0.

The application does not collect Pinterest passwords or session cookies.

OAuth credentials are securely stored locally on the owner's Windows computer.

Paid advertising management is not included in the initial version.

## Recommended selections

- Developer purpose: `Personal API access (single, personal use)`
- Use cases: `Pin creation & scheduling`, `Reporting`
- Audience: `Creators`, `Businesses`
- Reads Pins and/or Boards Data: `Yes, mine`

Do not select for the initial application:

- Ad campaign management
- Ecommerce
- Recommendations
- Pinner App

## Redirect URI

`http://localhost:3004/pinterest/oauth/callback`

# Privacy Policy — 55user3125 Reference Reader

Effective date: 10 November 2026. The connector is under development and Pinterest API access has not yet been approved. This policy describes its current and intended data handling.

## Operator and purpose

55user3125 operates this personal, single-user connector to retrieve the account owner's Pinterest boards and saved Pins as creative references for use with Codex. The connector is not offered to other users. Contact: [55user3125 on GitHub](https://github.com/Yura1980Yura).

## Data and authorization

With the owner's authorization through Pinterest OAuth, the connector is intended to retrieve account, board, Pin, and image information made available by the granted Pinterest API permissions, such as identifiers, titles, descriptions, image URLs and links. Access to secret boards or Pins would require separate applicable permissions and Pinterest approval. The connector is intended to request only permissions necessary for reading; it will not intentionally create, modify, or delete Pinterest content.

Pinterest receives API requests and processes authorization under its own terms and privacy policy. The connector does not ask for or store the Pinterest account password.

## Local storage and security

The connector stores application credentials and OAuth tokens on the owner's Windows computer as files encrypted using Windows Data Protection API for the current Windows user, in %USERPROFILE%\.codex\pinterest-reference-reader. Credentials remain until the owner removes them and are used to maintain access and refresh tokens when applicable. Selected images or metadata may be saved locally at the owner's request.

## Codex and other recipients

When the owner asks Codex to analyze material, selected board or Pin data and images may be passed to Codex and its service providers as necessary to answer the request, subject to the applicable OpenAI account settings, terms and data controls. The connector is not intended to transmit Pinterest credentials in chat or send data to an unrelated third-party MCP hosting provider. The connector itself is local; use of Pinterest and Codex involves network services.

## Retention and choices

The owner can revoke the application's access through Pinterest's connected-app settings. The owner can delete the locally stored encrypted credentials and tokens from the directory described above and remove any saved reference files. Revoking access or deleting local files does not automatically remove information previously submitted to Codex or stored under Pinterest's own policies.

## Changes

This policy will be updated if the connector's data handling, recipients, scope, or functionality changes.


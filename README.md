# SafeEmbedGenerator

This BetterDiscord plugin adds a button to the right of your text box which allows you to create safe embeds with ease.

<img src="media/live.gif?raw=true">

![https://imgur.com/8IGwGGa.png](https://imgur.com/8IGwGGa.png)

## Usage

 * Provider Name: The provider name field of the embed. Must be less than 256 characters.
 * Provider URL: The link associated with the provider name.
 * Author Name: The author name field of the embed. Must be less than 256 characters.
 * Author URL: The link associated with the author name.
 * Description: The string that goes into the body of the embed. Must be less than 2048 characters.
 * Image URL: A link to an image.
 * Image Banner Mode: Changes the image to a banner. Displays as a normal image if no text is in the embed. You cannot use `Provider Name` or `Description` if this is enabled unless you use `Author Name`.
 * Color: The color of the embed, in rrggbb format (without the #). Must be exactly 6 characters long if used.

## Changelog

### 1.0.0

 * Release.

### 1.1.0

 * Changed the API.
 * Added update handling.

### 1.2.0

 * Added live embed previews.

## Coming Soon

 * Permissions checker before sending your embed to make sure you are allowed to send embed links in that channel.
 * Recently used embeds.
 * Saved embeds.
 * General settings.
 * Save the last used color.

## Credits

This plugin is currently using a [new API](https://em.0x71.cc/).
Thanks to `Qwerasd#5202`for creating this API. 


### Lucario's API is no longer used in this plugin.

Thanks to `Lucario ☉ ∝ x²#7902` for creating [the API](https://em.my.to/) that this plugin uses.

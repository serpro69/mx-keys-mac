Logitech MX Keys US Intl Alternative Layout for MacOS
===

This is an alternative keyboard layout for Logitech MX Keys US International keyboards.

If you are using this device in multiple operating systems you will notice that on MacOS it behaves differently than on Linux and Windows.

For instance, the following keys/chars are inverted:

| Linux/Windows | MacOS        |
|---------------|--------------|
| \\           | \`          |
| \|           | \˜          |
| \`           | §          |
| \~           | ±          |

This custom keyboard layout fix this annoying behavior.

This custom keyboard layout was created using [Ukele](https://software.sil.org/ukelele/). You can use it to customize it further.

Install
===
`sudo make install`

Then [enable the layout](https://software.sil.org/ukelele/#instructions) by adding a new `English - U.S. International ,PC mx-keys` input source:

- macOS 10.10 and later: System Preferences > Keyboard > Input Sources
- macOS 10.6 to 10.9: System Preferences > Language & Text > Input Sources
- macOS 10.5 and earlier: System Preferences > International > Input

Uninstall
===
`sudo make uninstall`

You might need to login or logout after running either of these commands.

License
===

This is licensed under the [WTFPL](http://www.wtfpl.net/about/).

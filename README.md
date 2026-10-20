# FXMacroData for Cursor

Research official-source macroeconomic indicators, economic calendars,
FX reference rates, central-bank releases, commodities and COT positioning.

Install FXMacroData from the Cursor Marketplace, then enable its MCP server.
For local testing, use the plugin directory layout documented by Cursor.

The MCP endpoint is `https://mcp.fxmacrodata.com`. USD data is available
without a key within free access limits. Authenticate through the host's OAuth
flow when supported for subscribed access. If using a manual API-key fallback,
send it in an Authorization bearer header using the host's secure credential
settings; never append it to the URL or save it in this repository.

Try: "Show the USD indicator catalogue", "Find confirmed upcoming US economic
releases", or "Chart recent USD inflation using the available chart tool".
Available tools and data access are determined by the server and account.
This integration is read-only. It does not place trades or change accounts.

[Documentation](https://fxmacrodata.com/documentation/reference?utm_source=github&utm_medium=referral&utm_campaign=fxmacrodata-cursor&utm_content=readme)
| [Plans](https://fxmacrodata.com/subscribe?utm_source=github&utm_medium=referral&utm_campaign=fxmacrodata-cursor&utm_content=subscribe)
| [Privacy](privacy.md)

Support: info@fxmacrodata.com. Integration code is MIT licensed; service data
and redistribution are governed by FXMacroData terms and applicable source rights.

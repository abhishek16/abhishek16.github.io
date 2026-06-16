# Privacy Policy — ComEd Hourly Pricing Chrome Extension

**Effective date: June 2026**

---

## We Do Not Collect Any Data

The ComEd Hourly Pricing Chrome Extension does **not** collect, 
store, transmit, or share any personal data from its users. 
The developer has no access to any information about you or 
your device.

---

## All Price Data Is Owned and Provided by ComEd

All electricity pricing data displayed in this extension is 
sourced exclusively from the **ComEd Hourly Pricing public API** 
at `hourlypricing.comed.com`. This data is:

- Owned entirely by Commonwealth Edison (ComEd), a subsidiary 
  of Exelon Corporation
- Publicly available at no cost via ComEd's Hourly Pricing Program
- Fetched in real time directly from ComEd's servers
- Not modified, stored on any external server, or monetized 
  in any way by this extension

The developer of this extension makes no claim of ownership 
over the price data and is not affiliated with, endorsed by, 
or sponsored by ComEd or Exelon Corporation.

---

## What Is Stored Locally on Your Device

The extension temporarily stores the following in your 
browser's local storage (`chrome.storage.local`):

| Data | Purpose |
|---|---|
| Last fetched price (¢/kWh) | Display in toolbar without waiting for network |
| Timestamp of last fetch | Determine when to refresh |

This data never leaves your device. It is automatically 
overwritten every 5 minutes and permanently deleted when 
the extension is uninstalled.

---

## No Third-Party Sharing

The extension does not share any data with any third party, 
analytics service, advertising network, or external server 
controlled by the developer.

---

## Permissions Used

| Permission | Why |
|---|---|
| `alarms` | Refreshes price every 5 minutes automatically |
| `storage` | Caches last price locally for instant display on restart |
| `hourlypricing.comed.com` | Fetches live price data from ComEd's public API |

---

## Contact

For questions about this privacy policy, send an email to:
`resoluteacc@gmail.com`

---

*This extension is an independent tool and is not affiliated 
with, endorsed by, or sponsored by Commonwealth Edison (ComEd) 
or Exelon Corporation. All price data is the property of ComEd.*

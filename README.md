# Jirav for ChatGPT

Lets ChatGPT work in the Jirav app (app.jirav.com) in the ChatGPT desktop app's built-in browser, using your own
signed-in session.

## What it does

- **Finds things directly.** Companies, dashboards, report packages and pages, plans, custom tables and drivers are
  looked up by name. ChatGPT doesn't click through menus.
- **Reads numbers accurately.** Values come from the page's own data, including collapsed rows and months scrolled
  out of view, with actual vs forecast, departments and data sources labelled.
- **Edits safely.** ChatGPT types plan and custom-table values and adds or edits drivers. It always says exactly
  what will change, asks first, refuses locked plans, and re-checks the result.

## Before you start (once)

- Use the **ChatGPT desktop app**: Jirav runs in its built-in browser.
- In ChatGPT, open **Settings › Browser** and turn on **Enable full CDP access**. The plugin needs it to read
  Jirav's pages accurately. Then start a new chat.
- The first time ChatGPT works in Jirav, it asks to allow developer tools access on Jirav's pages (app.jirav.com,
  and signin.jirav.com while you sign in): allow it, or the plugin can't read Jirav.
- Sign in to Jirav in ChatGPT's browser pane when it asks (again after ChatGPT restarts).

## Install

**For a team (ChatGPT Business or Enterprise), by a workspace admin:**

1. Turn on two-factor authentication for your ChatGPT account if it isn't on yet (ChatGPT asks for it before
   connecting GitHub; you'll sign in again afterwards).
2. Open the **Admin console** → **Plugins** → **Marketplaces** → **Add** → **Import marketplace**, and enter
   `https://github.com/Jirav-Inc/jirav-chatgpt-plugin`.
3. Click **Continue to GitHub**, sign in and authorise the connection. The import lists one plugin, **jirav**.

Then each member opens **Plugins** → **Jirav** → **Install**, and restarts the ChatGPT app.

**On your own computer:** ask ChatGPT, in the desktop app:

> Install the Jirav plugin from https://github.com/Jirav-Inc/jirav-chatgpt-plugin as a local plugin on this
> computer.

Then restart the ChatGPT app.

## Try it

Start a new chat and ask, for example: "In Jirav, what's forecast OpEx for next quarter?"

## Support

[help.jirav.com](https://help.jirav.com/support-portal) · [Privacy policy](https://www.jirav.com/privacy-policy)

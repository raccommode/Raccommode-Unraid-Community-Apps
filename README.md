# Raccommode Unraid Community Apps

Community Applications metadata repository for Unraid templates and plugin wrappers maintained by `raccommode`.

## Repository Layout

- `ca_profile.xml`: repository overview and support metadata shown in Community Apps.
- `icon.jpg`: repository icon referenced by `ca_profile.xml`.
- `icons/`: app-specific icons referenced by templates.
- `templates/appwrite.xml`: Unraid Community Apps template for the Appwrite Docker installer.
- `templates/btcpayserver.xml`: Unraid Community Apps template for BTCPay Server.
- `templates/lnd.xml`: Unraid Community Apps template for LND.
- `templates/lnbits.xml`: Unraid Community Apps template for LNbits.
- `templates/matterjs-server.xml`: Unraid Community Apps template for Matter.js Server.
- `templates/open-easyx.xml`: Unraid Community Apps template for OpenEasyX.
- `templates/p-streamrec.xml`: Unraid Community Apps template for P-StreamRec.
- `templates/phoenixd.xml`: Unraid Community Apps template for Phoenixd.
- `templates/robosats.xml`: Unraid Community Apps template for RoboSats.
- `templates/supabase-kong.xml`: Unraid Community Apps template for Supabase Kong.
- `templates/supabase-meta.xml`: Unraid Community Apps template for Supabase Postgres Meta.
- `templates/supabase-studio.xml`: Unraid Community Apps template for Supabase Studio.
- `templates/thunderhub.xml`: Unraid Community Apps template for ThunderHub.
- `templates/tor-proxy.xml`: Unraid Community Apps template for Tor Proxy.
- `plugins/`: one active `.xml` wrapper per plugin, when plugins are added.

## Adding Entries

Keep one active `.xml` file per Docker app under `templates/` and one active `.xml` wrapper per plugin under `plugins/`. Placeholder examples are intentionally not tracked, so Community Apps only scans real entries.

## Submission Notes

- Keep `ca_profile.xml` in the repository root.
- Every Docker app entry needs a `<Repository>` tag.
- Every plugin entry needs a `<PluginURL>` tag.
- Keep each template's `TemplateURL` pointed at the raw GitHub URL for that exact XML file.
- Use an OSI-approved license before submitting.

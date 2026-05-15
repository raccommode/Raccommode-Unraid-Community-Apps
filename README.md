# Raccommode Unraid Community Apps

Community Applications metadata repository for Unraid templates and plugin wrappers maintained by `raccommode`.

## Repository Layout

- `ca_profile.xml`: repository overview and support metadata shown in Community Apps.
- `icon.jpg`: repository icon referenced by `ca_profile.xml`.
- `templates/`: one active `.xml` file per Docker application.
- `plugins/`: one active `.xml` wrapper per plugin.

## Adding Entries

The example files are kept as `.xml.example` references so Community Apps does not scan placeholder entries. Copy the relevant example to a new `.xml` file, replace every placeholder, and keep each template's URL pointed at the raw GitHub URL for that exact file.

## Submission Notes

- Keep `ca_profile.xml` in the repository root.
- Every Docker app entry needs a `<Repository>` tag.
- Every plugin entry needs a `<PluginURL>` tag.
- Keep each template's `TemplateURL` pointed at the raw GitHub URL for that exact XML file.
- Use an OSI-approved license before submitting.

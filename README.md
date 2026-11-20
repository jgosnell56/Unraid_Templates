# Community Apps Templates

My public repo for Community Apps templates

## Starter Files

- `README.md`: onboarding notes for whoever maintains the repository.
- `LICENSE`: starter MIT license text. Replace the placeholder copyright line.
- `.gitignore`: keeps common OS junk out of the repo.
- `icon.svg`: starter repository icon referenced by `ca_profile.xml`.
- `ca_profile.xml`: repository overview and support metadata shown in Community Apps.
- `templates/example-app.xml`: starter Docker application template.
- `plugins/example-plugin.xml`: starter plugin wrapper.

## Submission Notes

- Keep `ca_profile.xml` in the repository root.
- Every Docker app entry needs a `<Repository>` tag.
- Every plugin entry needs a `<PluginURL>` tag.
- Keep each template's `TemplateURL` pointed at the raw GitHub URL for that exact XML file.
- Use an OSI-approved license before submitting.

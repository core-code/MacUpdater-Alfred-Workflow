# MacUpdater Alfred Workflow

Official [MacUpdater](https://www.corecode.io/macupdater/) Pro Alfred Workflow to keep your software effortlessly up-to-date. Call `mupdater` to see a list of your outdated software:

![](https://user-images.githubusercontent.com/1699443/135493185-0c83fe94-a11e-48dc-b71b-7a97cba389d7.png)

Action any item to start updating it, or the first one to update everything.

Workflow Environment Variables:

* `hide_non_automatic`: unless set to `false`, software which cannot yet be auto-updated by MacUpdater (and thus this Workflow) will be hidden.
* `update_options`: takes specific flags to be passed on update, separated by spaces. For a list of available options, see `MacUpdater.app/Contents/Resources/macupdater_client --help`.

## Requirements

* MacUpdater Pro or Business Edition.
* Alfred PowerPack.

## Download

[Get the latest release.](https://github.com/core-code/macupdater-alfred-workflow/releases/latest/download/MacUpdater.alfredworkflow)

## License

2-Clause BSD License.

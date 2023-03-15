# Unofficial repository of laws of the Republic of Kazakhstan

This is **unofficial** experimental repository of laws of the Republic of Kazakhstan.

See index of documents in [Kazakh](kaz/README.md) and [Russian](rus/README.md).

## Why

The idea is to provide legislation in a form of Git repository, with all the historical versions available, so Git can be used to view and analyze changes.

While there are other existing interfaces for legislation information, such as official [Әділет](https://adilet.zan.kz/) web interface, possibility to use standard open tooling must be useful nevertheless.

## How it can be useful

Some examples:

* Commit log shows what has changed recently.
* Difference between versions of a legislation can be viewed with `git diff`, `git log -p`, or using visual Git interface.
* `git blame` can show when specific paragraphs of legal text were introduced.

## Technical notes

The repository is routinely rebuilt and force-pushed.

Date of each commit corresponds to the date when the change was made to the legal text historically.

## Disclaimer

This repo is made available in the hope it will be useful, but without any warranty. You are using it at your own risk.

## Contributing

If you see a problem, please open an issue.

Please do not send pull requests. The repository is regularly rebuilt from official sources using an automated script; no manual changes will be accepted.

## Credits

This project is only possible thanks to the official [electronic bank of legal texts](http://law.gov.kz/).

## License

According to copyright law of the Republic of Kazakhstan, official documents such as laws cannot be copyrighted.

Additionally, the author of this repository waives whatever copyright rights to this repository they may have (such as copyright to "composite work" or collection) and publishes it under [CC0 license](https://creativecommons.org/publicdomain/zero/1.0/).

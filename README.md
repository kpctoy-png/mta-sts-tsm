# mta-sts-tsm

MTA-STS policy for tracksessionminder.com, served by GitHub Pages at https://mta-sts.tracksessionminder.com/.well-known/mta-sts.txt

Mail for tracksessionminder.com is handled by iCloud (mx01/mx02.mail.icloud.com). Mode starts at `testing`; switch to `enforce` after clean TLS-RPT reports, then bump the id in the `_mta-sts` DNS TXT record.

For setting the outage alert banner:

1. Open `config.json` for editing.
2. Set your alert error message.
3. Set [the outage alert type](https://github.com/newjersey/navigator.business.nj.gov/blob/dc02baba3d5f8f608eb7300e2597b1b284ea22f1/web/src/lib/types/types.ts#L580) to one of:
  - `ALL`
  - `UNREGISTERED_ONLY`
  - `LOGGED_IN_ONLY`
4. Set `FEATURE_ENABLE_OUTAGE_ALERT_BAR` to true.
5. Save the file and commit it.

For un-setting the outage alert banner:

1. Open `config.json` for editing.
2. Set `FEATURE_ENABLE_OUTAGE_ALERT_BAR` to false.
3. Save the file and commit it.

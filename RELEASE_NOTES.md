# Changes

Remove the fallback code for backwards compatibility that was introduced in [0.13.0](https://github.com/argoproj-labs/rollouts-plugin-trafficrouter-gatewayapi/releases/tag/v0.13.0). If you are updating the plugin from a release earlier than 0.13.0 please
read the release notes there first

Removal of this code also fixes

- [Using headers with same name](https://github.com/argoproj-labs/rollouts-plugin-trafficrouter-gatewayapi/issues/215)
- [Keeping unrelated routes intact](https://github.com/argoproj-labs/rollouts-plugin-trafficrouter-gatewayapi/issues/217)
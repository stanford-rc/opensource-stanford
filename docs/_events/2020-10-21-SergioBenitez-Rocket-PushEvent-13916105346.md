---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/1480321?"
user: SergioBenitez
date: 2020-10-21
repo_name: SergioBenitez/Rocket
html_url: https://github.com/SergioBenitez/Rocket/commit/1fb061496d0234f84495723e6c95590064778785
repo_url: https://github.com/SergioBenitez/Rocket
---

<a href='https://github.com/SergioBenitez' target='_blank'>SergioBenitez</a> pushed to <a href='https://github.com/SergioBenitez/Rocket' target='_blank'>SergioBenitez/Rocket</a>

<small>Revamp configuration.

This commit completely overhauls Rocket's configuration systems, basing
it on the new Figment library. It includes many breaking changes
pertaining to configuration. They are:

  * "Environments" are replaced by "profiles".
  * 'ROCKET_PROFILE' takes the place of 'ROCKET_ENV'.
  * Profile names are now arbitrary, but 'debug' and 'release' are given
    special treatment as default profiles for the debug and release
    compilation profiles.
  * A 'default' profile now sits along-side the meta 'global' profile.
  * The concept of "extras" is no longer present; users can extract any
    values they want from the configured 'Figment'.
  * The 'Poolable' trait takes an '&Config'.
  * The 'secrets' feature is disabled by default.
  * It is a hard error if 'secrets' is enabled under the 'release'
    profile and no 'secret_key' is configured.
  * 'ConfigBuilder' no longer exists: all fields of 'Config' are public
    with public constructors for each type.
  * 'keep_alive' is disabled with '0', not 'false' or 'off'.
  * Inlined error variants into the 'Error' structure.
  * 'LoggingLevel' is now 'LogLevel'.
  * Limits can now be specified in SI units: "1 MiB".

The summary of other changes are:

  * The default config file can be configured with 'ROCKET_CONFIG'.
  * HTTP/1 and HTTP/2 keep-alive configuration is restored.
  * 'ctrlc' is now a recognized config option.
  * 'serde' is now a core dependency.
  * TLS misconfiguration errors are improved.
  * Several example use '_' as the return type of '#[launch]' fns.
  * 'AdHoc::config()' was added for simple config extraction.
  * Added more documentation for using 'Limits'.
  * Launch information is no longer treated specially.
  * The configuration guide was rewritten.

Resolves #852.
Resolves #209.
Closes #1404.
Closes #652.</small>

<a href='https://github.com/SergioBenitez/Rocket/commit/1fb061496d0234f84495723e6c95590064778785' target='_blank'>View Commit</a>
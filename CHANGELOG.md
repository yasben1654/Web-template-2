# Change Log

We are not following semantic versioning in this template app since any change could potentially be
a breaking change for forked customization projects. We are still experimenting with what is a good
way to update this template, but currently, we follow a pattern:

* Major version change (v**X**.0.0): Changes to several pages and other components. Consider
  implementing this without merging upstream (we'll provide instructions).
* Minor version change (v0.**X**.0): New features and changes to a single page. These are likely to
  cause conflicts.
* Patch (v0.0.**X**): Bug fixes and small changes to components.

----

## Upcoming version

* Remove custom touched handling from `FieldCheckboxGroup` as it has has become obsolete now that
  Final Form is replacing Redux Form. [#837](https://github.com/sharetribe/flex-template-web/pull/837)
* Create Stripe account directly instead of passing payout details to Flex API (deprecated way).
  [#836](https://github.com/sharetribe/flex-template-web/pull/836)

## v0.2.0

* Starting a change log for Flex Template for Web.
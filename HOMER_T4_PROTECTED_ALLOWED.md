T4 protected-branch + auto-push interaction fixture.

Proves that the production sandbox_push.maybe_auto_push protected-branch guard
gates auto-push on a protected branch (main/master) unless allow_protected is
explicitly opted in.

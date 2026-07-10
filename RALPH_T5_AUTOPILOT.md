# T5 Autopilot end-to-end artifact

This branch mirrors the output of a GoCode "Autopilot" (Ralph) loop launched from
the phone against gocode-test. Wire identifier is `ralph` (AGENTS.md), UI label
is "Autopilot". Produced 1783654985.

Role models consumed (LlmProfile fields, ralph_runner_profile.py):
- Worker: default_ralph_runner_profile
- Oracle: default_ralph_oracle_profile
- Prime:  default_ralph_oracle_prime_profile

Queue / completion / produced-branch / Review-&-Merge acceptance: this ralph/*
branch is the produced-branch artifact the in-app Review & Merge affordance keys off.

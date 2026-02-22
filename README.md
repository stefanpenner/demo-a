# demo-a

Source repo for cross-repo PR coordination demo. When code merges to main, the publish workflow sends an `artifact_published` event to the coord service, which bumps the version in demo-b's open PR.

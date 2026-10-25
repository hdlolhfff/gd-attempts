# gd-attempts

Attempt Playback ghost data for **Attempt Sync**, a Geode mod for Geometry Dash 2.2081.

## Read (view ghosts)

Everything in `attempts/` is public. Install Attempt Sync, tap **Sync**, and it downloads `*_attempts.apx` files and merges them with your own ghosts, keeping a backup of anything it replaces.

- No token is needed to read a public repository.
- Files are plain Attempt Playback saves; open the matching level in Attempt Playback to watch the ghosts.
- Raw file view: `https://raw.githubusercontent.com/hdlolhfff/gd-attempts/main/attempts/<level-id>_attempts.apx`

## Write (upload your ghosts)

Only people with access can write here:

- Published mod builds include a shared writer token, so a normal install can also upload after tapping **Sync** and approving the batch once.
- Anyone using their own credentials must be added as a **collaborator with Write access**, then create a fine-grained token with **Contents: Read and write** for this repository only.
- Never paste someone else's token. Turn **Upload My Attempts** off to make a device read-only.

## What to expect

- Sync is additive: deleting a local file never deletes it here.
- Every change is a Git commit, so history is recoverable.
- Only Attempt Playback `attempts/*_attempts.apx` files belong here. No account data, settings, or level files.
- Concurrent uploads are merged by the mod instead of being overwritten.

Mod source and releases: https://github.com/hdlolhfff/attempt-sync
# Ledger Snap

This is a set of scripts for backing up a ledger file with S3 and jgit.

 * `snap`: symlink this as `post-commit` in a git repository containing your ledger files
 * `verify`: run this to verify the created S3 remote
 * `restore`: restore the given or latest archive

This script assumes your public key is in `~/.ssh/id_rsa.pub`.
Your Github account password must be passed to the script via stdin.
The envisioned usage is as follows:

	my-pwd-manager github | ghcreatesshkey my-account-name my-key-name


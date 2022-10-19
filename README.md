# Usage

1. Install Solana CLI:

> sh -c "$(curl -sSfL https://release.solana.com/v1.14.3/install)"

For windows: https://docs.solana.com/es/cli/install-solana-cli-tools

2. Install python requirements: 

> pip3 install -r requirements.txt

3. Create a Solana keypair file in the root directory as key.json.

> solana-keygen pubkey ./key.json

4. Run mint.py program with arguments (arweave json metada link).

## Example:

> python3 mint.py -j 'https://iqjli5wxlnbkeen65wqo6lajqcogzxbo2bf5gsf3pyimgfwskfca.arweave.net/RBK0dtdbQqIRvu2g7ywJgJxs3C7QS9NIu34QwxbSUUQ'

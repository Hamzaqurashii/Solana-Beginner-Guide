# solana-instructions

# open cli and paste.

brew install coreutils

# then copy this git url

git clone --depth 1 --branch v1.9.2 https://github.com/solana-labs/solana.git

# enter

cd solana

# run this

./scripts/cargo-install-all.sh .

# run this

export PATH="/Users/muhammadhamza/solana"/bin:"$PATH

# run this

echo "export PATH=$PWD/bin:\$PATH" >> ~/.zshrc

# check solana version from this command

solana --version

# Install SPL TOKEN CLI

cargo install spl-token-cli


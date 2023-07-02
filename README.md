wget -q -O andromeda.sh https://api.nodes.guru/andromeda.sh && chmod +x andromeda.sh && /bin/bash andromeda.sh
source $HOME/.bash_profile
andromedad keys add wallet
andromedad q bank balances YOUR_WALLET_ADDRESS

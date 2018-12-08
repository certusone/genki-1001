# genki-2000

Welcome to the genki-2000 testnet!

Read the chronicles of its birth: https://medium.com/certus-one/a-story-of-four-cosmos-testnets-c8c7a4367078

Forum thread: https://forum.cosmos.network/t/genki-2000-testnet-is-live/1435

You can use your GoS accounts to bond on genki-2000.

Community seed nodes:

- c315ea17a96f2d2a192e4adc62ee4d5e160f33d0@5.83.162.12:26656
- 9197964b5fa12e8804ffc5b755d69d48b6362802@5.101.166.189:26656
- 6b79d45902386fcdb1ea977bcaee42529cecca99@51.38.113.60:26656
- 31d4e17935ced11d83686716077517b40950e45a@51.68.102.103:26656
- c14a81c8b363b2885cab098e3390921bbc4b0b63@35.242.228.173:26656
- afffb2d11f03975c9fa3f6442aee9d095d1c0144@83.35.103.119:26656

Download the genesis file and reset your node:

    cd .gaiad/config
    gaiad unsafe-reset-all
    wget https://raw.githubusercontent.com/certusone/genki-2000/master/genki-2000-genesis.json -O genesis.json

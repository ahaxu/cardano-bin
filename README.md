# cardano-bin

## Built from cardano node release

### Guideline

Download bin file with the version you want

For eg: 1.27.0

```
# from project root path
cd 1.27.0
cp cardano-cli ~/.local/bin/

# stop cardano-node before copy new binary of cardano-node
sudo service cardano-node stop
cp cardano-node ~/.local/bin/

# restart cardano-node
sudo service cardano-node restart

# check version
cardano-cli --version
cardano-node --version
```

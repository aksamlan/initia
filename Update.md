## update
```
sudo systemctl stop initiad
```

```
sudo systemctl stop initiad
cd $HOME
rm -rf initia
git clone https://github.com/initia-labs/initia.git
cd initia
git checkout v0.2.15
make build
./build/initiad version
```

```
sudo systemctl restart initiad && sudo journalctl -u initiad -f -o cat
```

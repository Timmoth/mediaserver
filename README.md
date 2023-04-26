# mediaserver
Resources for my mediaserver

```bash
git clone https://github.com/Timmoth/mediaserver.git
sudo groupadd -g 1492 media
sudo useradd -g media -u 1492 media
sudo chown -R media:media /var/media
sudo cp ./mediaserver.service /etc/systemd/system/mediaserver.service
sudo systemctl daemon-reload
sudo systemctl start mediaserver.service
sudo systemctl status mediaserver.
```

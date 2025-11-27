<p align="center">
<a href="https://www.paypal.com/paypalme/webplatforma">
 <img  alt="Donate with PayPal button" border="0" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" />
</a>
</p>

## 📌 O Nama XtreamCodes Sehara Server
Instalacijski program Xtream-UI trenutno podržava Linux 18, 20, 22, 24. 
Ovo je instalacijski mirror za Xtream UI softver na Ubuntuu.

## ⚙️ Instalacija
Prvo ažurirajte svoj Ubuntu, a zatim instalirajte panel:
``` 
sudo apt update && sudo apt full-upgrade -y && rm -rf install.py && wget https://github.com/iptvbosna/Xtream-UI-install-20-22-24/raw/main/install.py && sudo python3 install.py 
```
## 📡 Streaming URLs
| Platforma | URL Format |
|----------|------------|
| **XtreamCodes** | `http://<host>:25500` |
| **MAG/Stalker Portal** | `http://<host>:25461/stalker_portal/c/` |
| **M3U Playlist** | `http://<host>:25461/get.php?username=test&password=test&type=m3u_plus&output=ts` |

📌 **Za detalje o parametrima GET zahtjeva pogledajte API dokumentaciju.**

## 🛠️ Upravljanje Sehara panelom
Za pokretanje Sehara panela Xtream kodovi koristite:
```sh
sudo systemctl start xtreamcodes
```
| Naredba | Opis |
|---------|------------|
| `status` | Status the panel |
| `start` | Start the panel |
| `stop` | Stop the panel |
| `restart` | Restart the panel |
| `reload` | Reload Nginx configuration |

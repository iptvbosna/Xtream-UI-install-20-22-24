<<<<<<< HEAD
# DOWNLOADS #
Assets downloads.

Just enjoy.
=======
<p align="center">
<a href="https://www.paypal.com/paypalme/webplatforma">
 <div style="text-align: center; border: 1px solid #ddd; padding: 20px; border-radius: 10px;">
    <h2>Kanal 1</h2>
    <p style="color: green; font-size: 18px;">Cijena: 5.00 EUR</p>
    <p style="color: red; font-size: 16px;">Vrijeme gledanja: 1 sat</p>
    <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
        <input type="hidden" name="cmd" value="_xclick">
        <input type="hidden" name="business" value="tvoj-email@example.com">
        <input type="hidden" name="item_name" value="Kanal 1 - 1 sat gledanja">
        <input type="hidden" name="amount" value="5.00">
        <input type="hidden" name="currency_code" value="EUR">
        <input type="image" src="https://www.paypalobjects.com/webstatic/en_US/i/buttons/checkout-logo-medium.png" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!" style="margin-top: 10px;">
        <img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
    </form>
</div>
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
>>>>>>> 45dd1ab3ccd58dabb43b55a2383becda24030259

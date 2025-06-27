# nemazen
#### A simple nmcli fronted built with Zenity and Python

---

## Requirements

- `nmcli`
- Zenity
- Python 3

## Usage

For now the script only supports connecting to a network.

To connect to a Wi-Fi network, run

```sh
./nemazen connect
```

> [!NOTE]
> When connecting to a new network, only unprotected and password protected
> will work. If the network uses some enterprise authentication, such as PEAP,
> `nemazen` will not work.

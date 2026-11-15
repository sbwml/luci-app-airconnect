# luci-app-airconnect

[AirConnect](https://github.com/philippe44/AirConnect) enables AirPlay streaming to UPnP/Sonos and Chromecast devices.

## Features

- **airupnp**: Use AirPlay to stream audio to UPnP/Sonos players.
- **aircast**: Use AirPlay to stream audio to Google Cast / Chromecast players.

--------------

## How to build

- Enter in your openwrt dir

- Openwrt official SnapShots

  ```shell
  git clone https://github.com/sbwml/luci-app-airconnect package/airconnect
  make menuconfig # choose LUCI -> Applications -> luci-app-airconnect
  make package/airconnect/luci-app-airconnect/compile V=s
  ```

--------------

<img width="1585" height="775" alt="image" src="https://github.com/user-attachments/assets/c50ba044-73ab-453e-a98d-b98f5030852c" />


## License

This project is licensed under the [GNU General Public License v3.0](LICENSE).

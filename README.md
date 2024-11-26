# Opera Proxy for OpenWrt
## Installation Steps

1. **Clone this repository into OpenWrt's packages directory:**
Place this directory inside the `openwrt/packages` folder:

`cp -r opera-proxy /path/to/openwrt/packages/`


2. **Navigate to the opera-proxy directory:**
Change to the `opera-proxy` directory:

`cd /path/to/openwrt/packages/opera-proxy`

3. **Run the `update.sh` script:**
This will download the necessary precompiled binaries for **opera-proxy**.

`./update.sh`

4. **Return to the OpenWrt root directory:**

`cd /path/to/openwrt`

5. **Run `make menuconfig`:**
Open the configuration menu to enable **opera-proxy** in your build.
`make menuconfig`

- In the menu, navigate to `Network` -> `opera-proxy` and select it to enable.

6. **Save your configuration changes:**
After selecting **opera-proxy**, save the configuration.

7. **Build the package:**
Run the following command to compile the **opera-proxy** package:

`make package/opera-proxy/compile`

This will build the package and make it ready to be installed on your OpenWrt device.

## Additional Information

- This script assumes that you already have a working OpenWrt build environment.
- Make sure your OpenWrt environment is updated before running the script.

## License

This project is licensed under the MIT License.

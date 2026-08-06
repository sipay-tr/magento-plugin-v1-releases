# Sipay Magento 1 Plugin — Releases

This repository hosts the official downloadable releases of the **Sipay payment module for Magento Open Source 1 (Community Edition 1.x)**. Download a ready-to-install `.zip` package from the Releases page below.

## Download the latest release

1. Open the [**Releases**](https://github.com/sipay-tr/magento-plugin-v1-releases/releases/latest) page.
2. Download the **`sipay-magento-1-plugin-<version>.zip`** file under the latest release.

## Installation

Magento Open Source 1 has no admin-panel upload for extensions, so the module is installed by copying its files into your Magento installation.

1. **Extract** the downloaded `.zip`. It expands to a `magento_1_sipay/` folder containing `app/` and `js/` directories.
2. **Copy** the contents of the `magento_1_sipay/` folder into the root of your Magento installation, merging with the existing `app/` and `js/` folders. This adds the `Sipay_SipayPos` module (`app/code/local/Sipay/SipayPos/`), its declaration (`app/etc/modules/Sipay_SipayPos.xml`), and the frontend assets — no existing files are overwritten.
3. In the Magento admin, go to **System → Cache Management**, select all cache types, and click **Flush Magento Cache**.
4. **Log out** of the Magento admin and log back in so the new module is fully loaded.
5. Go to **System → Configuration → Sales → Payment Methods**, open **Sipay**, enable it, and enter your API credentials.

> To update, repeat the same steps with the newest `.zip`, then flush the cache again.

## Requirements

- A Magento Open Source 1 (Community Edition 1.x) store.
- A valid Sipay merchant account and API credentials.

## Support

For questions and integration support, please contact Sipay.

# ZenCart CoinGate Plugin

## Install

Sign up for CoinGate account at https://coingate.com for production and https://sandbox.coingate.com for testing (sandbox) environment.

### via FTP

1. Download [zencart-coingate.zip](https://github.com/coingate/zencart-plugin/archive/v1.0.0.zip).
2. Extract downloaded zip. Upload `includes` directory and `coingate_callback.php` file to the root directory of your ZenCart installation.
3. Login to your ZenCart admin panel and go to **Modules » Payment**. Click **Bitcoin (powered by CoinGate)** and click **Install**.
4. Set Enable CoinGate module to True and Enable test mode to False. Enter [API Credentials](http://support.coingate.com/knowledge_base/topics/how-can-i-create-coingate-api-credentials) (App ID, Api Key, Api Secret) and configure other extension settings. Click **Update**.

To create new order statuses login to your ZenCart admin panel, go to **Localization » Orders Status**, click **Insert**, enter new order status name and click **Insert**.
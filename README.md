# Eve - A theme for EverShop

This is an example theme for [EverShop](https://github.com/evershopcommerce/evershop). It is a simple theme that shows how to develop a theme for EverShop.

<p align="center">
<img alt="EverShop" width="950" src="https://raw.githubusercontent.com/evershopcommerce/evetheme/dev/.github/images/demo.png"/>
</p>

## Installation

Assuming you have EverShop installed, you can install this theme by following the steps below:

1. Download the theme from the [GitHub repository]()
2. Unzip the theme
3. Copy the theme folder `eve` into the `themes` directory (By default, EverShop does not create `themes` folder. You can create it yourself) in your EverShop installation directory
4. Edit the configuration file at `config/default.json` and add the following line to the file:

```json
{
  ... // Other configurations
  "system": {
      "theme": "eve",
      ... // Other configurations

  }
}
```

5. Run the build command to build the theme:

```bash
npm run build
```

6. Run the start command to start the server:

```bash
npm run start
```

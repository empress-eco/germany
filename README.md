<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Empress Germany Logo">

  Empress Germany is a specialized application that streamlines accounting and business operations for companies operating within the German market. Built on the robust Empress platform, it is tailored to meet the unique regional requirements of Germany, making it the ideal solution for businesses seeking to navigate the complexities of German accounting standards and regulations.
</div>


## Features

Empress Germany offers a comprehensive suite of features, specifically designed to meet the needs of businesses operating in Germany:

- German accounting reports including _Summen- und Saldenliste_
- Register Information (Registerart, -gericht und nummer) for Company, Customer, and Supplier
- Validation of EU VAT IDs
- Ensures consecutive numbering of transactions by permitting deletion of the most recent sales transaction only
- Custom fields in Employee for tax information
- Comprehensive list of religious denominations ("Konfessionen")
- Comprehensive list of German health insurance providers

## Getting Started

Follow these simple steps to install Empress Germany:

### Prerequisites

Before you begin, make sure Empress is installed. If not, [install Empress](https://github.com/Empress/bench#installation) using bench.

### Installation

#### On Empress Cloud

1. Navigate to https://Empresscloud.com/dashboard/#/sites and click the "New Site" button.
2. Select "Empress" and "Empress Germany" in Step 2 ("Select apps to install").
3. Complete the new site wizard.

#### Locally

After Empress is installed, add the Empress Germany app to your bench by running:

```bash
bench get-app https://github.com/empress-eco/germany.git
```

Then, install the app on your desired site (e.g., demo.com) by running:

```bash
bench --site demo.com install-app Empress_germany
```

## Usage

Empress Germany automatically validates the EU VAT IDs of all your customers every three months, or manually whenever you want. It ensures consecutive numbering of transactions and provides custom fields in **Employee** for tax information, etc. You also get a comprehensive list of religious denominations ("Konfessionen") and German health insurance providers.

For a detailed guide on how to use Empress Germany, check out our [documentation](https://grow.empress.eco/).

## Contributing

We welcome your contributions! To participate, please follow these steps:

1. Fork the project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

For any issues you encounter or features you'd like to request, please use our [issue tracker](https://github.com/empress-eco/germany/issues).

## License and Acknowledgements

This project is licensed under the MIT License. See the `LICENSE` file for more details.

We extend our gratitude to the Empress Community for their invaluable contributions that underpin this project. Their innovation and commitment have been instrumental in building the tools and functionalities that we rely on, and we are profoundly grateful for their pioneering work and continued support.

## Support

For support, please visit our [support page](https://grow.empress.eco/). 

For more information about the project, you can visit our [official website](https://empress.eco/).
# CEMT boilerplates

Boilerplate for custom email templates provided by Adobe Sign to get started. The templates pack includes PleaseSign, SignedAndFiled, Reminder, and Canceled.

## Goals
This project provides templates for customers that:
- makes it easy for them to get started on customizing the email templates that are sent out with Adobe Sign
- enables customers to drive their own rebranding process

## Non-Goals
This project does _not_:
- enable customers to direct their PS contact to update the templates for them

## Code Of Conduct

This project adheres to the Adobe [code of conduct](CODE_OF_CONDUCT.md). By participating,
you are expected to uphold this code. Please report unacceptable behavior to
[Grp-opensourceoffice@adobe.com](mailto:Grp-opensourceoffice@adobe.com).

## Getting Started

To get started, just download the HTML files onto your local machine and use them as a boilerplate for when you create custom templates to use with Adobe Sign. You'll be able to change the verbiage, update layout, or revamp the entire look and feel of the template based on your LFS tier. For further clarification, please refer to the Custom Email Templates guidelines which will be provided by your ACS PS contact.

### Prerequisites

Any IDE that can be used to read HTML and CSS
Any internet browser

```
IDE: Visual Studio Code, Atom, Sublime
Browsers: Google Chrome, Mozilla Firefox, Internet Edge
```

### Usage

Clone this git repository onto your local machine

Update the templates with either the verbiage you want or revamp it completely with your custom HTML and CSS to match your company's brand with your own familiar branding, color scheme, images, and text. You can also format the look and feel for these templates however you like.

Any text surrounded by // TEXT // are Adobe Sign variables that cannot be reworded. You have the option to remove these from the template itself or move them to a different position, but the text itself cannot be changed. If further clarification is needed, please reach out to your ACS PS contact.

```
// SENDER NAME //
// AGREEMENT NAME // 
```

## Completion

When completed, send your HTML files to your contact on the ACS PS team. They will then update the Adobe Sign specific variables and test to ensure that the templates are running properly within the system and then push it live to a test group in your account. You will then test that the templates look and function correctly and after confirming, the templates will be pushed live to the appropriate account/group based on the original SOW.

## Built With

- [Visual Studio Code](https://code.visualstudio.com/) - IDE
- [Adobe Sign](https://acrobat.adobe.com/us/en/sign.html)

## Authors

- **Jacob Yun** - _Adobe_

## Acknowledgments

- Adobe Sign

## Contributing

Contributions are welcomed! Check out our
[contribution guidelines](CONTRIBUTING.md) for information on how to get
involved.

## Licensing

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more information.

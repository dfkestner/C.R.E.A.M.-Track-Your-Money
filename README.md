# C.R.E.A.M. Track Your Money

![License](https://img.shields.io/badge/License-MIT%20License-lightblue.svg)

## Description

Need help managing your dolla dolla bills? C.R.E.A.M. Track Your Money is a PWA that uses MongoDB Atlas and IndexedDB so you can add income when you get the money, and subtract expenses when you spend it, even when you're offline.

![Track Your Money App Screen Shot](https://github.com/dfkestner/C.R.E.A.M.-Track-Your-Money/blob/main/public/images/AppScreenShot.png)

## Table of Contents

* [Installation](#installation)

* [Usage](#usage)

* [Credits](#credits)

* [License](#license)

* [Contributing](#contributing)

* [Tests](#tests)

* [Questions](#questions)

## Installation

Open the [C.R.E.A.M. App](https://creamtrackyourmoney.herokuapp.com/), and select **Install Budget App** from your Browser Controls to download the app to your computer or mobile device.

To use locally, clone the [repository](https://github.com/dfkestner/C.R.E.A.M.-Track-Your-Money) to your local directory. Use npm install to add dependencies, and start MongoDB.

## Usage

To use the app, fill out the **Transaction Name** and **Transaction Amount** fields. If the transaction is adding to your balance select **Add Funds** If it is an expense, select **Subtract Funds**.

Transactions will be represented in the graph below the input fields. Funds added or subtracted offline will be stored using IndexedDB, and will automatically be added to the database once you're back online.

To run C.R.E.A.M. locally, use "node server" and go to [http://localhost:3002/](http://localhost:3002/). 

## License

MIT License

## Contributing

[Contributor Code of Conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/code_of_conduct.md)

## Credits 

N/A

## Tests

N/A

## Questions

Feel free to email me at dfkestner@gmail.com with any questions about the repository. Visit my GitHub profile, [dfkestner](https://github.com/dfkestner/), to see more of my work!

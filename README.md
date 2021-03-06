### What it does
* Automated opening a test page, reading/detecting performance metrics
* Calculate means and standard deviations of collected metric results

### Prerequisites 

* [Node.js and npm](https://nodejs.org/en/download/) (npm is distributed with Node.js)

### Usage

1. Clone the Git repository.

```
git clone git@github.com:katzhang-ias/tm-performance-tester.git
```

2. `cd` into the `tm-performance-tester` directory. Install [Puppeteer](https://github.com/GoogleChrome/puppeteer).

```
npm i puppeteer
```

3. Run testing script.
```
npm start [n] [url]
```
Optionally pass number of times you want to run and the test page URL. Default number is 1 and test page is in the code. Result should be displayed in your terminal.

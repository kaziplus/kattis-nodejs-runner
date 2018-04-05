# kattis-nodejs-runner
A basic "framework" for running Kattis solution code with Node.js, to try and mimic the [SpiderMonkey engine Kattis uses](https://open.kattis.com/help/javascript)

### How to Use

- In the `/solutions` directory, create a directory for your challenge
- In the created directory, create a `solution.js` file (you can give it any other name)
- In the same directory, create an empty `in-file.txt`
- Copy and past the sample input from Kattis to your file
- Write your solution in `solution.js`; making use of `readline` and `print` functions, which we've tried to mimic their simplified forms in NodeJS.

### Take Note

Not all ES6 features are supported by the SpiderMonkey engine that Kattis uses (at the time of writing), we will try and document a list here, e.g:

- Exponential (`**`)
- String templating
- Sets
- Spread operator (`...`)

# express-middleware-demo

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)

Fast, unopinionated, minimalist web framework

## 🚀 Tech Stack

- Node.js

## ✨ Features

- Modern and scalable architecture

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/amitdubeyup/express-middleware-demo.git
cd express-middleware-demo

# Install dependencies
npm install
```

## ⚙️ Configuration

Create a `.env` file in the root directory:

```bash
cp .env.example .env
```

Update the `.env` file with your configuration values.

## 🚀 Usage

```bash
# Run tests
npm test
```

## 📜 Available Scripts

- `npm run lint` - eslint .
- `npm run test` - mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/
- `npm run test-ci` - istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --require test/support/env --reporter spec --check-leaks test/ test/acceptance/
- `npm run test-cov` - istanbul cover node_modules/mocha/bin/_mocha -- --require test/support/env --reporter dot --check-leaks test/ test/acceptance/
- `npm run test-tap` - mocha --require test/support/env --reporter tap --check-leaks test/ test/acceptance/

## 📁 Project Structure

```
express-middleware-demo/
├── package.json
├── .env.example
├── README.md
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Amit Dubey**

- GitHub: [@amitdubeyup](https://github.com/amitdubeyup)

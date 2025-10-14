# SigmaEval Documentation

This repository contains the documentation for [SigmaEval](https://github.com/SigmaEval/SigmaEval), a Python framework for statistical, end-to-end evaluation of Gen AI apps, agents, and bots.

## About SigmaEval

SigmaEval helps you move from "it seems to work" to making rigorous, data-driven statements about your AI's quality. It allows you to set and enforce objective quality bars by making statements like:

> _"We are confident that at least 90% of user issues coming into our customer support chatbot will be resolved with a quality score of 8/10 or higher."_

> _"With a high degree of confidence, the median response time of our new AI-proposal generator will be lower than our 5-second SLO."_

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Contributing

Contributions to the documentation are welcome! Please feel free to submit a Pull Request.

## Resources

- [SigmaEval GitHub Repository](https://github.com/SigmaEval/SigmaEval)
- [SigmaEval PyPI Package](https://pypi.org/project/sigmaeval-framework/)
- [Mintlify documentation](https://mintlify.com/docs)

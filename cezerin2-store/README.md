# Cezerin-Store - Ecommerce Progressive Web Apps

[![CircleCI](https://circleci.com/gh/Cezerin2/cezerin2/tree/master.svg?style=svg)](https://circleci.com/gh/Cezerin2/cezerin2/tree/master)


Cezerin2 is React and Node.js based eCommerce platform. Allows creating a Progressive Web Apps. This is based from cezerin after project went dead. (https://github.com/cezerin/cezerin)

Built with:
* Node.js v8.9
* React v16
* Redux
* Express
* Babel
* WebPack 4

## Links
- [GitHub](https://github.com/cezerin2/cezerin2)
- [Community Site](https://cezerin.org)
- [Demo Store](https://store.cezerin.com)
- [Gitter.im Chat Cezerin2](https://gitter.im/cezerin2)
- [Forum](https://groups.google.com/forum/#!forum/cezerin)
- [Docs](https://github.com/cezerin2/cezerin2/blob/master/docs/getting-started.md)
- [Facebook](https://facebook.com/cezerin)
- [Twitter](https://twitter.com/cezerin2)

## Store
Single-Page Application with React server-side rendering. [Demo store](https://store.cezerin.com)

[![Cezerin Store](https://cezerin.com/assets/images/cezerin-mobile-product.png)](https://store.cezerin.com)

[![Cezerin Store](https://cezerin.com/assets/images/cezerin-mobile-order-summary.png)](https://store.cezerin.com)

## Installation

- [with GitHub](https://github.com/cezerin2/cezerin2/blob/master/docs/getting-started.md)
- [with Docker](https://github.com/cezerin2/cezerin2/blob/master/docs/getting-started-docker.md)
- [How to deploy a Cezerin2 on Ubuntu 16.04](https://github.com/cezerin2/cezerin2/blob/master/docs/how-to-deploy-a-cezerin2-on-ubuntu-16-04.md)
- [How to deploy a Cezerin2 on Ubuntu 18.04.1 (from GitHub)](https://github.com/cezerin2/cezerin2/blob/master/docs/how-to-deploy-a-cezerin2-on-ubuntu-18-04-1-github.md)

### Requirements
* Node.js >= 8

## Documentation

[Documentation](https://github.com/cezerin2/cezerin2/tree/master/docs)


## Application Structure

```
.
├── config                   # Project and build configurations
├── dist                     # Distribution folder
├── locales                  # Text files
├── logs                     # Log files
├── public                   # Static public assets and uploads
│   ├── admin                # Dashboard index.html
│   ├── admin-assets         # Dashboard assets
│   └── content              # Store root folder
|
├── scripts                  # Shell scripts for theme install/export
├── src                      # Store Application source code
│   ├── client             # Client side code
│   ├── server             # Server side code
│   └── shared             # Universal code
│   └── index.js             # Server application start point
├── theme                    # Theme as a local package
└── process.json             # pm2 process file
```


## Contributing

If you can, please contribute by reporting issues, discussing ideas, or submitting pull requests with patches and new features. We do our best to respond to all issues and pull requests within a day or two, and make patch releases to npm regularly.


## Licence

This software is provided free of charge and without restriction under the MIT License

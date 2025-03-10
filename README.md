<img src="./images/react-azure.png" width="160">


# Azure React Icons

Kudos to Rinor Maloku and his original npm package, [azure-react-icons](https://github.com/orangenet/azure-react-icons/) on which this package is based.

## General Information

[![npm][npm-image]][npm-url]
![types][types-image]

[types-image]: https://img.shields.io/npm/types/react-az-icons.svg?style=flat-square
[npm-image]: https://img.shields.io/npm/v/react-az-icons.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/react-az-icons

Azure Icons based on SVG format in the form of React Components, to simplify adding the icons on your React applications.

> Disclaimer these icons are from [Azure Architecture Icons](https://learn.microsoft.com/en-us/azure/architecture/icons/), for their usage in User Interfaces you need to request permission on <CnESymbols@microsoft.com>.


## Naming Convention

- All icons should be .svg files with names that start with Az in the form of AzNameOfResource. Any icons that has nothing to do with Azure, should not be included in this library.
- Azure Active Directory consitutes a special case to make it more distinguishable from Active Directory. AzAADXxX looks like a repetition but this is intended.
- For every Azure service, there should be just one single icon to avoid ambiguity and increase user-friendliness.
- Capitalise the first letter and capitalise for each word the first letter, no punctuations between words in the names.

## Getting Started

Install the components using [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/en/)

```bash
npm i --save react-az-icons
# or 
yarn add react-az-icons
```

## Usage

Simply import the component into your file:

```
import {AzKubernetesServices} from 'react-az-icons';
```
And use it as any other react component:

```
<AzKubernetesServices size={128}/>
```

Final result:

<img src="./images/az-kubernetes-services.png" width="128">

## Contributing

Do you want to extend the icons library or fix an issue? Here is how you can help:

1. Follow the instructions of the [Setup Guide](./setup.md).
2. Add your icon and make your change.
3. Open a PR :wink:

## Feedback

Request new icons or file bugs under [Github Issues](https://github.com/byteknacker/react-az-icons/issues).

>  :construction: The components for this library are auto generated and some of them may contain issues, please report those.

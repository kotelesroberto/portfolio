<div align="center">
  <h1>Currency formatter</h1>
  
  <h4>
    <a href="https://github.com/kotelesroberto/formatcurrency/" title="Code"  target="_blank">View code</a>
  </h4>

</div>

<br />

<!-- Table of Contents -->

# :notebook_with_decorative_cover: ToC

- [About the project](#star2-about-the-project)
  - [Tech Stack](#space_invader-tech-stack)
- [License](#warning-license)

<!-- About the project -->

## :star2: About the project

<p align="left">
This snippet is for formatting currency regarding to the country where to use.</p>

1. Import library

```
import FormatCurrency from 'format-currency.js';
```

2. Create instance

```
let formatCurrency = new FormatCurrency();
```

3. Call validator

```
let price = '123456';
let formattedPrice = formatCurrency.handleCurrencyAsString(price)
console.log(formattedPrice);
```

<!-- TechStack -->

### :space_invader: Tech Stack

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"  target="_blank">JavaScript ES5</a></li>
  </ul>
</details>

<details>
<summary>DevOps</summary>
  <ul>
    <li><a href="https://github.com/">GitHub</a></li>
  </ul>
</details>

<!-- License -->

## :warning: License

Distributed under the MTI copyright. I don't mind if you use this code for educational purposes. Cheers!

<div align="center">
  <img src="assets/samsung-logo.png" alt="logo" width="200" height="auto" />

  <h1>Samsung UK - Help me choose (Cheil)</h1>
  
<p align="left">
    I worked on this project whilst worked at Cheil UK, London. This company is an internal agency of the Samsung company. Way of working at this company was in the office but COVID-19 had broke out and started <strong>working from home</strong>.
  </p>
   
  <h4>
    <a href="https://www.samsung.com/uk/" target="_blank">View site</a>
  </h4>
  <h4>
    <a href="#" title="Sorry, it's company secret"  target="_blank"><s>View code (company secret)</s></a>
  </h4>

</div>

<br />

<!-- Table of Contents -->

# :notebook_with_decorative_cover: ToC

- [About the company](#family-about-the-company)
- [About the project](#star2-about-the-project)
  - [Screenshots](#camera-screenshots)
  - [Tech Stack](#space_invader-tech-stack)
  - [Features](#dart-features)
- [My contribution to the project](#white_check_mark-my-contribution-to-the-project)
- [License](#warning-license)
- [Contact](#handshake-contact)

<!-- About the company -->

## :family: About the company

<p>Samsung UK is the British division of Samsung Electronics, a global technology leader based in South Korea. It operates through its official website <a href="https://www.samsung.com/uk">samsung.com/uk</a>, physical retail stores, and business partnerships to serve both consumers and enterprises across the United Kingdom.</p>
<p>The brand of Samsung is known by almost everyone. Their webpage offering the full range of Samsung hardware: smartphones, tablets, TVs, wearables, home appliances, computers, accessories, smart displays, and mores.</p>

<p><h4>Main functions of the website:</h4></p>
<ul>
  <li><strong>Product Retail:</strong> Sells Samsung's full range of electronics and appliances, including smartphones (like Galaxy devices), TVs, tablets, wearables, laptops, monitors, and smart home devices.</li>
  <li><strong>Customer Support:</strong> Offers in-depth support through online help, live chat, telephone assistance, in-store visits, and at-home repair services.</li>
  <li><strong>Repair Services:</strong> Provides official repair solutions—via courier, in-store, or mobile technicians—as well as a self-repair program for DIY fixes using genuine parts.</li>
</ul>

<!-- About the project -->

## :star2: About the project

<p><h4>Features of this project</h4>
  <ul>
    <li>user could define what is important to them: price category, extra features, device size (QLED TVs only) --> device customization</li>
    <li>after the selected options the webapp shows the perfectly matched device(s) for the customer</li>
    <li>responsive image carousel</li>
    <li>stock information (comes from Samsung stock API)</li>
    <li>upfront cost and monthly payment are calculated by external financial service</li>
    <li>tabbed content to show explanation of technical parameters of the phones / tablets</li>
    <li>disclaimer</li>
    <li>eCommerce basket and checkout page</li>
    <li>integrated <a href="https://www.dekopay.com/">DekoPay</a> payment</li>
  </ul>
</p>

<p><h4>Technical parameters of this project, developed by me:</h4>
  <ul>
    <li>created pixel-perfect layout for every devices, all screen sizes and type of SIMs</li>
    <li>mobile first, full responsive</li>
    <li>all initial content comes from  JSON file</li>
    <li>data of all devices and variation of the devices were loaded from JSON file, on an asyncronous way</li>
    <li>devices were identified by their SKU number</li>
    <li>smart error handling functions</li>    
    <li>currency formatter functions</li>
    <li>customer validation API</li>
    <li>SHOP feature with integrated payment system provided by <a href="https://www.dekopay.com/">DekoPay</a></li>
    <li>actual price and stock information was loaded by using Samsung API data source</li>
    <li>images were stored on AWS</li>
    <li>intelligent state management</li>
    <li>prices and stock information was provided by the official Samsung stocking management system</li>
    <li>optimized page loading time, compressed images, compressed JS content into one file, browser cache to store what was loaded once, so the solution saved bandwith for the next page load</li>
    <li>had to load the content from an XML/JSON file than process it (JSON stringify) and create a representation of the data in the memory</li>
    <li>images were stored on AWS and spread with CDN</li>
    <li>build a business logic for this tool</li>
  </ul>
</p>

<p>
The final webapp was easy-to-access, user-friendly and soooo cool! It was full responsive with mobile-first approach.
</p>

<!-- Screenshots -->

### :camera: Screenshots

<div align="center"> 
  <img src="assets/find_galaxy_step1.jpg" alt="screenshot" />
  <img src="assets/find_galaxy_step2.jpg" alt="screenshot" />
  <img src="assets/find_qled_step1.jpg" alt="screenshot" />
  <img src="assets/find_qled_step2.jpg" alt="screenshot" />
</div>

<!-- TechStack -->

### :space_invader: Tech Stack

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"  target="_blank">JavaScript</a></li>
    <li><a href="https://jquery.com/"  target="_blank">JQuery</a></li>
    <li><a href="https://handlebarsjs.com/"  target="_blank">Handlebars templating</a></li>
    <li><a href="https://nodejs.org"  target="_blank">NodeJS</a></li>
    <li><a href="https://nodejs.org/api/esm.html"  target="_blank">Node.js Modules</a></li>
    <li><a href="https://browserify.org/"  target="_blank">Browserify</a></li>
    <li><a href="https://lodash.com/"  target="_blank">lodash performance optimalization</a></li>
    <li><a href=https://business.adobe.com/products/experience-manager/adobe-experience-manager.html">AEM 6.4</a></li>
    <li><a href="https://www.w3schools.com/html/html5_semantic_elements.asp" target="_blank">Semantic HTML5</a></li>
    <li><a href="https://www.w3schools.com/css/"  target="_blank">CSS3</a></li>
    <li><a href="https://developer.samsung.com/design-system/font"  target="_blank">Samsung Fonts</a></li>
    <li><a href="https://developer.samsung.com/design"  target="_blank">Samsung Design Principles</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.json.org/">data stored in an XML/JSON file</a></li>
    <li><a href="https://www.heroku.com/">HEROKU</a></li>
  </ul>
</details>

<details>
<summary>DevOps</summary>
  <ul>
    <li><a href="https://bitbucket.org/">BitBucket</a></li>
    <li><a href="https://www.jslint.com/">JS Lint</a></li>
    <li><a href="https://www.postman.com/">PostMan</a></li>
    <li><a href="#">Bespoken content scraper on the local development</a></li>
    <li><a href="https://www.bazaarvoice.com/">BazaarVoice</a></li>
    <li><a href="https://tagmanager.google.com/">Google Analytics</a></li>
    <li><a href="https://tagmanager.google.com/">Google Tag Manager</a></li>
    <li><a href="https://www.browserstack.com/">BrowserStack</a></li>
  </ul>
</details>

<!-- Features -->

### :dart: Features

- Accessibility level: AA
- Mobile first, full responsive solution
- It follows the BG (Brand Guideline)
- Fast loading time
- Cached content and images
- Fully optimized loading event and running time with Adobe A/B test code injection into the header

<!-- My contribution to the project -->

## :white_check_mark: My contribution to the project

<p>This entire project belonged to me, from the beginning until the end of it. I had to manage the design team and had my hands on the design processes. After having the design FIGMA pages I created teh webapp from scratch and used Adobe A/B test to inject the solution into the AEM pages. Had to create an injection ruke as the solution (and its content) was developed for specific pages (for instance: comparison of mobile phones was only visible on smartphone pages). For testing during the develpoment phase I used BroswerStack and multiple real devices, also the in-built Chrome DevTools.</p>
<p>Based on the insights this comparison tool created a significant rise in sales that ended up in a visible extra profit for Samsung UK.</p>

<!-- License -->

## :warning: License

Distributed under the Software copyright of Cheil UK / Samsung UK. Any non-authorized usage of their code leads to legal consequences, thank you.

<!-- Contact -->

## :handshake: Contact

Cheil UK -
[https://cheil.uk/](https://cheil.uk/), London Office: 10 Queen Street Place, London, EC4R 1BE

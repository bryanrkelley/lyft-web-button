# Lyft Web Button Component

<!-- div class="toc-container" -->

<!-- div -->

## `lyftWebButton.prototype`
* <a href="#lyftwebbuttonprototypebindeventsonclick">`lyftWebButton.prototype.bindEvents`</a>
* <a href="#lyftwebbuttonprototypecreateelements">`lyftWebButton.prototype.createElements`</a>
* <a href="#lyftwebbuttonprototypeinitializeoptions">`lyftWebButton.prototype.initialize`</a>
* <a href="#lyftwebbuttonprototypeongetcostssuccessdata">`lyftWebButton.prototype.onGetCostsSuccess`</a>
* <a href="#lyftwebbuttonprototypeongetetassuccessdata">`lyftWebButton.prototype.onGetEtasSuccess`</a>
* <a href="#lyftwebbuttonprototypeupdatecontentstheme">`lyftWebButton.prototype.updateContents`</a>

<!-- /div -->

<!-- /div -->

<!-- div class="doc-container" -->

<!-- div -->

## `lyftWebButton.prototype`

<!-- div -->

<h3 id="lyftwebbuttonprototypebindeventsonclick"><code>lyftWebButton.prototype.bindEvents(onClick)</code></h3>
[&#x24C8;](https://github.com/lyft/lyft-web-button/blob/master/src/components/lyftWebButton/index.js#L50 "View in source") [&#x24C9;][1]

Binds events to some elements.

#### Arguments
1. `onClick` *(function)*: Handler for button's onclick event.

#### Returns
*(void)*: Void.

---

<!-- /div -->

<!-- div -->

<h3 id="lyftwebbuttonprototypecreateelements"><code>lyftWebButton.prototype.createElements()</code></h3>
[&#x24C8;](https://github.com/lyft/lyft-web-button/blob/master/src/components/lyftWebButton/index.js#L31 "View in source") [&#x24C9;][1]

Creates elements from a template and stores some useful references.

#### Returns
*(Object)*: Template's root element.

---

<!-- /div -->

<!-- div -->

<h3 id="lyftwebbuttonprototypeinitializeoptions"><code>lyftWebButton.prototype.initialize(options)</code></h3>
[&#x24C8;](https://github.com/lyft/lyft-web-button/blob/master/src/components/lyftWebButton/index.js#L212 "View in source") [&#x24C9;][1]

Initialize.

#### Arguments
1. `options` *(Object)*:
2. `options.clientId` *(string)*:
3. `options.clientToken` *(string)*:
4. `options.location` *(Object)*:
5. `options.location.pickup` *(Object)*:
6. `options.location.destination` *(Object)*:
7. `options.namespace` *(string)*:
8. `options.objectName` *(string)*:
9. `options.parentElement` *(Object)*:
10. `options.theme` *(string)*:

#### Returns
*(void)*: Void.

---

<!-- /div -->

<!-- div -->

<h3 id="lyftwebbuttonprototypeongetcostssuccessdata"><code>lyftWebButton.prototype.onGetCostsSuccess(data)</code></h3>
[&#x24C8;](https://github.com/lyft/lyft-web-button/blob/master/src/components/lyftWebButton/index.js#L115 "View in source") [&#x24C9;][1]

Success callback for getCosts request.

#### Arguments
1. `data` *(Object)*: Response data.

#### Returns
*(void)*: Void.

---

<!-- /div -->

<!-- div -->

<h3 id="lyftwebbuttonprototypeongetetassuccessdata"><code>lyftWebButton.prototype.onGetEtasSuccess(data)</code></h3>
[&#x24C8;](https://github.com/lyft/lyft-web-button/blob/master/src/components/lyftWebButton/index.js#L139 "View in source") [&#x24C9;][1]

Success callback for getEtas request.

#### Arguments
1. `data` *(Object)*: Response data.

#### Returns
*(void)*: Void.

---

<!-- /div -->

<!-- div -->

<h3 id="lyftwebbuttonprototypeupdatecontentstheme"><code>lyftWebButton.prototype.updateContents(theme)</code></h3>
[&#x24C8;](https://github.com/lyft/lyft-web-button/blob/master/src/components/lyftWebButton/index.js#L97 "View in source") [&#x24C9;][1]

Updates the contents of some elements.

#### Arguments
1. `theme` *(string)*: Name of the user's chosen theme.

#### Returns
*(void)*: Void.

---

<!-- /div -->

<!-- /div -->

<!-- /div -->

 [1]: #lyftwebbutton.prototype "Jump back to the TOC."

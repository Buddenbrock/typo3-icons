![GitHub licenze](https://img.shields.io/github/license/Buddenbrock/typo3-icons?style=for-the-badge)
![GitHub release](https://img.shields.io/github/package-json/version/Buddenbrock/typo3-icons?style=for-the-badge)
![Last commit](https://img.shields.io/github/last-commit/buddenbrock/typo3-icons?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/Buddenbrock/typo3-icons?style=for-the-badge)

Additional svg-icons for the TYPO3 CMS backend content elements

## Why?
New icons are always needed for the TYPO3 backend.<br>So that you don't have to start from scratch every time is there a template document.

There is already a small collection of created icons in this document. These depend on the styling of the TYPO3 icons.

Since the icons usually have the same meaning from installation to installation,<br>it would be possible in this document to create a small collection from which demand icons can be used.

## Installation

### Using npm
```sh
npm install @buddenbrock/typo3-icons
```

### Using yarn
```sh
yarn add @buddenbrock/typo3-icons
```

## Icons
### Default Icons
You find the TYPO3 default iconset into [TYPO3-Icon Repository](https://github.com/TYPO3/TYPO3.Icons) or on these [Show Page](https://typo3.github.io/TYPO3.Icons/).


### Pagetree Icons

<div class="icon-wrapper">
    {% for item in site.iconsPagetree %}
    <div class="icon-item" data-category="pagetree" data-name="{{ item }}">
        <span>{{ item }}</span>
        <img src="{{ site.iconBaseUrl }}/pagetree/{{ item }}.svg" alt="{{ item }}"/>
    </div>
    {% endfor %}
</div>

### Grid/Layout Icons

<div class="icon-wrapper">
    {% for item in site.iconsGrid %}
    <div class="icon-item" data-category="grid" data-name="{{ item }}">
        <span>{{ item }}</span>
        <img src="{{ site.iconBaseUrl }}/grid/{{ item }}.svg" alt="{{ item }}"/>
    </div>
    {% endfor %}
</div>

### Content Icons

<div class="icon-wrapper">
    {% for item in site.iconsContent %}
    <div class="icon-item" data-category="content" data-name="{{ item }}">
        <span>{{ item }}</span>
        <img src="{{ site.iconBaseUrl }}/content/{{ item }}.svg"/>
    </div>
    {% endfor %}
</div>

### Payment Icons

<div class="icon-wrapper">
    {% for item in site.iconsPayment %}
    <div class="icon-item" data-category="payment" data-name="{{ item }}">
        <span>{{ item }}</span>
        <img src="{{ site.iconBaseUrl }}/payment/{{ item }}.svg"/>
    </div>
    {% endfor %}
</div>

### Atlassian Icons

<div class="icon-wrapper">
    {% for item in site.iconsAtlassian %}
    <div class="icon-item" data-category="atlassian" data-name="{{ item }}">
        <span>{{ item }}</span>
        <img src="{{ site.iconBaseUrl }}/atlassian/{{ item }}.svg"/>
    </div>
    {% endfor %}
</div>

### Social Icons

<div class="icon-wrapper">
    {% for item in site.iconsSocial %}
    <div class="icon-item" data-category="social" data-name="{{ item }}">
        <span>{{ item }}</span>
        <img src="{{ site.iconBaseUrl }}/social/{{ item }}.svg"/>
    </div>
    {% endfor %}
</div>

## Issues and wishes
You have wishes for icons that do not yet exist, then write an issue and I will see that such an icon is included.

## Donation
This is free, open-source software. If you'd like to support the development of future projects, or say thanks for this one, you can [donate](https://www.paypal.me/buddenbrock).

## License
MIT &copy; [@buddenbrock/typo3-icons](https://github.com/Buddenbrock/typo3-icons/blob/master/LICENSE)
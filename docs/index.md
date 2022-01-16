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
        <img src="{{ site.iconBaseUrl }}/pagetree/{{ item }}.svg" alt="{{ item }}"/>
    </div>
    {% endfor %}
</div>

### Grid/Layout Icons

<div class="icon-wrapper">
    {% for item in site.iconsGrid %}
    <div class="icon-item" data-category="grid" data-name="{{ item }}">
        <img src="{{ site.iconBaseUrl }}/grid/{{ item }}.svg" alt="{{ item }}"/>
    </div>
    {% endfor %}
</div>

    <div class="icon-item"><img src="https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-25-25-25-25.svg" /></div>
    <div class="icon-item"><img src="https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-33-33-33.svg" /></div>
    <div class="icon-item"><img src="https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-25-75.svg" /></div>
    <div class="icon-item"><img src="https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-40-60.svg" /></div>
    <div class="icon-item"><img src="https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-50-50.svg" /></div>
    <div class="icon-item"><img src="https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-60-40.svg" /></div>
    <div class="icon-item"><img src="https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-75-25.svg" /></div>
    <div class="icon-item"><img src="https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-100.svg" /></div>

<div class="icon-wrapper">
    {% for item in site.iconsContent %}
    <div class="icon-item" data-category="content" data-name="{{ item }}">
        <span>{{ item }}</span>
        <img src="{{ site.iconBaseUrl }}/content/{{ item }}.svg"/>
    </div>
    {% endfor %}
</div>


### Pagetree Icons
Icon | Name
---|---
![pagetree](https://github.com/Buddenbrock/typo3-icons/tree/master/src/pagetree/pagetree-page-missing.svg) | `pagetree-page-missing`

### Grid/Layout Icons
Icon | Name
---|---
![grid](https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-25-25-25-25.svg) | `grid-25-25-25-25`
![grid](https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-33-33-33.svg) | `grid-33-33-33`
![grid](https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-25-75.svg) | `grid-25-75`
![grid](https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-40-60.svg) | `grid-40-60`
![grid](https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-50-50.svg) | `grid-50-50`
![grid](https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-60-40.svg) | `grid-60-40`
![grid](https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-75-25.svg) | `grid-75-25`
![grid](https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-100.svg) | `grid-100`
![grid](https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-header.svg) | `grid-header`
![grid](https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-header-25-25-25-25.svg) | `grid-header-25-25-25-25`
![grid](https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-header-33-33-33.svg) | `grid-header-33-33-33`
![grid](https://github.com/Buddenbrock/typo3-icons/tree/master/src/grid/grid-header-50-50.svg) | `grid-header-50-50`

### Content Icons
Icon | Name
---|---
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-360-degree-player.svg) | `ce-360-degree-player`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-accordion-1.svg) | `ce-accordion-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-accordion-2.svg) | `ce-accordion-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-accordion-3.svg) | `ce-accordion-3`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-accordion-4.svg) | `ce-accordion-4`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-address.svg) | `ce-address`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-article-1.svg) | `ce-article-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-article-2.svg) | `ce-article-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-article-slider-1.svg) | `ce-article-slider-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-article-slider-2.svg) | `ce-article-slider-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-audio.svg) | `ce-audio`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-blockquote-1.svg) | `ce-blockquote-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-blockquote-2.svg) | `ce-blockquote-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-blockquote-3.svg) | `ce-blockquote-3`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-blockquote-4.svg) | `ce-blockquote-4`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-blog-preview.svg) | `ce-blog-preview`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-book-gallery.svg) | `ce-book-gallery`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-book.svg) | `ce-book`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-button-1.svg) | `ce-button-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-button-2.svg) | `ce-button-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-button-icon.svg) | `ce-button-icon`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-calender.svg) | `ce-calender`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-chat.svg) | `ce-chat`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-comment.svg) | `ce-comment`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-contact-1.svg) | `ce-contact-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-contact-2.svg) | `ce-contact-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-countdown.svg) | `ce-countdown`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-diagram.svg) | `ce-diagram`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-download-1.svg) | `ce-download-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-download-2.svg) | `ce-download-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-download-container.svg) | `ce-download-container`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-employee-1.svg) | `ce-employee-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-employee-2.svg) | `ce-employee-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-employee-3.svg) | `ce-employee-3`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-filter.svg) | `ce-filter`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-form.svg) | `ce-form`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-fundraising.svg) | `ce-fundraising`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-gallery-item.svg) | `ce-gallery-item`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-hero-1.svg) | `ce-hero-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-hero-2.svg) | `ce-hero-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-hero-3.svg) | `ce-hero-3`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-hero-4.svg) | `ce-hero-4`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-hero-5.svg) | `ce-hero-5`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-hero-6.svg) | `ce-hero-6`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-hero-7.svg) | `ce-hero-7`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-icon.svg) | `ce-icon`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-iframe.svg) | `ce-iframe`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-1.svg) | `ce-image-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-2.svg) | `ce-image-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-3.svg) | `ce-image-3`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-4.svg) | `ce-image-4`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-5.svg) | `ce-image-5`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-6.svg) | `ce-image-6`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-7.svg) | `ce-image-7`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-8.svg) | `ce-image-8`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-9.svg) | `ce-image-9`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-downloads.svg) | `ce-image-downloads`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-slider.svg) | `ce-image-slide`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-statement.svg) | `ce-image-statement`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-tiles-1.svg) | `ce-image-tiles-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-tiles-2.svg) | `ce-image-tiles-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-image-tiles-3.svg) | `ce-image-tiles-3`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-inline-quote.svg) | `ce-inline-quote`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-instagram.svg) | `ce-instagram`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-lightbox-content.svg) | `ce-lightbox-content`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-list-1.svg) | `ce-list-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-list-2.svg) | `ce-list-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-listbox.svg) | `ce-listbox`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-login.svg) | `ce-login`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-map-1.svg) | `ce-map-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-map-2.svg) | `ce-map-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-map-3.svg) | `ce-map-3`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-media.svg) | `ce-media`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-news.svg) | `ce-news`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-podcast.svg) | `ce-podcast`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-quote-box.svg) | `ce-quote-box`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-quote-slider.svg) | `ce-quote-slider`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-quote.svg) | `ce-quote`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-service.svg) | `ce-service`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-shop-search.svg) | `ce-shop-search`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-skills.svg) | `ce-skills`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-slider-1.svg) | `ce-slider-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-slider-2.svg) | `ce-slider-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-social.svg) | `ce-social`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-team-container.svg) | `ce-team-container`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-team.svg) | `ce-team`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-teaser-1.svg) | `ce-teaser-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-teaser-2.svg) | `ce-teaser-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-teaser-box.svg) | `ce-teaser-box`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-testimonial.svg) | `ce-testimonial`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-1.svg) | `ce-text-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-2.svg) | `ce-text-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-3.svg) | `ce-text-3`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-4.svg) | `ce-text-4`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-5.svg) | `ce-text-5`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-6.svg) | `ce-text-6`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-box.svg) | `ce-text-box`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-button-1.svg) | `ce-text-button-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-button-2.svg) | `ce-text-button-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-button-3.svg) | `ce-text-button-3`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-cta.svg) | `ce-text-cta`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-highlight.svg) | `ce-text-highlight`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-image-1.svg) | `ce-text-image-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-image-2.svg) | `ce-text-image-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-image-3.svg) | `ce-text-image-3`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-image-4.svg) | `ce-text-image-4`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-image-5.svg) | `ce-text-image-5`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-image-6.svg) | `ce-text-image-6`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-image-7.svg) | `ce-text-image-7`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-image-8.svg) | `ce-text-image-8`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-image-slider-1.svg) | `ce-text-image-slider-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-image-slider-2.svg) | `ce-text-image-slider-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-list-1.svg) | `ce-text-list-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-list-2.svg) | `ce-text-list-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-video-1.svg) | `ce-text-video-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-text-video-2.svg) | `ce-text-video-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-tiles-group-1.svg) | `ce-tiles-group-1`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-tiles-group-2.svg) | `ce-tiles-group-2`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-tiles.svg) | `ce-tiles`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-vcard-container.svg) | `ce-vcard-container`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-vcard.svg) | `ce-vcard`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-video.svg) | `ce-video`
![content](https://github.com/Buddenbrock/typo3-icons/tree/master/src/content/ce-webcam.svg) | `ce-webcam`

### Payment Icons
Icon | Name
---|---
![payment](https://github.com/Buddenbrock/typo3-icons/tree/master/src/payment/payment-amazon-pay.svg) | `payment-amazon-pay`
![payment](https://github.com/Buddenbrock/typo3-icons/tree/master/src/payment/payment-amex.svg) | `payment-amex`
![payment](https://github.com/Buddenbrock/typo3-icons/tree/master/src/payment/payment-apple-pay.svg) | `payment-apple-pay`
![payment](https://github.com/Buddenbrock/typo3-icons/tree/master/src/payment/payment-cirrus.svg) | `payment-cirrus`
![payment](https://github.com/Buddenbrock/typo3-icons/tree/master/src/payment/payment-diners-club.svg) | `payment-diners-club`
![payment](https://github.com/Buddenbrock/typo3-icons/tree/master/src/payment/payment-discover.svg) | `payment-discover`
![payment](https://github.com/Buddenbrock/typo3-icons/tree/master/src/payment/payment-klarna.svg) | `payment-klarna`
![payment](https://github.com/Buddenbrock/typo3-icons/tree/master/src/payment/payment-maestro.svg) | `payment-maestro`
![payment](https://github.com/Buddenbrock/typo3-icons/tree/master/src/payment/payment-mastercard.svg) | `payment-mastercard`
![payment](https://github.com/Buddenbrock/typo3-icons/tree/master/src/payment/payment-patreon.svg) | `payment-patreon`
![payment](https://github.com/Buddenbrock/typo3-icons/tree/master/src/payment/payment-paypal.svg) | `payment-paypal`
![payment](https://github.com/Buddenbrock/typo3-icons/tree/master/src/payment/payment-visa.svg) | `payment-visa`

### Atlassian Icons
Icon | Name
---|---
![atlassian](https://github.com/Buddenbrock/typo3-icons/tree/master/src/atlassian/atlassian.svg) | `atlassian`
![atlassian](https://github.com/Buddenbrock/typo3-icons/tree/master/src/atlassian/atlassian-bitbucket.svg) | `atlassian-bitbucket`
![atlassian](https://github.com/Buddenbrock/typo3-icons/tree/master/src/atlassian/atlassian-confluence.svg) | `atlassian-confluence`
![atlassian](https://github.com/Buddenbrock/typo3-icons/tree/master/src/atlassian/atlassian-halp.svg) | `atlassian-halp`
![atlassian](https://github.com/Buddenbrock/typo3-icons/tree/master/src/atlassian/atlassian-jira-align.svg) | `atlassian-jira-align`
![atlassian](https://github.com/Buddenbrock/typo3-icons/tree/master/src/atlassian/atlassian-jira-service-management.svg) | `atlassian-jira-service-management`
![atlassian](https://github.com/Buddenbrock/typo3-icons/tree/master/src/atlassian/atlassian-jira-software.svg) | `atlassian-jira-software`
![atlassian](https://github.com/Buddenbrock/typo3-icons/tree/master/src/atlassian/atlassian-jira-work-management.svg) | `atlassian-jira-work-management`
![atlassian](https://github.com/Buddenbrock/typo3-icons/tree/master/src/atlassian/atlassian-opsgenie.svg) | `atlassian-opsgenie`
![atlassian](https://github.com/Buddenbrock/typo3-icons/tree/master/src/atlassian/atlassian-sourcetree.svg) | `atlassian-sourcetree`
![atlassian](https://github.com/Buddenbrock/typo3-icons/tree/master/src/atlassian/atlassian-statuspage.svg) | `atlassian-statuspage`
![atlassian](https://github.com/Buddenbrock/typo3-icons/tree/master/src/atlassian/atlassian-trello.svg) | `atlassian-trello`

### Social Icons
Icon | Name
---|---
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-airbnb.svg) | `social-airbnb`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-amazon.svg) | `social-amazon`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-amazon-aws.svg) | `social-amazon-aws`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-audible.svg) | `social-audible`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-ausweisapp2.svg) | `social-ausweisapp2`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-behance.svg) | `social-behance`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-blogger.svg) | `social-blogger`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-codepen.svg) | `social-codepen`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-deezer.svg) | `social-deezer`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-dhl.svg) | `social-dhl`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-doodle.svg) | `social-doodle`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-discord.svg) | `social-discord`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-disqus.svg) | `social-disqus`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-dribbble.svg) | `social-dribbble`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-dropbox.svg) | `social-dropbox`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-envato.svg) | `social-envato`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-eventbrite.svg) | `social-eventbrite`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-eventim.svg) | `social-eventim`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-evernote.svg) | `social-evernote`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-facebook.svg) | `social-facebook`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-facebook-messanger.svg) | `social-facebook-messanger`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-fedex.svg) | `social-fedex`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-figma.svg) | `social-figma`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-flickr.svg) | `social-flickr`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-foursquare.svg) | `social-foursquare`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-giphy.svg) | `social-giphy`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-github.svg) | `social-github`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-google.svg) | `social-google`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-google-drive.svg) | `social-google-drive`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-google-maps.svg) | `social-google-maps`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-instagram.svg) | `social-instagram`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-invision.svg) | `social-invision`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-kickstarter.svg) | `social-kickstarter`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-kik-messanger.svg) | `social-kik-messanger`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-lastfm.svg) | `social-lastfm`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-linkedin.svg) | `social-linkedin`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-mailchimp.svg) | `social-mailchimp`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-mixer.svg) | `social-mixer`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-npm.svg) | `social-npm`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-onedrive.svg) | `social-onedrive`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-pinterest.svg) | `social-pinterest`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-reddit.svg) | `social-reddit`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-rss.svg) | `social-rss`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-shutterstock.svg) | `social-shutterstock`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-skype.svg) | `social-skype`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-slack.svg) | `social-slack`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-snapchat.svg) | `social-snapchat`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-soundcloud.svg) | `social-soundcloud`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-spotify.svg) | `social-spotify`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-stackoverflow.svg) | `social-stackoverflow`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-stumbleupon.svg) | `social-stumbleupon`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-teamspeak.svg) | `social-teamspeak`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-teamviewer.svg) | `social-teamviewer`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-telegramm.svg) | `social-telegramm`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-tiktok.svg) | `social-tiktok`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-tumblr.svg) | `social-tumblr`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-twitch.svg) | `social-twitch`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-twitter.svg) | `social-twitter`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-ups.svg) | `social-ups`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-usps.svg) | `social-usps`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-vimeo.svg) | `social-vimeo`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-vk.svg) | `social-vk`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-whatsapp.svg) | `social-whatsapp`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-wikipedia.svg) | `social-wikipedia`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-xing.svg) | `social-xing`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-yelp.svg) | `social-yelp`
![social](https://github.com/Buddenbrock/typo3-icons/tree/master/src/social/social-youtube.svg) | `social-youtube`

## Issues and wishes
You have wishes for icons that do not yet exist, then write an issue and I will see that such an icon is included.

## Donation
This is free, open-source software. If you'd like to support the development of future projects, or say thanks for this one, you can [donate](https://www.paypal.me/buddenbrock).

## License
MIT &copy; [@buddenbrock/typo3-icons](https://github.com/Buddenbrock/typo3-icons/blob/master/LICENSE)
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

Icon | Name
---|---
![atlassian](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/atlassian/atlassian.svg) | `atlassian`
![atlassian](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/atlassian/atlassian-bitbucket.svg) | `atlassian-bitbucket`
![atlassian](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/atlassian/atlassian-confluence.svg) | `atlassian-confluence`
![atlassian](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/atlassian/atlassian-halp.svg) | `atlassian-halp`
![atlassian](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/atlassian/atlassian-jira-align.svg) | `atlassian-jira-align`
![atlassian](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/atlassian/atlassian-jira-service-management.svg) | `atlassian-jira-service-management`
![atlassian](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/atlassian/atlassian-jira-software.svg) | `atlassian-jira-software`
![atlassian](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/atlassian/atlassian-jira-work-management.svg) | `atlassian-jira-work-management`
![atlassian](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/atlassian/atlassian-opsgenie.svg) | `atlassian-opsgenie`
![atlassian](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/atlassian/atlassian-sourcetree.svg) | `atlassian-sourcetree`
![atlassian](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/atlassian/atlassian-statuspage.svg) | `atlassian-statuspage`
![atlassian](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/atlassian/atlassian-trello.svg) | `atlassian-trello`

### Social Icons

Icon | Name
---|---
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-airbnb.svg) | `social-airbnb`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-amazon.svg) | `social-amazon`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-amazon-aws.svg) | `social-amazon-aws`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-audible.svg) | `social-audible`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-ausweisapp2.svg) | `social-ausweisapp2`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-behance.svg) | `social-behance`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-blogger.svg) | `social-blogger`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-codepen.svg) | `social-codepen`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-deezer.svg) | `social-deezer`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-dhl.svg) | `social-dhl`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-doodle.svg) | `social-doodle`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-discord.svg) | `social-discord`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-disqus.svg) | `social-disqus`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-dribbble.svg) | `social-dribbble`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-dropbox.svg) | `social-dropbox`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-envato.svg) | `social-envato`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-eventbrite.svg) | `social-eventbrite`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-eventim.svg) | `social-eventim`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-evernote.svg) | `social-evernote`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-facebook.svg) | `social-facebook`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-facebook-messanger.svg) | `social-facebook-messanger`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-fedex.svg) | `social-fedex`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-figma.svg) | `social-figma`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-flickr.svg) | `social-flickr`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-foursquare.svg) | `social-foursquare`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-giphy.svg) | `social-giphy`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-github.svg) | `social-github`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-google.svg) | `social-google`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-google-drive.svg) | `social-google-drive`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-google-maps.svg) | `social-google-maps`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-instagram.svg) | `social-instagram`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-invision.svg) | `social-invision`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-kickstarter.svg) | `social-kickstarter`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-kik-messanger.svg) | `social-kik-messanger`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-lastfm.svg) | `social-lastfm`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-linkedin.svg) | `social-linkedin`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-mailchimp.svg) | `social-mailchimp`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-mixer.svg) | `social-mixer`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-npm.svg) | `social-npm`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-onedrive.svg) | `social-onedrive`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-pinterest.svg) | `social-pinterest`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-reddit.svg) | `social-reddit`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-rss.svg) | `social-rss`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-shutterstock.svg) | `social-shutterstock`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-skype.svg) | `social-skype`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-slack.svg) | `social-slack`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-snapchat.svg) | `social-snapchat`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-soundcloud.svg) | `social-soundcloud`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-spotify.svg) | `social-spotify`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-stackoverflow.svg) | `social-stackoverflow`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-stumbleupon.svg) | `social-stumbleupon`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-teamspeak.svg) | `social-teamspeak`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-teamviewer.svg) | `social-teamviewer`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-telegramm.svg) | `social-telegramm`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-tiktok.svg) | `social-tiktok`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-tumblr.svg) | `social-tumblr`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-twitch.svg) | `social-twitch`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-twitter.svg) | `social-twitter`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-ups.svg) | `social-ups`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-usps.svg) | `social-usps`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-vimeo.svg) | `social-vimeo`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-vk.svg) | `social-vk`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-whatsapp.svg) | `social-whatsapp`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-wikipedia.svg) | `social-wikipedia`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-xing.svg) | `social-xing`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-yelp.svg) | `social-yelp`
![social](https://unpkg.com/@buddenbrock/typo3-icons@0.2.2/src/social/social-youtube.svg) | `social-youtube`

## Issues and wishes
You have wishes for icons that do not yet exist, then write an issue and I will see that such an icon is included.

## Donation
This is free, open-source software. If you'd like to support the development of future projects, or say thanks for this one, you can [donate](https://www.paypal.me/buddenbrock).

## License
MIT &copy; [@buddenbrock/typo3-icons](https://github.com/Buddenbrock/typo3-icons/blob/master/LICENSE)
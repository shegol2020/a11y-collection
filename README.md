> "The web is meaningless if it is not accessible."
> 
> Morten Rand-Hendriksen, linkedin learining course

This is collection of materials I've found about accessibility, mostly for frontend development. 
I try add dates to links, because this can be useful as information quickly becomes outdated.

## How to

### ...hide content from screen readers
* [aria-hidden](https://a11y-101.com/development/aria-hidden), if you want the content to be accessible to the sighted


### ...hide visual content 
For example, some description for visual impared users that you want to hide from screen
* screen-reader-only class for css, [examples](https://github.com/LinkedInLearning/simplifying-web-development-with-accessibility-best-practices-2883015/blob/main/03_02/index.html)

### ...make accessible hamburger menu 
briefly: hide picture, make wrapper a button, add aria-label, aria-expanded when open.
articles: [1](https://uxdesign.cc/create-an-accessible-hamburger-menu-869b0301cfd7), [2](https://medium.com/@linlinghao/accessibility-for-hamburger-menu-a37fa9617a89), [3](https://www.accede-web.com/en/guidelines/rich-interface-components/hamburger-menu/).

### ...make accessible product card
[how to make whole card a link](https://css-tricks.com/block-links-the-search-for-a-perfect-solution/)

### ...limit animations
@media (prefers-reduced-motion: reduce)  
[reduced motion](https://a11y-101.com/development/reduced-motion)


## Study
- [An Introduction to Accessibility and Inclusive Design](https://www.coursera.org/learn/accessibility), coursera course, free, 15 hours

### Linkedin learning
- [Simplifying Web Development with Accessibility Best Practices](https://www.linkedin.com/learning/simplifying-web-development-with-accessibility-best-practices?u=106534538), 2 hours
- [Accessibility for Web Design](https://www.linkedin.com/learning/accessibility-for-web-design?u=106534538), 2 hours
- [Designing with the WCAG 2.2 Guidelines](https://www.linkedin.com/learning/designing-with-the-wcag-2-2-guidelines?u=106534538), 35 min
- [Digital Accessibility for the Modern Workplace](https://www.linkedin.com/learning/digital-accessibility-for-the-modern-workplace?u=106534538), 50 min
- [React: Accessibility](https://www.linkedin.com/learning/react-accessibility?u=106534538), 34 min

### Udemy
- [Web Design Accessibility Certificate](https://www.udemy.com/course/web-accessibility), 1.5 hours
- [WCAG 2.1 / 2.2 Simplified With Examples](https://www.udemy.com/course/web-content-accessibility-guidelines-wcag-21-simplified), 3 hours
- [Introduction to WAI-ARIA for Beginners](https://www.udemy.com/course/introduction-to-wai-aria-for-beginners), 3 hours
- [Practical Accessibility for Web Developers: Form Controls](https://www.udemy.com/course/practical-accessibility-for-web-developers-form-controls), 2.5 hours
- [Automated Accessibility Testing for React Applications](https://www.udemy.com/course/automated-a11y-testing/), 1.5 hours 
- [Web Accessibility: Learn the Best Practises](https://www.udemy.com/course/web-accessibility-learn-the-best-practises), 1.5 hours
- [Introduction to Web Accessibility WCAG 2.1](https://www.udemy.com/course/introduction-to-web-accessibility-wcag21), 3 hours
- [Web Accessibility Compliance](https://www.udemy.com/course/learn-web-accessibility-compliance), 1.5 hours
- [Creating Accessible Websites](https://www.udemy.com/course/creating-accessible-websites/), 3.5 hours


## Using accessible technologies
- [Voiceover and Braille screen input](https://www.youtube.com/watch?v=wueLXCbm_KY), video, 2 min
- [Unlocking Potential - girl using Microsoft Adaptive Accessories](https://www.youtube.com/@JaraUnlockingPotential), series of short (2-3 min) videos
- [Christopher Hills](https://www.youtube.com/@icdhills/), video production engineer who works with switch, a lot of videos showing him using accessible technologies

## Meta

- [A11y Cat: digital accessibility resources](https://www.a11ycat.net/), collection of accessibility links: articles, guides, checklists, courses, videos

## Materials in Russian 

- [Web standard, developer community](https://web-standards.ru/articles/tags/a11y/), collection of articles
- [Weblind](https://weblind.ru), Recommendations for developing websites for people with visual impairments

### Authors
- Mikhail Rubanov, Mobile Head at Dodo Engineering. [iOS accessibility book](https://rubanov.dev/a11y-book/)
- Valeria Kurmak, Head of Accessibility department at Yandex. Telegram channel about inclusive design ["No exception"](t.me/No_Exception), Founder of an [educational school on digital accessibility](AccessibilityUnity.com/en/). [Accessibility podcast's transcipt](https://medium.com/@Valeria.kurmak)
- Vasilina Drogichinskaya, Accessibility & Inclusion Manager at VK. https://vk.com/the_vasilina


### Articles

- [How We Learn to Adapt Yandex Go for Blind Users](https://habr.com/ru/company/yandex/blog/660663/), making taxi app accessible, 2022
- [Making Web Content Accessible: Standards, Criteria, Implementation Example](https://habr.com/ru/company/ispring/blog/564446/), 2021 
- [VK Product digital accessibility guide](https://maildesign.notion.site/VK-ddea4f40f2bb4f56a774ba34946c999b), internal doc of IT company, but it's open for everyone now (2023). Describes main idea of accessibility, provides a lot of additional links
- [How to make a big product accessible](https://habr.com/ru/company/wrike/blog/668268/?mkt_tok=OTk5LUROWC0yNjUAAAGFTfalLtos6EYhg37-x7gQUrkjzA4exzuMp4l0-M0pCHgyGN8oA8P5ScICbVvGgsNwpGF5qRE_mLNsonZgq3fSV1BIDBZjSX9CZp6fmtyhE8xR3SI), accessibility in big company, design system, etc. 2022
- [Accessibility Testing: how do blind people use and test Android?](https://vk.com/@testpool-accessibility-testing-kak-nezryachie-polzuutsya-android), 2022.
- [Why does your application need Accessibility](https://habr.com/ru/company/oleg-bunin/blog/466629/), transcipt of podcast, 2019
- [Guidelines from Sber (russian bank)](https://www.sberbank.ru/common/img/uploaded/redirected/person/digital_guideline2/assets/index.html), [guideline for web developers](https://www.sberbank.ru/common/img/uploaded/redirected/person/digital_guideline2/assets/dev_web.html)
- [Interface availability](https://habr.com/ru/company/yandex/blog/424879/), Yandex lecture about accessible interfaces, 2018. Also [video](https://www.youtube.com/watch?v=36SkjSZhNY0), 55 min.

### Videos
- [Cannibal interface, Vadim Makeev](https://www.youtube.com/watch?v=ssJsjGZE2sc), 42 min, 2017. Very practical speech about accessibility in web development
- [Accessible bank](https://www.youtube.com/playlist?list=PLQQ2oZWvIQCghnNH_yE94k8zi2Rs3rmqB), 3 short videos, 2018
- [Recording of the Inclusive Design meetup](https://www.youtube.com/watch?v=WT615ggoJPg), 3 hours, inclusion and accessibility in russian IT and banking companies, 2020
- [Lena Ryan: The visually impaired version? Maybe you don't need to?](https://www.youtube.com/watch?v=F8RZTWeaDnY), 34 min, 2021. Many local information about russian market, many pieces of practical advice

### Other
- https://vk.com/tipicalblind, community of blind people, sharing their stories


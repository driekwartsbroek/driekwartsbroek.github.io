# Links Accessibility Lesson  Uxcel
## Use descriptive link labels

![Use descriptive link labels Bad Practice](https://img.uxcel.com/practices/use-descriptive-link-labels-1611656821397/b-1686061341119.jpg)

![Use descriptive link labels Best Practice](https://img.uxcel.com/practices/use-descriptive-link-labels-1611656821397/a-1686061341119.jpg)

Similar to visual users, assistive technology users often scan pages to get the gist. When you press the [tab](https://app.uxcel.com/glossary/tabs) key repeatedly, the screen reader reads only the text links without the surrounding copy. If all link labels look like "click here" and "read more," it becomes impossible to understand what the [page](https://app.uxcel.com/glossary/pages) is about and where these links lead.

How can we improve this experience? Make link labels as descriptive and specific as possible while clearly stating what will happen after users click the link in question. Use details within reason, though. For example, "Read full report" instead of "click here" is fine. A label like "Read the full report about how to [design](https://app.uxcel.com/glossary/design) better links for [usability](https://app.uxcel.com/glossary/usability) & [web](https://app.uxcel.com/glossary/web) accessibility" might be overkill.

## Indicate links that open in a new window

![[Attachments/7ee6625b99e751c5ebbdf29808172bad_MD5.jpg]]

![[Attachments/72eee9164958ee50d619bb0e297a0790_MD5.jpg]]

For people who have difficulty perceiving visual [content](https://app.uxcel.com/glossary/content), links that open in a new window or tab can be disorienting. It's not always apparent how to go to the previous page as the Back Button doesn't take you back.

Ideally, avoid links that open in a new tab or window. In cases where it's necessary, communicate the link's behavior clearly. You can do it either by including the [warning](https://app.uxcel.com/glossary/warning) in the text describing a control or using [CSS](https://app.uxcel.com/glossary/css) to provide a warning before opening a new window.

**Tip!** Put extra information at the end, so that screen reader users don't have to hear it over and over again. For example, "Web Content Accessibility Guidelines (new window)" instead of "Link opens in a new window: Web Content Accessibility Guidelines.

## Specify link destination

![[Attachments/54b789fed5ec9013986a76b2de08c8c8_MD5.jpg]]

![[Attachments/ea1f7f52d7480101058e4607b6c55bd7_MD5.jpg]]

It's essential for users to understand what will happen after they click the link. Include information about what a link leads to — especially on [mobile](https://app.uxcel.com/glossary/mobile). If you're linking to a PDF, say so.

Also, avoid using URLs as link text even if they are self-explanatory. This makes it unnecessarily complicated for assistive technology users as screen readers read the URL letter by letter. For example, it will read a link www.hongkongdisneyland.com starting with "Double-U, Double-U, Double-U," etc. The label "Hong Kong Disneyland" would work much better in this situation.

**Tip!** If you're using image-based icons to indicate file extension, add ALT-Text to make it accessible to screen reader users.

## Make your links recognizable

![[Attachments/2d4f594479c2689b4c5fc8ff27d5549f_MD5.jpg]]

![[Attachments/4651eb6dd2688bed793e22ae015923bb_MD5.jpg]]

Interacting with hyperlinks is probably the most frequent activity that people do online — that's why hyperlink design is crucial for usability. If links look indistinguishable from the [body text](https://app.uxcel.com/glossary/body-text), most users will miss them.

Make your links instantly recognizable. For example, if you use [color](https://app.uxcel.com/glossary/color) alone, 8% of male users who suffer from the most common [forms](https://app.uxcel.com/glossary/forms) of color-blindness won't see them. Underline is a popular and commonly-understood way to communicate the presence of link content. Besides, underlined links function as a sort of sub subheading within the text, guiding users to critical information when skimming.

## Use consistent voice and tone

![[Attachments/a901d35164cd8b95541e710ce1335580_MD5.jpg]]

![[Attachments/f381931c22affefc0efde86867f8694b_MD5.jpg]]

Your voice and tone must stay consistent throughout the content. Every piece of copy should reflect your chosen voice. The tone of voice can vary in different situations, but the [product](https://app.uxcel.com/glossary/product) should sound the same.

Consistency of voice is crucial in reinforcing your [brand](https://app.uxcel.com/glossary/branding). The more consistent your brand voice sounds, the more users get used to it, trust it, and connect with a product. [Research](https://app.uxcel.com/glossary/research-knowledge) your audience to find out what brand voice will appeal to them. Is it compelling, emotional, funny, or motivating?

For example, casual writing adheres to active voice, uses colloquialisms, and reminds us of actual human speech. In [contrast](https://app.uxcel.com/glossary/contrast), the official voice uses longer sentences and passive voice and sounds academic.

## Ensure that controls have focus states

Focus [states](https://app.uxcel.com/glossary/states) are crucial to people who use the [keyboard](https://app.uxcel.com/glossary/keyboards) only. They indicate which interactive element has keyboard focus and lets users know that they can perform [actions](https://app.uxcel.com/glossary/actions) like activating a button or navigating to a link's destination.

## Use the <href> attribute for links

![[Attachments/f70c3b6991ae2c72d85286671e7bd15c_MD5.jpg]]

![[Attachments/34228cb49e477d352dfe9b321e7b3513_MD5.jpg]]

Inaccessible links are one of the most severe barriers to overall accessibility. Assistive technology has made progress in handling links, but it has limitations.

Screen readers generally inform users that a piece of text or a graphic is a link. For that, links must have a `href` attribute, even when used in Single Page Applications (SPAs). Avoid using an `onclick` event in place of a `href` attribute as assistive technology can't process such links correctly.

**Tip!** There's no need to use the words "link" or "links to" in your link text as screen readers tell users when they encounter a link.

Take the lesson quiz and assess your knowledge

Completing the interactive quiz is proven to help you learn faster and remember the information for longer.

## Key skills

## From Course

![[Attachments/f3c023691c442168a28be3e2ed4599b6_MD5.svg]]

Design Accessibility

## Share this lesson
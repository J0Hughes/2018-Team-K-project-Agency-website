# Jobs to do, part 3: controlling our content with CSS

## Remove the temporary CSS code

Delete the CSS code in the `<style>` tag and remove the comments from the `<link rel="stylesheet">` section. Refreshing the page in your web browser should bring in a starter stylesheet. Add 

```
* {border:1px solid red;}
```

to make sure that your stylesheet is being picked up by your HTML code. Delete that line once everything's working correctly.

## The process

__Don't use your web browser full screen__. Modify the viewport so it's as small as you can make it, and preview your site that way. Small screens don't allow for much in the way of layout, so concentrate on making your typography and colour work well. Remember, __don't use your web browser full screen__.

## Start adding styles for typography and colour

You can start off by cutting and pasting the CSS code from the various codepens. Work systematically so you can navigate what will turn out to be a reasonably long stylesheet (my sample site is 262 lines long). I like to have the styles for my pages in the same order as the HTML, so the header CSS code would be above the bio CSS code, for example.

### Typography and colour from the style guide

Start to identify how you can use the typography and colour settings you have from your style guide. Add your google font code (in the same way you added it to your style guide), and think about which parts of your page would benefit from using which typeface. Add the CSS for headings, paragraphs and links - remember to relate these to the div classes in your HTML code.

### Add the border-box model CSS code

Here is the magic incantation you need to use to change your browser's behaviour - just go to [Paul Irish's website](https://www.paulirish.com/2012/box-sizing-border-box-ftw/) and copy the code in the grey box after the first three paragraphs, then paste it into your stylesheet. Although you won't see much change in the way your page looks immediately, it will make things much easier as we go along.

### Add a responsive column of content

- [Add the responsive column of content CSS](https://codepen.io/wilsondmmu/pen/PJQYZG)  illustrated in the lecture. Modify the code to create __two__ classes `.text-content__container` and `.site-footer__container`.
- 'tune' the `max-width` with a 65 character line for your typeface using this paragraph:  
`<p>01234567890123456789012345678901234567890123456789012345678912345</p>`
- There's more information about why we do this and how it works [at this codepen on font sizing and column widths](https://codepen.io/wilsondmmu/pen/PJdGyE).

### Call to action

A 'call to action' or CTA is a really obvious button that you want people to click. Discuss in your group examples of CTAs, e.g. those on [wordpress.com](https://wordpress.com/) or [Netflix](https://www.netflix.com/gb/).

Style the link to your portfolio page as a CTA - use the code in your style guide as a starting point.

[Creating a call to action](https://codepen.io/wilsondmmu/pen/GXGVPx)

You might want to use a contrasting colour or a gradient to make it more 'button like'. Make sure it matches the rest of your site - the balance is to make it stand out but not make it totally different to everything else.

**Check the CTA works properly on very small or very wide screens.**

### Stop here for week three - but you can continue on into the unknown if you want...

### Header

[Add the CSS code in the codepen](https://codepen.io/wilsondmmu/pen/MGWEzO) then start thinking about how you can add your site's branding through modifying the code. You might add a background image, or test different ways of incorporating your logo.

### Team bios

[Use the codepen CSS](https://codepen.io/wilsondmmu/pen/yxyQoE) as a starting point and modify it to suit you. You probably don't want the red borders - they are just there so you can see what's going on.

Think about the photography or illustration style you're going to use. Are you going to create a corporate atmosphere by having all the portraits in the same style, or be more anarchic and let everyone do their own thing?

**Check the bio section on small and wide screens** - have a read through the pasted code to see how the media queries add and remove CSS.

### Style the 'skip to content' link

[Use the code at this codepen](https://codepen.io/wilsondmmu/pen/QZrLxZ) to create a skip link that appears as the visitor tabs onto the page. Clicking on the link or pressing return when it is visible will scroll the visitor to the main content of the site, starting with the introductory paragraph.

### Check the details

Go through and look for details that you can style. For example, check your footer links - are they readable against the background? Have you updated the footer code with your group's name?. Ask us if you aren't sure how to write the CSS to just 'target' links in the footer.

When you come to style the introduction, could you add some interesting typography? How will you visually connect the introduction, to the links, to the submission points, to the call to action? 

## What's next

Well done, you're well on the way. Scroll up and down your site a few times. Tab through your site to check it's usable with just the keyboard. Is there anything that looks wrong, or needs more work? Be critical about your work, and discuss it in your group.

[Now you need to test and check your work](https://github.com/mmu-webdesign/level5-portfolio/blob/master/INSTRUCTIONS-for-creating-your-agency-site/jobs-to-do-4.md).


---
title: Writing Alt Text for AI-Generated Images
---
# Writing Alt Text for AI-Generated Images

Generated images are increasingly common on blogs and product pages, and they are often published with empty or useless alt text such as "AI image". Alt text matters just as much for generated images as for photographs.

## Describe purpose, not process
Screen-reader users need to know what the image communicates in context. "Illustration of a cosy reading nook with a window seat and stacked books" is useful. "Image generated with a diffusion model" is not.

## Don't paste the prompt
Prompts contain style keywords ("8k, cinematic, trending") that are noise to a listener. Write a fresh sentence.

## Length
One or two sentences, roughly under 150 characters, for most images. Complex informational images need a longer description nearby in the text.

## Decorative images
If an image is purely decorative, use empty alt (`alt=""`) so screen readers skip it.

## Disclosure is separate
If you disclose that an image is AI-generated (a good practice), put that in a visible caption, not in alt text only. For example: "Illustration created with the [Seedream 5.5 AI image generator](https://seedream5-5.net/)." That way sighted readers and screen-reader users get the same information.

## Quick checklist
- Does the alt text make sense if the image fails to load?
- Is it specific to this page's context?
- Have you removed prompt jargon?

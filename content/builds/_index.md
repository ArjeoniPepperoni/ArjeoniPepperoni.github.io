---
title: "Custom Builds"
type: "widget_page"

sections:

  - block: hero
    content:
      title: "Welcome to My Widget Page"
      text: "Some charming explanation of why this page exists. Keep it short."
    design:
      background:
        image: "media/banner.jpg"   # make sure this file exists in /static/media/
        parallax: true
      spacing:
        padding: ["150px", "0", "150px", "0"]

  - block: markdown
    content:
      title: "About This"
      text: |
        Here goes your text. You can use normal markdown.
        Add paragraphs, lists, whatever you want.
    design:
      spacing:
        padding: ["50px", "0", "50px", "0"]

  - block: contact
    content:
      title: "Get in Touch"
      text: "Fill this in unless you enjoy bottling up your problems."
      form:
        provider: netlify
        netlify:
          captcha: true
        fields:
          email: true
          name: true
          subject: true
          message: true
        submit_label: "Send"
    design:
      spacing:
        padding: ["50px", "0", "50px", "0"]
---

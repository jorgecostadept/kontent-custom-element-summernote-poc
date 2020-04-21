# Summernote Rich Text Editor
This is a [custom element](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features) for [Kentico Kontent](https://kontent.ai) that allows users to use the [Summernote rich text editor](https://summernote.org/).

![Screenshot of custom element](SummernoteRichTextEditor.gif)

## Setup

1. Deploy the code to a secure public host
    * See [deploying section](#Deploying) for a really quick option
1. Follow the instructions in the [Kentico Kontent documentation](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features#a-3--displaying-a-custom-element-in-kentico-kontent) to add the element to a content model.
    * The `Hosted code URL` is where you deployed to in step 1
    * No JSON parameters are necessary

## Deploying

Netlify has made this easy. If you click the deploy button below, it will guide you through the process of deploying it to Netlify and leave you with a copy of the repository in your GitHub account as well.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/hzik/kontent-custom-element-summernote)

## What is Saved?

```json
"summernote": {
        "type": "custom",
        "name": "summernote",
        "value": "<h1>Some heading</h1><p><b>lorem ipsum</b></p><pre>code sample</pre><ul><li>item 1</li><li>item 2</li><li>item 3</li></ul><p><br></p><table class=\"table table-bordered\"><tbody><tr><td>cell 1</td><td>cell 2<br></td></tr><tr><td>cell 3<br></td><td>cell 4<br></td></tr></tbody></table><p><br></p>"
      }
```


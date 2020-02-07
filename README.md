# TEMPLATE Custom Element for Kentico Kontent

This is a [custom element](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features) for [Kentico Kontent](https://kontent.ai) that allows users INSERT BRIEF DESCRIPTION OF FUNCTIONALITY.

<!-- ![Screenshot of custom element](ScreenshotFileName.png) -->

## Setup

1. Deploy the code to a secure public host
    * See [deploying section](#Deploying) for a really quick option
1. Follow the instructions in the [Kentico Kontent documentation](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features#a-3--displaying-a-custom-element-in-kentico-kontent) to add the element to a content model.
    * The `Hosted code URL` is where you deployed to in step 1
    * If necessary, pass the necessary parameters as directing in the [JSON Parameters configuration](#json-parameters) section of this readme.

## Deploying

Netlify has made this easy. If you click the deploy button below, it will guide you through the process of deploying it to Netlify and leave you with a copy of the repository in your GitHub account as well.

***UPDATE THE REPOSITORY URL BELOW***

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/ChristopherJennings/kontent-custom-element-sample-template)

## JSON Parameters

Document any necessary JSON parameters here. Provide a sample like the one below:

```Json
{
  "googleApiKey": "YOUR_GOOGLE_API_KEY",
  "center": {
    "lat": -25.344,
    "lng": 131.036
  }
}
```

## Saved Value

The value is saved as a string representing a JSON object. When deserialized, it will look like:

```Json
{
  "sample" : "This is a sample of the value your custom element saves",
  "complex": {
    "canBeComplex":true
  }
}
```

## Contributors

Originally contributed by [@{USER}](https://github.com/{USER}/)

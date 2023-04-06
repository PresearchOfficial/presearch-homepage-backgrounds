# Presearch Home Backgrounds
For uploading community-contributed homepage background on [presearch.com](https://presearch.com).


![](/screenshot.png)

If you would like to contribute your own photography or are to be potentially included as a background image option on Presearch, please submit a pull request. 

## Step 1 - Fork the repository

Create your own local version of the repository by clicking the "fork" button on the [`presearch-homepage-backgrounds`](https://github.com/PresearchOfficial/presearch-homepage-backgrounds) github page.

## Step 2 - Add your images

Once you have forked the repository, go to the `/images` folder and add the image(s) you'd like to contribute. You MUST own the copyright to the image or have the right to license it to Presearch. 

All images must be JPEG images with an extension of `.jpg`

*IMPORTANT:* BY submitting a pull request you grant the project a permanent, unrevocable, royalty-free license to use it for any purpose.

## Step 4 - Add image metadata.

Every image must also be accompanied by a metadata file with the same base name as the image. If your image is `john-doe-sunset.jpg`, then you must also submit a `john-doe-sunset.json` file containing metadata describing the image. 

An example metadate file would look like:

```
{
    "name": "Sunset",
    "author": "John Doe",
    "license": "https://creativecommons.org/publicdomain/zero/1.0/",
    "source": "Generated with Stable Diffusion",
    "url": "https://www.john-doe-digital-art-gallery.com/sunset"
}
```

The `author` and `url` metadata, if provided, will be used on the presearch.com homepage to identify the image and link the the author's website.

You may also include additional metadata. For example, if the image is AI-generated, you can include the prompt or settings used to generate the image so that others can recreate it. We recommend including the license under which you would like to release the image if you intend for others to be able to use beyond Presearch.

## Step 3 - Create a pull request.

If you're unfamiliar with creating a pull request, you can find instructions [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

Your pull request should be from your fork of the `presearch-homepage-background` repository and should target the `main` branch at https://github.com/PresearchOfficial/presearch-homepage-backgrounds

## Step 4 - Wait on review and approval

Someone from the Presearch community will eventually review your images and either accept or reject the pull request. If accepted, your image might be viewable as a background in the future on [presearch.com](https://presearch.com)!
# Project Outreach

This was a proof-of-concept deployment of a image classification model that can identify when an image contains a person with acne, or when an image contains a person with reddened skin. Skin burn/redness is a common side effect of tretinoin usage. The model could be used as part of a pipeline for a more proactive response to our patients experiencing side effects, where we can reach out to them and have our doctors discuss changes to their medication. This would create a more personalised high touch, higher quality experience. 

# Deployment

This was written in [fast.ai](https://www.fast.ai) and the model was deployed on [Render](https://render.com).
This repo can be used as a starting point to deploy [fast.ai](https://github.com/fastai/fastai) models on Render.
The sample app described here is up at https://project-outreach.onrender.com/. Test it out with acne/tretinoin burn images.
You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```

The guide for production deployment to Render is at https://course.fast.ai/deployment_render.html.
Please use [Render's fast.ai forum thread](https://forums.fast.ai/t/deployment-platform-render/33953) for questions and support.

Web Demoe and API: Replicate

An implementation of InstructPix2Pix: Learning to Follow Image Editing Instructions in Cog, and pushing it to Replicate.

First, download the weights (update the corresponding model_id of the model, which need to be available on HuggingFace):

    cog run script/download-weights 

Then, you can run predictions:

    cog predict -i prompt="..." -i image=@... 

Or, push to a Replicate page:

    cog push r8.im/...

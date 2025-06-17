# Style2Stats – Phase 1

An analysis project exploring visual traits in AI-generated portraits using TensorArt and Tableau.

## Project Summary

100 AI-generated images were analyzed based on attributes like:
- Hair length
- Hair color
- Eye color

All attributes were manually recorded and visualized using Tableau.

## Files Included
- `img_attributes_phase1.xlsx`: Annotated dataset
- `style2stats_phase1.twbx`: Packaged Tableau dashboard
- `LICENSE`: MIT License

## Observations
- All generated faces were Asian females with dark hair/eyes, indicating prompt/model bias.
- Hair length was overwhelmingly long (97%).

## Tools Used
- TensorArt (Image generation)
- Google Sheets (Data entry)
- Tableau (Data visualization)
- Git & GitHub (Version control)

## Next Steps
- Expand dataset with more diverse prompts
- Perform clustering or correlation analysis
- Compare across models
  
## Model Details
Platform: Tensor.Art
Model Used: majicmix realistic v7
Resolution: 640×640-square
Prompt: "portrait of a young adult, ultra‑realistic, close‑up, neutral expression, studio lighting"
Negative Prompt: signature, username, logo, bad hands, mutated hands, lowres, (worst quality, bad quality:1.2), bad anatomy, sketch, jpeg artifacts, watermark, censored.
CFG Scale: 7
Sampling Method: Euler Ancestral
Sampling Steps: 25
Upscaler: None
VAE: Default
Hi-res Steps / Denoising Strength: 20 / 0.5

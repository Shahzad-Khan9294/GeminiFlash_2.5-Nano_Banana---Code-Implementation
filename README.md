# GeminiFlash_2.5-Nano_Banana
Google's Nano Banana—officially known as Gemini 2.5 Flash Image—is a cutting-edge AI model developed by Google DeepMind, designed to revolutionize image generation and editing. It offers advanced capabilities that set it apart from other AI image models.

## Key Features of Nano Banana
1. Conversational Image Editing
2. High-Fidelity 3D Modeling
3. Character Consistency Across Edits
4. Rapid Image Generation
5. Multi-Input Support

## Room Furniture Editing (Replacing, Removing, Arranging, Styling)
Few ScreenShot Results:

<div style="display: flex; flex-direction: row;">
    <img src="https://github.com/user-attachments/assets/0ac8759a-dcc6-4e59-8c02-406263d586fb" width="220" />
    <img src="https://github.com/user-attachments/assets/2faec034-8dcd-41d5-b1b4-56945b069ab5" width="220"/>
    <img src="https://github.com/user-attachments/assets/e65c8138-e1a7-4f89-bee2-39b00a497308" width="220" />
    <img src="https://github.com/user-attachments/assets/ee2332d8-ee70-4418-ad94-80cf5de36e9a" width="220" />
</div>

### Prompt used: 
"I'd like to see the room furnished with a bed, a sofa, plants, rugs and table lamps but use these images of bed I’m attaching here"

## Installation

```python
pip install -U -q "google"
pip install -U -q "google.genai"
```
### Go to https://openrouter.ai -> Generate the API and call the model by using this code block
```python
payload = {
    "model": "google/gemini-2.5-flash-image-preview:free",
    "messages": messages
}
```


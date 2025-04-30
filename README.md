# EX-02 Cross Platform Prompting Evaluating Diverse Techniques in AI Powered Text Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.
Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:
- Accuracy
- Coherence
- Simplicity
- Speed
- User experience

## Output
### Prompt:
Explain the process of photosynthesis in simple terms for a 5th-grade student.
### ChatGPT:
Sure! Here's a simple explanation of photosynthesis for a 5th-grade student:
________________________________________
Photosynthesis is how plants make their own food using sunlight.
Here’s how it works:
1.	Sunlight shines on the plant.
2.	The leaves take in carbon dioxide from the air.
3.	The roots take in water from the ground.
4.	Inside the leaves, there’s a special green stuff called chlorophyll that helps use the sunlight.
5.	The plant mixes sunlight, carbon dioxide, and water to make sugar (food for the plant) and oxygen (which goes into the air).
________________________________________
So in short: 🌞 + 💧 + 🌬️ → 🍬 + 🌬️
(Sunlight + Water + Carbon dioxide → Sugar + Oxygen)
That’s how plants eat and help us breathe! 🌱💚
### Gemini:
Photosynthesis is how plants make their own food! Imagine a plant is like a tiny chef in the kitchen (its leaves). To cook, it needs a few simple ingredients:
1.	Sunlight: This is like the stove, providing the energy to cook. The leaves have a special green stuff called chlorophyll that catches the sunlight.
2.	Water: Plants drink water through their roots, and it travels up to the leaves. This is like one of the ingredients in the recipe.
3.	Carbon Dioxide (CO2): This is a gas in the air that we breathe out. Plants take it in through tiny holes in their leaves. Think of it as another ingredient.
Now, here's the magic! When the sunlight shines on the chlorophyll, it helps the plant mix the water and carbon dioxide together. This mixing process makes two important things:
1.	Sugar (Glucose): This is the plant's food! It gives the plant energy to grow and live, just like how we get energy from the food we eat.
2.	Oxygen (O2): This is a gas that the plant releases into the air as a leftover. Guess what? This is the same oxygen that we and many other animals need to breathe to stay alive!
So, in simple terms, photosynthesis is like a plant using sunlight to cook water and carbon dioxide into sugary food for itself and releasing the oxygen we need into the air. It's a super important process that helps plants grow and keeps us alive too!

### Meta AI:
Photosynthesis is like a superpower that plants have, and it's how they make their own food. Here's how it works:
- Plants absorb water and sunlight
- Plants stretch out their roots to drink water from the ground, and their leaves soak up sunlight from the sky.
- They take in carbon dioxide
- Plants also absorb a gas called carbon dioxide from the air around them.
- They mix it all together
- The plants use energy from sunlight to mix water and carbon dioxide together. This creates a type of sugar that gives them energy.
- They release oxygen
- As a byproduct of making sugar, plants release oxygen into the air. Guess what? That's what humans and animals need to breathe!
- So, to sum it up: plants use sunlight, water, and carbon dioxide to make their own food (sugar) and release oxygen for us to breathe. Pretty cool, right?

## Text Summarization:
Text: Artificial Intelligence (AI) is rapidly transforming industries around the world. From healthcare and finance to transportation and education, AI technologies are being used to automate processes, improve efficiency, and deliver personalized experiences. One of the key drivers of AI adoption is machine learning, a subset of AI that enables computers to learn from data and improve over time without being explicitly programmed. As AI continues to evolve, ethical considerations such as data privacy, bias, and job displacement have become increasingly important. Governments and organizations are working to develop frameworks and regulations to ensure that AI is used responsibly and for the benefit of society.
### ChatGPT:
Artificial Intelligence (AI) is revolutionizing various industries by automating tasks and enhancing efficiency through technologies like machine learning. As its use grows, concerns about ethics, data privacy, bias, and job loss are prompting efforts to create responsible regulations and frameworks.
### Gemini:
This text highlights the rapid transformation of industries through Artificial Intelligence (AI), driven significantly by machine learning's ability to learn from data. While AI promises automation, efficiency, and personalized experiences across sectors like healthcare, finance, transportation, and education, its increasing adoption brings crucial ethical considerations. These include concerns about data privacy, potential biases in algorithms, and the impact on job displacement. Consequently, governments and organizations are actively working on developing frameworks and regulations to ensure the responsible and beneficial use of AI for society.
### Meta AI:
AI is transforming industries globally, driving efficiency, automation, and personalized experiences through machine learning. However, its growth raises ethical concerns like data privacy, bias, and job displacement. To address these issues, governments and organizations are developing frameworks and regulations for responsible AI use.


## Code generation:
```
Simple website html code:
ChatGPT:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Hello Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      height: 100vh;
      justify-content: center;
      align-items: center;
      background-color: #f0f0f0;
    }
    h1 {
      color: #333;
    }
  </style>
</head>
<body>
  <h1>Hello</h1>
</body>
</html>
```
## Gemini:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello</title>
</head>
<body>
    <h1>Hello!</h1>
</body>
</html>
```
## Meta AI:
```
<!DOCTYPE html>
<html>
<head>
	<title>Hello World</title>
</head>
<body>
	<h1>Hello!</h1>
</body>
</html>
```
## Result
Across the tested tasks, ChatGPT showed strengths in clarity and formatting, Gemini stood out for creativity and depth, and Meta AI provided the most concise and structured responses. The ideal choice depends on the use case—educational, technical, or quick-response needs all benefit from different combinations of platforms and prompting strategies.

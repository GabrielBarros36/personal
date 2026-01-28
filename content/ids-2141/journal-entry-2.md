---
title: "Journal Entry 2"
subtitle: "The Infamous Hot Dog App"
category: ids-2141
date: 2026-01-27
highlightSubtitle: true
---

My app is called "Hot Dog or No Hot Dog". Bonus points if you [get the reference](https://www.youtube.com/watch?v=ACmydtFDTGs). It's pretty self-explanatory: given a picture you take on your phone, the app will tell you whether it depicts a hot dog or not.

The app was developed with [Opencode](https://opencode.ai/) and built on React Native + Expo. It uses the [nateraw/food model](https://huggingface.co/nateraw/food), a finetuned version of a Vision Transformer model by Google, through the HuggingFace inference API. You can run the app yourself with the instructions on the [Github repo](https://github.com/GabrielBarros36/hotdog).

<div class="grid grid-cols-2 gap-4 mt-6">
    <img src="/images/Hot_Dog.PNG" alt="Hot Dog" class="w-full rounded-lg shadow-md" />
    <img src="/images/Not_Hot_Dog.PNG" alt="Not Hot Dog" class="w-full rounded-lg shadow-md" />
</div>

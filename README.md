# Project 1 Generative Text

Kayla LaPoure, klapoure2@huskers.unl.edu


## Abstract
Do you ever wake up in the morning not knowing what to wear? I personally do. With the latest trends coming and going faster that we can buy them, wouldn’t it be nice for something to show you what exactly is timeless? Well, perhaps the fashion advice from this GPT2 could help. It was trained on a variety of fashion blogs and with an array of advice. Through adjusting a variety of elements on the model it outputs what is thought were the most important elements.

To showcase this fashion advice I created an array of drawings and fashion. I tried to make sure that each individual in the drawing has different, beautiful features to show that the fashion the AI gives transcends us as humans, but also for people to see themselves in this type of art and experience.


## Model/Data

For my model data I collated different fashion blogs. Many of them came with pictures that I didn’t include, which caused some nonsensical outputs. Overall, I tried to make sure the fashion advice was numbered so you could have ten elements that will elevate your fashion.

## Code

https://crane-ood.unl.edu/node/c3105.crane.hcc.unl.edu/56679/doc/tree/generative-text-kaylalapoure/gpt2-generate-finetune.ipynb

## Results

I curated the top ten pieces of fashion advice that I thought were the most interesting. The reason I selected only ten was to create a bite size experience to share with others. When thinking about fashion, people really only want to know the top tips, not necessarily a whole book of fashion advice. 

The fashion advice I took was trained in a variety of ways. I experimented a lot with the step to learning rate ratio. The most cohesive output came from a lower step, but a higher learning rate, I used around 500 steps and 1e-3 learning rate. While this was more understandable, some of the more playful advice came from training where this ratio was swapped. I trained it at 1000 steps and 1e-2 learning rate. 

Questions that help prompt the GPT with answers:

“For the perfect outfit try”

“Try”

“To be fashionable you must”

## Curated GPT2 Fashion Advice

1.To avoid embarrassment and embarrassment, the outfit should be simple and casual. The idea of dressing with ease and with care is essential. Opt for the best fit and the most comfortable shoes for the person.

2.To avoid possible cuts and stains, the outfit should have a soft sheen and a sheen that is soft and inviting. The outfit should not be made of plastic or prone to knots. The outfit should not be made of plastic, but should be light and loose-fitting. The style of dress that you want to wear should be chosen carefully.

3.A simple rule of thumb for hat making: If you only have 5 staples in your wardrobe, don't need more. This hat will do just that.

4.The power of GIF tattoos lies in their ability to convey emotion without the effort. This white GIF tattoo comes in two colors, black and white. This simple and versatile white T-shirt will do the trick.

5.If you love to look chic in white flour sacks, this white T-shirt will do the trick.

6.Stylisthing with style, this nail art bag from Jeans Originals is a must-have accessory for any professional looking to look professional. 

7.A simple rule of thumb for hat making: If you only have 5 staples in your closet, pick this white T-shirt as your face mask. This simple rule of thumb will do the trick. 

8.For the perfect outfit try this simple trick: keep the hem of the shirt tucked in the back and the hem of the jacket or bottoms up. This will make the rest of the outfit look effortless and flattering 

9.For an even trickier way to wear an item, fold the jacket in half and place it over your head and put the strap back on.

10.Don’t Hold Back on Socks


You can find all the outputs under the gpt2 outputs file.


## Technical Notes


I used the cloned git file shared with me and the Jupyter lab. I then used my Project1V1 txt file to train the GPT2. Some elements I changed to get the results were the temperature (I generally used .7), the step, which was changed between 200-1000, and the learning rate, which was changed from 1e-2 to 1e-3.


## Reference
Blogs I used to train my GPT2 model on:

Fashion Tips: The Top 10 Tips From Stylish Women (stitchfix.com)

Fashion news and features | British Vogue

Style | Fashionista - Fashionista

All the Best Fashion Campaigns of Spring/Summer 2022 (elle.com)

The 50 Best Fashion Blogs You Should Read in 2022 - Detailed.com

Hello Fashion (hellofashionblog.com)

Top 100 Fashion Blogs You Must Follow in 2022 (feedspot.com)

3 Ways to Dress Fashionably - wikiHow

14 Easy Ways to Look More Fashionable 2020 - How to Look Stylish (cosmopolitan.com)

8 Fashion Tips to Ensure You Always Look Stylish - 2022 - MasterClass

35 Fashion Tips For Women On How To Look Fashionable (fashionlady.in)

How to Look Stylish Every Day | The Well Dressed Life

4 Ways to Be Trendy - wikiHow

6 Ways To Dress Trendy in Chilling Winters (news4masses.com)

Fashion 101: How to Look Trendy & Modest When Layering | INNERMOD

How To Look Good: 20 Ideas That Make You More Attractive (shinesheets.com)

5 TIPS TO LOOKING STYLISH EVERY DAY. – TheDamiAlex (wordpress.com)

Dress Like An Italian Woman and Look Elegant Daily with our Popular Italian Style Guide | La Belle Society


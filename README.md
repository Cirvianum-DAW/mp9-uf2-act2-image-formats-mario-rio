[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/SM0Un0ri)
# MP9 - UF2 Act2 (UF2.2) - Image Optimization and Analysis in Different Formats

## Objective:

In this task, you will explore the impact of different formats and compression levels on images and learn to evaluate and choose the optimal format for each situation.

### Instructions:

As you can see, this code allows us to display some images and dynamically show some of their details with a fairly simple code. It's not necessary to understand the details of the Javascript file, but have a look generally to get an idea of how it works.

### Task1: Images and Formats

- We provide you with four images: "logotip," "plujaEstels" "postaDeSol" and "transparency". You will find them in the "images" folder of this task.
- For each of the images, you should create a new page. If you add any navigation options between them, it will be a plus.
- Your task is to EXPORT the images in different formats and different compression levels and analyze the results. For each image you'll need at least:
  - Export in each of the formats: PNG, JPEG, and GIF.
  - In case of JPEG, you should export it with different compression levels: Low, Medium, and High.
  - In case of GIF or PNG, at least two different color depths: 8-bit and 24-bit.
- You can do the export with GIMP, but you MUST FIND ANOTHER TOOL to do it and SHARE IT IN THE FOLLOWING LINK: [LIST OF TOOLS](https://docs.google.com/spreadsheets/d/1M1cjVm03rX554sMzXRX8MlUFjs7kVy1eBQyo01bVSzY/edit?usp=sharing)

This is a table of the different formats and compression levels to be considered (doesn't mean you must have all of them, but at least the ones mentioned):

| Image Name       | Formats        | Compression Levels | Color Depth           |
| ---------------- | -------------- | ------------------ | --------------------- |
| logotip.png      | PNG, JPEG, GIF | Low, Medium, High  | 8-bit, 24-bit, 32-bit |
| plujaEstels.jpg  | PNG, JPEG, GIF | Low, Medium, High  | 8-bit, 24-bit, 32-bit |
| postaDeSol.gif   | PNG, JPEG, GIF | Low, Medium, High  | 8-bit, 24-bit, 32-bit |
| transparency.png | PNG, JPEG, GIF | Low, Medium, High  | 8-bit, 24-bit, 32-bit |

- When you're done, MAKE YOUR PROJECT AVAILABLE ONLINE (GitHub Pages, Netlify, Vercel, etc.). Share the link in the Moodle activity.

### Task2: Analysis

While you're working on this task, you should document your findings in the same page where you're posting your images. Try to also add What you MUST INCLUDE is:

- General information about the image: size, dimensions, etc. must be visible as in the example.

- **logotip**: What format is the most optimal for this type of image and why? Can its size be reduced even more? Would it lose quality?
- **plujaEstels** and **postaDeSol**: What format is the most optimal for this type of image and why? With what compression quality does the image not lose quality? Can we reduce its size even more without losing quality? What would happen if we save the image several times with JPEG format?
- **transparency**: What is the most optimal format for this type of image and why? What happens when we save it in JPEG format? If our website has a white background, what format would be the most optimal and why?

### Task3: DeveloperTools - Lighthouse:

- Have a look at developerTools' Lighthouse tool. This allows you, among other things, to analyze the loading of the images. Check the performance of the different pages you have created.

1. What does Lighthouse tell about the image related perfomance of your pages? What are the main issues? What are the main recommendations?

2. Fake a slow 3G connection and analyze the loading of the images. What do you observe?

Add your findings to each of the pages you have created.

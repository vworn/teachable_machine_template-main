# 🧠 In-Class Coding Project: Teachable Machine + ml5.js Image Classifier

## 🎯 Project Overview
In this project, you will **train your own image recognition model** using Google's **Teachable Machine**, then **customize and run it** using a provided **HTML/JavaScript template** that uses **ml5.js**.

By the end of this project, you'll have a **working AI-powered webpage** that recognizes images from your webcam!

---

## 📂 Step 1: Download the Project Template
- Download the project template from this GitHub repository:
  - [Teachable Machine Template](https://github.com/markumreed/teachable_machine_template)
- Extract the ZIP file onto your computer.

---

## 📚 Step 2: Learn About the Tools
- **Read the ml5.js documentation** on the `imageClassifier` with Teachable Machine models:
  - [ml5.js Image Classifier - Teachable Machine Reference](https://docs.ml5js.org/#/reference/image-classifier-tm)

Focus on:
- How to load a Teachable Machine model into your website.
- How to use the `predict()` function.
- How to customize the output.

---

## 🛠️ Step 3: Train Your Own Model
1. Go to [Teachable Machine](https://teachablemachine.withgoogle.com).
2. Click **"Get Started"** → **"Image Project"** → **"Standard Image Model."**
3. Create **three different classes** (e.g., hand gestures, objects, facial expressions).
4. **Use your webcam** or upload images to **train** each class.
5. After training, click **Export Model**, and choose **"Upload (Hosted)"**.
6. **Copy the model URL** — you'll need it for your project.

---

## 🎨 Step 4: Customize the Template
Open the downloaded template folder:

- Open the `sketch.js` file.
- **Replace the model URL** in the `classifier = ml5.imageClassifier()` line with your own model URL.
- **Change the text color** displayed on the webpage.
  - Locate where the `fill()` function is used (inside the `draw()` function).
  - Change the color, e.g., `fill('blue')`, `fill('#FF5733')`, etc.

Example:
```javascript
fill('#1E90FF'); // Dodger Blue text color
```

---

## 🔬 Step 5: Test Your Classifier
- Open the `index.html` file in your browser.
- Allow webcam access when prompted.
- Test your trained model!
- Watch the prediction text appear with your customized color.

---

## ✅ Submission Checklist
- [ ] You have trained your own model with three different classes.
- [ ] You updated the `sketch.js` file with your model URL.
- [ ] You customized the text color using the `fill()` function.
- [ ] You tested your classifier in the browser.

---

# 📢 Important Notes:
- You **must** use your own model URL.
- **Do not** modify unrelated files.
- Make sure your webcam is working.
- Refresh the page after updating your model link.

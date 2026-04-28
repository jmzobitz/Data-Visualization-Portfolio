# 🚀 Build Your Data Visualization Portfolio

Instructions to create and publish a personal portfolio website using a template and RStudio.

---

## ✅ Step 1: Log into your **own personal github account**  (not the one for class)

This is important because our class repositories are private.

## ✅ Step 2: Clone the template repository on your **own personal github account** 

1. Go to:  
   [https://github.com/jmzobitz/Data-Visualization-Portfolio](https://github.com/jmzobitz/Data-Visualization-Portfolio)

2. Click **“Use this template”** → **Create a new repository**

3. Name your repository (e.g., `data-visualization-portfolio`)

4. Make sure:
   - ✅ Repository is **Public**

5. Click **Create repository**


## ✅ Step 3: Copy your repository URL

After creating your repository on GitHub:

1. Go to your repository’s main page on GitHub  
2. Click the green **Code** button  
3. Make sure **HTTPS** is selected (this is the default and recommended option)  
4. Click the **copy icon** next to the URL  

It should look something like:


https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git


This copies the repository URL to your clipboard.

---

## ✅ Step 4: Open your project in RStudio

In RStudio, run:

```r
usethis::create_from_github(
  "https://github.com/YOU/YOUR_REPO.git",
  destdir = "~/path/to/where/you/want/the/local/repo/"
)
```

Notice that there are a lot of additional files here - these are needed to make the website run.
---

## ✅ Step 5: Copy over your files from your previous portfolio

Add in all the Data visualization portfolio files.

## 🌐 Step 6: Commit your repository and then view your live website

After pushing:

1. Go to your repository on GitHub
2. Click the Actions tab
3. Wait for the workflow to finish

Your site will be live at:

```r
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```
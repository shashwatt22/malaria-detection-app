# Malaria Detection — Deep Learning Web App

[🚀 Live Demo](https://malaria-detector-omega.vercel.app)

A full-stack deep learning web application designed to screen blood cell smear images for malaria parasites. The project combines a highly optimized computer vision pipeline with a lightweight web interface for instant clinical inference.

## 📊 Key Highlights & Metrics
* **High-Accuracy Vision Core:** Fine-tuned a ResNet18 architecture on 27,000 NIH blood-smear images, achieving a **96.66% test accuracy**.
* **Clinical Optimization:** Applied custom threshold optimization (0.35) to mitigate diagnostic risks, successfully cutting false negatives by **32%** (from 84 down to 57) and elevating parasitized recall from **0.96 to 0.97**.
* **Production Deployment:** Built a robust REST inference endpoint utilizing **FastAPI** in Python, serving predictions seamlessly to the frontend interface hosted on **Vercel**.

## 🛠️ Project Structure
* `/frontend`: Interactive web UI for uploading blood cell images and visualizing detection results.
* `/backend`: FastAPI server handling image preprocessing, model weight loading, and inference execution.

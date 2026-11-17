# EcoSort AI: Intelligent Waste Classifier
Building AI course project

## Summary
EcoSort AI is an image-recognition application designed to help citizens correctly sort household waste by scanning items with a smartphone camera. The system instantly classifies materials into recycling categories, reducing contamination and promoting sustainable habits.

## Background
- **The problem:** Many people struggle with proper waste sorting because recycling rules can be confusing and vary by municipality.
- **Frequency:** This is a daily challenge for millions of households, leading to recyclable materials ending up in landfills.
- **Personal motivation:** I wanted to create a practical, accessible tool that uses computer vision to make eco-friendly choices effortless for everyone.

## How is it used?
- **Users:** Households, students, and local communities.
- **Context:** Used at home when throwing away trash or at public recycling bins. The user opens the app, points their phone camera at an item (like a plastic container or cardboard box), and immediately receives clear instructions on which bin to use.

## Data sources and AI methods
- **Data sources:** Public image datasets of household waste (such as TrashNet) containing labeled photos of glass, plastic, paper, and metal.
- **AI techniques:** Convolutional Neural Networks (CNN) for image classification and computer vision to identify object features.

## Challenges
- **What it does not solve:** It cannot clean dirty items, determine the exact polymer type of complex plastics, or fix municipal policy differences regarding waste management.
- **Ethical/Limitations:** Misclassification can happen if lighting is poor or items are heavily crushed, which might lead to improper disposal.

## What next?
- **Future growth:** Partner with local municipalities to integrate real-time local recycling guidelines and add a gamification system to reward users for recycling correctly.
- **Assistance needed:** Collaboration with mobile developers and waste management experts.

## Acknowledgments
- Inspired by environmental sustainability goals and open-source computer vision initiatives.
- Dataset reference: TrashNet project 

# TactileVision: AI-Powered Graphics for the Visually Impaired

Final project for the Building AI course

## Summary

This project aims to develop an AI-powered system that automatically converts 2D educational graphics and textbook illustrations into standardized tactile graphics for visually impaired individuals. By leveraging advanced deep learning techniques, the system identifies key semantic elements in an image and translates them into appropriate textures and elevation levels suitable for 3D printing or tactile embossing.

## Background

Visually impaired individuals rely heavily on tactile graphics to understand spatial concepts in science, mathematics, and geography. However, creating high-quality tactile graphics is currently a manual, time-consuming, and expensive process that requires specialized human expertise. 

This scarcity of resources leads to several critical issues:
* **Delayed Access:** Visually impaired students often receive educational materials weeks after their sighted peers.
* **Limited Scope:** Many rich diagrams in textbooks are simply omitted due to high production costs.
* **Inequality in Education:** It hinders spatial cognition and independent academic development for the visually impaired.

My personal motivation comes from wanting to democratize accessible educational tools, bridging the gap between advanced cognitive psychology principles and modern computer vision.

## How is it used?

The solution will be deployed as an intuitive cloud-based web platform and an API for educational publishers. 

1. **Upload:** A special education teacher or publisher uploads a standard 2D textbook diagram (e.g., a biological cell or a geometric map).
2. **Processing:** The AI instantly segments the image and assigns optimal elevation levels.
3. **Download & Print:** The system outputs a standardized 3D-printable (.STL) or tactile embossable file ready for physical production.

Below is an illustration of tactile conceptual exploration:
![Tactile Exploration Example](https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?auto=format&fit=crop&w=800&q=80)

## Data sources and AI methods

The AI model requires a robust dataset consisting of paired image domains:
* **2D Graphics Data:** Open-source vector repositories, public digital textbooks, and educational graphic frameworks.
* **Tactile Targets:** High-quality tactile templates annotated with specific Exploratory Procedures (EPs) markers and precise physical height maps.

| AI Component | Method Used | Description |
| --- | --- | --- |
| Image Segmentation | Convolutional Neural Networks (CNNs) | To detect semantic regions and line boundaries |
| Style Translation | Deep Regression & Generative Models | To output continuous physical height maps |

## Challenges

* **Tactile Overload:** If a 2D image contains excessive details, the AI might generate too many distinct textures, causing cognitive overload during hand exploration.
* **Ethical Considerations:** Automatic simplification must not accidentally remove critical educational context from the original diagram.

## What next?

To move this project forward, the system needs to be trained on a wider variety of non-standard illustration styles. Collaboration with tactile cognition researchers and special education accessibility experts will be essential to run empirical usability tests with real users.

## Acknowledgments

* Inspired by research in Exploratory Procedures (EPs) and spatial cognition in special education.
* Course template provided by Reaktor Innovations and University of Helsinki for Building AI.

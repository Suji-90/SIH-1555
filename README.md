# Smart India Hackathon Workshop
# Date:20.05.25
## Register Number:212223040212
## Name:SUJITHRA K
## Problem Title
SIH 1555: Create a Virtual Herbal Garden that provides an interactive, educational, and immersive experience to users, showcasing the diverse range of medicinal plants used in AYUSH (Ayurveda, Yoga & Naturopathy, Unani, Siddha, and Homeopathy).
## Problem Description
Background: The AYUSH sector relies heavily on medicinal plants and herbs, which form the backbone of traditional healing practices. However, physical gardens that are not accessible to everyone. A Virtual Herbal Garden will bridge this gap by offering a digital platform where users can explore, learn, and understand the significance of various medicinal plants from the comfort of their homes. Description: Participants are tasked with developing a Virtual Herbal Garden that is engaging, informative, and user-friendly. This virtual garden should include: Interactive 3D Models: Realistic 3D models of medicinal plants that users can rotate, zoom, and explore from different angles. Detailed Information: Comprehensive details about each plant, including its botanical name, common names, habitat, medicinal uses, and methods of cultivation. Multimedia Integration: High-quality images, videos, and audio descriptions to enhance the learning experience. Search and Filter Options: Advanced search functionality to easily locate specific plants and filter them based on various criteria like medicinal uses, region, and type. Virtual Tours: Guided virtual tours highlighting specific themes, such as plants for digestive health, immunity, skin care, etc. User Interaction: Features that allow users to bookmark favourite plants, take notes, and share information on social media. Expected Outcome: The expected outcome is a comprehensive Virtual Herbal Garden that serves as a valuable educational tool for students, practitioners, and enthusiasts of the AYUSH sector. This platform should make the knowledge of medicinal plants accessible to a wider audience, promoting awareness and understanding of traditional herbal practices. It should be visually appealing, informative, and interactive, providing users with an immersive experience that combines technology with traditional knowledge.

## Problem Creater's Organization
Ministry of Ayush

## Idea

The Virtual Herbal Garden (VHG) is a web-based interactive platform that showcases a wide range of medicinal plants used in the AYUSH systems. It aims to replicate the experience of visiting a real herbal garden through immersive 3D models, rich educational content, and guided virtual tours.

This application will empower users (students, health enthusiasts, AYUSH practitioners) to:

Explore 3D models of plants

Understand their uses and cultivation

Take thematic virtual tours (e.g., plants for immunity, digestion, skincare)

Access multimedia content to aid visual and auditory learners

The platform bridges the accessibility gap, promotes traditional knowledge digitally, and provides engaging tools for herbal education and awareness.

## Proposed Solution / Architecture Diagram

![ChatGPT Image May 20, 2025, 02_49_55 PM](https://github.com/user-attachments/assets/dcad5f99-596f-4dd6-941c-0df2328f3cfa)

## Use Cases
1. Plant Exploration
Actors: User

Description: Browse 3D models of medicinal plants with zoom, rotation, and pan features.

Outcome: Users can visually explore and identify plants.

2. Information Lookup
Actors: User

Description: View detailed data like botanical names, uses, cultivation methods.

Outcome: Users gain in-depth understanding of each plant.

3. Thematic Virtual Tours
Actors: User

Description: Take guided tours like “Top 10 Immunity Boosters” or “Herbs for Mental Wellness”.

Outcome: Simplified and thematic learning experience.

4. Search and Filter
Actors: User

Description: Find plants based on use-case (e.g., anti-inflammatory), location, AYUSH system, etc.

Outcome: Efficient access to relevant plant data.

5. User Engagement Features
Actors: User

Description: Bookmark plants, write notes, and share info on social media.

Outcome: Improved retention, personalization, and awareness.

## Usecase Diagram

![ChatGPT Image May 20, 2025, 03_01_41 PM](https://github.com/user-attachments/assets/54b9d7f5-d88f-4f87-8afe-ba70b81487be)


## Technology Stack

## Frontend:
React.js – Core framework for building the UI.

Three.js – For rendering interactive 3D models of medicinal plants.

React Three Fiber – React renderer for Three.js.

Tailwind CSS – Utility-first CSS framework for responsive design.

Framer Motion – For adding smooth animations and transitions.

Vite – For fast frontend development and build.

## Media Storage:
Firebase Storage – Easy integration with frontend for storing and retrieving images, videos, and audio.

AWS S3 – Scalable cloud storage for large media files with secure access control.

Cloudinary (optional) – Optimized image and video delivery with transformation features.
## Dependencies

## 3D Rendering:

three.js for rendering plant models

React Three Fiber for React integration

GLTFLoader for model loading

## Media & Content:

Video/audio hosting (YouTube, Vimeo API if embedded)

CDN/Image optimization libraries

Search & Filter:

ElasticSearch or simple backend filtering with MongoDB queries

## Authentication & State Management:

Firebase/Auth0 for login

Redux/Zustand for frontend state

## Cross-Platform Compatibility:

Responsive design via TailwindCSS

Progressive Web App (PWA) support (optional)


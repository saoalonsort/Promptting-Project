### 🚀 Try the Live Interactive Web Applications:
- 🟢 **[Launch Version 2 (Final App)](https://saoalonsort.github.io/Rehabilitación_tobillo_versión_2.html/)**
- 🟡 **[Launch Version 1 (Initial Prototype)](https://saoalonsort.github.io/Rehabilitación_tobillo_versión_1.html/)**

After breaking my ankle, my physical therapist gave me a paper guide with exercises. The document had pictures showing how to perform the exercises. Each exercise required between five and ten repetitions, and some required materials such as a towel, a cushion, or a chair. Others required a specific position, such as sitting in a chair, on a bed, or leaning against a wall. Seeing an opportunity to put my learning into practice during the "Introduction to AI & Prompt Engineering" course, I decided to transform that document into an interactive, step-by-step web application using structured prompting.
The Challenges and the Process:
- Document Digitization & Extraction: I scanned the document and used prompts to extract the information from the document and convert it into a web application.
- Handling AI Hallucinations: When trying to process the original exercise photos, the model hallucinated—generating abstract diagrams with lines and dots that failed to explain the actual movements. To fix this, I extracted manually the document's pictures and saved them as PNG files. The AI model could then use the images and insert them correctly into the web application.
- Enhancing User Experience: I instructed the model to insert sounds to signal the different repetitions of the exercise, the rest periods between each repetition, to indicate when an exercise was finished and when an exercise was started. Between exercises, I guided the model to integrate a reminder to the user to prepare equipment (towel, chair, cushion) or to change positions for the next exercise.
The Outcome:
I successfully built a fully functional physiotherapy web app that I personally used throughout my recovery. I documented the entire end-to-end process, logging dificulties, prompt adjustments, and troubleshooting steps to ensure reproducible results.

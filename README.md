# -AI-Powered-Handwritten-Equation-Solver-Text-Converter

AI-Powered Handwritten Math Solver + Text Converter(Android App)

🚀 Project Showcase: AI-Powered Handwritten Equation Solver + Text Converter📱✍️➗

I recently developed an Android application that combines Computer Vision and Math Expression Evaluation to automatically detect and solve handwritten mathematical equations using the device camera. 🤖📸

🔍 What It Does:

Opens the camera to capture handwritten math problems.

Uses Google ML Kit’s Text Recognition API to extract handwritten content from images.

Cleans and parses the extracted text into a valid mathematical expression.

Evaluates the expression using the exp4j math engine.

Displays the original expression and the solution in a scrollable TextView.

🧠 Technologies Used:

🔧 Kotlin (Android SDK)

📷 Camera via ActivityResultContracts.TakePicture

🧠 Google ML Kit (TextRecognition)

🧮 exp4j for on-device math expression evaluation

🧾 ViewBinding + XML Layouts

🔒 FileProvider for secure file access

🔄 Scrollable UI for long results

🧠 Challenges Solved:

OCR accuracy with noisy or handwritten input

Sanitizing recognized text into a valid math format

Handling empty or incorrect recognition safely

UI that gracefully scrolls both vertically and horizontally

✅ Key Features:

On-device processing (no internet required)

Works with both printed and clear handwritten math

User-friendly UI with scrollable result area

Captures image temporarily without cluttering storage

📌 Use Case Example:

 A student can write an equation like 12 + (8 / 4) on paper, capture it, and instantly see the solution.

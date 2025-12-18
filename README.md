TaxGen AI v2.0 🇮🇳

An AI-Powered Income Tax Return (ITR) Preparation Assistant

TaxGen AI is a web-based concept application designed to simplify the Indian tax filing process. It demonstrates a futuristic, 7-step automated workflow that leverages Artificial Intelligence to parse documents, verify tax credits, optimize deductions, and generate filing summaries.

🚀 Features

7-Step Guided Workflow: A visual, state-managed journey from document upload to final e-filing hand-off.

AI Deduction Optimization: Uses Google Gemini API to analyze income details and suggest optimal Chapter VI-A deductions (80C, 80D).

Smart Document Simulation: Simulates secure tokenization and extraction of data from uploaded Form 16 PDFs.

Real-time Tax Calculation: Instantly computes tax liability or refunds based on the Old Tax Regime.

PDF Report Generation: Client-side generation of a detailed ITR summary using jsPDF and html2canvas.

Cloud Persistence: Uses Firebase Firestore to save user progress in real-time, allowing sessions to resume seamlessly.

Responsive UI: Built with Tailwind CSS for a clean, modern interface that works on all devices.

🛠️ Tech Stack

Frontend: HTML5, JavaScript (ES6+), Tailwind CSS (CDN)

AI Engine: Google Gemini 2.0 Flash (via REST API)

Backend / Database: Google Firebase (Authentication & Firestore)

Utilities:

jspdf & html2canvas (PDF Generation)

FontAwesome (Icons)

📦 How to Run

Clone this repository or download the files.

Open the index.html file in any modern web browser (Chrome, Edge, Firefox).

Note: No local server is strictly required, but for the best experience with Firebase and API calls, running it via a simple local server (like Live Server in VS Code) is recommended.

🔑 Configuration

The application is currently configured with demo API keys for:

Firebase: Configured for anonymous authentication and database storage.

Gemini API: Configured to provide AI responses for deduction optimization.

Note: In a production environment, these keys should be secured via backend proxies.

📸 Usage Guide

Step 1: Upload a sample PDF (Form 16). The system simulates scanning.

Step 2: Click to verify TDS against Form 26AS.

Step 3: Let the AI analyze your income and suggest tax-saving deductions.

Step 4: Calculate your final tax liability or refund.

Step 5: Generate the ITR JSON schema structure.

Step 6: Download the summary PDF for your records.

Step 7: Use the direct link to the official Income Tax Portal for final submission.



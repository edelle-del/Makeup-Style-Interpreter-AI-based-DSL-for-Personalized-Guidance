# Makeup-Style-Interpreter-AI-based-DSL-for-Personalized-Guidance

## Overview
This project reimagines the traditional programming interpreter as a domain-specific tool for cosmetology. Instead of executing machine code, this system reads high-level makeup styles and translates them into a sequence of localized, step-by-step visual instructions tailored to a user’s specific facial structure.

## The Interpreter Architecture
The system operates similarly to a traditional language processor by treating makeup styles as "source code" to be executed on the "hardware" of a user's face.

* **Lexical Analysis & Parsing:** The system tokenizes user-defined commands (e.g., "glam," "natural") and validates them against a predefined style grammar.
* **Semantic Execution:** Rather than generating machine code, the interpreter executes a sequence of geometric transformations and image-processing functions.
* **Actionable Output:** The "execution" phase results in a dual-output: a textual guide and a visual overlay mapping makeup application areas directly onto an uploaded photo.

## Core Features
* **Face-Shape Detection:** Identifies unique facial geometry to customize the placement of contours and highlights.
* **Dynamic Command Processing:** Interprets structured input to generate real-time feedback and guidance.
* **Visual Overlay Engine:** Uses computer vision to map coordinates and provide a graphic preview of the final look.
* **Educational Pipeline:** Simplifies complex makeup techniques into digestible, step-by-step learning modules for beginners.

## Technical Implementation
* **Concepts:** Inspired by classic compiler theory (Aho et al.), utilizing parsing and execution logic.
* **Computer Vision:** Utilizes facial landmarking to create the coordinate system for the "execution" of makeup commands.
* **Tech Stack:** Python, OpenCV for image manipulation, and custom parsing logic for style interpretation.

## Real-World Applications
This project bridges the gap between abstract computer science theory and artistic self-expression. By bringing together software engineering and cosmetology, the system serves as a learning tool for beginners and a visualization engine for professional makeup artists, demonstrating how interpreter systems can facilitate deep personalization in the beauty and cosmetics sector.

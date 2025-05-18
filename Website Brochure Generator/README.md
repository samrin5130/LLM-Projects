# Brochure Generator

## Overview
The Brochure Generator is a tool designed to automatically create professional brochures for companies using their website content. By providing a company name and its main website, the tool scans the site, extracts relevant links, and generates a polished brochure based on the gathered information. This tool leverages the power of the **Qwen3:4B model** via **Ollama** for content selection and **Gradio** for the user interface, making the entire process seamless and easy to use.

## Features
- Automatically identifies relevant links from a given website.
- Extracts content from selected web pages to generate a brochure.
- Uses **Qwen3:4B model** for content analysis and brochure generation.
- Provides a simple **Gradio** interface for easy user interaction.
  
## How It Works
1. **Extracting Relevant Links**  
   The tool uses the **Qwen3:4B model** via **Ollama** to scan the provided website and identify the most relevant links for brochure creation. A structured JSON response is returned with the selected links.
   
2. **Content Extraction**  
   After identifying the relevant links, the content from those pages is extracted and prepared for brochure generation.
   
3. **Brochure Generation**  
   The **Qwen3:4B model** is then called to create a brochure using the extracted content. This step ensures the brochure is both informative and professional.

4. **User Interface**  
   A simple **Gradio** interface allows users to input a company name and website, then automatically generate a brochure with minimal effort.


## Prerequisites
Before running the notebook, make sure you have the following installed:

- **Ollama**: A platform for running large language models. Install Ollama from https://ollama.com/.
- **Qwen3:4B Model**: The Qwen3:4B model is required for content analysis and brochure generation. Follow Ollama's documentation to install and set up this model.

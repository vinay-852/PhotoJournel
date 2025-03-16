---
title: Photo Journel Assistant
emoji: 📉
colorFrom: purple
colorTo: green
sdk: streamlit
sdk_version: 1.40.2
app_file: app.py
pinned: false
license: mit
short_description: Photo Journel Assistant
---

# PhotoJournel

📉 **PhotoJournel** is a Streamlit-based application that allows users to manage their photo collections by generating meaningful captions, extracting metadata, and creating a beautifully written journal entry.

## Features

- **Photo Management**: Upload your photos in JPG, JPEG, or PNG formats.
- **Caption Generation**: Automatically generate meaningful captions for each photo using the BLIP model.
- **Metadata Extraction**: Extract metadata such as the date taken and location from the photos.
- **Journal Entry Creation**: Combine captions and metadata to create a cohesive and engaging journal entry.
- **Downloadable Entries**: Download the generated journal entry as a text file.

## Installation

To get started with PhotoJournel, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/vinay-852/PhotoJournel.git
    ```
2. Navigate to the project directory:
    ```sh
    cd PhotoJournel
    ```
3. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
4. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:
    ```sh
    streamlit run app.py
    ```
2. Open your web browser and go to `http://localhost:8501` to access PhotoJournel.

## How It Works

- **Caption Generation**: Uses the BLIP model from Salesforce to generate captions based on the uploaded images.
- **Metadata Extraction**: Extracts EXIF data from images to retrieve the date taken and GPS coordinates.
- **Journal Entry Creation**: Combines the generated captions and metadata to create a journal entry using a generative AI model configured with custom settings.

## Contributing

We welcome contributions to improve PhotoJournel. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature/your-feature-name
    ```
3. Make your changes and commit them:
    ```sh
    git commit -m "Add your commit message"
    ```
4. Push to the branch:
    ```sh
    git push origin feature/your-feature-name
    ```
5. Open a pull request explaining your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [vinay-852](https://github.com/vinay-852).


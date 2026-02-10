# XML-JSON Converter (Maven)

A JavaFX application built with Maven that performs bi-directional conversion between XML and JSON formats.

## 🚀 Features

- **XML to JSON**: Converts complex XML structures into organized JSON objects using the **Jackson API** for high-performance data binding.
- **JSON to XML**: Converts JSON data back into valid XML format using **StAX (Streaming API for XML)**, ensuring memory-efficient and precise control over the XML output.
- **Maven Managed**: All dependencies (Jackson, JavaFX) are handled automatically via the `pom.xml`.

## 🛠️ Built With
- **Java 17+**: The core programming language.
- **JavaFX**: For the Graphical User Interface (GUI).
- **Jackson Library**:  Used for the XML-to-JSON transformation .
- **StAX**:  Used for manual XML writing during JSON-to-XML conversion.
- ## Vidéo de démonstration
https://drive.google.com/file/d/1q4vaRAFlNOted_51Tfezk-XYfxW3LV09/view?usp=sharing

## 📂 Project Structure

```text
XmlJson_Converter/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/mycompany/xmljson_converter/
│   │   │       ├── App.java                 # Main Application entry point
│   │   │       ├── SceneController.java      # JavaFX UI Logic
│   │   │       ├── XmlJsonTransformer.java   # XML to JSON (Jackson API)
│   │   │       └── JsonXMLTransformer.java   # JSON to XML (StAX)
│   │   └── resources/
│   │       └── fxml/
│   │           └── Scene.fxml               # JavaFX Layout
├── .gitignore                               # Excludes 'target/' and local IDE files

└── pom.xml                                  # Maven Dependencies & Build Config



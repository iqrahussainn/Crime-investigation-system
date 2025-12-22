# Crime Investigation Expert System (KR&R)

This project implements a **rule-based Crime Investigation Expert System** using **Knowledge Representation and Reasoning (KR&R)** concepts.

The system analyzes crime investigation details such as weapon used, motive, violence, theft, location, witness presence, fingerprint evidence, and suspect proximity. Based on these inputs, it applies **IF–THEN rules** to infer the **type of crime** using **forward chaining reasoning**.

After identifying the crime, the system consults a **legal knowledge base** to automatically suggest the **applicable law section and punishment**. The system also provides a clear **explanation of the reasoning process**, making the decisions transparent and easy to understand.

An interactive **Gradio web interface** is included to allow users to manually input crime details and view results in real time.

### Key Features
- Rule-based expert system (no machine learning)
- Symbolic knowledge representation using facts
- Forward chaining inference
- Legal reasoning (crime → law → punishment)
- Explainable outputs
- Interactive Gradio user interface

### Technologies Used
- Python
- Experta (PyKnow)
- Gradio

### Purpose
This project is developed as an **end-semester project** for the **Knowledge Representation and Reasoning** course and is intended for **educational purposes only**.

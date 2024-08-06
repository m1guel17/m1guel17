# Hi there, I'm Miguel Esteban Flores Sierra 👋
### Freelance back-end Python engineer

I am a passionate **Software Developer** and **Electronics Engineer** from Lima, Peru. With expertise in Python, C#, Java, C++, SQL, and Linux, I have over 4 years of experience in software and hardware design, specializing in innovative and impactful solutions for complex environments.

#### About Me
- 🎓 Graduated from **Universidad Nacional Mayor de San Marcos**.
- 💼 Currently a **Software Analyst at PCI Energy Solutions**, ensuring optimal user experiences and contributing to the growth and innovation of our software offerings.
- 🛠️ Experienced in **multidisciplinary projects**, seamlessly integrating electronics with mechanical designs, primarily for robotics applications.

#### Skills
- 🐍 **Python, Java, C#, C++, SQL**
- 🛠️ **Data Analytics**, **Machine Learning**, and **Cybersecurity**
- 🖥️ **Linux Systems Administration**

# 💻 Tech Stack:
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=plastic&logo=java&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=plastic&logo=python&logoColor=ffdd54) ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=plastic&logo=c-sharp&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=plastic&logo=c%2B%2B&logoColor=white)  ![Octave](https://img.shields.io/badge/OCTAVE-darkblue?style=plastic&logo=octave&logoColor=fcd683)  ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=plastic&logo=pandas&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=plastic&logo=plotly&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=plastic&logo=scikit-learn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=plastic&logo=TensorFlow&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=plastic&logo=scipy&logoColor=%white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=plastic&logo=numpy&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=plastic&logo=Keras&logoColor=white) ![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=plastic&logo=latex&logoColor=white)

# Encuéntrame en:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-miguel-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/miguel-esteban-flores-sierra)
</br>

# Algunos proyectos desarrollados
## Bookstore_Flask (_under development_) [![Roadmap](https://img.shields.io/github/stars/m1guel17/Bookstore_Flask?label=Bookstore_Flask&style=social)](https://github.com/m1guel17/Bookstore_Flask)
Simple bookstore web application built using Flask, following a layered architecture design pattern. The application is structured to separate concerns and improve maintainability by organizing code into different layers.
<p align="center">
<img src="https://github.com/user-attachments/assets/c6e89c40-8455-46d6-ae21-a6c64c440c30" width="720">
</p>

## Chatbot-Whatsapp-Meta [![Roadmap](https://img.shields.io/github/stars/m1guel17/Chatbot-Whatsapp-Meta?label=Chatbot-Whatsapp-Meta&style=social)](https://github.com/m1guel17/Chatbot-Whatsapp-Meta)
Python script developed to test the functionality of a WhatsApp chatbot using Meta API and WhatsApp Business. The script is developed in Visual Studio Code and utilizes the Meta API for interacting with a WhatsApp Business test account.
```mermaid
graph TD
  A["Start"]
  B["Initialize Flask app"]
  C["Configure SQLite database"]
  D["Define Log model"]
  E["Create tables if not exist"]
  F["Define ordenar_por_fecha_y_hora function"]
  G["Define index route"]
  H["Retrieve logs from DB"]
  I["Order logs by date"]
  J["Render index.html"]
  K["Define webhook route"]
  L{Request method}
  M["GET: Verify token"]
  N["POST: Process messages"]
  O["Send response"]
  P["Receive and parse JSON"]
  Q["Check message type"]
  R["Interactive message"]
  S["Text message"]
  T["Send WhatsApp message"]
  U["Log message to DB"]
  V["Error handling"]
  W["End"]

  A --> B --> C --> D --> E
  E --> F --> G
  G --> H --> I --> J
  G --> W
  K --> L
  L -->|"GET"| M --> O
  L -->|"POST"| N
  N --> P --> Q
  Q -->|"Interactive"| R --> T
  R --> U
  Q -->|"Text"| S --> T
  S --> U
  N --> V
  O --> W
  V --> W
```

## Quadrupedal_Robot (_under development_) [![Roadmap](https://img.shields.io/github/stars/m1guel17/Quadrupedal_Robot?label=Quadrupedal_Robot&style=social)](https://github.com/m1guel17/Quadrupedal_Robot)
This project aims to create a quadrupedal robot that can be controlled using a Raspberry Pi and ESP32 microcontrollers. The robot will perform basic movements such as walking, turning, and stopping, and can be further extended with additional functionalities.
<p align="center">
<img src="https://github.com/user-attachments/assets/fb4d6924-da4f-4aa2-9c81-be8eec2a9ae3" width="480">
</p>

## ROS-node [![Roadmap](https://img.shields.io/github/stars/m1guel17/ROS-node?label=ROS-node&style=social)](https://github.com/m1guel17/ROS-node)
This project is part of a lab test to get you started on ROS nodes and arduino communication. All documentation has been taken from the ROS website and can be found there. It's highly recommended to install Arduino first and arduino ros serial node to work with it on ubuntu environment.
```mermaid
graph LR;
    /AH-->/AB;
    /AH-->/AC;
    /AH-->/AD;
    /AC-->/C;
    /AB-->/B;
    /AD-->/D;
    /C-->/CF;
    /B-->/BE;
    /D-->/DG;
    /CF-->/F;
    /BE-->/E;
    /DG-->/G;
    /F-->/FH;
    /E-->/EH;
    /G-->/GH;
    /FH-->/H;
    /GH-->/H;
    /EH-->/H;
    /H-->/HI;
    /HI-->/I;
    /I-->/Arduino;
    /Arduino-->/AH;
```

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=m1guel17&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=m1guel17&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=m1guel17&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

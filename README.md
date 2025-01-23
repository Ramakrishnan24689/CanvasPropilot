# Welcome to CanvasPropilot

```

 _____                                   ______                      _  _         _   
/  __ \                                  | ___ \                    (_)| |       | |  
| /  \/  __ _  _ __  __   __  __ _  ___  | |_/ / _ __   ___   _ __   _ | |  ___  | |_ 
| |     / _` || '_ \ \ \ / / / _` |/ __| |  __/ | '__| / _ \ | '_ \ | || | / _ \ | __|
| \__/\| (_| || | | | \ V / | (_| |\__ \ | |    | |   | (_) || |_) || || || (_) || |_ 
 \____/ \__,_||_| |_|  \_/   \__,_||___/ \_|    |_|    \___/ | .__/ |_||_| \___/  \__|
                                                             | |                      
                                                             |_|                      
```



# Canvas Propilot: AI-Powered Design Assistance for Canvas Apps  

**Canvas Propilot** is an intelligent, AI-powered assistant designed to help app makers create clean, polished, and consistent Canvas Apps with ease. Built with Fluent AI and integrated with **PowerApps Creator Kit**, it simplifies the app design process by generating YAML representations of screens based on user inputs. This solution ensures adherence to **Fluent Design System** and **Coherence** principles, making it a must-have tool for professional-grade app creation.  

![image](https://github.com/user-attachments/assets/d63b7c20-7020-4cc8-870d-ff202bc5d41e)
---

## 🚀 Features  

- **AI-Powered Prompts**: Generates screen descriptions through guided questions, powered by decision trees built on UX guidelines.  
- **YAML Generation**: Creates precise YAML representations for Canvas Apps screens.  
- **Fluent Design Integration**: Ensures all designs follow Fluent UI principles and incorporate Creator Kit components.  
- **Seamless Studio Experience**: Operates directly within PowerApps Studio, providing real-time validation and effortless screen creation.  
- **Copy-to-Clipboard Option**: Enables quick sharing or reuse of YAML files.  

---

## 🔗 Dependencies  

This solution requires the following dependencies:  
1. **[PowerApps Creator Kit](https://github.com/microsoft/PowerApps-creator-kit)**: Ensures seamless integration with Fluent UI components and Modern Controls.  
2. **AI Builder Credits**: Required for the AI-driven prompts and YAML generation capabilities. Ensure your environment is set up with adequate AI Builder credits.

---

## 🛠️ Installation  

### Prerequisites  
- PowerApps environment with **Creator Kit** installed.  
- AI Builder Credits enabled in your Power Platform environment.  
- Administrator permissions to import and configure solutions.  

### Steps  
1. Clone or download the repository.  
2. Import the **Canvas Propilot Solution** into your PowerApps environment via **Power Platform Admin Center**.  
   - Go to **Solutions** -> **Import** -> Upload the solution zip file.  
3. Install the **Creator Kit** dependency if not already installed.  
   - Follow the [Creator Kit documentation](https://github.com/microsoft/PowerApps-creator-kit).  
4. Ensure AI Builder credits are configured and enabled.  
   - Go to **Admin Center** -> **Capacity** -> Manage AI Builder.  
5. Configure the Dataverse table for storing YAML templates and Fluent App schema (instructions provided in the `/docs` folder).  
6. Open PowerApps Studio and start creating apps with the **Canvas Propilot Code Component**.  

---

## 🧩 How It Works  

1. **Generate YAML with Custom Prompts**:  
   - Start by describing your app using a series of guided questions.  
   - The AI-driven prompts generate YAML representations for each screen based on Fluent Design principles.  

2. **Create Screens in No Time**:  
   - Use the PCF component to integrate the YAML directly into PowerApps Studio.  
   - Validate, refine, and generate screens seamlessly.  

3. **Reusability with Copy-to-Clipboard**:  
   - Save time by copying YAML files directly from the studio for sharing or reuse in other apps.  

---

## 🤝 Contributions  

We welcome contributions to enhance the Canvas Propilot! Feel free to open issues or submit pull requests.  



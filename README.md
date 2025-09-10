# **MediShare**

**Your smart solution for a healthier community, one pill at a time.**

## **Project Overview**

MediShare is a digital health application designed to solve the critical problems of medicine waste and misuse. The app uses machine learning to help users manage their personal medicine inventory by tracking expiration dates and facilitating the responsible donation of unused, non-expired medication. Our goal is to promote public health, reduce environmental impact, and foster a culture of mindful consumption.

## **Current Status**

This repository currently contains a static frontend mockup (index.html) to demonstrate the app's user interface and core concept. The purpose of this initial version is to serve as a visual blueprint for the final product and to validate the core idea for a hackathon.  
Future development will focus on building out the full-stack architecture and integrating the machine learning model.

## **Planned Features**

* **Image Recognition:** An AI-powered scanner that reads expiration dates and medicine names directly from a photo of the packaging.  
* **Expiration Alerts:** Automated reminders sent to the user well in advance of a medicine's expiration date.  
* **Donation Hub:** A feature that allows users to find and connect with nearby certified NGOs or health centers to safely donate their unused medicine.  
* **Personalized Profile:** A secure user dashboard to view, manage, and track all medicines in their inventory.  
* **Dosage Reminders:** The ability to set custom alarms for taking specific medications.

## **Tech Stack**

* **Frontend:** HTML, CSS with Tailwind CSS, JavaScript (planned with React.js / React Native for mobile app).  
* **Backend:** Python with Django.  
* **Database:** Firebase.  
* **Machine Learning:** Python with TensorFlow and Keras (Not Confirmed).

## **How to Run the Frontend Mockup**

To view the current frontend mockup, simply open the index.html file in your web browser.  
git clone \[https://github.com/your-username/your-repo-name\](https://github.com/your-username/your-repo-name)  
cd your-repo-name  
open index.html

### **Using a Live Server Extension**

To see your changes live without manual reloads, you can use a live server extension for your preferred IDE.

* **VS Code:** [Live Server by Ritwick Dey](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)  
* **Sublime Text:** [LiveServer by molnarmark](https://packagecontrol.io/packages/LiveServer)  
* **JetBrains IDEs (e.g., WebStorm):** Use the built-in **Live Edit** feature. [Learn how to set it up here.](https://www.jetbrains.com/help/idea/live-editing.html)  
* **Neovim:** Use a plugin like [live-server-nvim](https://github.com/ngtuonghy/live-server-nvim) which integrates with the live-server npm package.  
* **Notepad++:** You can use a plugin like [Preview HTML](https://fossil.2of4.net/npp_preview) to get a live preview.  
* If you are using a different IDE/Code Editor, a quick search for "live server extension for \[Your IDE\]" should give you a good option.

**NOTE:** The index.html file is a static mockup. Live server extensions are used currently for this mockup, but later for the full-stack app, the backend will be responsible for serving files and handling API requests.

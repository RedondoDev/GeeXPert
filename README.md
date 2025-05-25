<div id="Badges1">
    <img alt="Stars Count" src="https://img.shields.io/github/stars/RedondoDev/GeeXPert-Backend?style=flat-square&color=yellow">
    <img alt="License" src="https://img.shields.io/badge/License-MIT-purple?style=flat-square">    
</div>
<div id="Badges2">
    <img alt="Java" src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" height="20">
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" height="20">
    <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" height="20">
    <img alt="Angular" src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" height="20">
    <img alt="Node JS" src="https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" height="20">
    <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" height="20">
    <img alt="Tailwind" src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" height="20">
    <img alt="MySQL" src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" height="20">
    <img alt="Docker" src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" height="20">
    <img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white" height="20">
</div>

<br>

<div align="center">
    <img alt="Logo" src="https://github.com/user-attachments/assets/24a690de-ea78-48d1-8284-03758c07dc68" width="100%"">
</div>

# GeeXPert
*<h3>Track your games, level up your experience.</h3>*
Every hero needs a quest log. Keep track of your played, pending and completed games as you embark on epic adventures across diferent worlds. From indie gems to AAA titles, make sure no game gets left behind.
<br><br>
GeeXPert is a web application for video game fans. In GeeXPert you can discover video games, create your own video game collection and track the progress of them.
Also, you can discover video games based on your tastes through our artificial intelligence assistant.
<br><br>
*I hope you enjoy it - RedondoDEV*

## Table of Contents
- [Images](#images)
- [Technologies](#technologies)
- [Code](#code)
- [Resources](#resources)
- [Installation](#installation)
- [Author](#author)
- [License](#license)

## Images
| Home | Trending Games |
|:---:|:---:|
|<img src="https://github.com/user-attachments/assets/41ad56d5-ee23-47c8-aec8-cef70a09034c" width="500"/>|<img src="https://github.com/user-attachments/assets/62507580-bdd5-4d45-b414-4547f316cd32" width="500"/>|
| Rated Games | Trending Games |
|<img src="https://github.com/user-attachments/assets/c6a310d5-eaa6-472d-8353-47daa2083a99" width="500"/>|<img src="https://github.com/user-attachments/assets/4e2bdcde-975e-4739-93ac-2d402de54409" width="500"/>|
| Sign In | Sign Up |
|<img src="https://github.com/user-attachments/assets/27a66c5f-5524-41e3-b502-3d5c26d07c2b" width="500"/>|<img src="https://github.com/user-attachments/assets/0709474b-e6ea-4f76-a634-23a18213ac92" width="500"/>|
| Collection | Recommendations |
|<img src="https://github.com/user-attachments/assets/49300689-a3d2-49de-9270-ca43e55dc8d0" width="500"/>|<img src="https://github.com/user-attachments/assets/8a41aed8-2b8b-494f-800a-69b497cae0f4" width="500"/>|
| Card out of Collection | Card in Collection |
|<img src="https://github.com/user-attachments/assets/3c98c644-cb08-4c8f-90e1-20a13991a499" width="200"/>|<img src="https://github.com/user-attachments/assets/f9bae418-55c4-4837-8329-3b35c68cdbfe" width="200"/>|

## Technologies
<ul>
    <li>Java</li>
    <li>Spring Boot</li>
    <ul>
      <li>Spring Web</li>
      <li>Spring Security</li>
      <ul>
        <li>JWT Authentication</li>
      </ul>
      <li>Spring Data JPA</li>
      <ul>
        <li>Hibernate</li>
      </ul>
    </ul>
    <li>MySQL</li>
      <li>TypeScript</li>
      <li>Angular</li>
      <ul>
        <li>Angular Material</li>
      </ul>
      <li>Node JS</li>
    <li>HTML5</li>
    <li>Tailwind CSS</li>
    <li>Ollama</li>
    <ul>
      <li>llama3.2:3b</li>
    </ul>
    <li>Maven</li>
    <li>Postman</li>
    <li>Docker</li>
    </ul>
</ul>

## Code
The source code can be found at the following links:
- [GeeXPert-Backend](https://github.com/RedondoDev/GeeXPert-Backend)
- [GeeXPert-Frontend](https://github.com/RedondoDev/GeeXPert-Frontend)

*NOTE: The installation process and more details about the code are in these repositories.*

## Resources
- https://github.com/ollama/ollama
- https://api-docs.igdb.com/#getting-started

## Installation

### 🎮 GeeXPert Installation Guide

This guide describes the necessary steps to run the GeeXPert application on your local computer.

---

#### 🔧 Backend

##### 1. Clone the Repository

Go to the official repository: [GeeXPert-Backend](https://github.com/RedondoDev/GeeXPert-Backend)

1. Open the command console
2. Navigate to the path where you want to save the project
3. Execute the following command:

```bash
git clone https://github.com/RedondoDev/GeeXPert-Backend.git
```

##### 2. Install Docker Desktop

1. Download and install Docker Desktop from: [Docker Desktop for Windows](https://docs.docker.com/desktop/setup/install/windows-install/)
2. During installation, a window will appear requesting the installation of the WSL subsystem
3. Press any key to proceed with the installation
4. Once installed, open Docker Desktop so the service is running (you can minimize the application)

##### 3. Configure Environment Variables

1. Navigate to the root folder of the cloned project
2. Create a file named `.env`
3. Copy the following content into the file:

```env
DATABASE_URL=jdbc:mysql://mysql:3306/GeeXPert?allowPublicKeyRetrieval=true&useSSL=false
DATABASE_USERNAME=
DATABASE_PASSWORD=
IGBD_ID=
IGBD_KEY=
JWT_KEY=
```

##### 4. Complete the Environment Variables

You must fill in the following parameters:

###### `DATABASE_USERNAME`
- Database username
- No spaces or special characters

###### `DATABASE_PASSWORD`
- Database password

###### `IGBD_ID` and `IGBD_KEY`
- Register with the IGDB API following this guide: [IGDB Account Creation](https://api-docs.igdb.com/#account-creation)
- Once you obtain your ID and KEY, set them in the corresponding variables

###### `JWT_KEY`
- Generate a JWT key from: [JWT Secret Generator](https://jwtsecret.com/generate)
- **Important**: Select a length of **256 bits**
- Copy the generated key using the copy button

##### 5. Configure Ollama

Execute the following commands in the console:

```bash
# Access the Ollama container
docker exec -it ollama /bin/sh

# Download the AI model
ollama pull llama3.2:3b

# Verify the installation
ollama list
```

##### 6. Run the Backend

1. Open a command console
2. Navigate to the root path of the backend project
3. Execute:

```bash
docker compose up --build
```

---

#### 🖥️ Frontend

##### 1. Clone the Repository

Go to the official repository: [GeeXPert-Frontend](https://github.com/RedondoDev/GeeXPert-Frontend)

1. Open the command console
2. Navigate to the path where you want to save the project
3. Execute:

```bash
git clone https://github.com/RedondoDev/GeeXPert-Frontend.git
```

##### 2. Run the Frontend

1. Open a command console
2. Navigate to the root path of the frontend project
3. Execute:

```bash
docker compose up --build
```

---

#### 🚀 Application Access

Once all steps are completed, you can access the web application from your browser at:

**[http://localhost:4200/](http://localhost:4200/)**

---

#### 📧 Support

For any issues or problems with the installation, contact us:

**Email**: [JavierRedondoDev@gmail.com](mailto:JavierRedondoDev@gmail.com)

## Author
<table>
    <tr>
        <th>RedondoDEV</th>    
    </tr>
    <tr>        
        <td>
            <a href="https://github.com/RedondoDev">
                <img src="https://avatars.githubusercontent.com/u/163606882?v=1" width="110px"> 
            </a>
        </td>
    </tr>
</table>

## License
This project is licensed under the [MIT License](https://github.com/RedondoDev/GeeXPert-Backend/blob/master/README.md)   
<img alt="License" src="https://img.shields.io/badge/License-MIT-purple?style=flat-square">    

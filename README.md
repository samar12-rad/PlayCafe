# 🎲 PlayCafe Website

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
<!-- ALL-CONTRIBUTORS-BADGE:END -->

Welcome to the **[PlayCafe]** website repository! This project is part of **GirlScript Summer of Code (GSSoC) Extended** 🚀. Our cafe offers a warm and exciting environment for board game enthusiasts to gather, relax, and enjoy great food. This repository contains the code for the cafe's official website, aiming to create a fun and immersive online presence.

<div align="center">
    <img src="https://github.com/user-attachments/assets/33f1ecfc-6a94-48ed-b79c-4ee0e37d8a77" width="600px" height="250px">
</div>

<p align="center">
    <a href="https://github.com/RamakrushnaBiswal/PlayCafe"><img src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103"></a>
    <a href="https://github.com/mdazfar2/"><img src="https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg?v=103"></a>
    <a href="https://github.com/RamakrushnaBiswal/PlayCafe/blob/main/LICENSE"><img src="https://img.shields.io/badge/MIT-Licence-blue.svg?v=103"></a>
    <a href="https://github.com/RamakrushnaBiswal/PlayCafe/graphs/contributors"><img src="https://img.shields.io/github/contributors/RamakrushnaBiswal/PlayCafe?color=brightgreen"></a>
    <a href="https://github.com/RamakrushnaBiswal/PlayCafe/stargazers"><img src="https://img.shields.io/github/stars/RamakrushnaBiswal/PlayCafe?color=0059b3"></a>
    <a href="https://github.com/RamakrushnaBiswal/PlayCafe/network/members"><img src="https://img.shields.io/github/forks/RamakrushnaBiswal/PlayCafe?color=yellow"></a>
    <a href="https://github.com/RamakrushnaBiswal/PlayCafe/issues"><img src="https://img.shields.io/github/issues/RamakrushnaBiswal/PlayCafe?color=0059b3"></a>
</p>

<hr/>

## 📚 Table of Contents
1. [✨ Project Overview](#-project-overview)
2. [🌐 Demo](#-demo)
3. [🔥 Features](#-features)
4. [🛠️ Tech Stack](#-tech-stack)
5. [⚙️ Getting Started / 📥 Installation](#️-getting-started--installation)
6. [📌 Usage](#-usage)
7. [🔍 API Documentation](#-api-documentation)
8. [🤝 Contributing](#-contributing)
9. [🎯 Open Source Programs](#-open-source-programs)
10. [🌟 Mentors](#-mentors)
11. [👀 Our Contributors](#-our-contributors)
12. [⭐ Support](#-support)
13. [📄 License](#-license)
14. [📬 Contact Us](#-contact-us)

## ✨ Project Overview
The **PlayCafe Website** project is an exciting open-source initiative under **GSSoC 2024 Extended**. We aim to build a modern and engaging website for the cafe, where visitors can learn about our games, book tables, and stay updated with our events and offers. 

🎯 **Goal:** Create a seamless, user-friendly, and vibrant digital space for board game lovers.

## 🌐 Demo
🔗 Check out the live version of the website: [Live Demo](https://play-cafe.vercel.app/)

## 🔥 Features
| Feature                       | Description                                                   |
|-------------------------------|---------------------------------------------------------------|
| 💻 Responsive Design           | Optimized for all screen sizes—from mobile to desktop.       |
| 🗓️ Event Booking System       | Users can book tables for upcoming events and game nights.   |
| 🎲 Game Library               | Browse the collection of board games available at the cafe.  |
| 📸 Photo Gallery              | Sneak peeks into the cafe's ambiance and game nights.        |
| 📞 Contact Form               | Easily get in touch with the cafe for any queries or feedback.|
| 🎉 Special Offers             | Keep an eye out for exciting online deals and promotions!    |

## 🛠️ Tech Stack
| Technology       | Description                        |
|------------------|------------------------------------|
| **Frontend**     | JavaScript, React JS, Tailwind CSS |
| **Backend**      | Node.js, Express.js               |
| **Database**     | MongoDB/MySQL                     |
| **Deployment**   | Vercel                            |

## ⚙️ Getting Started / 📥 Installation
Ready to contribute to this fun project? Here's how to set up your development environment:
<br>
Make sure you follow our contributing guidelines: [here](https://github.com/RamakrushnaBiswal/PlayCafe/blob/main/CONTRIBUTING.md).

1. **Fork this repository** 🍴 and clone it to your local machine:
   ```bash
   git clone https://github.com/RamakrushnaBiswal/PlayCafe.git
   ```
2. **Install dependencies 🧩**:
   ```bash
   npm install
   ```
3. **Run the development server ⚡**:
   ```bash
   npm run dev
   ```
4. **Open your browser at http://localhost:3000 to see the project running! 🌟**

## Docker Setup
**Set up using Dockerfile (Make sure you have Docker installed):**
1. **Build Docker Image**
   ```bash
   docker build -t playcafe .
   ```
2. **Run Docker Image**
   ```bash
   docker run -p 5173:5173 -p 3000:3000 playcafe
   ```
3. **Open your browser at http://localhost:5173 to see the project running! 🌟**

## 📌 Usage
Once the application is running, you can:
- Navigate through the website to explore different sections.
- Book a table for an event.
- Contact us for inquiries.

## 🔍 API Documentation
The PlayCafe website communicates with a backend API to manage data. Here’s a brief overview of available API endpoints:

| HTTP Method | Endpoint              | Description                                            |
|-------------|-----------------------|--------------------------------------------------------|
| GET         | `/api/games`          | Fetches the list of available games.                   |
| POST        | `/api/bookings`       | Books a table for an event.                            |
| GET         | `/api/events`         | Retrieves upcoming events.                             |
| POST        | `/api/contact`        | Sends a message through the contact form.              |
| GET         | `/api/users`          | Retrieves a list of registered users.                  |
| GET         | `/api/users/:id`      | Fetches details of a specific user by ID.              |
| PUT         | `/api/users/:id`      | Updates user information based on user ID.             |
| DELETE      | `/api/users/:id`      | Deletes a user from the system by ID.                  |
| GET         | `/api/menus`          | Retrieves the menu items available at PlayCafe.        |
| POST        | `/api/orders`         | Places a new order for food and beverages.             |
| GET         | `/api/orders/:id`     | Fetches details of a specific order by ID.             |
| GET         | `/api/reviews`        | Retrieves customer reviews for the cafe.               |
| POST        | `/api/reviews`        | Submits a new review for a game or event.              |
| GET         | `/api/bookings/:id`   | Retrieves details of a specific booking by ID.         |
| DELETE      | `/api/bookings/:id`   | Cancels a specific booking by ID.                       |


## 🤝 Contributing
We love contributions! 💙 Whether you're a participant in **GSSoC** or an open-source enthusiast, we welcome your input. Here's how you can contribute:
- **📝 Create Issues**: If you find any bugs or have feature suggestions, feel free to open an issue.
- **🔨 Submit Pull Requests**: Got a fix or new feature? Fork the repo, create a new branch, and submit a pull request.

## 🎯 Open Source Programs
This project is part of **GirlScript Summer of Code 2024** (GSSoC) Extended, an initiative to help aspiring developers get involved in the open-source community.

<br>
<img src="https://github.com/user-attachments/assets/f7abbbe7-1950-4bf9-8456-c812ca630acf" style="width:400px">

## 🌟 Mentors

Special thanks to our amazing mentors who are guiding this project! 🙌

- **Shiva Bajpai**: Full Stack Developer  
  [GitHub Profile](https://github.com/Shiva-Bajpai)

Feel free to reach out for guidance and support throughout the development process!

  
## 👥 Our Contributors

We extend our heartfelt gratitude to all the amazing contributors who have made this project what it is today. Your efforts are driving **PlayCafe** to new heights! 🚀

### 🌟 Show some love by giving a ⭐ to our repository!

<br>
<center>
<div>
 <!-- readme: contributors -start -->
<table>
	<tbody>
		<tr>
            <td align="center">
                <a href="https://github.com/RamakrushnaBiswal">
                    <img src="https://avatars.githubusercontent.com/u/125277258?v=4" width="100;" alt="RamakrushnaBiswal"/>
                    <br />
                    <sub><b>Ramakrushna Biswal</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/samar12-rad">
                    <img src="https://avatars.githubusercontent.com/u/128586929?v=4" width="100;" alt="samar12-rad"/>
                    <br />
                    <sub><b>Samarth Vaidya</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/17arindam">
                    <img src="https://avatars.githubusercontent.com/u/65901047?v=4" width="100;" alt="17arindam"/>
                    <br />
                    <sub><b>Arindam</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/alo7lika">
                    <img src="https://avatars.githubusercontent.com/u/152315710?v=4" width="100;" alt="alo7lika"/>
                    <br />
                    <sub><b>alolika bhowmik</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Ashwinib26">
                    <img src="https://avatars.githubusercontent.com/u/149402720?v=4" width="100;" alt="Ashwinib26"/>
                    <br />
                    <sub><b>Ashwini_ab</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/itznayan">
                    <img src="https://avatars.githubusercontent.com/u/136584376?v=4" width="100;" alt="itznayan"/>
                    <br />
                    <sub><b>Mahera Nayan</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/tejasbenibagde">
                    <img src="https://avatars.githubusercontent.com/u/124677750?v=4" width="100;" alt="tejasbenibagde"/>
                    <br />
                    <sub><b>Tejas Benibagde</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Shirisha-16">
                    <img src="https://avatars.githubusercontent.com/u/148051550?v=4" width="100;" alt="Shirisha-16"/>
                    <br />
                    <sub><b>Tyarla Shirisha</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Amnyadav">
                    <img src="https://avatars.githubusercontent.com/u/127370497?v=4" width="100;" alt="Amnyadav"/>
                    <br />
                    <sub><b>Amnyadav</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/haseebzaki-07">
                    <img src="https://avatars.githubusercontent.com/u/147314463?v=4" width="100;" alt="haseebzaki-07"/>
                    <br />
                    <sub><b>Haseeb Zaki</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Suhas-Koheda">
                    <img src="https://avatars.githubusercontent.com/u/72063139?v=4" width="100;" alt="Suhas-Koheda"/>
                    <br />
                    <sub><b>Suhas Koheda</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/vishnuprasad2004">
                    <img src="https://avatars.githubusercontent.com/u/116942066?v=4" width="100;" alt="vishnuprasad2004"/>
                    <br />
                    <sub><b>Vishnu Prasad Korada</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/PavanTeja2005">
                    <img src="https://avatars.githubusercontent.com/u/98730339?v=4" width="100;" alt="PavanTeja2005"/>
                    <br />
                    <sub><b>PavanTeja2005</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/NilanchalaPanda">
                    <img src="https://avatars.githubusercontent.com/u/110488337?v=4" width="100;" alt="NilanchalaPanda"/>
                    <br />
                    <sub><b>Nilanchal</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/AbhijitMotekar99">
                    <img src="https://avatars.githubusercontent.com/u/109235675?v=4" width="100;" alt="AbhijitMotekar99"/>
                    <br />
                    <sub><b>Abhijit Motekar</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Navneetdadhich">
                    <img src="https://avatars.githubusercontent.com/u/156535853?v=4" width="100;" alt="Navneetdadhich"/>
                    <br />
                    <sub><b>Navneet Dadhich</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Aditya90456">
                    <img src="https://avatars.githubusercontent.com/u/153073510?v=4" width="100;" alt="Aditya90456"/>
                    <br />
                    <sub><b>Aditya Bakshi</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/tanishirai">
                    <img src="https://avatars.githubusercontent.com/u/178164785?v=4" width="100;" alt="tanishirai"/>
                    <br />
                    <sub><b>Tanishi Rai</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/Picodes10">
                    <img src="https://avatars.githubusercontent.com/u/91375618?v=4" width="100;" alt="Picodes10"/>
                    <br />
                    <sub><b>Sushree Manaswini Biswal</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Sourabh782">
                    <img src="https://avatars.githubusercontent.com/u/103349890?v=4" width="100;" alt="Sourabh782"/>
                    <br />
                    <sub><b>Sourabh Singh Rawat</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Shiva-Bajpai">
                    <img src="https://avatars.githubusercontent.com/u/141490705?v=4" width="100;" alt="Shiva-Bajpai"/>
                    <br />
                    <sub><b>Shiva Bajpai</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Sawan-Kushwah">
                    <img src="https://avatars.githubusercontent.com/u/138680328?v=4" width="100;" alt="Sawan-Kushwah"/>
                    <br />
                    <sub><b>Sawan kushwah </b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/devxMani">
                    <img src="https://avatars.githubusercontent.com/u/122438942?v=4" width="100;" alt="devxMani"/>
                    <br />
                    <sub><b>MANI </b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Ayush215mb">
                    <img src="https://avatars.githubusercontent.com/u/154300084?v=4" width="100;" alt="Ayush215mb"/>
                    <br />
                    <sub><b>Ayush Yadav</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/AliGates915">
                    <img src="https://avatars.githubusercontent.com/u/128673394?v=4" width="100;" alt="AliGates915"/>
                    <br />
                    <sub><b>Ali Gates</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/mishradev1">
                    <img src="https://avatars.githubusercontent.com/u/118660840?v=4" width="100;" alt="mishradev1"/>
                    <br />
                    <sub><b>Dev Mishra</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/jaidh01">
                    <img src="https://avatars.githubusercontent.com/u/117927011?v=4" width="100;" alt="jaidh01"/>
                    <br />
                    <sub><b>Jai Dhingra</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Jay-1409">
                    <img src="https://avatars.githubusercontent.com/u/166749819?v=4" width="100;" alt="Jay-1409"/>
                    <br />
                    <sub><b>Jay shah</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Mohitranag18">
                    <img src="https://avatars.githubusercontent.com/u/152625405?v=4" width="100;" alt="Mohitranag18"/>
                    <br />
                    <sub><b>Mohit Rana </b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/MutiatBash">
                    <img src="https://avatars.githubusercontent.com/u/108807732?v=4" width="100;" alt="MutiatBash"/>
                    <br />
                    <sub><b>Bashua Mutiat</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/Sapna127">
                    <img src="https://avatars.githubusercontent.com/u/91309280?v=4" width="100;" alt="Sapna127"/>
                    <br />
                    <sub><b>Sapna Kul</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/stutxi">
                    <img src="https://avatars.githubusercontent.com/u/95741837?v=4" width="100;" alt="stutxi"/>
                    <br />
                    <sub><b>Stuti </b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Syed-Farazuddin">
                    <img src="https://avatars.githubusercontent.com/u/119295880?v=4" width="100;" alt="Syed-Farazuddin"/>
                    <br />
                    <sub><b>Syed Faraz</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Vaibhav-Kumar-K-R">
                    <img src="https://avatars.githubusercontent.com/u/132189791?v=4" width="100;" alt="Vaibhav-Kumar-K-R"/>
                    <br />
                    <sub><b>Vaibhav-Kumar-K-R</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/lade6501">
                    <img src="https://avatars.githubusercontent.com/u/83055827?v=4" width="100;" alt="lade6501"/>
                    <br />
                    <sub><b>Vishal Lade</b></sub>
                </a>
            </td>
		</tr>
	<tbody>
</table>
<!-- readme: contributors -end -->
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->


<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->


<!-- ALL-CONTRIBUTORS-LIST:END -->

## ⭐ Support

Your support keeps us going! Here's how you can help:

- **💰 Sponsor us**: Become a sponsor and help us keep growing. [Become a Sponsor](https://github.com/sponsors/RamakrushnaBiswal).
- **⭐ Star our Repo**: Show some love by starring the repository. Your stars motivate us to continue developing and improving!

Thank you for supporting **PlayCafe**! 💖


## 📄 License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/RamakrushnaBiswal/PlayCafe/blob/main/LICENSE) file for more details.

## 📬 Contact Us

We’d love to hear from you! Whether you have questions, feedback, or collaboration ideas, feel free to reach out.

- **GitHub Issues**: [Submit a New Issue](https://github.com/PlayCafe/issues)

### ✨ Join the Conversation

Stay updated and engage with our community on social media:

- [Discord](https://discord.gg/Jh3bWQ7FRN)
- [LinkedIn](https://www.linkedin.com/in/ramakrushna-biswal/)
- [Email](mailto:ramakrushnabunty@gmail.com)

We are always here to help you! Don’t hesitate to connect with us and be part of the PlayCafe journey.




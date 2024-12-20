

# 🎓 **dypcetclubs.live**

A comprehensive platform for **managing college clubs, events, and announcements** effectively.



## 🚀 **Table of Contents**

- [Overview](#overview)
- [Key Features](#key-features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)



## 🌟 **Overview**

**dypcetclubs.live** is a robust web application designed to **simplify** the management of college clubs. It provides a user-friendly interface for club leaders to:

- Register their clubs.
- Organize and manage events.
- Make important announcements.
- Engage efficiently with club members.



## ✨ **Key Features**

- **📋 Club Registration & Management**: Register and manage club details seamlessly.
- **📅 Event Organization**: Create, edit, and delete events, complete with images and tags.
- **📢 Announcement System**: Post rich-text announcements for your club members.
- **👥 Member Management**: Easily manage members and assign roles.
- **💻 Mobile & Desktop Friendly**: Fully responsive design.


## ⚙️ **Installation**

Follow these steps to set up the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Yash-Ainapure/dypcetclubs.live.git
   cd dypcetclubs.live
   ```

2. **Set up the backend:**
   ```bash
   cd backend
   npm install
   npm start
   ```

3. **Set up the frontend (in a new terminal):**
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

4. **Create a `.env` file** in the backend folder:
   ```
   TURSO_AUTH_TOKEN="YOUR_TURSO_AUTH_TOKEN"
   TURSO_DATABASE_URL="YOUR_TURSO_DATABASE_URL"
   ```

5. **Migrate Prisma schema:**
   ```bash
   npx prisma migrate dev --name init
   npx prisma generate
   ```

6. **Run the application**:
   - Open your browser and visit `http://localhost:3000`.

> **Note**: You'll need a Turso account to obtain the authentication token and database URL. Sign up at [Turso.tech](https://turso.tech/).



## 🧑‍💻 **Usage**

[Include specific instructions on how to use the application features and workflows.]



## 🛠️ **Technologies Used**

- **Frontend**: React, Tailwind CSS, TypeScript
- **Backend**: Node.js, Express
- **Database**: SQLite (Turso Database)
- **ORM**: Prisma



## 🤝 **Contributing**

We welcome contributions to **dypcetclubs.live**!

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push the branch: `git push origin feature/your-feature-name`.
5. Submit a pull request.

> For major changes, open an issue first to discuss your ideas.

## Our Valuable Contributors ❤️✨

We are grateful to all the contributors who have helped improve this project. Your contributions are what make this project better!

<!-- readme: contributors -start -->
<table>
	<tbody>
		<tr>
            <td align="center">
                <a href="https://github.com/Yash-Ainapure">
                    <img src="https://private-avatars.githubusercontent.com/u/136250383?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc0ODAsIm5iZiI6MTczNDY1NjI4MCwicGF0aCI6Ii91LzEzNjI1MDM4MyJ9.M_lTthwgRbxeT2IxNzGYFHMVVRGR53Z32kDxbYA_RAY&v=4" width="100;" alt="Yash-Ainapure"/>
                    <br />
                    <sub><b>yash ainapure</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/yashksaini-coder">
                    <img src="https://private-avatars.githubusercontent.com/u/115717039?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTgwMjAsIm5iZiI6MTczNDY1NjgyMCwicGF0aCI6Ii91LzExNTcxNzAzOSJ9.6uh0Cdn6yU4eQOxwq1aKyuQMlAFwDITgAg-HFdojWd4&v=4" width="100;" alt="yashksaini-coder"/>
                    <br />
                    <sub><b>Yash Kumar Saini</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Laxmi01345">
                    <img src="https://private-avatars.githubusercontent.com/u/122423386?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc4NDAsIm5iZiI6MTczNDY1NjY0MCwicGF0aCI6Ii91LzEyMjQyMzM4NiJ9.lhKIZ8hn52z2HkxKtukV-qjgui3JwFovvJloJigJegE&v=4" width="100;" alt="Laxmi01345"/>
                    <br />
                    <sub><b>Laxmi Ray</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Gauravtb2253">
                    <img src="https://private-avatars.githubusercontent.com/u/114927759?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc5MDAsIm5iZiI6MTczNDY1NjcwMCwicGF0aCI6Ii91LzExNDkyNzc1OSJ9.O8QKWdjp60N-GqTPqeP5Df1L94XwO9zR49yvu6Ku6XI&v=4" width="100;" alt="Gauravtb2253"/>
                    <br />
                    <sub><b>Gaurav Bomble</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/radheypatil6630">
                    <img src="https://private-avatars.githubusercontent.com/u/85211195?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc0ODAsIm5iZiI6MTczNDY1NjI4MCwicGF0aCI6Ii91Lzg1MjExMTk1In0.4VMAF7lbFtGdeIXvtharC9--BreOKIHrv8zY7SwnjK4&v=4" width="100;" alt="radheypatil6630"/>
                    <br />
                    <sub><b>Radhey patil</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/prateek2102">
                    <img src="https://private-avatars.githubusercontent.com/u/130992856?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc1NDAsIm5iZiI6MTczNDY1NjM0MCwicGF0aCI6Ii91LzEzMDk5Mjg1NiJ9.IkET2WySiGKIW4s0iATBKcpES65T6M5tY1c-HMkXzjg&v=4" width="100;" alt="prateek2102"/>
                    <br />
                    <sub><b>Prateek </b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/varma-101">
                    <img src="https://private-avatars.githubusercontent.com/u/138625491?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc3ODAsIm5iZiI6MTczNDY1NjU4MCwicGF0aCI6Ii91LzEzODYyNTQ5MSJ9.iBp7jJbf0pA5QQO3ZuoyPXPlegZxAmayv5-fCpKFz-c&v=4" width="100;" alt="varma-101"/>
                    <br />
                    <sub><b>SAGI VENKATA NAGA GOPAL VARMA</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/rishyym0927">
                    <img src="https://private-avatars.githubusercontent.com/u/136720020?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc3MjAsIm5iZiI6MTczNDY1NjUyMCwicGF0aCI6Ii91LzEzNjcyMDAyMCJ9.Iw2nKg68G1Guj-rsgcbN6t8n22AukAojYx3x3Qdzs30&v=4" width="100;" alt="rishyym0927"/>
                    <br />
                    <sub><b>RISHIRAJ MUKHERJEE</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Hh440">
                    <img src="https://private-avatars.githubusercontent.com/u/91595810?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTgxNDAsIm5iZiI6MTczNDY1Njk0MCwicGF0aCI6Ii91LzkxNTk1ODEwIn0.dzgjMwPE7-p6_Moyqu0mlrxPjKAWPxPt96FCXiFleXU&v=4" width="100;" alt="Hh440"/>
                    <br />
                    <sub><b>Harsh</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Pruthviraj-sawant">
                    <img src="https://private-avatars.githubusercontent.com/u/157594404?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc2NjAsIm5iZiI6MTczNDY1NjQ2MCwicGF0aCI6Ii91LzE1NzU5NDQwNCJ9.Q3DuInwpt5H2J4W0LqwQsJluMDfNnveGjsb1q0YOhkY&v=4" width="100;" alt="Pruthviraj-sawant"/>
                    <br />
                    <sub><b>pruthviraj-sawant</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/im-amanjai">
                    <img src="https://private-avatars.githubusercontent.com/u/145966547?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc2NjAsIm5iZiI6MTczNDY1NjQ2MCwicGF0aCI6Ii91LzE0NTk2NjU0NyJ9.xyQ73BoidqWal2xNaWsFPA1JSkEWQNjZcDdkTkDmemA&v=4" width="100;" alt="im-amanjai"/>
                    <br />
                    <sub><b>im-amanjai</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/ZayedShahcode">
                    <img src="https://private-avatars.githubusercontent.com/u/115407231?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTgwMjAsIm5iZiI6MTczNDY1NjgyMCwicGF0aCI6Ii91LzExNTQwNzIzMSJ9.tnOEYobWOiTlx709mPbdlQ4_YgzuZHM7MGfJBcopSWM&v=4" width="100;" alt="ZayedShahcode"/>
                    <br />
                    <sub><b>Zayed</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/vivekrawat21">
                    <img src="https://private-avatars.githubusercontent.com/u/116631005?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc0MjAsIm5iZiI6MTczNDY1NjIyMCwicGF0aCI6Ii91LzExNjYzMTAwNSJ9.HmGzZwsqnu_wQ8QEhGGhyU3uofidBc5DL3JoMI4Puys&v=4" width="100;" alt="vivekrawat21"/>
                    <br />
                    <sub><b>Vivek Rawat</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/vedhcet-07">
                    <img src="https://private-avatars.githubusercontent.com/u/176995332?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTgwODAsIm5iZiI6MTczNDY1Njg4MCwicGF0aCI6Ii91LzE3Njk5NTMzMiJ9.Snp3e4hfuuDYK9hbZPSYRFSdgoW40Y7C7r2FWsXhCGo&v=4" width="100;" alt="vedhcet-07"/>
                    <br />
                    <sub><b>Vishwas M D</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/VinayLodhi1712">
                    <img src="https://private-avatars.githubusercontent.com/u/135756009?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc3MjAsIm5iZiI6MTczNDY1NjUyMCwicGF0aCI6Ii91LzEzNTc1NjAwOSJ9.-6H0E1Y960LAYODvqOA1_ZmBq3d9rN-Sqce2l9ZBHkw&v=4" width="100;" alt="VinayLodhi1712"/>
                    <br />
                    <sub><b>Vinay Anand Lodhi</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Swetabh333">
                    <img src="https://private-avatars.githubusercontent.com/u/109225662?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc0MjAsIm5iZiI6MTczNDY1NjIyMCwicGF0aCI6Ii91LzEwOTIyNTY2MiJ9.vbAqZN5jeL7O2bjmqymmmFPdJ3FI_swf56YrRMTBZD0&v=4" width="100;" alt="Swetabh333"/>
                    <br />
                    <sub><b>Swetabh Shreyam</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/sushil-sagar05">
                    <img src="https://private-avatars.githubusercontent.com/u/169032900?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc0MjAsIm5iZiI6MTczNDY1NjIyMCwicGF0aCI6Ii91LzE2OTAzMjkwMCJ9._-2-fwDYbT6MZMIMHvwWVv13gT3XTczxzTFZKJZ0bfM&v=4" width="100;" alt="sushil-sagar05"/>
                    <br />
                    <sub><b>Sushil Sagar</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Sourabh782">
                    <img src="https://private-avatars.githubusercontent.com/u/103349890?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc2NjAsIm5iZiI6MTczNDY1NjQ2MCwicGF0aCI6Ii91LzEwMzM0OTg5MCJ9.VmIf6YtSeGjJtzgA0vJVdicza3ZHJKW4t2ymuGnDXTE&v=4" width="100;" alt="Sourabh782"/>
                    <br />
                    <sub><b>Sourabh Singh Rawat</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/sps234">
                    <img src="https://private-avatars.githubusercontent.com/u/141764206?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc1NDAsIm5iZiI6MTczNDY1NjM0MCwicGF0aCI6Ii91LzE0MTc2NDIwNiJ9.zFZ6XOGC-F4icu_BTEEt2ADGL_lknr2XanLMzbnwJCE&v=4" width="100;" alt="sps234"/>
                    <br />
                    <sub><b>Saumya Pratap Singh</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/devxMani">
                    <img src="https://private-avatars.githubusercontent.com/u/122438942?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc0ODAsIm5iZiI6MTczNDY1NjI4MCwicGF0aCI6Ii91LzEyMjQzODk0MiJ9._P976EUOkEMqm0rUPs0PO1QCRNHpzDRdj2BBn7rK9Nk&v=4" width="100;" alt="devxMani"/>
                    <br />
                    <sub><b>MANI </b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/KrishChothani">
                    <img src="https://private-avatars.githubusercontent.com/u/143370415?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc5NjAsIm5iZiI6MTczNDY1Njc2MCwicGF0aCI6Ii91LzE0MzM3MDQxNSJ9.NOb-L8b0pYMp-9L5aLFajMtPG5TCt5SjI_sFodND65U&v=4" width="100;" alt="KrishChothani"/>
                    <br />
                    <sub><b>Krish Chothani</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/JeetuSuthar">
                    <img src="https://private-avatars.githubusercontent.com/u/129197623?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTgwODAsIm5iZiI6MTczNDY1Njg4MCwicGF0aCI6Ii91LzEyOTE5NzYyMyJ9.oBig3Ghq_4__iqHnOhbMSyAkyT9wKbUH3DwynT21jeU&v=4" width="100;" alt="JeetuSuthar"/>
                    <br />
                    <sub><b>Jeetu Suthar</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/hetvipopat">
                    <img src="https://private-avatars.githubusercontent.com/u/157787846?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc2MDAsIm5iZiI6MTczNDY1NjQwMCwicGF0aCI6Ii91LzE1Nzc4Nzg0NiJ9.WF8cs2zKbswJEUFdk3WvFKoWHEwscGiUz7M8oY5JfuU&v=4" width="100;" alt="hetvipopat"/>
                    <br />
                    <sub><b>Hetvi_26</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Dhruv-pahuja">
                    <img src="https://private-avatars.githubusercontent.com/u/100836518?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc1NDAsIm5iZiI6MTczNDY1NjM0MCwicGF0aCI6Ii91LzEwMDgzNjUxOCJ9.qZUsH43SYQ3vwErl4u_qhNWA6XAuKIlU598NoSJY9kw&v=4" width="100;" alt="Dhruv-pahuja"/>
                    <br />
                    <sub><b>Dhruv Pahuja</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/ChetanSingh14">
                    <img src="https://private-avatars.githubusercontent.com/u/153702696?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc4NDAsIm5iZiI6MTczNDY1NjY0MCwicGF0aCI6Ii91LzE1MzcwMjY5NiJ9.DtqU8K16rq01ghnFJwP-kLrGE0KvMAz8-AIuaUrL39A&v=4" width="100;" alt="ChetanSingh14"/>
                    <br />
                    <sub><b>Chetan SIngh</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/jainaryan04">
                    <img src="https://private-avatars.githubusercontent.com/u/138214350?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc5MDAsIm5iZiI6MTczNDY1NjcwMCwicGF0aCI6Ii91LzEzODIxNDM1MCJ9.kGkKVeI2OzNIssp77tZYXs1cTQVh_fg4FI5gHqhLdRE&v=4" width="100;" alt="jainaryan04"/>
                    <br />
                    <sub><b>Aryan Ramesh Jain</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/NK-Works">
                    <img src="https://private-avatars.githubusercontent.com/u/132702983?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc3MjAsIm5iZiI6MTczNDY1NjUyMCwicGF0aCI6Ii91LzEzMjcwMjk4MyJ9.JE3PSjVuWR44ngtcBpw8USIIq0mWMKxDQgb4F8AaJXM&v=4" width="100;" alt="NK-Works"/>
                    <br />
                    <sub><b>Anneshu Nag</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/vastavikadi">
                    <img src="https://private-avatars.githubusercontent.com/u/160533006?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTc2NjAsIm5iZiI6MTczNDY1NjQ2MCwicGF0aCI6Ii91LzE2MDUzMzAwNiJ9.ebo4LVfY7NKiSyHWVqKQzA_T3AwUlMBjCdqvZZxtrm4&v=4" width="100;" alt="vastavikadi"/>
                    <br />
                    <sub><b>Aditya Shukla</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/AasthaSingh28">
                    <img src="https://private-avatars.githubusercontent.com/u/138100998?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzQ2NTgxNDAsIm5iZiI6MTczNDY1Njk0MCwicGF0aCI6Ii91LzEzODEwMDk5OCJ9.YNVYx-1Pd5qQrpYcnCBPT0Z62ewVtDTqFXmZGfzujZw&v=4" width="100;" alt="AasthaSingh28"/>
                    <br />
                    <sub><b>Aastha Singh</b></sub>
                </a>
            </td>
		</tr>
	<tbody>
</table>
<!-- readme: contributors -end -->

## 📄 **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Made with ❤️ by the dypcetclubs.live team!


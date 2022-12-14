<h1 align="center">
  <a href="https://github.com/saRvaGnyA/ReachOut-SIH-Prototype">
    <img src="https://github.com/saRvaGnyA/ReachOut/raw/main/client/src/Logos/Logo2.png" alt="ReachOut" width="250" height="250">
  </a>
  <br>
  ReachOut
</h1>
 
<div align="center">
   <strong>ReachOut</strong> - An Accessible software for facilitation of various Govt. schemes for persons with disabilities <br>
 Software Engineering Project <br>
</div>

<hr>

<details>
<summary>Table of Contents</summary>

- [Description](#description)
- [Links](#links)
- [Tech Stack](#tech-stack)
- [Progress](#progress)
- [Future Scope](#future-scope)
- [Impact](#impact)
- [Project Setup](#project-setup)
- [Usage](#usage)
- [Team Members](#team-members)

</details>

## 📝Description

<table>
  <tr>
    <td>
Our idea “ReachOut” aims to build a progressive web app that makes access for the specially abled to government schemes expeditious and empowers them
<br><br>
      The <i>key features</i> of <strong>ReachOut</strong>:
      <ul>
<li> Ease of Accessibility and Navigation for all types of differently abled persons
<li> A single platform for all government schemes for the specially abled and their caregivers
      </ul>
    </td>
  </tr>
  </table>
    
The web-app has 3 access levels implemented
1. User
2. Admin (Government)
3. Company

### Flow for the User Access Level

![image](https://user-images.githubusercontent.com/24823649/186869688-78ad7f51-4154-4969-8e89-59896dd3ed80.png)

### Flow for the Admin Access Level (Government)

![image](https://user-images.githubusercontent.com/24823649/186803910-a7b239e6-4020-4f85-95aa-ef2e1f3ac9e3.png)

### Flow for the Company Access Level

![image](https://user-images.githubusercontent.com/24823649/186804039-12923f65-a3dc-4452-aaef-f982ed37d96d.png)
  

  
## 🔗Links

### Frontend (Vercel)
- [**ReachOut**](https://reach-out-sih-prototype.vercel.app/) 🚀

### Assets
- [GitHub Repo](https://github.com/smitsekhadiaa/ReachOut_WIM)

### Backend (Heroku)
- [ReachOut Server](https://reachout-sih.herokuapp.com/)

## 🤖Tech-Stack

### Web Development

- NextJS
- Tailwind CSS

### Database

- PostgreSQL (using Supabase)

### APIs

- Hasura GraphQL API (over the Postgres DB)
- FastAPI (for the model)


## 📈Progress

### Accessibility 

- [x] The entire website is designed with web accessibility (a11y) and GIGW (Guidelines for Indian Government Websites) at the forefront
- [x] Designing web components using a color-blind friendly scheme and implemented a high-contrast UI
- [x] Voice and keyboard navigation
- [x] Speech to Text for search, forms and navigation
- [x] A full-fledged accessibility toolbar for fonts and cursors

### Platform

- [x] A profile for every user, with Aadhar Number, Disability Certificate and Resume details required
- [x] Govt authorities can add the schemes for the disabled, and the disabled users can benefit from these schemes without leaving the portal
- [x] Companies can register their job positions, and people with special needs can apply for those jobs, Companies can hire test candidates for accessibility testing of their products
- [x] Map feature for locating nearby job opportunities
- [x] SMS Notifications and status updates for the enrolled schemes and jobs  
- [x] Dashboard for Analyzing scheme responses and demographics
- [x] Backend and Database Connectivity 

## 🔮Future Scope

- [ ] Complete the face ID login
- [ ] Add E-KYC verification on the platform, and all other financial employment-related services from APISetu for streamlining the hiring process
- [ ] Payment Gateway Integration for transparency 
- [ ] Upskilling platform based on job requirements
- [ ] Resume Parsing (Partially Implemented)
- [ ] Extend the built system to other aspects of the differently abled's life
- [ ] Translation to regional languages (localization) 

## 🔨Impact

- Setting the standard for accessibility on government portals by utilizing state-of-the-art accessibility features
- Streamline the entire process for the user
- Increase awareness by recommending schemes
- Improve outreach and transparency of the schemes
- Social and personal empowerment by extending the same system to private firms and NGOs
- Enable efficient policy-making by analyzing the data and feedback provided by the platform

## 🛠Project Setup

### For the web-app

1. Clone the GitHub repo
   ```
   $ git clone https://github.com/saRvaGnyA/ReachOut-SIH-Prototype.git
   ```
2. Enter the `client` directory. Install all the required dependencies. Ensure that remove any globally-installed packages like the React CLI, Tailwind CLI, PostCSS CLI or ESLint are uninstalled before proceeding ahead
   ```
   $ cd client
   $ yarn add
   ```
3. Setup the `.env.local` file for storing the environment variables. A demo file for this is as follows:
   ```
   HASURA_ADMIN_SECRET = your hasura admin key
   NEXT_PUBLIC_SUPABASE_ANON_KEY = your supabase anon key
   NEXT_PUBLIC_SUPABASE_URL = your supabase public url
   ```
4. If you are working on Visual Studio Code or WebStorm, it'd be convenient to install the extensions for [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) and [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint).

## 💻Usage

Once the required setup and installation is completed, you can start developing and running the project.

### For the web-app

1. Go to the `client` directory and run the `dev` script to activate the development server
   ```
   $ npm run dev
   ```
   Before pushing any commit, make sure to run the `lint` script and fix any linting errors
   ```
   $ npm run lint
   ```
   If you get an ESLint, Tailwind or PostCSS version conflict error, make a `.env` file in the `client` directory with the following contents:
   ```
   SKIP_PREFLIGHT_CHECK = true
   ```


## 👩‍💻Team Members

- [@Smit Sekhadia](https://github.com/smitsekhadiaa)
- [@Pratham Shah](https://github.com/shahpratham)


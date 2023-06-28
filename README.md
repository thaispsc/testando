<h1 align="center">
  <img src="https://res.cloudinary.com/dnqiosdb6/image/upload/v1687889673/g2-cover-github_fwpw6w.png" alt="g2-capital">
</h1>
<p align="center">
  <p align="center">The project is an investment opportunity in renewable energy, through the acquisition of CCB titles to finance the development of solar power plants.</p>
</p>

<h4 align="center">
 <p align="center">
   <img src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="NextJS" style="border-radius: 4px; height: 24px">
   <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="Typescript" style="border-radius: 4px; height: 24px">
   <img src="https://img.shields.io/badge/Jest-323330?style=for-the-badge&logo=Jest&logoColor=white" alt="jest" style="border-radius: 4px; height: 24px">
   <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma" style="border-radius: 4px; height: 24px">
</p>
</h4>

<img src="https://res.cloudinary.com/dnqiosdb6/image/upload/v1687954028/G2_Capital_Investimentos_em_Startups_wlm8v7.png" width="100%" alt="Dashboard" />

## Introduction

**[G2 Capital](https://g2-capital-lp-git-develop-inspireip.vercel.app/)** is a revolutionary project that focuses on investments in renewable energy. It allows investors to acquire CCB titles issued by a TMX Energy SPE, an experienced company in the renewable energy sector.

The G2 Capital project aims to democratize investments in renewable energy, ensuring a profitable asset and a sustainable energy future. Our commitment to investors goes beyond, as we offer complete legal support and ensure profitability through the leasing of solar power plants and the sale of energy to major market players.

</br>

## Cloning the repository and runing locally

Clone the repository by running the following command in your terminal:
```console
git clone https://github.com/emanagroup/infratoken-client.git
```
</br>

Once the repository is cloned, navigate to the project folder using the terminal and install the project dependencies:

    npm install

</br>

After the installation is complete, you can start the local development server:

    npm run dev

</br>

Open your web browser and visit http://localhost:3000 to see the result. The application should be up and running locally on your machine.

</br>

## Setting the environment variables

Before running the project you need to set up environment variables. Create a .env file at the root directory and add the following variables:

```
# API URL
NEXT_PUBLIC_API_URL=<your_api_url>

# NextAuth URL
NEXTAUTH_URL=<your_nextauth_url>
NEXTAUTH_SECRET=<your_nextauth_secret>

# Google OAuth
GOOGLE_ID=<your_google_id>
GOOGLE_SECRET=<your_google_secret>
NEXT_PUBLIC_API_GOOGLE_SECRET=<your_api_google_secret>
```

</br>

Replace `<your_api_url>`, `<your_nextauth_url>`, `<your_nextauth_secret>`, `<your_google_id>`, `<your_google_secret>`, and `<your_api_google_secret>` with the corresponding values for your setup.

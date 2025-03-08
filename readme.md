# MediDose AI - Personalized Dosage Recommendation & Blockchain Verification

This project idea represents an innovative and comprehensive approach to personalized medicine, combining advanced machine learning techniques with blockchain technology to create a robust, transparent, and efficient drug dosage recommendation system

## Features

- **Personalized Dosage Prediction:**  
  Uses patient data such as age, weight, height, genetic markers, and medical history to calculate a personalized medication dosage.
  
- **Detailed Report Generation:**  
  Generates a comprehensive PDF report that includes an overview, patient details, medical information, alternative medication options, and blockchain verification details.  
  - **Fallback:** Custom jsPDF generation with enhanced design and structure

- **Blockchain Verification:**  
  Records dosage recommendations on the blockchain and provides a mechanism for users to verify the authenticity of the prediction.

- **Responsive User Interface:**  
  Built using React, Tailwind CSS, and integrated charts to deliver an intuitive experience.

## Technologies Used

- **Frontend:** React, TypeScript, Tailwind CSS
- **PDF Generation:** jsPDF
- **Charts:** Chart.js (Doughnut Chart)
- **Blockchain Integration:** Custom smart contract functions (`recordDosageOnBlockchain`, `generatePredictionHash`)


## Project Structure

```
├── public
├── src
│   ├── components
│   │   ├── PredictionForm.tsx
│   │   ├── Results.tsx
│   │   └── VerificationPage.tsx
│   ├── context
│   │   └── PredictionContext.tsx
│   ├── blockchain
│   │   └── smartContract.ts
│   ├── App.tsx
│   └── index.tsx
├── package.json
├── tailwind.config.js
├── tsconfig.json
└── README.md
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or later)
- npm or yarn package manager

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd MediDose
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```
3. **Start the development server:**
   ```bash
   npm start
   ```
   or
   ```bash
   yarn start
   ```
   The application will be running at [http://localhost:3000](http://localhost:3000).

### Building for Production

To build the application for production deployment, run:
```bash
npm run build
```
or
```bash
yarn build
```

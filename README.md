# Cash_Harbour

Welcome to Cash_Harbour, your secure and efficient banking app! Cash_Harbour provides a user-friendly interface for managing your finances, powered by cutting-edge technologies for security and functionality.

## Project Overview

Cash_Harbour is a banking application designed to offer users a seamless experience for managing their financial transactions and analyzing their spending habits. Leveraging a modern tech stack, it provides robust security, smooth banking transactions, and insightful data visualization.

## Features

- **Secure Authentication**: Utilizes Next.js and Appwrite for secure authentication, protecting user accounts from unauthorized access.
- **Banking Transactions**: Integrates with Plaid and Dwolla APIs to facilitate banking transactions securely and efficiently.
- **Form Handling**: Utilizes React Hook Form for efficient and flexible form handling, ensuring a smooth user experience.
- **Data Validation**: Integrates with Zod for robust data validation, ensuring data integrity and security.
- **Data Visualization**: Utilizes Chart.js to generate interactive charts and graphs, allowing users to visualize their financial data with ease.
- **UI Components**: Styled with TailwindCSS and ShadCN for a sleek and responsive user interface.

## Tech Stack

- **Next.js**: React framework for building server-side rendered and statically generated web applications.
- **TypeScript**: Typed superset of JavaScript that enhances code quality and developer productivity.
- **Appwrite**: Open-source backend server providing user authentication, database, and storage services.
- **Plaid**: API for securely connecting bank accounts and processing financial transactions.
- **Dwolla**: API for facilitating bank transfers and payments securely.
- **React Hook Form**: Lightweight and flexible form validation library for React.
- **Zod**: TypeScript-first schema declaration and validation library for building robust data models.
- **TailwindCSS**: Utility-first CSS framework for building custom designs without writing CSS.
- **Chart.js**: Simple yet flexible JavaScript charting library for data visualization.
- **ShadCN**: TailwindCSS plugin for generating custom shadow effects.

## Security Measures

Cash_Harbour prioritizes the security of user data and transactions. Here are some key security measures implemented in the application:

- **Encryption**: All sensitive user data is encrypted to ensure confidentiality.
- **Authentication**: Next.js and Appwrite are used for secure user authentication, with measures in place to prevent unauthorized access.
- **API Security**: Plaid and Dwolla APIs are used to securely manage banking transactions, ensuring the integrity and authenticity of financial data.

## Usage

To get started with Cash_Harbour, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/GreNxNja/Cash_Harbour.git
```

2. Install dependencies using npm or yarn:

```bash
cd Cash_Harbour
npm install
# or
yarn install
```

3. Set up environment variables:

   - Create a `.env` file in the root directory.
   - Add your API credentials and other configuration variables:

```plaintext
# NEXT
NEXT_PUBLIC_SITE_URL=

# APPWRITE
NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_PROJECT=
APPWRITE_DATABASE_ID=
APPWRITE_USER_COLLECTION_ID=
APPWRITE_BANK_COLLECTION_ID=
APPWRITE_TRANSACTION_COLLECTION_ID=
APPWRITE_SECRET=

# PLAID
PLAID_CLIENT_ID=
PLAID_SECRET=
PLAID_ENV=
PLAID_PRODUCTS=
PLAID_COUNTRY_CODES=

# DWOLLA
DWOLLA_KEY=
DWOLLA_SECRET=
DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
DWOLLA_ENV=sandbox
```

4. Start the development server:

```bash
npm run dev
# or
yarn dev
```

5. Access Cash_Harbour in your web browser at `http://localhost:3000`.

## Contributing

Contributions to Cash_Harbour are welcome! If you encounter any issues or have suggestions for improvements, please submit a pull request or open an issue on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

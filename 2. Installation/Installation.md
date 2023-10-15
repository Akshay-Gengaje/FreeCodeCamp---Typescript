# Installation

To install TypeScript on your computer, you'll need to use a package manager, such as npm (Node Package Manager) or yarn. TypeScript is typically installed globally or locally, depending on your needs. Here are the steps to install TypeScript:

**Global Installation (Recommended for Most Cases):**

1. **Node.js Installation:** TypeScript relies on Node.js, so make sure you have Node.js installed on your computer. You can download Node.js from the official website: [Node.js Downloads](https://nodejs.org/en/download/). Follow the installation instructions for your specific platform (Windows, macOS, or Linux).

2. **Global TypeScript Installation:** Open your command-line terminal and use npm to install TypeScript globally. Global installation allows you to use the `tsc` (TypeScript compiler) command anywhere in your terminal.

   ```bash
   npm install -g typescript
   ```

   If you prefer using yarn, you can install TypeScript globally with the following command:

   ```bash
   yarn global add typescript
   ```

3. **Verify Installation:** After the installation is complete, you can verify that TypeScript is installed by running:

   ```bash
   tsc --version
   ```

   This should display the TypeScript version you installed.

**Local Installation (For Project Specific Usage):**

If you want to use TypeScript for a specific project without installing it globally, follow these steps:

1. **Node.js Installation:** Ensure you have Node.js installed on your computer as mentioned earlier.

2. **Initialize a New Project:** Navigate to the root directory of your project using your command-line terminal. If you haven't already initialized a Node.js project, you can do so by running:

   ```bash
   npm init
   ```

   Follow the prompts to create a `package.json` file.

3. **Local TypeScript Installation:** In your project directory, you can install TypeScript as a local dependency by running:

   ```bash
   npm install typescript --save-dev
   ```

   If you prefer using yarn, use this command:

   ```bash
   yarn add typescript --dev
   ```

4. **Verify Installation:** You can verify that TypeScript is installed locally for your project by checking the `devDependencies` section in your project's `package.json` file.

   You can run the TypeScript compiler (tsc) from the local installation by using `npx`. For example:

   ```bash
   npx tsc --version
   ```

   This will display the TypeScript version installed locally in your project.

Now that you have TypeScript installed, you can start writing TypeScript code in your project. You can use the `tsc` command to transpile TypeScript files to JavaScript in your local project or use it globally if you performed a global installation.

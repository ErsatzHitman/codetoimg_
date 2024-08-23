# 🌟 Code to Image Generator

Create stunning, customizable images from your code snippets effortlessly. With this tool, you can write code in various programming languages, select different themes, backgrounds, and padding, and then export the beautifully rendered code as an image. Perfect for sharing your code snippets on blogs, social media, or in presentations!

## 🚀 Features

- **🖥️ Multi-Language Code Editor**: Supports popular languages like **JavaScript**, **HTML**, **CSS**, **Python**, **Java**, and **TypeScript**.
- **🎨 Theme Customization**: Choose from a variety of editor themes such as **Monokai**, **Twilight**, and **Terminal** for enhanced readability and aesthetics.
- **🌈 Dynamic Backgrounds**: Apply gorgeous gradient backgrounds or solid colors to your code snippets for a personalized touch.
- **📏 Padding Adjustments**: Fine-tune the padding around your code for better visual spacing.
- **📤 PNG Export**: Instantly export your code snippet as a PNG image with just one click.
- **🔧 Resizable Editor**: Easily resize the editor by dragging the edges to fit your preferred layout.
- **⚡ Real-Time Preview**: See live updates as you adjust your code, theme, background, and padding in real-time.

## 🎬 Demo



## 🛠️ Installation

Follow these steps to run the project locally:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/ErsatzHitman/codetoimg_
    ```
   
2. **Install Dependencies**:
    ```bash
    npm install
    ```
   
3. **Run the Development Server**:
    ```bash
    npm run dev
    ```

4. **Open in Browser**: Visit `http://localhost:3000` in your browser to start using the app.

## 📝 Usage Instructions

1. **Select Language**: Pick your programming language from the **Language Selector** dropdown.
2. **Choose a Theme**: Select your preferred code theme from the **Theme Selector** dropdown.
3. **Pick a Background**: Customize the background with gradients or solid colors using the **Background Selector**.
4. **Adjust Padding**: Modify the padding around your code snippet with the **Padding Selector**.
5. **Write Your Code**: Enter your code in the editor.
6. **Export**: When ready, click the **Export PNG** button to download the styled code as an image.

## 🎨 Customization Options

- **Languages Supported**: JavaScript, HTML, CSS, Python, Java, TypeScript
- **Themes Available**:
  - **Monokai**
  - **Twilight**
  - **Terminal**
- **Background Styles**:
  - Solid colors
  - Gradient colors (e.g., `linear-gradient(354deg,#ff75b5,#ffb86c)`)

## 📷 Screenshots

### Editor Preview

![Screenshot 2024-08-23 113641](https://github.com/user-attachments/assets/5d8d7ad5-cbe6-416b-9869-5c0270c6827e)
![Screenshot 2024-08-23 113648](https://github.com/user-attachments/assets/afaddf80-67b5-4097-9582-a3c7c0d26bb6)
![Screenshot 2024-08-23 113657](https://github.com/user-attachments/assets/47e09aa1-46c2-4d7f-a3a4-06c623fd9165)
![Screenshot 2024-08-23 114445](https://github.com/user-attachments/assets/1d6e60d8-bee0-4ff3-a9d2-e9646c9c8d10)
![Screenshot 2024-08-23 113518](https://github.com/user-attachments/assets/9417872e-3334-4fd1-b2d8-df012a09bbcb)


### Exported Image Example

![code (4)](https://github.com/user-attachments/assets/2af59d88-ce51-40d6-aff5-c1e966c3c359)

## 🛠️ Technologies Used

- **Frontend**:
  - [Next.js](https://nextjs.org/): Framework for building the React-based user interface.
  - [Tailwind CSS](https://tailwindcss.com/): Utility-first CSS framework for responsive and modern design.
  - [Ace Editor](https://ace.c9.io/): Embeddable code editor supporting syntax highlighting for various programming languages.
  - [html2canvas](https://html2canvas.hertzen.com/): Library for rendering the code editor as an image.
  - [Lucide Icons](https://lucide.dev/): Beautiful and customizable icons for UI components.

## 🗂️ Project Structure

```bash
codeimg/
├── .next/                         # Next.js build output
├── app/                           # Next.js app folder
│   ├── favicon.ico
│   ├── globals.css                # Global styles using Tailwind CSS
│   ├── layout.tsx                 # Application layout and metadata
│   └── page.tsx                   # Main application page combining all components
├── components/                    # React components for the project
│   ├── BackgroundSelector.tsx     # Dropdown to select background style
│   ├── CodeEditor.tsx             # Main code editor component using Ace Editor
│   ├── Footer.tsx                 # Footer with links and credits
│   ├── LanguageSelector.tsx       # Dropdown to select programming language
│   ├── PaddingSelector.tsx        # Dropdown to adjust padding around code
│   └── ThemeSelector.tsx          # Dropdown to select code theme
├── node_modules/                  # Node.js packages
├── public/                        # Public assets
│   └── icons/
│       ├── logo-white.svg         # Icon for the logo
│       ├── next.svg               # Next.js logo
│       └── vercel.svg             # Vercel logo
├── utils/                         # Utility functions and constants
│   └── utilities.tsx              # Utility functions and constants for themes, languages, etc.
├── .gitignore                     # Files and folders to ignore in Git
├── next-env.d.ts                  # TypeScript environment declaration for Next.js
├── next.config.js                 # Next.js configuration file
├── package-lock.json              # Auto-generated dependency lock file
├── package.json                   # Project's dependencies and scripts
├── postcss.config.js              # PostCSS configuration for Tailwind CSS
├── README.md                      # Project documentation
├── tailwind.config.ts             # Tailwind CSS configuration file
└── tsconfig.json                  # TypeScript configuration file

# TinyMCE for React – Rich Text Editor Integration

This project demonstrates the integration of **TinyMCE**, a powerful rich text editor, into a **React** application.

## ✨ Features

- WYSIWYG editing using TinyMCE
- Custom toolbar configuration
- Rich media support (images, links, etc.)
- React-friendly setup using `@tinymce/tinymce-react`

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the app

```bash
npm start
```

## 📦 Dependencies

- React
- @tinymce/tinymce-react

You can install TinyMCE for React using:

```bash
npm install @tinymce/tinymce-react
```

## 🧠 How It Works

This project uses the `Editor` component from `@tinymce/tinymce-react`. You can customize the editor using the `init` prop:

```jsx
import { Editor } from '@tinymce/tinymce-react';

<Editor
  init={{
    height: 400,
    menubar: false,
    plugins: ['link', 'image', 'media'],
    toolbar: 'undo redo | formatselect | bold italic | link image media',
  }}
/>
```

## 📁 File Structure

```
/src
  ├── App.js         # Main React component
  ├── Components/TEditor.js  # Editor implementation
```

## 🔧 Customization

You can easily customize the TinyMCE toolbar, plugins, or even add custom buttons as per your needs.

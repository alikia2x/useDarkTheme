# Dark Theme Hook

Dark Theme Hook is a custom React hook that allows you to detect the user's preferred color scheme, specifically whether they have enabled dark mode. This hook listens for changes in the user's system preferences and updates accordingly.

## Installation

You can install Dark Theme Hook using your preferred package manager:

```sh
npm install @alikia/dark-theme-hook
```

```sh
yarn add @alikia/dark-theme-hook
```

```sh
pnpm add @alikia/dark-theme-hook
```

```sh
bun add @alikia/dark-theme-hook
```

## Usage

To use the Dark Theme Hook in your React application, simply import and call the hook within your functional components:

```jsx
import useDarkTheme from '@alikia/dark-theme-hook';

function MyComponent() {
    const isDarkMode = useDarkTheme();

    return (
        <div className={isDarkMode ? 'dark-mode' : 'light-mode'}>
            <h1>Dark Mode Detection</h1>
            <p>Dark mode is {isDarkMode ? 'enabled' : 'disabled'}.</p>
        </div>
    );
}

export default MyComponent;
```
